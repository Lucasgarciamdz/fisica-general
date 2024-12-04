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

### Deducción de la Aceleración Centrípeta

Para deducir la fórmula de la aceleración centrípeta, consideremos las relaciones geométricas y las definiciones de velocidad y aceleración en movimiento circular.

Consideremos un triángulo isósceles donde los lados iguales representan la velocidad tangencial $v$ y la base representa el cambio en la velocidad $\Delta v$. Este triángulo es similar a otro triángulo formado por el arco $\Delta s$ y el radio $r$ de la circunferencia. Por lo tanto, las proporciones entre sus lados son iguales:

$$
\frac{\vec{\Delta v}}{v} = \frac{\Delta s}{r}
$$

Despejando $\vec{\Delta v}$:

$$
\vec{\Delta v} = v \cdot \frac{\Delta s}{r}
$$

La velocidad angular $\omega$ se relaciona con la longitud del arco mediante:

$$
\omega = \frac{\Delta \theta}{\Delta t}
\\
\frac {\text{longitud del arco}}{\text{radio}} =
\Delta \theta = \omega \Delta t = \frac{\Delta s}{r}
$$

Sustituyendo en la ecuación de $\Delta v$ para t = 0:

$$
\vec{\Delta v} = v \cdot \omega t
$$

La aceleración centrípeta $a_c$ es la aceleración media, definida como:

$$
a_c = \frac{\vec{\Delta v}}{\Delta t} = \frac{v \cdot \omega t}{t} = v \cdot \omega
$$

Usando la relación $v = \omega r$, obtenemos:

$$
a_c = \frac{v^2}{r} = \omega^2 r
$$

Por lo tanto, la aceleración centrípeta se puede expresar como:

$$
a_c = \frac{v^2}{r} \quad \text{o} \quad a_c = \omega^2 r
$$

Estas deducciones muestran cómo la aceleración centrípeta depende de la velocidad tangencial y el radio de la trayectoria circular.

**Donde:**

- $a_c$ es la aceleración centrípeta.
- $v$ es la velocidad tangencial del objeto.
- $r$ es el radio de la trayectoria circular.
- $\omega$ es la velocidad angular.

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

# Movimiento Circular Uniforme (M.C.U.)

El Movimiento Circular Uniforme es aquel en el que un objeto se desplaza a lo largo de una trayectoria circular con velocidad tangencial constante. En este tipo de movimiento, ciertas magnitudes mantienen una constancia que facilita su análisis.

## Características del M.C.U.

1. **Velocidad Angular Constante ($\omega$):**
    - La velocidad angular del objeto permanece constante durante su movimiento.
    - Se describen ángulos centrales iguales en tiempos iguales.
    - **Unidad:** radianes por segundo (rad/s)

2. **Velocidad Tangencial Constante ($v$):**
    - El módulo de la velocidad tangencial del objeto no varía.
    - Se relaciona con la velocidad angular y el radio:
      $$
      v = \omega \cdot r
      $$
    - **Unidad:** metros por segundo (m/s)

3. **Aceleración Centrípeta Constante ($a_c$):**
    - La aceleración centrípeta mantiene constante la dirección del vector velocidad tangencial.
    - Calculada como:
      $$
      a_c = \frac{v^2}{r} = \omega^2 \cdot r
      $$
    - **Unidad:** metros por segundo al cuadrado (m/s²)

4. **Fuerza Centrípeta Constante ($F_c$):**
    - Fuerza necesaria para mantener el objeto en movimiento circular.
    - Calculada mediante la segunda ley de Newton:
      $$
      F_c = m \cdot a_c = m \cdot \frac{v^2}{r} = m \cdot \omega^2 \cdot r
      $$
    - **Unidad:** Newton (N)

5. **Periodo de Rotación ($T$):**
    - Tiempo que tarda el objeto en completar una vuelta completa.
    - Relación con la velocidad angular:
      $$
      T = \frac{2\pi}{\omega} = \frac{2\pi \cdot r}{v}
      $$
    - **Unidad:** segundos (s)

## Ejemplo: Satélite en Órbita Circular

Consideremos un satélite que orbita la Tierra a una distancia de $r = 7 \times 10^6_{\scriptsize {m}}$ con una velocidad tangencial de $v = 7.5 \times 10^3_{\scriptsize {m/s}}$. Calculamos su periodo de rotación y la fuerza centrípeta necesaria para mantener su órbita.

1. **Periodo ($T$):**

