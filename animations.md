## CSS Tricks
https://css-tricks.com/snippets/html/glyphs/

## icon website
icomoon https://icomoon.io
linea http://linea.io/

## Keyframes 
La règle @ @keyframes permet aux auteurs de définir les étapes qui composent la séquence d'une animation CSS. Cela permet de contrôler une animation plus finement que ce qu'on pourrait obtenir avec les transitions.

ex: 
@keyframes moveInLeft {
    0% {
        opacity: 0
        transform: translateX(-10rem)
        /* transform: rotate(0deg); */
    }

    80% {
        transform: translateX(1rem)
    }

    100% {
        opacity: 1
        transform: translate(0)
    }
}

- animation-name: moveInLef
- animation-duration : 5s
- animation-iteration-count: 3
- animation-delay : 3s
- animation-timing-function: ease/ease-in/ease-out/ease-in-out...
more: https://developer.mozilla.org/fr/docs/Web/CSS/animation-timing-function

## backface-visibility
La propriété backface-visibility indique si la face arrière d'un élément doit être visible lorsqu'elle est orientée vers l'utilisateur. La face arrière d'un élément est un arrière-plan transparent qui, lorsqu'il est visible, permet de voir un reflet symétrique de la face avant de l'élément.
- visible / hidden

## state CSS
a:link - a normal, unvisited link
a:visited - a link the user has visited
a:hover - a link when the user mouses over it
a:active - a link the moment it is clicked

## perspective
La propriété perspective détermine la distance entre le plan d'équation z = 0 et la position de l'utilisateur afin de donner une perspective aux objets positionnés dans l'espace 3D. Chaque élément pour lequel la côte (z)est positif sera plus grand et chaque élément pour lequel z est négatif apparaîtra plus petit. La force de cet effet est déterminée par la valeur de cette propriété.

## background-blend-mode
La propriété CSS background-blend-mode définit la façon dont les images d'arrière-plan doivent être fusionnées entre elles et avec la couleur d'arrière-plan.
