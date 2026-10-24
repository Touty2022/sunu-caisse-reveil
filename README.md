# Réveil de Sunu Caisse

Solution temporaire : une tâche GitHub Actions visite `https://sunu-caisse.onrender.com/api/sante` toutes les 10 minutes, de 7 h à 23 h (heure de Dakar), pour que l'hébergement gratuit de Render ne mette pas l'application en veille pendant les heures d'ouverture.

- Le dépôt est public pour que GitHub Actions reste gratuit. Il ne contient que l'adresse publique de l'application, aucun secret.
- Lancer un réveil à la main : onglet **Actions** → **Réveil de Sunu Caisse** → **Run workflow**.
- GitHub met en pause les tâches planifiées d'un dépôt public sans activité depuis 60 jours (un e-mail prévient avant) : il suffit alors de cliquer sur **Enable workflow** dans l'onglet Actions.
- Quand Sunu Caisse passera en formule payante (Starter), supprimer ce dépôt ou désactiver la tâche.
