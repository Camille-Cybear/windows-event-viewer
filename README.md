# windows-event-viewer
answer for the eventvwr quest

Cette vue filtre les évènements DNS :
- 2: Démarrage du serveur DNS
- 4: Arrêt du serveur DNS
- 409: Erreur de résolution de nom
- 501-502: Échec de chargement de zone
- 6001-6002: Problèmes de réplication DNS

Avec pour sources :
- DNS-Server-Service: Pour les opérations du serveur DNS
- DNS Client Events: Pour les événements côté client

Et niveaux de criticité :

- Critique (1)
- Erreur (2)
- Avertissement (3)
- Information (4) - Pour les démarrages/arrêt

Le fichier est l'export de la vue personallisée en xml.

   