$$
T = \frac{2\pi r}{v} = \frac{2\pi \times 7 \times 10^6_{\scriptsize {m}}}{7.5 \times 10^3_{\scriptsize {m/s}}} \approx 5880_{\scriptsize {s}} \approx 1.63_{\scriptsize {horas}}
$$

2. **Fuerza Centrípeta ($F_c$):**

Si la masa del satélite es $m = 500_{\scriptsize {kg}}$,

$$
F_c = m \cdot \frac{v^2}{r} = 500_{\scriptsize {kg}} \cdot \frac{(7.5 \times 10^3_{\scriptsize {m/s}})^2}{7 \times 10^6_{\scriptsize {m}}} \approx 403571.43_{\scriptsize {N}}
$$

Este ejemplo muestra cómo se aplican las fórmulas del Movimiento Circular Uniforme para determinar características clave de un satélite en órbita.
## Movimiento Circular Uniformemente Variado (M.C.U.V.)

El Movimiento Circular Uniformemente Variado se caracteriza por un cambio en la velocidad angular del objeto en movimiento. A diferencia del Movimiento Circular Uniforme (M.C.U.), en el M.C.U.V. la velocidad angular no permanece constante, lo que provoca variaciones en otras magnitudes relacionadas.

### Características del M.C.U.V.

1. **Velocidad Angular Variable ($\omega$):**
    - La velocidad angular cambia con el tiempo.
    - **Unidad:** radianes por segundo (rad/s).

2. **Aceleración Angular ($\alpha$):**
    - Representa el cambio en la velocidad angular.
    - **Unidad:** radianes por segundo al cuadrado (rad/s²).
    - **Fórmula:**
      $$
      \alpha = \frac{d\omega}{dt}
      $$

3. **Velocidad Tangencial Variable ($v$):**
    - La velocidad tangencial varía debido al cambio en la velocidad angular.
    - **Relación con la velocidad angular:**
      $$
      v = \omega \cdot r
      $$
    - **Unidad:** metros por segundo (m/s).

4. **Aceleración Centrípeta Variable ($a_c$):**
    - Depende de la velocidad tangencial, por lo que varía con el tiempo.
    - **Fórmula:**
      $$
      a_c = \frac{v^2}{r} = \omega^2 \cdot r
      $$
    - **Unidad:** metros por segundo al cuadrado (m/s²).

5. **Aceleración Tangencial ($a_t$):**
    - Causa el cambio en la velocidad tangencial.
    - **Relación con la aceleración angular:**
      $$
      a_t = \alpha \cdot r
      $$
    - **Unidad:** metros por segundo al cuadrado (m/s²).

6. **Fuerza Centrípeta Variable ($F_c$):**
    - Necesaria para mantener el objeto en movimiento circular.
    - **Fórmula:**
      $$
      F_c = m \cdot a_c = m \cdot \omega^2 \cdot r
      $$
    - **Unidad:** Newton (N).

### Ejemplo: Satélite en Órbita con Movimiento Uniformemente Variado

Consideremos un satélite que orbita la Tierra cuya velocidad angular está aumentando de manera constante debido a una fuerza externa. Supongamos que:

- **Radio de la órbita:** $r = 7 \times 10^6 \, \text{m}$
- **Velocidad angular inicial:** $\omega_0 = 1 \, \text{rad/s}$
- **Aceleración angular:** $\alpha = 0.1 \, \text{rad/s²}$
- **Masa del satélite:** $m = 500 \, \text{kg}$

1. **Velocidad Angular en el Tiempo $t$:**
    $$
    \omega(t) = \omega_0 + \alpha \cdot t = 1 + 0.1t \, \text{rad/s}
    $$

2. **Velocidad Tangencial en el Tiempo $t$:**
    $$
    v(t) = \omega(t) \cdot r = (1 + 0.1t) \cdot 7 \times 10^6 = 7 \times 10^6 + 7 \times 10^5 t \, \text{m/s}
    $$

3. **Aceleración Centrípeta en el Tiempo $t$:**
    $$
    a_c(t) = \omega(t)^2 \cdot r = (1 + 0.1t)^2 \cdot 7 \times 10^6 \, \text{m/s²}
    $$

4. **Fuerza Centrípeta en el Tiempo $t$:**
    $$
    F_c(t) = m \cdot a_c(t) = 500 \cdot (1 + 0.1t)^2 \cdot 7 \times 10^6 \, \text{N}
    $$

Este ejemplo ilustra cómo, al aumentar la velocidad angular, se modifican la velocidad tangencial, la aceleración centrípeta y la fuerza centrípeta necesarias para mantener la órbita del satélite.



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

