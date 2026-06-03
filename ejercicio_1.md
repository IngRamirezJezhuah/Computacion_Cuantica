# ejercicio re un qubit real 
para amplitu de alfa y beta son de 0.43 y la beta de -0.90, la amplitu seria menos 0.50

> [!note] notas

la notacion de la base computacional de un qbit en el rango de los gets de 0 y 1 es en vectorews columba de un vector base un get de estado 0 en un vector columna

0 = [1]   COMO LO QUE VIERON PARA LOS PASOS ES ESCRIBIR 
    [0]    LOS GET DE O Y UNO como 

    ![alt text](image.png)

    para la solucion combierten los get en vectories vertivales y hacen la suma oh como es un factor negativo una resta
    y da el resultado de un vector de sobre raiz de 2

    la regla de born, 

    transforma amplitudes en probabilidades, para las amplitudes reales se eleva al cuadrado, la notacion implica

    P = implica la probabilidad de p
    la probabilidad de que este en o es el modulo de amplitus al cuadrado

    la probabilidad de que sea 0 sea igal al modulo alfa al cuadrado de su amplitud

    Lo mismo para beta

    para tomarlo es no confundir la amplitud con la probabilidad

    el signo no se pierde al medir ña base computacional

    identifica la amplitud eleva al cuadrado eh interpreta el resultado como probabilidad

Ejercicio resuelto, la amplitud del get 1 es negativa en .9a calcula pa probabilidad de observar 1, que seria

de -.90 al cuadrado es igual a = 0.80, ahi es donde se apica la regla de born, de alpha al cuadrado

Concepto de normaliacion cuantica

en un estado cuantico es valido tener norma uno,
 # Metodo de Normalizacion

 La condicion no es Alpa . Beta = 1, Esa seria una condicion de probabilidades clasicas,

 1 elevar a l cuadrado cada amplitud real suma los cuadrados

 ![alt text](/Capturas/image-1.png)

 Que si eso es valido si se normaliza, si sacamos que la suma de todos esos son indistintos de uno ya la normalizaicon cuantica no seria valida,

 ![](/Capturas/image-2.png)


un vector cuantico puede tener entradas negativas lo que importa es la suma de cuadrados
la sumatoria total de esta nos da 1,

el metodo valido maneja los siguientes pasos :

![alt text](image-3.png)

Los signos negativos si son permitidos en amplitudes; desaparecen al elevarse

![alt text](image-4.png)

Vectores validos,

la solucion de elevear al cuadrado los elementos seria 1 medio mas un medio, al elevar una raiz els el numero tal cual

da como resultado 1 para ese ejercisio de vector es valido.

#Concepto no validos, 
un vector de falla si la suma de cuadrados no es 1

![alt text](image-5.png)

Cunado se descarte, a pesar de que parescan esntradas razonables , no hay que darlo como un vector valido hay que normalizarlo

Tiene que ser distinto de 1,un vector no normalizado

![alt text](image-6.png)
es numerico y directo,

![alt text](image-7.png)

![alt text](image-8.png)


todo qubit normalizado es igual al coseno de x por el seno de su seno -1

> DJ Nota, revisar el documento de teroias para conseguir entenderlo mejor

![alt text](image-9.png)

![alt text](image-10.png)

el simbolo de '|+>' es el get(), oh resultado

#Metodo Hadamard

![Metodo Haamard](image-11.png)

|0> o |1> que seria su notacion de hadamard

![alt text](image-12.png)

se hace la multiplicacion de esos

# Concepto Hadamard dos veces

es su propia inversa al aplicarlo dos veces en su estado original regresa
![alt text](image-13.png)

![alt text](image-14.png)

es la notacion de codigo quiscque
oh qc.x(q[0])

# Concepto de medicionn de X |x>

![alt text](image-15.png)

`'1'` mediciones pares de la compuerta not
concepto de splitter como moneda cuantica

![alt text](image-16.png)

![alt text](image-17.png)

![alt text](image-18.png)

compuerta hadamar luego 
HX|o> = H|1>

se resuelve de izquierda a derecha

![alt text](image-19.png)
son equivalentes por las propiedades
matrices por los vertices por un vector

# Metodo crear |-> con Qiskit

![alt text](image-20.png)

![alt text](image-21.png)

la libreria qisk es la que ayuda a crear con la libreria la compuerta aplicada 

![alt text](image-22.png)

si el q1 esta en q0, la cadena esta en 01

No confundir el l roden visual 

![alt text](image-23.png)

En la lectura de resolucion es al reves

![alt text](image-24.png)
nos da el mismo 1 pero con 100 mediciones

![alt text](image-25.png)
estado pera la compuerta y hace  el estado final

