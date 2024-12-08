# Electromagnetismo

## Formulas Utilizadas en Campo Magnético

### Intensidad del Campo Magnético

La unidad del campo magnético en el Sistema Internacional es el **tesla (T)**, definida como:

$$
1\, \text{T} = 1\, \frac{\text{N}}{\text{A} \cdot \text{m}}
$$

Donde:
- **N**: Newton (unidad de fuerza)
- **A**: Amperio (unidad de corriente eléctrica)
- **m**: Metro (unidad de longitud)

---

### Fuerza Magnética sobre una Partícula Cargada

La fuerza magnética $\mathbf{F}$ sobre una partícula cargada se calcula mediante:

$$
\mathbf{F} = q\, \mathbf{v} \times \mathbf{B}
$$

Donde:
- $\mathbf{F}$: Fuerza magnética (N)
- $q$: Carga eléctrica (C)
- $\mathbf{v}$: Velocidad de la partícula (m/s)
- $\mathbf{B}$: Campo magnético (T)
- $\times$: Producto vectorial

La magnitud de la fuerza es:

$$
F = q\, v\, B\, \sin(\theta)
$$

Donde $\theta$ es el ángulo entre $\mathbf{v}$ y $\mathbf{B}$.

---

### Movimiento de Partículas Cargadas en un Campo Magnético

#### Movimiento Perpendicular al Campo ($\theta = 90^\circ$)

- **Fuerza Magnética**:

    $$
    F = q\, v\, B
    $$

- **Radio de la Trayectoria Circular**:

    $$
    r = \frac{m\, v}{q\, B}
    $$

    Donde $m$ es la masa de la partícula (kg).

- **Frecuencia Angular ($\omega$)**:

    $$
    \omega = \frac{v}{r} = \frac{q\, B}{m}
    $$

- **Frecuencia de Giro ($f$)**:

    $$
    f = \frac{\omega}{2\pi} = \frac{q\, B}{2\pi\, m}
    $$

#### Movimiento Paralelo al Campo ($\theta = 0^\circ$)

- La fuerza magnética es cero:

    $$
    F = 0
    $$

---

### Ley de Lorentz

La fuerza total sobre una partícula en presencia de campos eléctrico y magnético es:

$$
\mathbf{F} = q\, (\mathbf{E} + \mathbf{v} \times \mathbf{B})
$$

Donde:
- $\mathbf{F}$: Fuerza total (N)
- $q$: Carga eléctrica (C)
- $\mathbf{E}$: Campo eléctrico (V/m)
- $\mathbf{v}$: Velocidad de la partícula (m/s)
- $\mathbf{B}$: Campo magnético (T)

---

### Fuerza sobre un Conductor con Corriente

La fuerza magnética sobre un conductor que transporta una corriente es:

$$
\mathbf{F} = I\, \mathbf{L} \times \mathbf{B}
$$

Donde:
- $I$: Intensidad de la corriente (A)
- $\mathbf{L}$: Vector longitud del conductor (m)

La magnitud de la fuerza es:

$$
F = I\, L\, B\, \sin(\theta)
$$

Donde $\theta$ es el ángulo entre $\mathbf{L}$ y $\mathbf{B}$.

---

### Densidad de Corriente y Ley de Ohm Microscópica

La densidad de corriente $\mathbf{J}$ está relacionada con el campo eléctrico:

$$
\mathbf{J} = \sigma\, \mathbf{E}
$$

Donde:
- $\mathbf{J}$: Densidad de corriente (A/m²)
- $\sigma$: Conductividad eléctrica (S/m)

---

### Ecuación de Continuidad

La conservación de la carga eléctrica se expresa mediante:

$$
\nabla \cdot \mathbf{J} + \frac{\partial \rho}{\partial t} = 0
$$

Donde $\rho$ es la densidad de carga (C/m³).


---

### Momento de Torsión en una Espira de Corriente

El momento de torsión $\tau$ sobre una espira es:

$$
\tau = I\, A\, B\, \sin(\theta)
$$

Donde:
- $\tau$: Momento de torsión (N·m)
- $I$: Corriente eléctrica (A)
- $A$: Área de la espira (m²)
- $\theta$: Ángulo entre la normal de la espira y $\mathbf{B}$

El **momento magnético** $\mu$ es:

$$
\mu = I\, A
$$

Por lo tanto:

$$
\tau = \mu\, B\, \sin(\theta)
$$

---

### Campo Magnético de una Carga en Movimiento

El campo magnético $\mathbf{B}$ creado por una carga puntual $q$ moviéndose con velocidad $\mathbf{u}$ es:

$$
\mathbf{B} = \frac{\mu_0}{4\pi}\, \frac{q\, \mathbf{u} \times \hat{\mathbf{r}}}{r^2}
$$

Donde:
- $\mu_0$: Permeabilidad del vacío ($4\pi \times 10^{-7}$ T·m/A)
- $\hat{\mathbf{r}}$: Vector unitario desde la carga al punto de interés
- $r$: Distancia al punto de interés (m)

---

### Ley de Biot-Savart

El campo magnético $\mathbf{B}$ debido a un elemento de corriente es:

$$
d\mathbf{B} = \frac{\mu_0}{4\pi}\, \frac{I\, d\mathbf{l} \times \hat{\mathbf{r}}}{r^2}
$$

Para obtener $\mathbf{B}$ total:

$$
\mathbf{B} = \frac{\mu_0}{4\pi} \int \frac{I\, d\mathbf{l} \times \hat{\mathbf{r}}}{r^2}
$$

---

### Campo Magnético en el Centro de $N$ Espiras

Para $N$ espiras circulares de radio $R$ y corriente $I$:

$$
B = \frac{\mu_0\, N\, I}{2\, R}
$$

---

### Ley de Ampère

La integral de línea del campo magnético alrededor de un circuito cerrado es:

$$
\oint \mathbf{B} \cdot d\mathbf{l} = \mu_0\, I_{\text{enc}}
$$

Donde $I_{\text{enc}}$ es la corriente neta que atraviesa el área.

---

### Unidades

| Símbolo | Magnitud            | Unidad SI       | Símbolo Unidad |
|---------|---------------------|-----------------|----------------|
| $q$     | Carga eléctrica     | Coulomb         | C              |
| $m$     | Masa                | Kilogramo       | kg             |
| $v$     | Velocidad           | Metro/segundo   | m/s            |
| $B$     | Campo Magnético     | Tesla           | T              |
| $E$     | Campo Eléctrico     | Voltio/metro    | V/m            |
| $I$     | Corriente eléctrica | Amperio         | A              |
| $A$     | Área                | Metro cuadrado  | m²             |
| $r$     | Distancia/Radio     | Metro           | m              |
| $\mu_0$ | Permeabilidad del vacío | Tesla·metro/amperio | T·m/A    |

