# TP 30 : Pipeline CI/CD avec Jenkins, GitHub, Docker et ngrok

Ce TP met en place un pipeline CI/CD pour un projet Spring Boot :

- Récupération du code depuis GitHub
- Build Maven et tests
- Création d’une image Docker
- Lancement du conteneur
- Déclenchement automatique du pipeline à chaque push via GitHub Webhook et ngrok

## Lancer le pipeline et lire le résultat
<img width="1600" height="766" alt="image" src="https://github.com/user-attachments/assets/fbafb641-0424-4d76-a855-00bea3c0dfc2" />
<img width="1375" height="661" alt="image" src="https://github.com/user-attachments/assets/25e02c1d-4fad-4229-a78d-18767f73df4d" />

## Résumé final
Ce TP a permis de :

- installer et configurer Jenkins sur Windows ;
- paramétrer Maven comme outil Jenkins ;
- créer un Pipeline Jenkins pour un projet Spring Boot + Docker ;
- exposer Jenkins avec ngrok pour le rendre accessible depuis Internet ;
- configurer un webhook GitHub pour déclencher automatiquement un build à chaque push ;
- interpréter le Stage View pour comprendre le déroulement du pipeline.
