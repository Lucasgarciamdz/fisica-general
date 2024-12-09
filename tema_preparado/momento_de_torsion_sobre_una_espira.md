# Momento de torsión sobre una espira de corriente en un campo magnético uniforme

## Introducción

El momento de torsión, o torque, sobre una espira de corriente en un campo magnético uniforme es un fenómeno fundamental en el electromagnetismo que describe cómo una corriente eléctrica produce una fuerza de rotación cuando interactúa con un campo magnético. Este principio es la base de funcionamiento de muchos dispositivos electromecánicos, como motores eléctricos y generadores.

## Teoría del Torque en una Espira de Corriente

Cuando una espira de corriente, que consiste en un conductor por el que circula una corriente $I$, se coloca en un campo magnético uniforme $\mathbf{B}$, la interacción entre el campo magnético y la corriente produce una fuerza en cada segmento del conductor. Estas fuerzas generan un torque que tiende a rotar la espira.

### Cálculo del Torque

El torque $\boldsymbol{\tau}$ ejercido sobre una espira de corriente en un campo magnético uniforme se puede calcular utilizando la siguiente expresión:

$$
\boldsymbol{\tau} = \mathbf{m} \times \mathbf{B}
$$

**Donde:**
- $\boldsymbol{\tau}$ es el torque aplicado (N·m).
- $\mathbf{m}$ es el momento magnético de la espira de corriente (A·m²).
- $\mathbf{B}$ es el campo magnético (T).

El momento magnético $\mathbf{m}$ de la espira se relaciona con la corriente $I$ y el área $A$ de la espira mediante:

$$
\mathbf{m} = I \cdot \mathbf{A}
$$

**Donde:**
- $I$ es la corriente eléctrica (A).
- $\mathbf{A}$ es el vector área de la espira, cuya magnitud es el área y su dirección está dada por la normal a la espira según la regla de la mano derecha.

### Dirección del Torque

La dirección del torque está determinada por la regla de la mano derecha aplicada al producto cruzado entre el momento magnético y el campo magnético. Esto implica que el torque tiende a alinear el momento magnético de la espira con el campo magnético externo.

## Cálculo Detallado del Torque

Consideremos una espira rectangular de dimensiones $a \times b$, con corriente $I$, ubicada en un campo magnético uniforme $\mathbf{B}$.

### Área de la Espira

El área $A$ de la espira es:

$$
A = a \cdot b \quad \text{(m²)}
$$

### Momento Magnético

El momento magnético de la espira es:

$$
\mathbf{m} = I \cdot A \cdot \mathbf{n}
$$

**Donde:**
- $\mathbf{n}$ es el vector unitario normal a la superficie de la espira.

### Torque

El torque aplicado sobre la espira es:

$$
\boldsymbol{\tau} = \mathbf{m} \times \mathbf{B} = I \cdot A \cdot (\mathbf{n} \times \mathbf{B})
$$

Si definimos $\theta$ como el ángulo entre el vector normal $\mathbf{n}$ y el campo magnético $\mathbf{B}$, la magnitud del torque es:

$$
\tau = m B \sin(\theta) = I A B \sin(\theta)
$$

**Donde:**
- $\theta$ es el ángulo entre $\mathbf{m}$ y $\mathbf{B}$.

### Condiciones de Equilibrio

- **Posición de Equilibrio Estable:** Cuando $\theta = 0^\circ$ (el momento magnético alineado con el campo magnético), el torque es cero y la espira se encuentra en equilibrio estable.

- **Posición de Equilibrio Inestable:** Cuando $\theta = 180^\circ$ (el momento magnético opuesto al campo magnético), el torque es cero, pero la espira está en equilibrio inestable.

## Aplicaciones Prácticas

El concepto de torque en una espira de corriente es esencial en el diseño de motores eléctricos, donde se utiliza para convertir energía eléctrica en trabajo mecánico mediante la interacción de corrientes y campos magnéticos.

## Ejemplo de Cálculo

Supongamos una espira rectangular de $0.5 \, \text{m} \times 0.3 \, \text{m}$ con una corriente de $2 \, \text{A}$, colocada en un campo magnético uniforme de $1.5 \, \text{T}$. Calculamos el torque cuando el ángulo $\theta$ entre el vector normal de la espira y el campo magnético es de $30^\circ$.

### Cálculo del Área

$$
A = 0.5 \, \text{m} \times 0.3 \, \text{m} = 0.15 \, \text{m}²
$$

### Cálculo del Torque

$$
\tau = I \cdot A \cdot B \cdot \sin(\theta) = 2 \, \text{A} \times 0.15 \, \text{m}² \times 1.5 \, \text{T} \times \sin(30^\circ)
$$

$$
\tau = 2 \times 0.15 \times 1.5 \times 0.5 = 0.225 \, \text{N}·\text{m}
$$

Por lo tanto, el torque ejercido sobre la espira es de $0.225 \, \text{N}·\text{m}$.

