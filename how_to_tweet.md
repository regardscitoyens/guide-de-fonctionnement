# Tweeter via IRC avec gazouilleur

Pour envoyer des tweets depuis l'IRC de RegardsCitoyens (#regardscitoyens@irc.freenode.net), le bot gazouilleur2 dispose de plusieurs commandes :

- !count : pour compter le nombre de caractères d'un message

- !twitter (ou !tweet) : pour envoyer le message sur Twitter

- !rt +id_tweet : pour retweeter le tweet correspondant à cet id

- !answerlast : pour envoyer un message en réponse directe au dernier tweet envoyé (et non affiché)

- !answer +id_tweet : ex: !answer 690266444404252672 pour envoyer un message en réponse au tweet correspondant à cet id

- Pour poster un tweet avec une image :
 + mettre l'image en ligne quelque part, par exemple sur https://framapic.org/
 + ajouter à la fin des commande !twitter !answer ou !answerlast, après le texte du tweet ; "img:+lien_image" (sans espace entre : et l'url de l'image)

- !runlater +n_minutes +commande : ex !runlater 10 !rt 690266444404252672 pour programmer dans n_minutes la commande souhaitée

- !tweetlater + n_minutes : équivalent de !runlater !n_minutes !twitter
