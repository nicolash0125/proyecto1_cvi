# Proyecto 1 Computación visual interactiva
## Una escena procedimental, propia y compleja
### Realizado por: Nicolás Hernández Siachoque - 201716434

Para este proyecto se empleo la herramienta Blender.

La escena es una representación de la Universidad de los Andes.

Primero se realiza el suelo y las calles por medio de cubos con anchos angostos

Luego se realiza la construcción del edificio ML empleando cubos que se transforman en sus dimensiones con un marco local de referencia. Son transladados a la ubicación correspondiente. En el techo del edificio se encuentran unas tuberias realizadas con cilindros. Al frente del edificio se encuentran las banderas que constan de un mastil cilindrico rematado por una esfera. Las banderas son rotadas respecto al eje Z de tal manera que no se crucen entre ellas. Tambien se encuentran 7 estudiantes. Un estudiante está conformado de 2 cilindros para las piernas, un cilindro para los brazos, un cubo para el cuerpo y una esfera para la cabeza. Solo se define la translación para el marco global del primer estudiante, ya que en el ciclo, se realizan transformaciones en el marco local con el fin de ubicar los estudiantes restantes, respecto al principal.

La construcción del edificio W cuenta con 2 cubos principales y el puente que conecta con el edificio ML. Además se encuentran las escaleras que son unos cubos para cada peldaño que, por medio de un ciclo, aumentan en altura. Al lado se encuentra un muro que separa con el edificio Z que al ser demolido solo se representa con un cubo. 

Finalmente se encuentra el parque Espinoza. Se construye un arbol con cilindro para el tronco y esferas para las hojas. Este arbol se vuelve a generar en un ciclo y es transladado según el marco local. Las ubicaciones de los nuevos arboles estan predefinidas por un vector.
