# Last Asylum : Plague — Guide FR

Guide communautaire francophone **non officiel** consacré à *Last Asylum: Plague*.

Le contenu est rédigé en Markdown et le site est généré avec **MkDocs Material** puis publié automatiquement sur **GitHub Pages**.

## Aperçu local

```bash
python -m venv .venv
source .venv/bin/activate   # Linux / macOS
.venv\Scripts\activate    # Windows

pip install -r requirements.txt
mkdocs serve
```

Ouvrez ensuite <http://127.0.0.1:8000>.

## Préparer votre dépôt GitHub

1. Remplacez `VOTRE-PSEUDO` dans `mkdocs.yml`.
2. Créez un dépôt GitHub nommé `last-asylum-guide-fr`.
3. Poussez ce projet sur la branche `main`.
4. Dans **Settings → Pages → Build and deployment**, choisissez **GitHub Actions**.
5. Le workflow `.github/workflows/pages.yml` publiera le site automatiquement.

## Ajouter un guide

Créez un fichier `.md` dans le dossier approprié sous `docs/`, puis ajoutez-le à la section `nav:` de `mkdocs.yml`.

Le modèle conseillé se trouve dans [`docs/reference/contribuer.md`](docs/reference/contribuer.md).

## Philosophie éditoriale

Le guide distingue autant que possible :

- ✅ ce qui est vérifié dans le jeu ;
- 🧪 ce qui a été testé par la communauté ;
- 💡 les recommandations et optimisations ;
- ⚠️ les informations à confirmer ;
- 🆓 les approches F2P ;
- 💰 les approches nécessitant des achats.

## Sources

Le projet peut s'appuyer sur plusieurs sources publiques et retours de joueurs. Une source d'inspiration initiale est la rubrique Last Asylum de **Worst Guides Ever**, sans reproduction de leurs textes.

## Avertissement

Ce projet n'est ni affilié, ni approuvé, ni sponsorisé par les développeurs ou éditeurs de *Last Asylum: Plague*. Les noms, marques et éléments visuels du jeu appartiennent à leurs propriétaires respectifs.
