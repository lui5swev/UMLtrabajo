"Calculadora" es una clase que sirve para hacer algunas operaciones matematicas segun 2 numeros entregados, 
y "Carro compra" tiene un array con numeros y sus propios metodos, con ella podemos pobrar la clase calculadora, bajo el contexto de que
es un carro de compra y cada producto tiene un valor al cual le calcularemos su total.

Clase Claculadora:
posee los atributos "n1" y "n2" los cuales seran las variables a establecer al llamar al metodo calculadora para realizar operaciones.
el primer constructor ("Calculadora()") inicializa los atributos en 0, el segundo ("Calculadora(int, int)") asigna los valores ingresados a
la clase calculadora como los atributos n1 y n2, para realizar las operaciones dentro de la clase calculadora, el metodo sumar() suma 
estos dos numeros, el metodo multiplicar() multiplica estos dos numeros, y los setters son para cambiar de valor a los numeros 
si quisieramos que fueran distintos a los asignados inicialmente.

Clase CarroCompra:
posee el atributo productos, que es un array de 2x5 en el cual guardaremos los valores de cada "producto"
el primer inicializador establece todos los valores de la primera fila como 1, y todos los de la segunda fila como 1000.

el metodo calcularTotal() suma todos los valores del resultado de la multiplicacion entre productos de la fila 1 con los de la fila 2, 
usando un loop for iterando en cada columna, para hacer la multiplicacion, utiliza el metodo subTotal()

el metodo subTotal(), aqui inicia una objecto calculadora para multiplicar los dos valores de las columnas del array "productos".

Finalmente tenemos el metodo mostrarTotal() que imprime en pantalla el total de la compra resultado de el calcularTotal()