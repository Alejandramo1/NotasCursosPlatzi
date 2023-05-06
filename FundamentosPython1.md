
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




