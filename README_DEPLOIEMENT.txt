RELAIS COULEURS - SITE STATIQUE FR/EN - V1

CONTENU
- fr/index.html : page de présentation française
- en/index.html : English landing page
- fr/confidentialite.html : politique de confidentialité FR (BROUILLON A FINALISER)
- en/privacy.html : English privacy policy (DRAFT TO REVIEW)
- assets/ : illustrations extraites du jeu
- app-ads.txt : fichier AdMob à mettre impérativement à la RACINE du domaine

DEPLOIEMENT OVH / HTTPS :
1. Copier le contenu de ce dossier dans un sous-dossier /relais-couleurs/ du dossier www du site kptncorp.fr.
2. Copier en plus app-ads.txt A LA RACINE /www/app-ads.txt (PAS seulement sous /relais-couleurs/).
3. Dans Google Play Console, définir Site Web du développeur sur https://kptncorp.fr/relais-couleurs/
4. Pour la politique de confidentialité Google Play, utiliser https://kptncorp.fr/relais-couleurs/fr/confidentialite.html ; une version EN existe aussi.
5. Tester https://kptncorp.fr/app-ads.txt : il doit afficher une ligne TEXTUELLE, pas une page HTML.
6. Vérifier dans AdMob le bon ID éditeur : pub-9738538046538185. Il est dérivé de l'ID fourni ; confirmer que c'est bien celui du compte AdMob.
7. Lors de l'ajout d'un vrai lien Google Play à la mise en ligne, actualiser la page.

IMPORTANT / PRIVACY
La politique est un premier texte, pas une validation juridique. Compléter l'identité juridique de l'éditeur, son email ou moyen de contact réel, les traitements EXACTS des SDK réellement intégrés, données de consentement, sauvegardes et durées de conservation. Vérifier les déclarations Data safety et la politique des familles si applicable.

INFO TECHNIQUE
Site 100% statique : HTML/CSS, sans dépendance externe, sans cookies ni statistiques web ajoutées.
Les liens internes utilisent /relais-couleurs/ : modifier ce préfixe si vous publiez ailleurs.
Le fichier app-ads.txt à la racine du site peut être partagé entre plusieurs applications AdMob utilisant le même éditeur.
