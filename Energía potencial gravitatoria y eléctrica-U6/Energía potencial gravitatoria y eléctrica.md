# Energía Potencial Gravitatoria

La energía potencial gravitatoria es la energía que posee un objeto debido a su posición en un campo gravitatorio. Representa el trabajo requerido para mover un objeto desde una posición de referencia (usualmente el infinito) hasta una posición específica dentro del campo gravitatorio.

## Fórmula para Dos Masas Puntuales

La energía potencial gravitatoria ($U$) se calcula mediante:

$$
U = -G \frac{M m}{r}
$$

**Deducción:**

Paso 1:

El trabajo efectuado por la fuerza gravitatoria al mover un objeto no depende de la trayectoria, sino de la distancia entre los centros de masa. Por lo tanto, la energía potencial gravitatoria es:

$$
U = -W = -\int_{r_1}^{r_2} \mathbf{F} \cdot d\mathbf{r}
$$

Paso 2:

La fuerza gravitatoria entre dos masas puntuales es:

$$
\mathbf{F} = -G \frac{M m}{r^2} \hat{r}
$$

Paso 3:

Reemplazando la fuerza en la integral:

$$
U = -\int_{r_1}^{r_2} -G \frac{M m}{r^2} \hat{r} \cdot d\mathbf{r}
$$

Paso 4:

Sacando las constantes:

$$
U = -G {M m} -\int_{r_1}^{r_2} \frac{\delta r}{r^2} 
$$

Paso 5:

Integrando:

$$
U = -G \frac{M m}{r_1} - \left[ -G \frac{M m}{r_2} \right] = -G \frac{M m}{r}
$$

Finalemnte:

$$
U = -G \frac{M m}{r}
$$

**Donde:**

- **\( U \)**: Energía potencial gravitatoria (julios, J).
- **\( G \)**: Constante de gravitación universal ($6.674 \times 10^{-11}$ N·m²/kg²).
- **\( M \)**: Masa del cuerpo masivo (kilogramos, kg).
- **\( m \)**: Masa del objeto (kg).
- **\( r \)**: Distancia entre los centros de masa (metros, m).

El signo negativo indica que la energía disminuye al acercar las masas debido a la naturaleza atractiva de la fuerza gravitatoria.
## Líneas de Fuerza y Superficies Equipotenciales

Las líneas de fuerza son representaciones gráficas que muestran la dirección y la intensidad de un campo (gravitatorio o eléctrico). Indican la dirección en la que una masa o carga positiva se movería dentro del campo. Las líneas de fuerza son siempre tangentes al vector intensidad del campo. Su sentido es siempre entrante hacia la masa que origina el campo. Las líneas de fuerza nunca se cruzan. El número de líneas de fuerza que atraviesan una unidad de superficie es proporcional al valor de \( g \).

Las superficies equipotenciales son superficies donde el potencial es constante. En estas superficies, no se realiza trabajo al mover una carga o masa porque el potencial no cambia. Todos los puntos que se encuentran a la misma distancia \( r \) de la masa \( m \) tienen el mismo valor del potencial y constituyen una superficie equipotencial. Las superficies equipotenciales nunca se cortan.

**Características:**

- Las líneas de fuerza son siempre perpendiculares a las superficies equipotenciales.
- En un campo uniforme, las superficies equipotenciales son paralelas y equidistantes.
- En campos radiales, como el gravitatorio alrededor de una masa puntual, las superficies equipotenciales son esferas concéntricas.
- Las líneas de fuerza son siempre tangentes al vector intensidad del campo.
- Las líneas de fuerza nunca se cruzan.
- El número de líneas de fuerza que atraviesan una unidad de superficie es proporcional al valor de \( g \).
- Todos los puntos que se encuentran a la misma distancia \( r \) de la masa \( m \) tienen el mismo valor del potencial y constituyen una superficie equipotencial.
- Las superficies equipotenciales nunca se cortan.

## Rapidez de Escape

La rapidez de escape es la velocidad mínima que un objeto necesita para escapar del campo gravitatorio de un cuerpo masivo sin aportes adicionales de energía.

Se calcula mediante:

$$
v_{\text{escape}} = \sqrt{\dfrac{2 G M}{r}}
$$

**Donde:**

