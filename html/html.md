# krkn:tablalwa

## html

On va forcément être peu souvent amenés à écrire des documents html tels quels, puisqu'ils seront pour la plupart générés par le code serveur.

Ceci dit, pour les documents écrits directement en html :

* Indentation à 4 espaces
* Encodage en `utf-8`
* Respect de la syntaxe xml
    * pas de balise d'ouverture sans balise de fermeture
    * les balises uniques sont fermées : `<br />`
    * balises & attributs en minuscule
    * les attributs booléens **doivent** avoir une valeur
* Le contenu d'un élément de type `block` doit être à la ligne, celui d'un élément `inline` peut être au choix à la ligne ou non (exception notable : la balise `<p>`).
* À l'exception notable d'*html5shiv* pour IE, les balises `<script>` sont déclarées en fin de `<body>`.
