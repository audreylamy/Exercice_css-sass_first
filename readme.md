## box-sizing
La propriété box-sizing est utilisée pour modifier le modèle de boîte CSS par défaut qui est utilisé pour calculer la largeur et la hauteur des éléments.
- content-box
- border-box
- inherit
ex : https://developer.mozilla.org/fr/docs/Web/CSS/box-sizing

## background-image
- url
- linear-gradient(#, #)

## background-size
La propriété CSS background-size définit la taille des images d'arrière-plan pour l'élément. La taille de l'image peut être contrainte, complètement ou partiellement afin de conserver ses proportions.
- contain
- cover
- 30%
- 200px 100px;
ex: https://developer.mozilla.org/fr/docs/Web/CSS/background-size

## background-position
La propriété background-position permet de définir la position initiale, relative à l'origine définie par background-origin, pour chaque image d'arrière-plan.
- top/bottom/left/right/center
- 25% 75%
- bottom 50px right 100px;
ex : https://developer.mozilla.org/fr/docs/Web/CSS/background-position

## clip-path
La propriété clip-path empêche une portion d'un élément d'être affichée en définissant une région de rognage. Seule une zone spécifique de l'élément sera affichée. La zone de rognage est un chemin défini avec une URL faisant référence à un SVG externe ou en ligne ou grâce à une fonction de forme comme circle().
- circle(40%)
- ellipse(130px 140px at 10% 20%)
- polygon(50% 0, 100% 50%, 50% 100%, 0 50%);
ex : https://developer.mozilla.org/fr/docs/Web/CSS/clip-path
Clip-path already created : https://bennettfeely.com/clippy/

## position
La propriété position définit la façon dont un élément est positionné dans un document. Les propriétés top, right, bottom et left déterminent l'emplacement final de l'élément positionné.
- static
- relative
top: 40px 
left: 40px
- absolute (parent will be in positon relative)
top: 40px
left: 40px
ex: https://developer.mozilla.org/fr/docs/Web/CSS/position

## display
more : http://fr.learnlayout.com/display.html
- inline-block = grille de boites qui s'adaptent à la largeur du navigateur


## image size
- height: 35px (don't need to specify width)

## transform
La propriété transform modifie l'espace de coordonnées utilisé pour la mise en forme visuelle. Grâce à cette propriété, il est possible de translater les éléments, de les tourner, d'appliquer des homothéties, de les distordre pour en changer la perspective.
- matrix(1, 2, 3, 4, 5, 6)
- translate(120px, 50%) / translate(-50%, -50%) => point de fix = milieu de l'image
- scale(2, 0.5)
- rotate(0.5turn)
- skew(30deg, 20deg)
- scale(0.5) translate(-100%, -100%)
ex : https://developer.mozilla.org/fr/docs/Web/CSS/transform

## background-clip (-webkit-background-clip)
La propriété background-clip définit la façon dont l'arrière-plan d'un élément (que ce soit l'image ou la couleur) s'étend sous la bordure.
- border-box
- padding-box
- content-box
- text
IMPORTANT : -webkit-background-clip = permet de faire couleur degrade texte