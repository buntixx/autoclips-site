# AutoClips — mini-site pour TikTok Developer

Ce dossier contient un petit site statique prêt à être publié gratuitement.

## Fichiers

- `index.html` : page d'accueil officielle AutoClips
- `terms.html` : Conditions d'utilisation
- `privacy.html` : Politique de confidentialité
- `styles.css` : design commun

## Publication rapide avec GitHub Pages

1. Crée un compte GitHub si nécessaire.
2. Crée un nouveau dépôt public, par exemple `autoclips-site`.
3. Ajoute tous les fichiers de ce dossier à la racine du dépôt.
4. Ouvre **Settings > Pages**.
5. Dans **Build and deployment**, sélectionne :
   - Source : `Deploy from a branch`
   - Branch : `main`
   - Folder : `/ (root)`
6. Enregistre.
7. Attends quelques minutes.

Ton site aura généralement une adresse de ce type :

`https://TON-PSEUDO.github.io/autoclips-site/`

## URLs à entrer dans TikTok Developer

Si ton pseudo GitHub est `bunti` et ton dépôt `autoclips-site`, utilise :

**Web/Desktop URL**
`https://bunti.github.io/autoclips-site/`

**Terms of Service URL**
`https://bunti.github.io/autoclips-site/terms.html`

**Privacy Policy URL**
`https://bunti.github.io/autoclips-site/privacy.html`

Remplace `bunti` par ton vrai pseudo GitHub.

## Important : Redirect URI TikTok

Le callback OAuth local ne va PAS dans les champs Terms/Privacy.

Dans la configuration de Login Kit / Desktop, garde le callback utilisé par AutoClips, par exemple :

`http://127.0.0.1:*/tiktok-callback/`

## Avant une diffusion publique importante

Les pages fournies sont une base adaptée au fonctionnement actuel d'AutoClips. Si tu commercialises
ou distribues largement l'application, ajoute au minimum une adresse e-mail de contact et fais vérifier
les mentions légales / confidentialité selon ton statut et ton pays.