- **\( v_{\text{escape}} \)**: Rapidez de escape (m/s).
- **\( G \)**: Constante de gravitación universal.
- **\( M \)**: Masa del cuerpo del cual se escapa.
- **\( r \)**: Distancia desde el centro del cuerpo masivo hasta la posición inicial del objeto.

**Deducción Paso a Paso de la Rapidez de Escape**

La **rapidez de escape** es la velocidad mínima que un objeto necesita para escapar completamente del campo gravitatorio de un cuerpo masivo sin requerir energía adicional.

**Paso 1: Establecer la Energía Mecánica Total**

La energía mecánica total (\( E \)) es la suma de la energía cinética (\( K \)) y la energía potencial gravitatoria (\( U \)) del objeto:

$$
E = K + U
$$

**Paso 2: Expresar las Energías Cinética y Potencial**

- Energía cinética:

$$
K = \dfrac{1}{2} m v_{\text{escape}}^2
$$

- Energía potencial gravitatoria:

$$
U = -G \dfrac{M m}{r}
$$

Donde:
- \( m \): Masa del objeto.
- \( M \): Masa del cuerpo masivo (por ejemplo, un planeta).
- \( r \): Distancia desde el centro del cuerpo masivo hasta el objeto.
- \( G \): Constante de gravitación universal.

**Paso 3: Condición para la Escape del Campo Gravitatorio**

Para que el objeto escape, su energía mecánica total debe ser al menos cero cuando esté a una distancia infinita (\( r \rightarrow \infty \)):

$$
E_{\infty} = 0
$$

**Paso 4: Igualar la Energía Mecánica Total a Cero**

Establecemos la ecuación:

$$
E = K + U = 0
$$

Sustituimos \( K \) y \( U \):

$$
\dfrac{1}{2} m v_{\text{escape}}^2 - G \dfrac{M m}{r} = 0
$$

**Paso 5: Despejar \( v_{\text{escape}} \)**

- Multiplicamos ambos lados por 2 (pasar el 1/2 al lado derecho):

$$
m v_{\text{escape}}^2 = 2 G \dfrac{M m}{r}
$$

- Simplificamos \( m \):

$$
v_{\text{escape}}^2 = 2 G \dfrac{M}{r}
$$

**Paso 6: Obtener la Expresión Final**

Tomamos la raíz cuadrada en ambos lados:

$$
v_{\text{escape}} = \sqrt{\dfrac{2 G M}{r}}
$$

**Resultado:**

La expresión para la rapidez de escape es:

$$
v_{\text{escape}} = \sqrt{\dfrac{2 G M}{r}}
$$

**Conclusión:**

Esta fórmula muestra que la rapidez de escape depende únicamente de la masa del cuerpo masivo y de la distancia desde su centro hasta el objeto, no de la masa del objeto que intenta escapar.

## Movimiento de Satélites (Órbitas Circulares)

Un satélite en órbita circular se mantiene en movimiento debido a la fuerza gravitatoria que actúa como fuerza centrípeta necesaria para cambiar continuamente la dirección de su velocidad.

**Ecuación fundamental:**

$$
G \dfrac{M m}{r^2} = m \dfrac{v^2}{r}
$$

**Despejando la velocidad orbital (\( v \)):**

$$
v = \sqrt{\dfrac{G M}{r}}
$$

**Donde:**

- **\( v \)**: Velocidad orbital del satélite (m/s).
- **\( M \)**: Masa del planeta o cuerpo central.
- **\( r \)**: Radio de la órbita (distancia desde el centro del planeta al satélite).

### Periodo orbital

El periodo orbital (\( T \)) de un satélite en órbita circular se relaciona con la velocidad y el radio de la órbita mediante:

$$
T = \dfrac{2 \pi r}{v}
$$

Sustituyendo la velocidad orbital:

$$
T = \dfrac{2 \pi r}{\sqrt{\dfrac{G M}{r}}}
$$

Simplificando:

$$
T = 2 \pi \sqrt{\dfrac{r^3}{G M}}
$$

**Donde:**


## Leyes de Kepler y el Movimiento de los Planetas

### Primera Ley (Ley de las Órbitas)

**Definición:**

Cada planeta se mueve en una órbita elíptica alrededor del Sol, el cual ocupa uno de los focos de la elipse.

**Características:**

- Las órbitas planetarias son elípticas, no circulares.
- El Sol está ubicado en uno de los focos de la elipse.
- La distancia entre el planeta y el Sol varía durante la órbita.

