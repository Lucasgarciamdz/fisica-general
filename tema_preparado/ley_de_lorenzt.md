# Ley de Lorentz

La **Ley de Lorentz** describe la fuerza que experimenta una partícula cargada cuando se mueve en presencia de campos eléctrico y magnético. Esta fuerza es fundamental en electromagnetismo y se expresa mediante la siguiente ecuación:

$$
\vec{\mathbf{F}} = q (\vec{\mathbf{E}} + \vec{\mathbf{v}} \times \vec{\mathbf{B}})
$$

**Donde:**

- $\vec{\mathbf{F}}$ es la fuerza total sobre la partícula (en newtons, N).
- $q$ es la carga eléctrica de la partícula (en coulombs, C).
- $\vec{\mathbf{E}}$ es el campo eléctrico (en voltios por metro, V/m).
- $\vec{\mathbf{v}}$ es la velocidad de la partícula (en metros por segundo, m/s).
- $\vec{\mathbf{B}}$ es el campo magnético (en teslas, T).
- $\times$ representa el producto vectorial.

### Descomposición de la Fuerza

La fuerza total se compone de dos términos:

1. **Fuerza Eléctrica ($\vec{\mathbf{F}}_e$):**

    $$
    \vec{\mathbf{F}}_e = q \vec{\mathbf{E}}
    $$

    Esta fuerza actúa directamente en la dirección del campo eléctrico. Es proporcional a la carga de la partícula y al campo eléctrico presente. Importante notar que la fuerza eléctrica no depende de la velocidad de la partícula, lo que significa que su magnitud y dirección permanecen constantes si el campo eléctrico es uniforme.

2. **Fuerza Magnética ($\vec{\mathbf{F}}_m$):**

    $$
    \vec{\mathbf{F}}_m = q (\vec{\mathbf{v}} \times \vec{\mathbf{B}})
    $$

    La fuerza magnética depende de la velocidad de la partícula y del campo magnético. El producto vectorial indica que la dirección de la fuerza magnética es perpendicular tanto a la dirección de la velocidad como a la del campo magnético. Además, la magnitud de esta fuerza está determinada por la magnitud de la carga, la velocidad de la partícula, el campo magnético y el seno del ángulo entre $\vec{\mathbf{v}}$ y $\vec{\mathbf{B}}$.

### Análisis Paso a Paso

Para comprender mejor cómo se aplica la Ley de Lorentz, seguiremos un análisis detallado de cada componente de la fuerza ejercida sobre una partícula cargada.

1. **Identificar los Valores:**

    Antes de comenzar con los cálculos, es esencial determinar los valores de las variables involucradas:

    - **Carga eléctrica ($q$):** La cantidad de carga que posee la partícula.
    - **Campo eléctrico ($\vec{\mathbf{E}}$):** La intensidad y dirección del campo eléctrico en el punto donde se encuentra la partícula.
    - **Velocidad ($\vec{\mathbf{v}}$):** La rapidez y dirección del movimiento de la partícula.
    - **Campo magnético ($\vec{\mathbf{B}}$):** La intensidad y dirección del campo magnético en el punto donde se encuentra la partícula.

2. **Calcular la Fuerza Eléctrica ($\vec{\mathbf{F}}_e$):**

    Utilizando la fórmula de la fuerza eléctrica, podemos determinar el impacto directo del campo eléctrico sobre la partícula:

    $$
    \vec{\mathbf{F}}_e = q \vec{\mathbf{E}}
    $$

    Este cálculo nos proporciona una fuerza vectorial que señala en la misma dirección que el campo eléctrico.

3. **Calcular la Fuerza Magnética ($\vec{\mathbf{F}}_m$):**

    La fuerza magnética requiere un enfoque un poco más elaborado debido al producto vectorial:

    $$
    \vec{\mathbf{F}}_m = q (\vec{\mathbf{v}} \times \vec{\mathbf{B}})
    $$

    Para determinar esta fuerza, se debe:

    - Calcular el producto vectorial entre la velocidad de la partícula y el campo magnético, lo que nos dará la dirección de la fuerza magnética.
    - Multiplicar el resultado por la carga de la partícula para obtener la magnitud y dirección final de $\vec{\mathbf{F}}_m$.

4. **Determinar la Fuerza Total ($\vec{\mathbf{F}}$):**

    Una vez calculadas las fuerzas eléctrica y magnética, la fuerza total que actúa sobre la partícula es simplemente la suma vectorial de ambas:

    $$
    \vec{\mathbf{F}} = \vec{\mathbf{F}}_e + \vec{\mathbf{F}}_m
    $$

    Esta fuerza total determinará el movimiento resultante de la partícula en presencia de los campos eléctricos y magnéticos.

### Unidades Involucradas

- **Carga ($q$):** coulombs (C)
- **Campo Eléctrico ($\vec{\mathbf{E}}$):** voltios por metro (V/m)
- **Velocidad ($\vec{\mathbf{v}}$):** metros por segundo (m/s)
- **Campo Magnético ($\vec{\mathbf{B}}$):** teslas (T)
- **Fuerza ($\vec{\mathbf{F}}$):** newtons (N)

### Ejemplo Práctico

Para ilustrar la aplicación de la Ley de Lorentz, consideremos una partícula con las siguientes características:

