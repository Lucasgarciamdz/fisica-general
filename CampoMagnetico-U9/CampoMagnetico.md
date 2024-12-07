# Electromagnetismo

## Campo Magnético

> La unidad del Sistema Internacional (SI) para la intensidad del campo magnético es el tesla (T), que equivale a un newton por amperio por metro ($\frac{N}{A \cdot m}$).

### Fuerza ejercida por un campo magnético

La fuerza magnética $\mathbf{F}$ sobre una partícula cargada en movimiento se determina mediante la medida de su interacción con el campo magnético $\mathbf{B}$. La fuerza se calcula con la siguiente expresión:

$$
\vec{\mathbf{F}} = q \vec{\mathbf{V}} \times \vec{\mathbf{B}}
$$

**Donde:**
- $q$ es la carga eléctrica de la partícula.
- $\mathbf{V}$ es la velocidad de la partícula.
- $\mathbf{B}$ es el campo magnético.

#### Demostración de la fuerza magnética

Consideremos una partícula con carga positiva que se mueve a velocidad constante $\mathbf{V}$ entrando en un campo magnético uniforme $\mathbf{B}$. La fuerza magnética actúa perpendicularmente tanto a la velocidad de la partícula como al campo magnético, lo que provoca una desviación de su trayectoria original, describiendo una curva circular si el campo es uniforme.

Este fenómeno puede observarse utilizando una brújula o analizando el movimiento de cargas en conductores eléctricos bajo la influencia de campos magnéticos, evidenciando así la naturaleza de la fuerza magnética descrita por la ecuación anterior.

### Fuerzas de cargas en movimiento

#### Movimiento perpendicular al campo magnético

Cuando una partícula cargada se mueve perpendicularmente a un campo magnético, la fuerza magnética actúa en dirección perpendicular tanto a la velocidad de la partícula como al campo magnético. La magnitud de la fuerza se calcula con la siguiente expresión:

$$
F = qvB
$$

**Donde:**
- $F$ es la fuerza magnética.
- $q$ es la carga eléctrica de la partícula.
- $v$ es la velocidad de la partícula.
- $B$ es la intensidad del campo magnético.

#### Movimiento paralelo al campo magnético

Cuando una partícula cargada se mueve paralelamente a un campo magnético, la fuerza magnética es nula, ya que el ángulo entre la velocidad de la partícula y el campo magnético es de 0°, lo que resulta en un producto vectorial nulo.

#### Movimiento con ángulo arbitrario

Cuando una partícula cargada se mueve con un ángulo arbitrario respecto al campo magnético, la fuerza magnética se calcula con la siguiente expresión:

$$
F = qvB \sin(\theta)
$$

**Donde:**
- $F$ es la fuerza magnética.
- $q$ es la carga eléctrica de la partícula.
- $v$ es la velocidad de la partícula.
- $B$ es la intensidad del campo magnético.
- $\theta$ es el ángulo entre la velocidad de la partícula y el campo magnético.

#### Órbita de una Partícula Cargada en un Campo Magnético Uniforme

Cuando una partícula cargada se mueve perpendicularmente a un campo magnético uniforme $\mathbf{B}$, experimenta una fuerza magnética que actúa como fuerza centrípeta, manteniendo la partícula en una trayectoria circular a velocidad constante.

#### Fuerza Magnética y Fuerza Centrípeta

La fuerza magnética sobre la partícula está dada por:
$$
\mathbf{F} = q\mathbf{v} \times \mathbf{B}
$$
Dado que el movimiento es perpendicular al campo, la magnitud de la fuerza es:
$$
F = qvB
$$

La fuerza centrípeta necesaria para una órbita circular de radio $r$ es:
$$
F_c = \frac{mv^2}{r}
$$

#### Igualando las Fuerzas

Para mantener la órbita, la fuerza magnética debe igualar la fuerza centrípeta:
$$
qvB = \frac{mv^2}{r}
$$

Resolviendo para el radio $r$:
$$
r = \frac{mv}{qB}
$$

#### Unidades y Parámetros

- $q$: Carga eléctrica (Coulombs, C)
- $m$: Masa de la partícula (kilogramos, kg)
- $v$: Velocidad de la partícula (metros por segundo, m/s)
- $B$: Intensidad del campo magnético (Tesla, T)
- $r$: Radio de la órbita (metros, m)

#### Frecuencia Angular y Movimiento

La frecuencia angular $\omega$ de la partícula en órbita está dada por:
$$
\omega = \frac{v}{r} = \frac{qB}{m}
$$

La frecuencia de giro $f$ es:
$$
f = \frac{\omega}{2\pi} = \frac{qB}{2\pi m}
$$

Esta frecuencia es independiente de la velocidad de la partícula y depende únicamente de la carga, el campo magnético y la masa de la partícula.

### Ley de Lorentz

La fuerza magnética sobre una partícula cargada en movimiento se describe mediante la ley de Lorentz, que considera tanto la fuerza eléctrica como la fuerza magnética. La fuerza total sobre la partícula es la suma de ambas fuerzas:

