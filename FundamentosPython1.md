
## Introducción a la programación.
**Lenguajes naturales vs lenguajes de programación **
 
 Las computadoras tienen su propio lenguaje llamado **Lenguaje Maquina**
 Un conjunto completo de comandos conocidos se llama lista de instrucciones, a veces abreviada IL (por sus siglas en inglés). 
 
 Mientras que los lenguajes naturales se crearon solos 
 
 **¿Qué compone a un lenguaje?**

Sin importar si es lenguaje maquina o natural el lenguaje se compone de los siguientes.

1. Alfabeto: Conjunto de símbolos para formar palabras de un determinado lenguaje
2. Léxico: Conjunto de palabras en un idioma
3. Sintaxis: Conjunto de reglas para hacer oraciones validas
4. Semántica: Conjunto de reglas que hacen que la frase tenga sentido.

**Lenguaje máquina vs lenguaje de alto nivel**

La lista de instrucciones o IL es un alfabeto del lenguaje de maquina, constituye la lengua materna de la computadora.

***Los lenguajes de programación de lato nivel*** permiten a los humanos expresar comando a las computadoras que son ás complejos que los ofrecidos por las IL.

***Un programa escrito en un lenguaje de programación de alto nivel se denomina código fuente*** ( en contraste con el código máquina ejecutado por las computadoras). Del mismo modo, el archivo que contiene el código fuente se denomina archivo fuente.

**Compilación vs. Interpretación**

alfabéticamente – un programa debe estar escrito en un alfabeto reconocible, como romano, cirílico, etc.

léxicamente – cada lenguaje de programación tiene su diccionario y hay que dominarlo; afortunadamente, es mucho más simple y pequeño que el diccionario de cualquier idioma natural;

sintácticamente – cada idioma tiene sus reglas y hay que obedecerlas;

semánticamente – el programa tiene que tener sentido.

Compilado: La computadora lo traduce una vez y es guardado el archivo fuente 
Interpretado: Se interpreta cuando se va a ejecutar.

El intérprete lee el código fuente de la forma habitual en la cultura occidental: de arriba a abajo y de izquierda a derecha. Hay algunas excepciones: se cubrirán más adelante en el curso.

