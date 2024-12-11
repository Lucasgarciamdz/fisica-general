# Ejercitación

## Enunciado

Una placa conductora cargada positivamente crea un campo eléctrico uniforme de $E = 1000 \, \text{V/m}$ en sus proximidades. Desde un punto de la placa, se lanza un electrón con una velocidad inicial $v_0 = 10^7 \, \text{m/s}$ formando un ángulo $\theta = 60^\circ$ con la normal de la placa. El electrón describe una trayectoria parabólica debido al campo eléctrico.

Datos:

- $k_0 = 9 \times 10^9 \, \text{N·m}^2/\text{C}^2$
- $q_e = -1.6 \times 10^{-19} \, \text{C}$
- $m_e = 9.1 \times 10^{-31} \, \text{kg}$

Se pide:

1. En el punto A, el más alejado de la placa, ¿con qué velocidad se mueve el electrón?
2. ¿Cuánto ha variado su energía potencial electrostática respecto al punto inicial?
3. Calcular la distancia $d$ entre el punto A y la placa.
4. Determinar la velocidad (módulo y orientación) del electrón cuando choca con la placa.

## Resolución paso a paso y con unidades del SI

### 1. Velocidad en el punto A

Descomponemos la velocidad inicial:

- Componente horizontal:
    $$v_{0x} = v_0 \cos \theta = 10^7 \times \cos 60^\circ = 5 \times 10^6 \, \text{m/s}$$
    
- Componente vertical:
    $$v_{0y} = v_0 \sin \theta = 10^7 \times \sin 60^\circ = 8.66 \times 10^6 \, \text{m/s}$$

El electrón se mueve contra el campo eléctrico, por lo que su componente vertical de velocidad disminuirá hasta anularse en el punto A.

La aceleración en la dirección $y$ es:
$$a = \frac{q_e E}{m_e} = \frac{(-1.6 \times 10^{-19} \, \text{C})(1000 \, \text{V/m})}{9.1 \times 10^{-31} \, \text{kg}} = -1.76 \times 10^{14} \, \text{m/s}^2$$

Calculamos la altura máxima ($v_y = 0$):
$$0 = v_{0y}^2 + 2 a \Delta y$$
$$\Delta y = -\frac{v_{0y}^2}{2a} = \frac{(8.66 \times 10^6 \, \text{m/s})^2}{2 \times 1.76 \times 10^{14} \, \text{m/s}^2} = 0.213 \, \text{m}$$

En el punto A, la velocidad es:
$$v_A = v_{0x} = 5 \times 10^6 \, \text{m/s}$$

**Respuesta:** La velocidad en el punto A es $5 \times 10^6 \, \text{m/s}$ horizontalmente.

### 2. Variación de la energía potencial electrostática

La variación de energía potencial es:
$$\Delta U = q_e E \Delta y$$
$$\Delta U = (-1.6 \times 10^{-19} \, \text{C})(1000 \, \text{V/m})(0.213 \, \text{m}) = -3.41 \times 10^{-17} \, \text{J}$$

**Respuesta:** La energía potencial electrostática disminuye en $3.41 \times 10^{-17} \, \text{J}$.

### 3. Distancia $d$ entre el punto A y la placa

Tiempo para alcanzar la altura máxima:
$$t = \frac{v_{0y}}{-a} = \frac{8.66 \times 10^6 \, \text{m/s}}{1.76 \times 10^{14} \, \text{m/s}^2} = 4.92 \times 10^{-8} \, \text{s}$$

Distancia horizontal recorrida:
$$d = v_{0x} t = (5 \times 10^6 \, \text{m/s})(4.92 \times 10^{-8} \, \text{s}) = 0.246 \, \text{m}$$

**Respuesta:** La distancia $d$ es $0.246 \, \text{m}$.

### 4. Velocidad al chocar con la placa

Tiempo total de vuelo:
$$t_{\text{total}} = 2t = 9.84 \times 10^{-8} \, \text{s}$$

Componente vertical de la velocidad al chocar:
$$v_{y} = v_{0y} + a t_{\text{total}} = 8.66 \times 10^6 \, \text{m/s} + (-1.76 \times 10^{14} \, \text{m/s}^2)(9.84 \times 10^{-8} \, \text{s}) = -8.66 \times 10^6 \, \text{m/s}$$

La magnitud de la velocidad:
$$v = \sqrt{v_{0x}^2 + v_{y}^2} = \sqrt{(5 \times 10^6 \, \text{m/s})^2 + (-8.66 \times 10^6 \, \text{m/s})^2} = 10^7 \, \text{m/s}$$

Ángulo de impacto:
$$\phi = \arctan\left(\frac{v_{y}}{v_{0x}}\right) = \arctan\left(\frac{-8.66 \times 10^6}{5 \times 10^6}\right) = -60^\circ$$

**Respuesta:** Al chocar con la placa, la velocidad del electrón es $1 \times 10^7 \, \text{m/s}$ con un ángulo de $60^\circ$ por debajo de la horizontal.

