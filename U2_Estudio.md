En la entidad estan las senales tambien presentes de forma implicita.

Señales Internas:
-interconectar componentes (Intanciacion)
-Para procesamiento (cambiar sus valores durante el desarrollo del algoritmo)

En las decripciones funcionales 

Señales externas

Por la conmutacion el contador 0 -59 consume una menor potencia.

- combinacional
- secuencial

Entre 60 y 1000 Hz  se realiza el switcheo para ver siempre encendido los display

None of the tri-color signals are driven with more than a 50% duty cycle
(Se necesita la conmutacion)

-----

Post Silicio -> Validacion (Ya en fisico el prototipo)

Pre Silicio -> Verificar

Verificacion : Simulacion logica

Verilog 2001 en Vivado desde 2018

### Elementos Fundamentales
Comentarios
// De una Linea

/*De varias lineas */

Identificadores: para reconocer las variables
- Caracteres, letrasm numeros, _
- Pueden iniciar con letra o con _
- Verilog es “sensible” a mayúscula


Tipos de datos: oNet (wire) o Register (reg, integer)

subtipos: wire, reg, integer.

Variables no almacenadas (net)

Flip-Flop Register

Modulo: Funcion Principal 
Se puede anidar submodulos

Directivas:

Codigo es el ejecutable
Include: Copia y pega texto y lo agrega al principal.
Define: Redifinimos texto

timescale (Para simulacion)

always es equiparable a process


![[pic.png]]

Concurrentes (fuera del processs)
(Multiplexeo de tareas)

Operador asignacion <= en VHDL

Dentro de un always seran concurrentes en Verilog (Sentencias de bloqueo y no Bloqueo)

----

3 Tipos de descripciones

Comportamental / De alto nivel / algoritmica

Flujo de Datos / Todas las sentencias utiliza concurrentes 
- Efecto al mismo tiempo.
- 

En Hardware la concurrencia es paralela
(Always)
assign 

base format decil predeterminada

Objetos de Datos en Verilog

Variables 
Constantes

Parameter es para constantes (Declara y definirla)

Variables se pueden solo declarar

reg tamano por omision es un bit
valor inicial desconocido

integer valor inicial cero

Practica viernes 17 (Contador Verilog)
revisiones de 9 a 10
- Diagrama de flujo
- Luego cada componente

La mayoria de los sistemas el RESET es en bajo
RC232 serial usa logica negativa

