# Intégration de la landing page

La page `index.html` reprend la structure des captures fournies. C’est une reconstruction à vérifier, pas un export des sources originales. Aucun déploiement n’a été effectué.

## Médias à ajouter dans assets/

Les fichiers joints à la conversation ne sont pas encore transférés dans ce dépôt. Comparer les images avant de les renommer ; les noms des fichiers sources ne permettent pas de tous les identifier avec certitude.

| Chemin attendu | Contenu |
| --- | --- |
| assets/hero.png | Shelby à la guitare devant les bateaux bleus |
| assets/portrait.png | Portrait souriant dans le décor avec planche de surf |
| assets/concert-gent.png | Affiche Concert in Gent |
| assets/festival-au-carre.png | Duo devant le panneau Festival au carré |
| assets/live-guitare.png | Shelby chantant à la guitare sous la tente |
| assets/live-profil.png | Autre vue de Shelby à la guitare |
| assets/scene.png | Photo sur scène avec les lumières roses |
| assets/dossier-de-presse-shelby-ouattara.pdf | PDF de presse fourni |

Certains fichiers photo fournis contiennent la barre système en bas : la retirer avant intégration, en conservant le sujet. Ne pas employer une capture de page entière comme image du site.

## Informations et vérifications restantes

- Intégrer l’URL officielle du clip Shine à la place du bloc temporaire.
- Vérifier les textes de biographie reconstruits depuis les captures avec le PDF de presse.
- Instagram fourni : https://www.instagram.com/shelby.ouattara/
- Confirmer les URL Facebook, Spotify, YouTube et le numéro WhatsApp avant de les ajouter. Ils ne sont pas inventés dans la page.
- Le formulaire prépare un e-mail via mailto ; il n’envoie pas automatiquement de message. Une réception serveur nécessiterait une implémentation supplémentaire.
- Vérifier les médias, les liens, la mise en page mobile, le clavier et le formulaire dans un navigateur.
- La police est chargée depuis Google Fonts ; les polices système prennent le relais en cas d’échec.

## Exécution

Page statique HTML/CSS/JS, sans dépendance de compilation. Servir le dossier racine via HTTP après ajout des médias. Aucun test navigateur ni exécution locale n’a pu être réalisé lors de la préparation.
