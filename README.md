 
 # Symfony

## NOUVEAU PROJET

- ouvrir un nouveau terminal
- se rendre dans le dossier ou on veux crrer le projet (ex : MAMP)
`
cd chemin_vers_le_dossier_MAMP
`
- creer le projet avec composer (pas besoin de creer le dossier du projet):
`
composer projet create-project symfony/wesbite-skeleton nom_du_projet ^5.4.* ( sur windows)
`

## GIT

- creer un depot GIT sur GITHUB
-avec un terminal, se rendre dans le dossier du projet ( cd... VSC)
-initialiser  un depot local :
`
git init
`
-lier le depot distant au depot local
`
git remote add origin lien_du_depot_GitHub
`
-ajouter tous les fichier :
`
git add *
`
- donner un nom au commit :
`
git commit -m "message_du_commit"
`
- recuperer les dernieres modifications:
`
git pull origin main
`
- envoyer les modifications:
```
git push origin main
```
- voir la liste de commit (fleches hauts et bas pour naviguer dans la liste , q pour quitter ):
```
git log
```

## RECUPERER DU PROJET

-télécharger le zip ou faire un pull
- recréer le fishier .env à la racine du projet (avec ses propres informations)
- les infos importante sont APP_ENV et  DATABASE_URL (éventuellemmnt MAILER_URL)
-mettre à jour le projet (l'insatalation) :
``` composer install ou (composer update)
```

## APACHE-PACK

- package pour le support d'Apache
- barre de débug / routing / .htaccess
- dans le terminal :
```





