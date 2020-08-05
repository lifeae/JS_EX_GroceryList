# Apprentissage actif: Une liste de courses dynamique

Pour clore l'article, nous aimerions vous proposer un petit challenge — nous voulons créer une simple **liste de courses** qui nous **permette d'ajouter des items à la liste dynamiquement en utilisant un champ de formulaire et un bouton**. Quand vous ajoutez une valeur au champ et appuyez sur le bouton:

La **valeur du champ doit être ajoutée à la liste**.
**Chaque élément de la liste doit avoir un bouton qui, quand il est pressé, supprime cet élément de la liste**.
**Le champ doit être vidé et prendre le focus pour que vous puissez entrer un autre élément directement**.

Pour compléter l'exercice, suivez les étapes ci-dessous, et assurez-vous que votre exemple se comporte comme décrit ci-dessus.

* Tout d'abord, téléchargez une copie du fichier shopping-list.html. Vous verrez qu'il contient un peu de CSS, un label, champ et bouton, une liste vide et un élément <script>. Vous devrez apporter toutes vos modifications à l'intérieur du script.
* Créez trois variables, contenant des références à la liste <ul>, champ <input>, et bouton <button>.
* Créez une fonction qui est déclenchée lorsqu'on clique sur le bouton.
* À l'intérieur du corps de la fonction, commencez par stoquer la valeur (propriété value) du champ dans une variable.
* Ensuite, videz le champ en définissant sa valeur à une chaîne vide — ''.
* Créez trois nouveaux éléments — un élément de liste <li>, un <span> et <button>, et stockez-les dans des variables.
* Ajoutez le <span> et <button> comme enfant du <li>.
* Définissez le contenu du <span> à la valeur du champ que vous avez récupéré précedemment, et définissez le contenu du boutton à "Supprimer".
* Ajoutez le <li> comme enfant de la liste.
* Ajoutez un gestionnaire d'événément pour le bouton "Supprimer", pour que quand il est cliqué, le <li> dans lequel il se situe est supprimé.
* Finalement, utilisez la méthode HTMLElement.focus pour donner le focus au champ, qu'il soit prêt à recevoir la valeur du prochain élément.

_Note : Si vous êtes vraiment bloqué, vous pouvez regarder notre liste de courses terminée (voir en direct.)_

Source : https://developer.mozilla.org/fr/docs/Apprendre/JavaScript/Client-side_web_APIs/Manipulating_documents