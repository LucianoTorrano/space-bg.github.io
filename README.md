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

GIF:<br>

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/91889090/174934638-00161710-dd80-470d-8f8d-b6c8e6f72df7.gif)


<br>
<h3>Espa??ol:</h3>

Fondo the pantalla hecho con HTML5 y Javascript. Las estrellas son din??micas, por lo que cada vez que se refresque la pantalla o cambie el tama??o de la ventana van a aparecer en diferentes posiciones con diferentes tama??os. El fondo es interactivo, si presion??s el click izquierdo del mouse las estrellas comenzaran a acelerar dando una sensaci??n de viaje en el tiempo.

<b>??C??mo lo hice?</b>

Hay dos formas de conseguir el mismo efecto, en ambas vas a necesitar Programaci??n Orientada a Objetos (POO):

  1) La dif??cil: Esta forma es la mas dif??cil porque se requiere algo de matem??ticas y f??sicas. Pod??s crear una clase con el nombre Estrellas. En la funci??n constructora vas a definir la posici??n y el tama??o que ocupar?? cada estrella (estos valores van a ser randoms), adem??s de estos valores vas a necesitar algunos atributos f??sicos como velocidad angular y aceleraci??n ya que cada estrella se deber?? mover a una velocidad distinta a medida que nos alejamos del centro de la pantalla (queremos tener la ilusi??n de estrellas girando alrededor del centro de la pantalla). Despu??s de crear el constructor, solo quedan dos m??todos m??s, uno para dibujar las estrellas en la pantalla (usando funciones que ofrece el objeto canvas) y otra (actualizar) para cambiar la posicion de las estrellas cada vez que se refresca la pantalla.
  2) La facil (Es la forma en la que se hizo en este repositorio): La idea es la misma, vas a necesitar el constructor (sin la velocidad angular ni la aceleraci??n), y los m??todos para dibujar y para actualizar.<br>
    Ac?? esta el truco: No necesitas muchas matem??ticas ni fisicas (necesitas muy poca y es b??sica). En lugar de definir las fisicas de cada una de las estrellas, lo que har??s ser?? definir la pantalla mas grande que el tama??o de la pantalla de la computadora, transladarla a otra posicion y comezar a rotarla cada vez que se refresque la pantalla. Haciendo esto obtendr??s el mismo efecto que antes, pero con menos c??digo y mas sencillo para leer.


Pod??s chequear el efecto aqu??: https://lucianotorrano.github.io/space-bg.github.io/