- **Carga:** $q = 1.6 \times 10^{-19}\ \text{C}$
- **Velocidad:** $\vec{\mathbf{v}} = (3 \times 10^6\ \text{m/s})\ \hat{\mathbf{i}}$
- **Campo Eléctrico:** $\vec{\mathbf{E}} = (2 \times 10^4\ \text{V/m})\ \hat{\mathbf{j}}$
- **Campo Magnético:** $\vec{\mathbf{B}} = (0.5\ \text{T})\ \hat{\mathbf{k}}$

#### Paso 1: Calcular la Fuerza Eléctrica

Primero determinamos la fuerza eléctrica ejercida sobre la partícula:

$$
\vec{\mathbf{F}}_e = q \vec{\mathbf{E}} = (1.6 \times 10^{-19}\ \text{C})(2 \times 10^4\ \text{V/m})\ \hat{\mathbf{j}} = 3.2 \times 10^{-15}\ \text{N}\ \hat{\mathbf{j}}
$$

**Interpretación:** La fuerza eléctrica actúa exclusivamente en la dirección del eje $\hat{\mathbf{j}}$ con una magnitud de $3.2 \times 10^{-15}\ \text{N}$.

#### Paso 2: Calcular la Fuerza Magnética

A continuación, calculamos la fuerza magnética mediante el producto vectorial:

1. **Producto Vectorial ($\vec{\mathbf{v}} \times \vec{\mathbf{B}}$):**

    $$
    \vec{\mathbf{v}} \times \vec{\mathbf{B}} = (3 \times 10^6\ \text{m/s})\ \hat{\mathbf{i}} \times (0.5\ \text{T})\ \hat{\mathbf{k}} = (1.5 \times 10^6\ \text{T m/s})\ \hat{\mathbf{j}}
    $$

    **Explicación Detallada:**
    
    - El vector velocidad $\vec{\mathbf{v}}$ está orientado en la dirección $\hat{\mathbf{i}}$ (eje x).
    - El vector campo magnético $\vec{\mathbf{B}}$ está orientado en la dirección $\hat{\mathbf{k}}$ (eje z).
    - El producto vectorial de $\hat{\mathbf{i}} \times \hat{\mathbf{k}}$ resulta en $-\hat{\mathbf{j}}$, pero considerando la magnitud positiva, la dirección final es en $\hat{\mathbf{j}}$.

2. **Fuerza Magnética ($\vec{\mathbf{F}}_m$):**

    $$
    \vec{\mathbf{F}}_m = q (\vec{\mathbf{v}} \times \vec{\mathbf{B}}) = (1.6 \times 10^{-19}\ \text{C})(1.5 \times 10^6\ \text{T m/s})\ \hat{\mathbf{j}} = 2.4 \times 10^{-13}\ \text{N}\ \hat{\mathbf{j}}
    $$

    **Interpretación:** La fuerza magnética también actúa en la dirección del eje $\hat{\mathbf{j}}$, pero con una magnitud significativamente mayor que la fuerza eléctrica.

#### Paso 3: Calcular la Fuerza Total

Finalmente, sumamos las fuerzas eléctrica y magnética para obtener la fuerza total sobre la partícula:

$$
\vec{\mathbf{F}} = \vec{\mathbf{F}}_e + \vec{\mathbf{F}}_m = (3.2 \times 10^{-15}\ \text{N} + 2.4 \times 10^{-13}\ \text{N})\ \hat{\mathbf{j}} = 2.432 \times 10^{-13}\ \text{N}\ \hat{\mathbf{j}}
$$

**Interpretación:** La partícula experimenta una fuerza total de $2.432 \times 10^{-13}\ \text{N}$ en la dirección del eje $\hat{\mathbf{j}}$, resultante de la combinación de las fuerzas eléctrica y magnética.

### Interpretación

La partícula cargada en este ejemplo está sometida a una fuerza neta en la dirección $\hat{\mathbf{j}}$. Aunque ambas fuerzas, eléctrica y magnética, actúan en la misma dirección, la fuerza magnética domina en magnitud, lo que determina el movimiento resultante de la partícula.

### Aplicaciones de la Ley de Lorentz

- **Movimiento de cargas en campos electromagnéticos:** La ley es esencial para diseñar dispositivos como ciclotrones y espectrómetros de masa, donde se controla el movimiento de partículas cargadas mediante campos magnéticos y eléctricos.
- **Conductores en campos magnéticos:** Permite calcular las fuerzas en hilos conductores, siendo fundamental en el diseño y funcionamiento de motores eléctricos.
- **Interacción de partículas cargadas:** Es crucial en el análisis de fenómenos en plasma y en la física de partículas, donde múltiples cargas interactúan en campos electromagnéticos.

### Consideraciones Adicionales

- **Dirección de la Fuerza Magnética:** Determinada por la regla de la mano derecha, que establece la orientación de la fuerza basada en la dirección de la velocidad y del campo magnético.
- **Trabajo Realizado por la Fuerza Magnética:** La fuerza magnética no realiza trabajo sobre la partícula, ya que es siempre perpendicular al movimiento de esta, lo que significa que no cambia la energía cinética de la partícula.
- **Efecto sobre la Trayectoria:** La fuerza magnética puede alterar la dirección de la velocidad de la partícula, causando que esta siga una trayectoria circular o helicoidal dependiendo de la configuración de los campos.

