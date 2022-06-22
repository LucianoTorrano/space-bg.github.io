# space-bg.github.io
<h3>English:</h3>

Space background made with HTML5 Canvas and JS. The stars are dinamic, so every time you refresh or change the size of the screen 
they will appear in different locations and with different sizes. This background is interactive, if you press the left button of
your mouse the stars will speed up giving the sensation of a space travel.

<b>How I made it?</b>

There are two different ways to get the same effect, in both you have to use POO:

  1) The hardest: This way is more difficult becouse you will need some maths formulas and physics. You can create a class named Stars. In the constructor function you set the position in the screen and size (this values are going to be random) then you will have to add some physics properties such as angular velocity and aceleration becouse every particle will move at a different speed as we go further from the center (we want to have the illusion of the stars spinning around the center of the screen). After you create the constructor, there are two methods left one to draw the star in the screen (using canvas functions) and other (update) to change the position in the screen everytime the screen refresh the state.
  2) The easiest (the way that it is made in this repository): The idea is the same, you will need the constructor(without angular velocity and acceleration) and the methods draw() and update().<br>
   The difference is that here you don't need a lot of math or phyisic (you need some, but very basic). And that is becouse you aren't going to program every star movement, instead you will set the screen size bigger than the actual computer screen, translate it to another position and then rotate it everytime the screen refresh. Doing this you will have the same effect but with less code and more easy to read.


You can check this background here: https://lucianotorrano.github.io/space-bg.github.io/
<br>
<br>
<h3>Español:</h3>

Fondo the pantalla hecho con HTML5 y Javascript. Las estrellas son dinámicas, por lo que cada vez que se refresque la pantalla o cambie el tamaño de la ventana van a aparecer en diferentes posiciones con diferentes tamaños. El fondo es interactivo, si presionás el click izquierdo del mouse las estrellas comenzaran a acelerar dando una sensación de viaje en el tiempo.

<b>¿Cómo lo hice?</b>

Hay dos formas de conseguir el mismo efecto, en ambas vas a necesitar Programación Orientada a Objetos (POO):

  1) La difícil: Esta forma es la mas difícil porque se requiere algo de matemáticas y físicas. Podés crear una clase con el nombre Estrellas. En la función constructora vas a definir la posición y el tamaño que ocupará cada estrella (estos valores van a ser randoms), además de estos valores vas a necesitar algunos atributos físicos como velocidad angular y aceleración ya que cada estrella se deberá mover a una velocidad distinta a medida que nos alejamos del centro de la pantalla (queremos tener la ilusión de estrellas girando alrededor del centro de la pantalla). Después de crear el constructor, solo quedan dos métodos más, uno para dibujar las estrellas en la pantalla (usando funciones que ofrece el objeto canvas) y otra (actualizar) para cambiar la posicion de las estrellas cada vez que se refresca la pantalla.
  2) La facil (Es la forma en la que se hizo en este repositorio): La idea es la misma, vas a necesitar el constructor (sin la velocidad angular ni la aceleración), y los métodos para dibujar y para actualizar.<br>
    Acá esta el truco: No necesitas muchas matemáticas ni fisicas (necesitas muy poca y es básica). En lugar de definir las fisicas de cada una de las estrellas, lo que harás será definir la pantalla mas grande que el tamaño de la pantalla de la computadora, transladarla a otra posicion y comezar a rotarla cada vez que se refresque la pantalla. Haciendo esto obtendrás el mismo efecto que antes, pero con menos código y mas sencillo para leer.


Podés chequear el efecto aquí: https://lucianotorrano.github.io/space-bg.github.io/
