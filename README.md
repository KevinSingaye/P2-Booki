# P2-Booki


Deuxième projet du parcours openclassroom

### L'objectif est d'intégrer la maquette d'un site de planification de vacances nommé "Booki" (voir l'image ci-dessous).

![Boooki](https://user-images.githubusercontent.com/75949789/205314712-7cbf5209-69cb-4c35-823a-9409f9efa104.png)

### Spécifications fonctionnelles et contraintes techniques

#### Fonction Description
#### Fonction recherche

● Les usagers pourront rechercher des hébergements dans la ville de leur choix.
● Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être
édité par l’utilisateur.
● Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas
être fonctionnelle - il s’agit d’une première version pour valider l’interface.

#### Cartes hébergements et activités

● Chaque carte d’hébergement ou d’activité devra être cliquable dans son
intégralité (pas uniquement le titre).
● Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour
simuler la présence d’un lien.

#### Filtres de recherche

● Les hébergements peuvent être filtrés par thématique, comme le budget ou
l’ambiance.
● Les filtres doivent changer d’apparence au survol. Par contre, ils ne doivent pas
être fonctionnels - il s’agit d’une première version pour valider l’interface..

#### Liens
“Hébergements” et “Activités”

● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils
doivent mener respectivement vers la section “Hébergements à Marseille” et
“Activités à Marseille”.

#### Spécifications techniques
Thème Informations techniques
Maquettes : Trois maquettes ont été réalisées : desktop, tablette et mobile.

#### Breakpoints

Nous avons convenu avec le designer UI d’utiliser 992 px et 768 px :
● >=992 px pour les écrans d’ordinateurs ;
● >=768 px pour les tablettes ;
● et tout ce qui est en dessous de 768 pour les téléphones portables.

#### Largeur max
Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer
une largeur maximum de 1 400 px.

#### Desktop first
Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first),
puis les tablettes et enfin les téléphones. L’utilisation des Media Queries nous permettra
de réaliser l’intégration pour les différents supports.

#### Bibliothèque
d’icônes
Les icônes proviennent de la bibliothèque Font Awesome.
Couleurs
Les couleurs de la charte sont le bleu (#0065FC), une version plus claire de ce bleu
(#DEEBFF) et le gris pour le fond (#F2F2F2).

#### Police
La police du site est Raleway. Nous pouvons passer par Google Fonts pour importer
facilement cette police dans le code : https://fonts.google.com/specimen/Raleway.
Mise en page Il est recommandé d'utiliser Flexbox.
#### Balises sémantiques
Il est important d’utiliser des balises sémantiques, au minimum “header”, “nav”,
“h1-h2-h3”, “main”, “section”, “article” et “footer”.

#### Validité du code

● Afin d’harmoniser les outils avec toute l’équipe, il faudra utiliser l’IDE Visual Studio
Code pour le développement du site.
● Le code doit être valide aux validateurs W3C HTML et CSS.
● Le code HTML ne doit pas contenir de propriété CSS.
● Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code
HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la
loupe).
● Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser
le nom de l’élément lui-même.
● Ne pas dupliquer des classes CSS inutilement. Exemple : si 4 éléments sont
identiques du point de vue de la mise en forme, alors utiliser une seule et même
classe CSS, et non pas 4.
#### Compatibilité navigateurs

La maquette doit être compatible avec les dernières versions de Google Chrome et de
Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.
Restrictions
Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass
ou Less) ne doit être utilisé.

Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).



Decouvrez le site ici : https://kevinsingaye.github.io/P2-Booki/