**Ecuaciones:**

La ecuación de una elipse en coordenadas polares es:

$$
r = \frac{a (1 - e^2)}{1 + e \cos \theta}
$$

Donde:

- \( r \): Distancia del planeta al Sol.
- \( a \): Semieje mayor de la elipse.
- \( e \): Excentricidad de la órbita.
- \( \theta \): Anomalía verdadera (ángulo).

**Deducción:**

Basado en la ley de gravitación universal y aplicando las condiciones de una fuerza central inversamente proporcional al cuadrado de la distancia, se obtiene que las trayectorias posibles son secciones cónicas (elipses, parábolas, hipérbolas). Para energías mecánicas negativas, las órbitas son elípticas.

**Unidades:**

- Distancia (\( r \), \( a \)): metros (m).
- Excentricidad (\( e \)): adimensional.
- Ángulo (\( \theta \)): radianes (rad).

---

### Segunda Ley (Ley de las Áreas)

**Definición:**

El radio vector que une un planeta con el Sol barre áreas iguales en tiempos iguales.

**Características:**

- Implica la conservación del momento angular.
- El planeta se mueve más rápido en el perihelio y más lento en el afelio.
- Refleja la variación de la velocidad orbital.

**Ecuaciones:**

La tasa a la cual se barre el área (\( dA/dt \)) es constante:

$$
\frac{dA}{dt} = \text{constante}
$$

**Deducción:**

1. El momento angular \( L \) es:

    $$
    L = m r^2 \frac{d\theta}{dt}
    $$

2. Como no hay torque externo, \( L \) es constante.

3. El área barrida en un intervalo \( dt \) es:

    $$
    dA = \frac{1}{2} r^2 d\theta
    $$

4. Entonces:

    $$
    \frac{dA}{dt} = \frac{1}{2} r^2 \frac{d\theta}{dt} = \frac{L}{2m} = \text{constante}
    $$

**Unidades:**

- Área (\( A \)): metros cuadrados (m²).
- Tiempo (\( t \)): segundos (s).
- Tasa de área (\( dA/dt \)): m²/s.

---

### Tercera Ley (Ley de los Períodos)

**Definición:**

El cuadrado del período orbital de un planeta es proporcional al cubo del semieje mayor de su órbita.

**Características:**

- Relaciona el período orbital y el tamaño de la órbita.
- Es válida para todos los planetas y satélites en órbitas elípticas similares.

**Ecuaciones:**

$$
T^2 = \left( \frac{4\pi^2}{G M} \right) a^3
$$

**Deducción:**

1. La fuerza gravitacional proporciona la fuerza centrípeta necesaria:

    $$
    G \frac{M m}{r^2} = m \frac{v^2}{r}
    $$

2. Simplificando:

    $$
    v^2 = \frac{G M}{r}
    $$

3. La velocidad orbital está relacionada con el período:

    $$
    v = \frac{2\pi r}{T}
    $$

4. Sustituyendo \( v \):

    $$
    \left( \frac{2\pi r}{T} \right)^2 = \frac{G M}{r}
    $$

5. Resolviendo para \( T^2 \):

    $$
    T^2 = \left( \frac{4\pi^2}{G M} \right) r^3
    $$

    Para órbitas elípticas, se usa el semieje mayor \( a \):

    $$
    T^2 = \left( \frac{4\pi^2}{G M} \right) a^3
    $$

**Unidades:**

- Período (\( T \)): segundos (s).
- Semieje mayor (\( a \)): metros (m).
- Constante gravitacional (\( G \)): N·m²/kg².
- Masa del Sol (\( M \)): kilogramos (kg).

---

## Movimiento de los Planetas

**Definición:**

El movimiento de los planetas está gobernado por las leyes de Kepler y la gravitación universal, describiendo cómo orbitan alrededor del Sol bajo la influencia de la fuerza gravitacional.

**Características:**

- Órbitas elípticas con velocidades variables.
- Influencia de la fuerza gravitatoria como fuerza central.
- Conservación del momento angular y energía mecánica.

**Ecuaciones:**

La ecuación de movimiento:

$$
m \frac{d^2 \mathbf{r}}{dt^2} = - G \frac{M m}{r^2} \hat{r}
$$

**Deducción:**

1. Aplicando la segunda ley de Newton y la fuerza gravitacional.

