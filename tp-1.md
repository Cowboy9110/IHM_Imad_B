TP1 – IHM / UCD

1) Besoin(s) utilisateur

Définition d’un besoin utilisateur :
Un besoin utilisateur est un objectif ou une attente qu’une personne souhaite accomplir en utilisant une interface. En d’autres termes, c’est quelque chose que l’interface doit permettre de faire de manière simple, sans confusion ni effort inutile de la part de l’utilisateur. (Par exemple, retourner sur la page d'accueil.)

Besoin adressé par mon interface(s) Figma :

Dans mon projet Figma (un site mobile axé sur la plongée sous-marine), j’ai veillé à répondre au besoin de simplicité et de clarté de la navigation. Par exemple, j’ai intégré une barre de navigation clairement visible en haut de l’écran et adopté des couleurs cohérentes avec le milieu marin, afin que l’utilisateur puisse passer rapidement d’une section à l’autre sans surcharge visuelle ni désorientation.

2) Processus du Design Centré Utilisateur (UCD)

Étapes UCD (rappel synthétique) :

Observation & analyse du contexte d’utilisation et des utilisateurs.

Identification des besoins des utilisateurs.

Conception de solutions (création de maquettes ou prototypes).

Tests utilisateur sur les prototypes et recueil des retours.

Améliorations itératives du design en fonction des retours utilisateurs.

Étape actuelle de mon projet :
Je me trouve actuellement à l’étape de conception/prototypage – je réalise des maquettes de l’interface mobile dans Figma (structure de l’application, écrans principaux, etc.).

Si une étape antérieure manque :
Si je n’ai pas réalisé une des étapes précédentes du processus UCD, je la complète dès maintenant. Par exemple, initialement je n’avais pas formalisé les besoins utilisateurs avant de commencer la maquette. J’ai donc corrigé cela : j’ai défini un persona (profil type d’un utilisateur plongeur) et listé ses besoins principaux, puis j’ai ajouté ces documents au dépôt git en tant que preuve. Ainsi, toutes les étapes du processus UCD sont bien prises en compte avant de poursuivre le projet.

3) Observateurs dans Figma

Observateurs ajoutés (qui / rôles) :
J’ai invité quelques camarades de classe à accéder à mon projet Figma en tant qu’observateurs (utilisateurs de test). Ils ont la possibilité de commenter la maquette et de donner leur avis sur l’interface.

Principe UCD appliqué :
Cette démarche applique un principe fondamental du design centré utilisateur : l’implication des utilisateurs dans le processus de conception. En faisant intervenir de futurs utilisateurs ou des pairs pour qu’ils testent et commentent tôt la maquette, je récolte des retours précieux et j’oriente les itérations du design en fonction de leurs besoins réels.

4) Calques (layers) dans Figma

Définition :
Dans Figma, un calque représente chaque élément de l’interface (par exemple un bouton, un bloc de texte, une image, etc.). Autrement dit, tous les objets que l’on place dans la maquette apparaissent comme des calques dans la liste des layers du projet.

Bonnes pratiques :

Nommer chaque calque de façon explicite (par exemple Bouton_Valider au lieu du nom par défaut) pour s’y retrouver facilement.

Regrouper les calques par sections logiques à l’aide de Frames ou de groupes (par exemple regrouper tous les éléments d’un même écran dans un frame) afin d’organiser la structure.

Verrouiller les calques qui ne doivent pas être modifiés (par exemple un arrière-plan fixe) pour éviter de les déplacer par erreur.

Conserver une hiérarchie claire et simple dans l’arborescence des calques (des noms et un ordre cohérents) de sorte à naviguer aisément dans le projet Figma et à maintenir la maquette bien structurée.

5) Composants (réutilisables) dans Figma

Définition :
Un composant est un élément d’interface réutilisable que l’on définit une fois pour pouvoir l’employer à plusieurs endroits du projet. Par exemple, on peut créer un composant pour un bouton standard ou pour la barre de navigation. L’intérêt est que toutes les instances copiées depuis ce composant resteront liées : en modifiant le composant principal, toutes ses occurrences dans le projet se mettront à jour automatiquement, assurant une cohérence globale.

Exemples créés/utilisés :
Dans mon projet, j’ai commencé par créer un composant de bouton principal (par exemple pour les actions du type “Valider” ou “S’inscrire”). Ce bouton de base pourra ainsi être réutilisé sur plusieurs écrans sans avoir à le recréer à chaque fois. De même, je prévois de convertir la barre de navigation supérieure en composant, de façon à l’insérer telle quelle sur toutes les pages de l’application tout en pouvant la mettre à jour en un seul endroit si nécessaire.

6) Design system – Boutons primaires, secondaires, tertiaires