registro clasico es un contador cuando tienes un qbit, y que vas a medir el clima 2 veces, el clima es un estado de probablidad, lo manejamos como dias pero el registro se maneja como 1 y 2, es como si ya te auxilias de entradas clasicas para tener un conteo de mediciones

![alt text](image-26.png)
![alt text](image-27.png)
no siempre pueden ser 200 contra 800, oh solo con sus complementos cons los casos deterministas

![alt text](image-28.png)

se puede esperar la mitad oh un cuarto no es una regla 

por amplitud no es al cuadrado ahi se conserva el 

alpha + beta la amplitud es un get = á b


![alt text](image-29.png)

![alt text](image-30.png)

no son del mismo obheta
el get positivo, por el signo , es diferente a la mescla clasica

la diferencia es la medicion que se hace antes de

![alt text](image-31.png)
ta que asi, al aplicar hadamar + 1 que se obtiene 

![alt text](image-32.png)

![](/Capturas/image-33.png)

    ejemplo de la notacion 
    a comparacion de la notacion clasica tenemos para 0 o 1

no eliminar signos 
la interferencia por signos 
![alt text](/Capturas/image-34.png)

eso viene en los ejecricios

![alt text](/Capturas/image-35.png)

tienen el get de funcion, y van desde 0 a lal ai, y eni tienen sus estados
y al sumar sus resultados da 1

![alt text](/Capturas/image-36.png)

en las amplituds son validos pero desaparecen al elevar

la tranpuesta del vector 
![alt text](/Capturas/image-37.png)
al obteber el cuadrado es 1 por lo tanto es valido

![alt text](/Capturas/image-38.png)

la notacion es la suma de las probabilidades por el producto tensorial cuantico para tra suma
y como se multiplica termino a termino tal que los coeficientes se multiplica para los 2 get, que seria beta + sigma se multiplica sigma por teta

![alt text](/Capturas/image-39.png)

y se ordena 00, 01, 10, y 11

![alt text](/Capturas/image-40.png)
que los hace independiente
como los mediste
si en ambos lados los dos vectores de producto son combinacion lineal de vector 0 y uno, como digo que son independientes si son de los mismo productos vectoriales
es solo la notacion, del quibit no de que sea el mismo
lo que lo diferencia es la amplitud individal

fisicamente seran dos quibit diferentes, por eso slae combinado cuando se multiplican

ejemplo del producto vectorial 

![alt text](/Capturas/image-41.png)
el get 0  y que da como resultado get 0,0 mas el get 0

![alt text](/Capturas/image-42.png)
es importante por que viene como evaluacion
no confundir el qubit como uno

ejemplo 
![alt text](/Capturas/image-43.png)

#medicion en base computacional 
![alt text](/Capturas/image-44.png)

![alt text](/Capturas/image-45.png)

si erma -1 sale positivo, es un calculo de probabilidad

Qiskit para medir todos los qubits

![alt text](/Capturas/image-46.png)
funionm que mide los qbit

![alt text](/Capturas/image-47.png)

![alt text](/Capturas/image-48.png)

como se muestra en los registros c1 y c2

#preparacion de estados simples 
![alt text](/Capturas/image-49.png)

## Preparacino de estados simples 
![alt text](/Capturas/image-50.png)
compuesrta no y hadamas nort = X

![alt text](/Capturas/image-51.png)

el disparo y la notacion de probablididades

![alt text](/Capturas/image-52.png)
que se hace si ya hubo una fluctuacion

![alt text](/Capturas/image-53.png)
![alt text](/Capturas/image-54.png)
entonces es el qet C la compuerta que se aplica la notacion de la compuerta, solo se usa hadamart y not en principio
se hace la medicion y se obtiene la amplitud y probabilidades

![alt text](/Capturas/image-55.png)

![alt text](/Capturas/image-56.png)

es importante usar los simbols por lo que da

![alt text](/Capturas/image-57.png)

|a| valor absoluto

![alt text](/Capturas/image-58.png)
en como seria en codigo esos caracteres sueltos, 
| pleca, 0 > menor que, aqrt2
esa seria la notacion en codigo {y abajo la normal }

![formulario](/Capturas/image-59.png)

el formulario
el primero es combinacion lineal
viven cada cubit en ihilbert diferente

el cuadrado

las compuertas de hadamar segun el get 0 o 1

y al final la combinacion de + y - que dicta como se va a hacer el simbolo



![alt text](/Capturas/image-60.png)

ahi ahy que definir que no se use el simbolo de raiz, es dejar clara las notaciones


![alt text](/Capturas/image-61.png)

usar esta apgina para verlo 
![alt text](/Capturas/image-62.png)

![alt text](/Capturas/image-63.png)
se muestra en radianes
![alt text](/Capturas/image-64.png)

![alt text](/Capturas/image-65.png)

