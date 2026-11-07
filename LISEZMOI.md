# Nova Store : construire l'APK depuis ton téléphone

1. github.com : crée un compte, puis « + » > New repository, nom `nova-store`, Public > Create.
2. Décompresse ce zip avec ton gestionnaire de fichiers.
3. Dans le dépôt : Add file > Upload files. Choisis ces 6 fichiers : index.html, package.json,
   capacitor.config.json, icon-only.png, icon-foreground.png, icon-background.png. Puis Commit changes.
4. Add file > Create new file. Dans le nom, tape exactement : .github/workflows/android.yml
   (les / créent les dossiers). Colle le contenu du fichier android.yml, puis Commit changes.
5. Onglet Actions (appuie sur « I understand my workflows, go ahead and enable them » si demandé)
   > « Construire l'APK » > Run workflow. Attends 5 à 10 minutes.
6. Ouvre l'exécution terminée > Artifacts > NovaStore-apk. Décompresse, ouvre NovaStore.apk, autorise l'installation.

Mise à jour : remplace index.html dans le dépôt (Add file > Upload files, même nom) puis relance Run workflow.
Si une étape est rouge, copie les dernières lignes d'erreur et envoie-les à Claude.
