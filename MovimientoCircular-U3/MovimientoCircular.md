# Movimiento Circular

## Introducción
El movimiento circular es un tipo de movimiento en el que un objeto se desplaza a lo largo de una trayectoria circular.
Es decir que **describe una circunferencia o un arco de ella**.


## Elementos del Movimiento Circular

### Angulo Central barrido
Es el ángulo que describe el objeto en movimiento a lo largo de la circunferencia. El ángulo central barrido es el ángulo formado en el centro de un círculo por dos radios que interceptan un arco. Este ángulo se mide en radianes o grados.

La medida del ángulo central en radianes ($\theta)$ se puede calcular usando la longitud del arco $(s)$ y el radio $(r)$ del círculo: [ $\theta = \frac{s}{r}$ ]


### Radián

Es importante notar que el radián **no es una unidad**. Al calcular el cociente entre la longitud del arco $(s)$ y el radio $(r)$, el resultado es una cantidad adimensional, es decir, no tiene unidades. Sin embargo, para indicar que se está utilizando el sistema circular de medición de ángulos, se emplea el término "radián". Esto ayuda a diferenciarlo de otros sistemas de medición de ángulos, como los grados.

### Radio
Es la distancia entre el centro de la circunferencia y el objeto en movimiento.

### Equivalencia entre sistemas de medición angular

Principal conversion de grados a radianes y viceversa.
### Equivalencia entre sistemas de medición angular

Para convertir entre grados y radianes, es importante entender la relación entre estas dos unidades de medida.

1. **Relación básica**:
    - 360° = 2$\pi$ radianes = 1 vuelta completa

2. **Deducción de la relación**:
    - La longitud de la circunferencia de un círculo es $2\pi r$.
    - Si el ángulo de barrido está definido como $\theta = \frac{s}{r}$, donde $s$ es la longitud del arco y $r$ es el radio.
    - Para una vuelta completa, $s = 2\pi r$.
    - Sustituyendo en la fórmula del ángulo de barrido: $\theta = \frac{2\pi r}{r} = 2\pi$ radianes.

Por lo tanto, se puede deducir que 360° es equivalente a $2\pi$ radianes.

### Velocidad Angular
Se define la velocidad angular w como la 
evolución de la posición angular en el 
tiempo.

En si es un vector perpendicular al plano de giro y su sentido
viene dado por la regla de la mano derecha o del tornillo de rosca derecha

 $\omega = \frac{\Delta \theta}{\Delta t}$

Lo que es equivalente a:

$\omega = \frac{\Delta \theta}{\Delta t} = \frac{2\pi}{T}$

Esta equivalencia se da cuando el objeto da una vuelta completa en un periodo T.


Donde:
- $\omega$ es la velocidad angular.
- $\Delta \theta$ es el cambio en el ángulo central.
- $\Delta t$ es el cambio en el tiempo.
- $T$ es el periodo de la rotación.


### Velocidad Tangencial

La velocidad tangencial es un vector, que resulta 
del producto vectorial entre el vector velocidad 
angular $\omega$ y el vector posición $r$ .

formula:

$v = \omega \times r \times sen(90) = \omega \times r \times 1 = \omega \times r$

Formula final de la velocidad tangencial:

$v = \omega \times r$

Donde:
- $v$ es la velocidad tangencial.
- $\omega$ es la velocidad angular.
- $r$ es el radio de la circunferencia.
- $sen(90)$ es el seno de 90 grados, que es igual a 1.
- $\times$ es el producto vectorial.


### Aceleración Centrípeta
Es la aceleración que mantiene al objeto en su trayectoria circular.

La segunda ley de Newton afirma que la resultante de las fuerzas $\mathbf{F}$ que actúan sobre 
un cuerpo de masa $\ m$  le provoca una aceleración en su misma dirección y sentido. 

$\ F = m \cdot a$

En el caso del movimiento circular, esta fuerza es la fuerza centrípeta, que siempre apunta hacia el centro de la trayectoria circular, provocando el cambio de dirección del vector velocidad. La aceleración centrípeta $\ a_c$ es la aceleración que un objeto experimenta debido a esta fuerza centrípeta.

