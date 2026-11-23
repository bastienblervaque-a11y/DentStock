# DentStock PWA

Prototype mobile de gestion de stock dentaire.

## Test local
La caméra exige HTTPS ou localhost. Sur ordinateur : `python -m http.server 8080`, puis ouvrir `http://localhost:8080`. La caméra d'un téléphone ne fonctionnera pas via une simple adresse HTTP du réseau local.

## Mise en ligne recommandée
1. Décompresser l'archive.
2. Déposer le dossier sur Netlify Drop, Vercel ou GitHub Pages.
3. Ouvrir l'URL HTTPS sur le téléphone.
4. Autoriser la caméra.
5. iPhone : Safari > Partager > Sur l'écran d'accueil. Android : Chrome > menu > Installer l'application.

## Limites du prototype
- Les données sont enregistrées uniquement dans le navigateur du téléphone (localStorage).
- Pas de synchronisation multi-utilisateur ni de sauvegarde serveur.
- ZXing est chargé depuis un CDN, donc le premier chargement et le scanner nécessitent Internet.
- Avant usage réel au cabinet : backend sécurisé, comptes, sauvegarde, historique des mouvements, registre des lots, export, rôles et politique RGPD.
