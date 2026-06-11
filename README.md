# Dashboard de gestion locative

Compagnon de travail quotidien pour gestionnaire locatif : échéancier central avec calendrier, congés locataires, arrêtés de compte, fins de gestion, sinistres, devis, éléments à saisir, location digitale et suivi d'objectifs (« Mes stats »).

## Lancement

Téléchargez le fichier **`dashboard-gestion-locative.html`**, puis **double-cliquez dessus** : il s'ouvre dans votre navigateur, c'est tout.

Rien à installer, aucune connexion Internet nécessaire. Vos données restent uniquement sur votre ordinateur, dans votre navigateur.

## Sauvegarde automatique + consultation sur téléphone

1. Sur le PC (Chrome ou Edge), ouvrez les **Réglages** (engrenage à droite des onglets), section « Sauvegarde automatique », cliquez sur **« Activer la sauvegarde automatique… »** et choisissez un dossier **synchronisé par Google Drive pour ordinateur** (par exemple un sous-dossier de votre Drive). Autorisez l'accès quand le navigateur le demande.
2. C'est tout : à chaque modification, l'application réécrit dans ce dossier `gestion-locative-sauvegarde.json` (la sauvegarde) et `gestion-locative-consultation.pdf` (la version lisible).
3. Sur le téléphone, ouvrez l'application **Google Drive**, naviguez vers ce dossier et touchez **`gestion-locative-consultation.pdf`** : vous consultez vos échéances et dossiers à jour. Ce PDF est un instantané de la dernière sauvegarde faite sur le PC.

## Bon à savoir

- Utilisez toujours le **même navigateur** sur le **même poste** pour retrouver vos données.
- L'export manuel (« Exporter la sauvegarde », fichier `.json` à recharger via « Importer ») reste disponible, notamment sur les navigateurs sans sauvegarde automatique (Firefox, Safari).
- Évitez la navigation privée : les données y sont effacées à la fermeture.
- En cas de mise à jour de l'application, remplacez l'ancien fichier `.html` par le nouveau et n'ouvrez que ce dernier.