***Compilación vs. Interpretación – Ventajas y Desventajas***
![image](https://user-images.githubusercontent.com/105448434/236584114-bc156387-350e-4354-a0f2-84e2f15cc854.png)

**Python es un lenguaje interpretado. Esto significa que hereda todas las ventajas y desventajas descritas. Por supuesto, agrega algunas de sus características únicas a ambos conjuntos.**

Si deseas programar en Python, necesitarás el intérprete de Python. No podrás ejecutar tu código sin él. Afortunadamente, Python es gratuito. Esta es una de sus ventajas más importantes.

Por razones históricas, los lenguajes diseñados para ser utilizados en la interpretación a menudo se denominan lenguajes de scripting, mientras que la fuente los programas codificados con ellos se denominan scripts. Bien, conozcamos a Python.

## Introducción a Python

**¿Qué es python?**

Lenguaje de programación de alto nivel, orientado a objetos.

Creado por  Guido van Rossum, nacido en 1956 en Haarlem, Países Bajos. Por supuesto, Guido van Rossum no desarrolló y evolucionó todos los componentes de Python.

** Objetivo de python**

1. Un lenguaje **fácil e intuitivo** tan poderoso como los de los principales competidores.
2. De **código abierto**, para que cualquiera pueda contribuir a su desarrollo.
3. El código que es tan **comprensible** como el inglés simple.
4. **Adecuado para tareas cotidianas**, permitiendo tiempos de desarrollo cortos.

**Python tiene dos competidores directos, con propiedades y predisposiciones comparables. Estos son:**

1. Perl - un lenguaje de scripting originalmente escrito por Larry Wall.

2. Ruby - un lenguaje de scripting originalmente escrito por Yukihiro Matsumoto.

** En donde no se utiliza Python **

A pesar de la creciente popularidad de Python, todavía existen algunos nichos en los que Python está ausente o rara vez se ve:

1. Programación de bajo nivel (a veces llamada programación "cercana al metal"): si deseas implementar un controlador o motor gráfico extremadamente efectivo, no se usaría Python.

2. Aplicaciones para dispositivos móviles: este territorio aún está a la espera de ser conquistado por Python, lo más probable es que suceda algún día.

**Python 3 es la versión más nueva (para ser precisos, la actual) del lenguaje. Está atravesando su propio camino de evolución, creando sus propios estándares y hábitos.**

**Implementaciones de Python**

una implementación de Python se refiere a "un programa o entorno que brinda soporte para la ejecución de programas escritos en el lenguaje Python, representado por la Implementación de Referencia de CPython.

CYTHON
***CPython es la implementación del lenguaje Python original (tradicional) escrita en el lenguaje C. Esto es lo que pretende hacer Cython: traducir automáticamente el código de Python (limpio y claro, pero no demasiado rápido) al código "C" (complicado y hablador, pero ágil)***

JYTHON
Para traducir los programas escritos en Python a Java, actualmente 

** ¿Qué necesito para programar en Python? **

Para comenzar tu trabajo, necesitas las siguientes herramientas:

1. Un editor que te ayudará a escribir el código (debe tener algunas características especiales, no disponibles en herramientas simples); este editor dedicado te dará más que el equipo estándar del sistema operativo.

2.Una consola en la que puedas ejecutar tu código recién escrito y detenerlo por la fuerza cuando se sale de control.

3. Una herramienta llamada depurador, capaz de ejecutar tu código paso a paso y te permite inspeccionarlo en cada momento de su ejecución.

***IDLE es un acrónimo de: Integrated Development and Learning Environment (Desarrollo Integrado y Entorno de Aprendizaje).***

![image](https://user-images.githubusercontent.com/105448434/236586485-4b9d5dba-7156-4971-864f-d81c3463321a.png)

el traceback (que es la ruta que recorre el código a través de diferentes partes del programa; puedes ignorarlo por ahora, ya que está vacío en un código tan simple) ;

la ubicación del error (el nombre del archivo que contiene el error, el número de línea y el nombre del módulo); nota: el número puede ser engañoso, ya que Python suele mostrar el lugar donde notó por primera vez los efectos del error, no necesariamente el error en sí;

el contenido de la línea errónea; nota: la ventana del editor de IDLE no muestra números de línea, pero muestra la ubicación actual del cursor en la esquina inferior derecha; utilízalo para localizar la línea errónea en un código fuente largo;

el nombre del error y una breve explicación.

## Funcion Print
** Funciones en Python **

Caracteres de escape y nueva línea en Python:

***La barra invertida (\) tiene un significado muy especial cuando se usa dentro de cadenas - se llama carácter de escape.***

Tanto la barra invertida como n forman un símbolo especial llamado un carácter de nuevalínea, que insta a la consola a iniciar una nuevalínea de salida.

** Argumentos de palabra clave**

1. END: Determina el final del primer argumento y enseguida llama el siguiente argumento.

![image](https://user-images.githubusercontent.com/105448434/236648743-a7d24eff-a11f-4c07-a09f-5ddf34b0dbe3.png)

2. SEP: Separa los argumentos con caracteres designados.

![image](https://user-images.githubusercontent.com/105448434/236649431-023a35e6-4a42-4c07-ba8e-819fc79674ee.png)

## Tipos de datos en Python

**1. Datos enteros**

**Números octales.**

Para convertir numeros octales se utiliza la siguiente conversion
print(0x123) el prefijo 0x

**Número hexadecimales**

Se utiliza el prefio 0x.
print(0x123)

***A continuación presento un ejemplo de como se calculan estos numeros matematicamente**

![image](https://user-images.githubusercontent.com/105448434/236647822-7c1dd451-366e-4059-af9c-13eb4ea92a5a.png)

**2. Datos flotantes**

Son números que tienen (o pueden tener) una parte fraccionaria después del punto decimal, y aunque esta definición es muy pobre, es suficiente para lo que se desea discutir.

**3. Cadenas**

Texto 

** 4. Valores Booleanos**

Se aplica para verificar true(1) o false(0)

No son tan obvios como los anteriores y se emplean para representar un valor muy abstracto - la veracidad.

## RESUMEN SECCIÓN TIPO DE DATO 

1. Los literales son notaciones para representar valores fijos en el código. Python tiene varios tipos de literales - es decir, un literal puede ser un número por ejemplo, 123), o una cadena (por ejemplo, "Yo soy un literal.").

2. El sistema binario es un sistema numérico que emplea 2 como su base. Por lo tanto, un número binario está compuesto por 0s y 1s únicamente, por ejemplo, 1010 es 10 en decimal.

Los sistemas de numeración Octales y Hexadecimales son similares pues emplean 8 y 16 como sus bases respectivamente. El sistema hexadecimal utiliza los números decimales más seis letras adicionales.

3. Los enteros (o simplemente int) son uno de los tipos numéricos que soporta Python. Son números que no tienen una parte fraccionaria, por ejemplo, 256, o -1 (enteros negativos).

4. Los números punto-flotante (o simplemente flotantes) son otro tipo numérico que soporta Python. Son números que contienen (o son capaces de contener) una parte fraccionaria, por ejemplo, 1.27.

5. Para codificar un apóstrofe o una comilla dentro de una cadena se puede utilizar el carácter de escape, por ejemplo, 'I\'m happy.', o abrir y cerrar la cadena utilizando un conjunto de símbolos distintos al símbolo que se desea codificar, por ejemplo, "I'm happy." para codificar un apóstrofe, y 'El dijo "Python", no "typhoon"' para codificar comillas.

6. Los valores booleanos son dos objetos constantes True y False empleados para representar valores de verdad (en contextos numéricos 1 es True, mientras que 0 es False.


  Extra  

Existe un literal especial más utilizado en Python: el literal None. Este literal es llamado un objeto de NoneType, y puede ser utilizado para representar la ausencia de un valor. Pronto se hablará más acerca de ello.

## Operadores básicos.

Residuo (módulo)
El siguiente operador es uno muy peculiar, porque no tiene un equivalente dentro de los operadores aritméticos tradicionales.

Su representación gráfica en Python es el símbolo de % (porcentaje), lo cual puede ser un poco confuso.

EXPONENTE ** UTILIZA ENLAZADO DE LADO DERECHO 

![image](https://user-images.githubusercontent.com/105448434/236657435-bd4d6de8-42f6-43a9-b4ae-4beeb5ad559e.png)

2.3.4 RESUMEN DE SECCIÓN
Puntos Clave
1. Una expresión es una combinación de valores (o variables, operadores, llamadas a funciones, aprenderás de ello pronto) las cuales son evaluadas y dan como resultado un valor, por ejemplo, 1 + 2.

2. Los operadores son símbolos especiales o palabras clave que son capaces de operar en los valores y realizar operaciones matemáticas, por ejemplo, el * multiplica dos valores: x * y.

3. Los operadores aritméticos en Python: + (suma), - (resta), * (multiplicación), / (división clásica: regresa un flotante siempre), % (módulo: divide el operando izquierdo entre el operando derecho y regresa el residuo de la operación, por ejemplo, 5 % 2 = 1), ** (exponenciación: el operando izquierdo se eleva a la potencia del operando derecho, por ejemplo, 2 ** 3 = 2 * 2 * 2 = 8), // (división entera: retorna el número resultado de la división, pero redondeado al número entero inferior más cercano, por ejemplo, 3 // 2.0 = 1.0)

4. Un operador unario es un operador con solo un operando, por ejemplo, -1, o +3.

5. Un operador binario es un operador con dos operandos, por ejemplo, 4 + 5, o 12 % 5.

6. Algunos operadores actúan antes que otros, a esto se le llama - jerarquía de prioridades:

El operador ** (exponencial) tiene la prioridad más alta;
Posteriormente los operadores unarios + y - (nota: los operadores unarios a la derecha del operador exponencial enlazan con mayor fuerza, por ejemplo 4 ** -1 es igual a 0.25)
Después *, /, //, y %,
Finalmente, la prioridad más baja: los operadores binarios + y -.
7. Las sub-expresiones dentro de paréntesis siempre se calculan primero, por ejemplo,  15 - 1 * ( 5 *( 1 + 2 ) ) = 0.

8. Los operadores de exponenciación utilizan enlazado del lado derecho, por ejemplo, 2 ** 2 ** 3 = 256.

## Variables cajas con forma de datos

![image](https://user-images.githubusercontent.com/105448434/236677082-b19a9f76-d97f-4dc7-a486-85376cb79c59.png)

**Nombres de variables**

1.El nombre de la variable debe de estar compuesto por MAYÚSCULAS, minúsculas, dígitos, y el carácter _ (guion bajo)

2.El nombre de la variable debe comenzar con una letra;

3.El carácter guion bajo es considerado una letra;
Las mayúsculas y minúsculas se tratan de forma distinta (un poco diferente que en el mundo real - Alicia y ALICIA son el mismo nombre, pero en Python son dos nombres de variable distintos, subsecuentemente, son dos variables diferentes);

4.El nombre de las variables no pueden ser igual a alguna de las palabras reservadas de Python (las palabras clave - explicará más de esto pronto).

**Buenas practicas para el nombramiento de variables**

1. Nombre de las variables debe estar en minuscula
2. Los nombres de funciones pueden empezar por fun, por ejemplo fun_suma
3. Se puede utilizar letras mixtas

![image](https://user-images.githubusercontent.com/105448434/236679317-a9e3522a-1602-4f98-abb3-2b6d823d7a27.png)

** Cómo crear una variable**

***Una variable se crea cuando se le asigna un valor. A diferencia de otros lenguajes de programación, no es necesario declararla.***

var = 1
print(var)

***Nota para concatenar en una funcion print se utiliza el simbolo (+) sin embargo deben ser el mismo tipo de dato, si este no es el caso es mejor utilizar (,)***

**OPERACIONES ABREVIADAS EN PYTHON**

![image](https://user-images.githubusercontent.com/105448434/236678600-678e7cdc-c670-438d-9500-af253ff4c158.png)

## Mutabilidad de las variables

Nivel avanzado

Las variables son nombres, no lugares. Detrás de esta frase se esconde la reflexión de que cuando asignamos un valor a una variable, lo que realmente está ocurriendo es que se hace apuntar el nombre de la variable a una zona de memoria en el que se representa el objeto (con su valor).

![image](https://user-images.githubusercontent.com/105448434/236679752-5806e68b-e602-41cb-91fe-23a8ad35c2a4.png)

***Los objetos mutables son aquellos que aunque cambien su valor no implica un cambio en la posición de memoria de la variable***

![image](https://user-images.githubusercontent.com/105448434/236679841-0892db31-003e-434b-93bc-e4e0961a98e5.png)







