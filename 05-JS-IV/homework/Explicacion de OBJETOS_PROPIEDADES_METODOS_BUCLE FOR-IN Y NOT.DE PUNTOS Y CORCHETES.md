1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Objetos
	* Propiedades
	* Métodos
	* Bucle `for…in`
	* Notación de puntos vs notación de corchetes

    1)OBJETOS: 
    
    Un objeto es una colección de propiedades, y una propiedad es una asociación entre un nombre (o clave) y un valor. El valor de una propiedad puede ser una función, en cuyo caso la propiedad es conocida como un método. Además de los objetos que están predefinidos en el navegador, puedes definir tus propios objetos. Este capítulo describe cómo usar objetos, propiedades, funciones y métodos; y cómo crear tus propios objectos.
    En JavaScript, un objeto es un entidad independiente con propiedades y tipos. Compáralo con una taza, por ejemplo. Una taza es un objeto con propiedades. Una taza tiene un color, un diseño, un peso, un material del que está hecha, etc. Del mismo modo, los objetos de JavaScript pueden tener propiedades que definan sus características.

    2)PROPIEDADES:
    
    Las propiedades son las características de un objeto..
    Como estamos con la clase Persona vamos a pensar en las propiedades que nos diferencien unos de otros
    Sexo
    Edad
    .. bueno suficiente para el ejemplo
    como ves, usamos la palabra clave "this" que sirve para decirle a Javascript que estamos hablando de un miembro de la clase. A este le asignamos el valor del parámetro (en el primer caso sexo, en el segundo edad).

    3)METODOS:
    
    Los métodos son subrutinas que manipulan los datos definidos por la clase y, en muchos casos, brindan acceso a esos datos. En la mayoría de los casos, otras partes de tu programa interactuarán con una clase a través de sus métodos.
    Un método contiene una o más declaraciones. En un código Java bien escrito, cada método realiza solo una tarea. Cada método tiene un nombre, y es este el que se usa para llamar al método. En general, puede dar el nombre que desee a un método cualquiera.Un método tendrá paréntesis después de su nombre. Por ejemplo, si el nombre de un método es getval, se escribirá getval() cuando su nombre se usa en una sentencia. Esta notación lo ayudará a distinguir los nombres de las variables de los nombres de los métodos.

    4)BUCLE 'FOR...IN'
    
    La instrucción for-in itera sobre todas las propiedades enumerables de un objeto que está codificado por cadenas (ignorando los codificados por Símbolos, incluidas las propiedades enumerables heredadas.
    Un bucle for...in solo itera sobre propiedades enumerables que no son símbolo. Los objetos creados a partir de constructores integrados como Array y Object han heredado propiedades no enumerables de Object.prototype y String.prototype, como el método indexOf() de String o el método toString() de Object. El bucle iterará sobre todas las propiedades enumerables del objeto en sí y aquellas que el objeto hereda de su cadena de prototipos (las propiedades de los prototipos más cercanos tienen prioridad sobre las de los prototipos más alejados del objeto en su cadena de prototipos).

    
    5)NOTACION DE PUNTOS VS NOTACION DE CORCHETES:
    La notación de puntos solo funciona con nombres de propiedad que son nombres identificadores válidos [espec.] , Así que básicamente cualquier nombre que también sea un nombre válido de variable
    Use la notación de corchetes
    
    Cuando el nombre de la propiedad está contenido en una variable, por ejemplo, obj[foo] .
    El nombre de la propiedad contiene caracteres no permitidos en los identificadores, por ejemplo, comienza con un dígito † , o contiene un espacio o guión ( - ), por ejemplo, obj["my property"] .
    
    Use notación de puntos: en todas las demás situaciones.

    Sin embargo, hay una advertencia sobre las palabras key reservadas. Si bien la especificación permite usarlos como nombres de propiedad y con la notación de puntos, no todos los browseres o herramientas respetan esto (especialmente las versiones anteriores de IE). Por lo tanto, la mejor solución, en mi opinión, es evitar el uso de palabras key reservadas para nombres de propiedad o usar la notación de corchetes si no puede hacerlo.

    †: Esa es también la razón por la que solo puedes usar la notación de corchetes para acceder a los elementos de la matriz. Los identificadores no pueden comenzar con dígitos y, por lo tanto, no pueden consistir únicamente en dígitos.
