# TRACE — Règles de publication publique

## Périmètre

- Dépôt de présentation : `AshtraySunn/trace-updates` (public).
- Branche du site : `main`, dossier `/(root)`.
- Adresse prévue : https://ashtraysunn.github.io/trace-updates/
- Dépôt applicatif TRACE : séparé et privé.

## Vérification avant une mise à jour

1. Publier uniquement du HTML, du CSS et des documents explicatifs sans données sensibles.
2. Vérifier que tout exemple ou écran est fictif.
3. Exclure adresses ou positions opérationnelles, identifiants, secrets, exports, logs, métadonnées et configurations.
4. Ne jamais relier le site GitHub Pages au serveur ou au déploiement privé de TRACE.
5. Ne pas annoncer de fonctionnalité en production sans vérification indépendante ni divulguer de détails techniques sensibles.
6. Vérifier le rendu mobile, l'accessibilité et les liens.

## Activer GitHub Pages

Ouvrir **Settings → Pages → Build and deployment**, choisir **Deploy from a branch**, sélectionner **main** et **/(root)**, puis cliquer sur **Save**.

GitHub publie ensuite les fichiers statiques du dépôt. Vérifier l'adresse publique dans l'onglet Pages.

## Mise à jour du journal

Mettre à jour [CHANGELOG.md](CHANGELOG.md) et [ROADMAP.md](ROADMAP.md) avec des informations génériques, sans événement réel ni informations d'exploitation du service.