$$
\mathbf{F} = q(\mathbf{E} + \mathbf{v} \times \mathbf{B})
$$

**Donde:**
- $\mathbf{F}$ es la fuerza total.
- $q$ es la carga eléctrica de la partícula.
- $\mathbf{E}$ es el campo eléctrico.
- $\mathbf{v}$ es la velocidad de la partícula.
- $\mathbf{B}$ es el campo magnético.

### Momento y Torsión de una Espira de Corriente

El **momento de torsión** (también conocido como torque) sobre una espira de corriente en un campo magnético se puede calcular utilizando las siguientes fórmulas:

- **Par de torsión (T):**
    $$
    T = I \cdot A \cdot B \cdot \sin(\theta)
    $$
    Donde:
    - $I$ es la corriente eléctrica.
    - $A$ es el área de la espira.
    - $B$ es la intensidad del campo magnético.
    - $\theta$ es el ángulo entre la normal de la espira y el campo magnético.

- **Momento magnético (M):**
    $$
    M = I \cdot A
    $$

#### Condiciones Máximas y Cero del Par de Torsión

- El par de torsión es **máximo** cuando $\theta = 90^\circ$, es decir, cuando el campo magnético está en el plano de la espira.
- El par de torsión es **cero** cuando $\theta = 0^\circ$ o $\theta = 180^\circ$, ya que la fuerza magnética actúa perpendicularmente al plano de la espira, resultando en un equilibrio estable o inestable.

#### Momento de Torsión en una Espira Rectangular

Considere una espira rectangular con corriente $I$ en un campo magnético uniforme $B$:

- Las fuerzas magnéticas sobre los lados perpendiculares crean un momento de torsión:
    $$
    T_{\text{máx}} = I \cdot A \cdot B
    $$
    donde $A = a \cdot b$ es el área de la espira.

Este resultado es válido cuando el campo magnético es paralelo al plano de la espira. La simulación de un motor de corriente continua demuestra cómo el momento de torsión permite la rotación de la espira en la dirección deseada.

### Campo magnético creado por cargas puntuales en movimiento

La fuerza magnética sobre una carga puntual en movimiento se puede calcular mediante la ley de Lorentz, que considera tanto la fuerza eléctrica como la fuerza magnética. La fuerza total sobre la carga puntual es la suma de ambas fuerzas:

$$
\mathbf{F} = q (\mathbf{E} + \mathbf{v} \times \mathbf{B})
$$

Además, el campo magnético $\mathbf{B}$ creado por una carga puntual $q$ en movimiento con velocidad $\mathbf{u}$ se puede expresar como:

$$
\mathbf{B} = \frac{\mu_0}{4\pi} \frac{q \, \mathbf{u} \times \mathbf{r}}{|\mathbf{r}|^3}
$$

**Donde:**
- $\mu_0$ es la permeabilidad del vacío.
- $q$ es la carga eléctrica.
- $\mathbf{u}$ es la velocidad de la carga.
- $\mathbf{r}$ es el vector de posición desde la carga hasta el punto donde se calcula el campo.
- $|\mathbf{r}|$ es la magnitud del vector $\mathbf{r}$.
- $\times$ denota el producto vectorial.
- $\mathbf{E}$ es el campo eléctrico.
- $\mathbf{v}$ es la velocidad de la partícula afectada por el campo.

### Ley de Biot-Savart

La ley de Biot-Savart describe el campo magnético creado por una corriente eléctrica en un punto específico. La ley establece que el campo magnético $\mathbf{B}$ en un punto $P$ debido a un elemento de corriente $d\mathbf{l}$ en un punto $Q$ es proporcional a la corriente y al vector de longitud $d\mathbf{l}$, y es inversamente proporcional al cuadrado de la distancia entre los puntos $P$ y $Q$.

La ley de Biot-Savart se expresa de la siguiente manera:

$$
\mathbf{B} = \frac{\mu_0}{4\pi} \int \frac{I \, d\mathbf{l} \times \mathbf{r}}{|\mathbf{r}|^3}
$$

### Campo magnético en el centro de N espiras

El campo magnético en el centro de $N$ espiras circulares concéntricas de radio $R$ y corriente $I$ se puede calcular mediante la ley de Ampère. La fórmula para el campo magnético en el centro de las espiras es:

$$
B = \frac{\mu_0 N I}{2R}
$$

### Ley de Ampère

La **ley de Ampère** relaciona el campo magnético alrededor de un camino cerrado con la corriente eléctrica que lo atraviesa. Se expresa matemáticamente como:

$$
\oint_{\partial S} \mathbf{B} \cdot d\mathbf{l} = \mu_0 I_{\text{enc}}
$$

**Donde:**
- $\mathbf{B}$ es el campo magnético.
- $d\mathbf{l}$ es un elemento diferencial de longitud a lo largo del camino cerrado.
- $\mu_0$ es la permeabilidad del vacío.
- $I_{\text{enc}}$ es la corriente eléctrica encerrada por el camino cerrado.

Esta ley es fundamental en el electromagnetismo y se utiliza para calcular campos magnéticos generados por corrientes con geometrías simétricas, como solenoides y bobinas.