La aceleración centrípeta siempre apunta hacia la concavidad de la curva. Mientras que la velocidad es tangente a la curva en todo sus puntos.
Siendo estos perpendiculares entre si.

La fórmula para la aceleración centrípeta es:

$\ a_c$ = $\frac{v^2}{r}$

### Deducción de la aceleración centrípeta

En base a la identidad trigonométrica de los triángulos, se puede deducir la fórmula de la aceleración centrípeta vectorialmente como:

Consideremos un triángulo isósceles con lados iguales $v$ y base $\Delta v$. Este triángulo es similar a otro triángulo isósceles formado por el arco $\Delta s$ y el radio $r$ de la circunferencia. La relación entre estos triángulos se puede expresar como:

$\ [ \frac{\Delta v}{v} = \frac{\Delta s}{r} ]$

El cambio en la velocidad $\Delta v$ es perpendicular a la velocidad tangencial y se puede relacionar con el cambio en el ángulo:

$\ [ \frac{\Delta v}{v} = \frac{\Delta s}{r} ]$

Despejando $\Delta v$:

$\ [ \Delta v = v \frac{\Delta s}{r} ]$



La aceleración centrípeta es la aceleración media:

$\ [ a_c = \frac{\Delta v}{\Delta t} = {\frac{v^2 \Delta t}{r}}{\Delta t} = \frac{v^2}{r} ]$

Otra forma de expresar la aceleración centrípeta es en términos de la velocidad angular $\omega$:

$\ [ v = \omega r ]$

Sustituyendo en la fórmula de la aceleración centrípeta:

$\ [ a_c = \frac{(\omega r)^2}{r} = \omega^2 r ]$

Por lo tanto, la aceleración centrípeta se puede expresar como:

$\ [ a_c = \frac{v^2}{r} ]$

o

$\ [ a_c = \omega^2 r ]$

Estas deducciones muestran cómo la aceleración centrípeta depende de la velocidad tangencial y el radio de la trayectoria circular.


donde:
- $\ a_c$ es la aceleración centrípeta.
- $\ v$ es la velocidad tangencial del objeto.
- $\ r$ es el radio de la trayectoria circular.

Otra forma de expresar la aceleración centrípeta es en términos de la velocidad angular $\\omega$ $\):

$\ a_c$ = $\omega^2 r$ 

donde:
- $\ \omega$ es la velocidad angular.
- $\ r$ es el radio de la trayectoria circular.

La fuerza centrípeta $\ F_c$ necesaria para mantener un objeto en movimiento circular se puede calcular usando la segunda ley de Newton:

$\ F_c = m a_c$

Sustituyendo la fórmula de la aceleración centrípeta:

$\ F_c = m \frac{v^2}{r}$

o

$\ F_c = m \omega^2 r$

Donde:
- $\ F_c$ es la fuerza centrípeta.
- $\ m$ es la masa del objeto.
- $\ v$ es la velocidad tangencial.
- $\ \omega$ es la velocidad angular.
- $\ r$ es el radio de la trayectoria circular.

Estas fórmulas son fundamentales para entender el movimiento circular y la dinámica de los objetos que se mueven en trayectorias curvas.

## Conceptos

### Velocidad Angular
La velocidad angular ($\Omega$) es una medida de la rapidez con la que un objeto gira o rota. Se define como el ángulo barrido por unidad de tiempo.

$\ \omega = \frac{\Delta \theta}{\Delta t}$

### Aceleración Centripeta
La aceleración centrípeta ($\ a_c$) es la aceleración que mantiene a un objeto en su trayectoria circular. Siempre apunta hacia el centro del círculo.

$\ a_c = \frac{v^2}{r}$

### Fuerza Centripeta
La fuerza centrípeta ($\ F_c$) es la fuerza que actúa sobre un objeto en movimiento circular, dirigiéndolo hacia el centro de la trayectoria circular.

$\ F_c = m \cdot a_c = m \cdot \frac{v^2}{r}$

## Ejemplos Comunes
- Movimiento de los planetas alrededor del sol.
- Movimiento de un automóvil en una curva.
- Movimiento de una rueda de bicicleta.

# Movimiento Circular Uniformemente Variado

## Introducción