Styles de boutons définis :
Dans une optique de design system cohérent, j’ai défini trois styles de boutons hiérarchisés : un bouton primaire, un bouton secondaire et un bouton tertiaire. Le bouton primaire correspond à l’action principale à mettre en avant sur un écran (par exemple “Commencer une plongée” ou “Réserver”), il est donc visuellement le plus accentué – par exemple rempli de la couleur dominante du site (bleu océan) avec un texte de couleur contrastée. Le bouton secondaire sert pour des actions moins prioritaires ; il est présenté avec un style un peu moins prononcé (par exemple contour coloré avec fond transparent ou d’une teinte plus neutre). Enfin, le bouton tertiaire est le plus discret et s’utilise pour des actions alternatives ou moins importantes (par exemple un simple lien texte cliquable ou un bouton avec un style minimaliste).

États et feedback (variants) :
Pour chacun de ces boutons (primaire, secondaire, tertiaire), j’ai créé des variantes d’état afin de garantir un feedback visuel pour chaque interaction de l’utilisateur. Concrètement, j’ai défini les états suivants : un état normal (par défaut), un état au survol (hover – pour la version web, le bouton change légèrement de couleur ou d’opacité lorsque la souris passe dessus), un état actif/pressé (lorsque l’utilisateur clique ou appuie, le bouton devient par exemple plus foncé pour indiquer l’enfoncement) et un état désactivé (quand l’action n’est pas disponible, le bouton apparaît grisé ou semi-transparent). Grâce à la fonctionnalité de variantes de Figma, ces états sont regroupés dans un même composant bouton. Ainsi, à l’utilisation, le bouton fournit un retour visuel immédiat à chaque état : l’utilisateur sait qu’il peut cliquer (changement au survol), voit quand il clique (changement à l’appui), et comprend si le bouton est inactif (aspect grisé si désactivé). Ce feedback renforce l’intuitivité et l’expérience utilisateur lors de l’interaction avec les boutons.

7) Wayfinding (guidage de l’utilisateur)

Définition du wayfinding :
Le wayfinding désigne l’ensemble des éléments et mécanismes de navigation qui aident l’utilisateur à s’orienter dans une interface. Cela comprend les repères visuels ou textuels qui indiquent à l’utilisateur où il se trouve dans l’application/site, d’où il vient et comment aller vers d’autres sections. En d’autres termes, c’est “l’art du guidage” dans l’interface : fournir des indices pour que l’utilisateur sache toujours quelle page ou section il regarde et comment naviguer aisément vers une autre.

Implémentation dans mes interfaces :
Dans mon projet, j’ai appliqué le principe de wayfinding de plusieurs façons. D’abord, la barre de navigation affiche clairement la section active : par exemple, l’onglet ou l’icône correspondant à la page en cours est mis en évidence (couleur ou surbrillance particulière) pour que l’utilisateur repère instantanément où il se situe dans le site. Ensuite, chaque écran comporte un titre explicite (et pourrait inclure un fil d’Ariane le cas échéant) afin de contextualiser la page et de rappeler à l’utilisateur la section ou la catégorie dans laquelle il se trouve. Enfin, j’ai rendu le logo du site (positionné en haut de l’écran) cliquable à tout moment, ce qui permet à l’utilisateur de revenir à l’accueil facilement depuis n’importe quelle page – une bonne pratique courante qui contribue au wayfinding en offrant un point de repère constant pour se réorienter.

8) Affordance d’un bouton (Don Norman)

Assurer l’affordance d’un bouton :
Selon Don Norman, l’affordance d’un élément représente les indications visuelles qui suggèrent à l’utilisateur comment cet élément peut être utilisé. Pour qu’un bouton communique bien sa fonction (cliquer pour effectuer une action), je m’assure de plusieurs points :

Utiliser des signifiants visuels explicites dans le design du bouton – par exemple une forme rectangulaire avec des bords arrondis, un effet de relief ou une ombre portée, et une couleur contrastée – de sorte qu’il ressemble visuellement à un bouton interactif plutôt qu’à un simple texte.

Ajouter un libellé clair (texte du bouton) et éventuellement une icône évocatrice qui indiquent l’action du bouton. L’utilisateur doit comprendre immédiatement ce que le bouton fait s’il clique dessus.

Fournir un feedback instantané lors de l’interaction pour renforcer l’affordance : par exemple, le bouton change légèrement d’apparence au moment où on le touche/clique (changement de couleur ou de luminosité pour simuler la pression), et sur un site web le curseur qui se transforme en forme de main au survol du bouton. Ces retours visuels et comportementaux signalent à l’utilisateur qu’il peut interagir avec le bouton et qu’il se passe quelque chose lorsqu’il le fait. Ainsi, en soignant l’apparence et les réactions du bouton, on s’aligne sur les principes de Don Norman afin que l’utilisateur perçoive naturellement que cet élément est cliquable et invitant à l’action.