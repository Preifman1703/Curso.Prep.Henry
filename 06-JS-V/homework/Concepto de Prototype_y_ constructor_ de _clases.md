1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* `prototype`
* _Constructors_ (de Clases)

1) `prototype`:
Es una propiedad que tienen todos los objetos de JavaScript, el cual representa el prototipo de cada objeto. 
ejemplo array => tiene  su 'Prototype' y => el de los objetos de array => tiene sus __proto__, son todas "funciones".

2) _Constructors_ (de Clases):

El constructor, como su nombre indica, es el código que construye y configura un objeto cuando se crea con new. Todas las clases tienen un constructor, si no escribimos nada dentro de class se crea por defecto un constructor vacío. Si queremos escribir un constructor por nosotros mismos tenemos que incluir una función llamada constructor dentro del cuerpo de la clase.

En el caso de function es el cuerpo de la función la que hace de constructor, de hecho, se les suele llamar funciones constructoras para diferenciarlas de las funciones que no se van a utilizar con new.

El constructor se incluye automáticamente en el prototipo como propiedad constructor y se crea una anidación, ya que ese constructor a su vez tiene una propiedad prototype que a su vez tiene una propiedad constructor que apunta al inicio.