2. Resolviendo las ecuaciones diferenciales para obtener las trayectorias orbitales.

3. Demostrando que las soluciones son órbitas elípticas conforme a las leyes de Kepler.

**Unidades:**

- Masa (\( m \), \( M \)): kilogramos (kg).
- Posición (\( \mathbf{r} \)): metros (m).
- Tiempo (\( t \)): segundos (s).
- Aceleración (\( \frac{d^2 \mathbf{r}}{dt^2} \)): m/s².


## Trabajo de una Fuerza Eléctrica

El trabajo realizado por una fuerza eléctrica al mover una carga (\( q \)) en un campo eléctrico (\( \mathbf{E} \)) es:

$$
W = q \int_{A}^{B} \mathbf{E} \cdot d\mathbf{s}
$$

En un campo eléctrico uniforme y desplazamiento en la dirección del campo:

$$
W = q E d
$$

**Donde:**

- **\( W \)**: Trabajo (julios, J).
- **\( q \)**: Carga eléctrica (coulombios, C).
- **\( E \)**: Intensidad del campo eléctrico (N/C).
- **\( d \)**: Distancia recorrida en la dirección del campo (m).

## Energía Potencial Eléctrica

La energía potencial eléctrica es la energía que posee una carga debido a su posición en un campo eléctrico.

$$
U = q V
$$

**Donde:**

- **\( U \)**: Energía potencial eléctrica (J).
- **\( q \)**: Carga eléctrica (C).
- **\( V \)**: Potencial eléctrico en el punto donde se encuentra la carga (voltios, V).

### Para Campo Constante

En un campo eléctrico uniforme:

$$
U = q E d
$$

### Para Campo Variable

Para un campo eléctrico variable, la energía potencial se determina mediante la integral:

$$
U = -q \int_{A}^{B} \mathbf{E} \cdot d\mathbf{s}
$$

### Para Dos Cargas Puntuales

$$
U = k_e \dfrac{q_1 q_2}{r}
$$

### Para Varias Cargas Puntuales

$$
U_{\text{total}} = \sum_{i<j} k_e \dfrac{q_i q_j}{r_{ij}}
$$

## Campo Eléctrico

El campo eléctrico en un punto en el espacio es una medida de la fuerza eléctrica que una carga unidad experimentaría en ese punto.

$$
\mathbf{E} = \dfrac{\mathbf{F}}{q}
$$

Para una carga puntual (\( Q \)):

$$
\mathbf{E} = k_e \dfrac{Q}{r^2} \hat{r}
$$

## Potencial Eléctrico

El potencial eléctrico en un punto es el trabajo por unidad de carga que se requiere para mover una carga desde el infinito hasta ese punto.

$$
V = k_e \dfrac{Q}{r}
$$

## Superficies Equipotenciales

Una superficie equipotencial es aquella en la que el potencial eléctrico es constante en todos sus puntos.

**Propiedades:**

- No se realiza trabajo al mover una carga sobre una superficie equipotencial.
- Las líneas de campo eléctrico son perpendiculares a las superficies equipotenciales.

## Placas Paralelas

En un capacitor de placas paralelas, se establece un campo eléctrico uniforme entre las placas debido a la diferencia de potencial aplicada.

**Campo Eléctrico:**

$$
E = \dfrac{V}{d}
$$

**Capacitancia:**

$$
C = \varepsilon_0 \dfrac{A}{d}
$$

## Unidades de Medida y Descripciones

- **Carga Eléctrica (\( q \))**: Coulombio (C). Cantidad de electricidad transportada.
- **Potencial Eléctrico (\( V \))**: Voltio (V). Trabajo por unidad de carga.
- **Campo Eléctrico (\( E \))**: Newton por coulomb (N/C) o voltio por metro (V/m).
- **Energía Potencial (\( U \))**: Julio (J). Capacidad para realizar trabajo.
- **Constante de Gravitación Universal (\( G \))**: $6.674 \times 10^{-11}$ N·m²/kg².
- **Constante de Coulomb (\( k_e \))**: $8.988 \times 10^{9}$ N·m²/C².

Estos temas proporcionan una base sólida para el estudio de la energía potencial gravitatoria y eléctrica, así como de conceptos relacionados con campos y potenciales. Es fundamental comprender las fórmulas, sus deducciones y las unidades involucradas para aplicarlas correctamente en problemas físicos.