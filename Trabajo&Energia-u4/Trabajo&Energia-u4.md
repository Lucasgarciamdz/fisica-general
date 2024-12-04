# Trabajo & Energía - Unidad 4

## Trabajo
### **1.1. Trabajo de una Fuerza Constante**

* Una fuerza realiza trabajo sobre un cuerpo cuando éste se desplaza por acción de la fuerza aplicada.
* El trabajo de una fuerza representa la mayor o menor capacidad que tiene $\vec{F}$ para provocar un desplazamiento en el cuerpo sobre el cual actúa.
* Si un cuerpo experimenta un desplazamiento por acción de una fuerza externa, se dice que $\vec{F}$ ha realizado trabajo sobre el cuerpo.

> **Definición:** Se define el trabajo $(W)$ que realiza una fuerza $\vec{F}$ como el producto escalar entre la fuerza aplicada y el desplazamiento logrado:
> $$
> W = \vec{F} \cdot \vec{\Delta x} = F \cdot \Delta x \cdot \cos(\theta)
> $$
> El trabajo es una magnitud escalar y sus unidades en el Sistema Internacional son el julio $(J) = \text{N} \cdot \text{m}$. ${\mathrm{\,N =\frac{kg\cdot m}{s^2}}}$

### **1.2. Trabajo de una Fuerza Variable**

* Si la fuerza aplicada varía en magnitud y dirección a lo largo del desplazamiento, el trabajo realizado por la fuerza se obtiene sumando los trabajos elementales realizados por la fuerza en cada punto del desplazamiento.

> Sea una fuerza $F$ variable que actúa sobre un cuerpo que se mueve de la posición $s_1$ a $s_2$.
> 
> **Definición:** El trabajo realizado por la fuerza $F$ desde $s_1$ hasta $s_2$ es la integral de los trabajos elementales $dW$ a lo largo de la trayectoria:
> 
> $$
> W = \int dW = \int_{s_1}^{s_2} \vec{F} \, . \,  \vec{ds} = \int_{s_1}^{s_2} F \, . \, ds \, . \, \cos(\theta)
> $$
> 
> Donde $F(s)$ es la función que describe la fuerza en función de la posición.

* En situaciones donde la fuerza se describe mediante una función específica de la posición, el trabajo se calcula utilizando la integral definida sobre el intervalo de desplazamiento.

### **1.3. Trabajo de la Fuerza Recuperadora en un Resorte**

* Consideremos un resorte cuya fuerza recuperadora varía con la posición. La fuerza ejercida por el resorte se puede expresar como:
> $$
> F = -k \Delta x
> $$
> 
> Donde $k$ es la constante del resorte y $x$ es la deformación desde la posición de equilibrio.

* El trabajo realizado por esta fuerza al comprimir o estirar el resorte desde $x = 0$ hasta $x = x_{\text{max}}$ es:
> $$
> W = \int_{0}^{x_{\text{max}}} (-k x) \, dx = -\frac{1}{2} k x_{\text{max}}^2
> $$
> 
> Este trabajo representa la energía almacenada en el resorte.

### **1.4. Trabajo de la Fuerza Peso en un Plano Inclinado**

* Cuando un cuerpo se desplaza por un plano inclinado sin fricción, la componente de la fuerza de gravedad que realiza trabajo es:
> $$
> W = P \sin(\alpha) \cdot d
> $$
> 
> Donde $P$ es el peso del cuerpo, $\alpha$ es el ángulo del plano inclinado y $d$ es la distancia recorrida.

* Este ejemplo ilustra cómo calcular el trabajo realizado por la fuerza peso en un contexto específico.

### **1.5. Trabajo de un Sistema de Fuerzas**

* Si múltiples fuerzas actúan sobre un objeto, el trabajo total realizado es la suma de los trabajos individuales de cada fuerza:
> $$
> W_{\text{total}} = W_1 + W_2 + \dots + W_n
> $$
> 
* En general, si las fuerzas se combinan para formar una fuerza resultante $\vec{F}_{\text{resultante}}$, entonces:
> $$
> W_{\text{total}} = \vec{F}_{\text{resultante}} \cdot \vec{d}
> $$

## Energía

### **2.1 Energía**

> **Definición:** La energía es una propiedad de un sistema que se puede transferir a otros sistemas o convertirse en diferentes formas, pero no puede ser creada ni destruida.

### **2.2. Energía Cinética**

> **Definición:** La energía cinética $(K)$ de un objeto es la energía escalar asociada al movimiento. Se define como:
> $$
> K = \frac{1}{2} m v^2
> $$
> Donde:
> - $K$ es la energía cinética, medida en julios (J).
> - $m$ es la masa del objeto, en kilogramos (kg).
> - $v$ es la velocidad del objeto, en metros por segundo (m/s).

#### **2.2.1. Teorema del Trabajo y la Energía Cinética**

* **Definición:** El trabajo realizado por una fuerza neta sobre un objeto es igual al cambio en la energía cinética del objeto:
  
  $$
  W_{\text{total}} = \Delta K
  $$

* **Demostración:**

  Consideremos un objeto de masa $m$ que se mueve hacia la derecha bajo la acción de una fuerza neta constante $F_{\text{net}}$ también dirigida hacia la derecha. Por la segunda ley de Newton, el objeto experimenta una aceleración constante $a = \frac{F_{\text{net}}}{m}$.

  Si el objeto se desplaza una distancia $\Delta x$, el trabajo realizado por la fuerza neta es:

  $$
  W = F_{\text{net}} \cdot \Delta x = m \cdot a \cdot \Delta x
  $$

  Utilizando una de las ecuaciones de movimiento con aceleración constante:

  $$
  v^2 = v_0^2 + 2a\Delta x
  $$

  Asumiendo que la velocidad inicial $v_0 = 0$, se tiene:

  $$
  v^2 = 2a\Delta x \implies a\Delta x = \frac{v^2}{2}
  $$

  Sustituyendo en la expresión del trabajo:

  $$
  W = m \cdot \frac{v^2}{2} = \frac{1}{2} m v^2 = \Delta K
  $$

  Por lo tanto, se demuestra que el trabajo neto realizado sobre el objeto es igual al cambio en su energía cinética.

### **2.3. Fuerza Conservativa y Energía Potencial**

* **Definición:** Una fuerza es conservativa si el trabajo realizado por la fuerza entre dos puntos es independiente de la trayectoria seguida por el objeto.

  * Ejemplos:
    * Fuerza gravitatoria.
    * Fuerza elástica.
    * Fuerza eléctrica.
    * Fuerza magnética.
    * Fuerza nuclear.
    * Fuerza de fricción.
    * Fuerza de tensión.

* **Definición:** La energía potencial $(U)$ es la energía que posee un cuerpo o sistema de
cuerpos en virtud de su posición o de su configuración (conjunto de posiciones) en
relación con su entorno. Solo las fuerzas conservativas pueden asociarse con una energía potencial.

> **Teorema:** El trabajo realizado por una fuerza conservativa es igual al negativo del cambio en la energía potencial asociada:
>
> $$
> W = -\Delta U
> $$

### demostracion

### **2.4. Energía Potencial Gravitatoria**

* **Definición:** La energía potencial gravitatoria $(U_g)$ es la energía asociada a la posición de un objeto en un campo gravitatorio. Se define como:
> $$
> U_g = P.h = m.g.h
> $$


### **2.5. Niveles de Referencia para la Energía Potencial Gravitatoria**

En situaciones donde las distancias son astronómicas, es conveniente definir la energía potencial gravitatoria con un nivel de referencia en el infinito, es decir, $U(\infty) = 0$. El trabajo necesario para mover una partícula de masa $m$ desde el infinito hasta una distancia $r$ de una masa gravitatoria $M$ es:

$$
W = -\int_{\infty}^{r} \vec{F} \cdot d\vec{r}
$$

Donde:
- $\vec{F}$ es la fuerza gravitatoria entre las masas $m$ y $M$.
- $d\vec{r}$ es un desplazamiento infinitesimal en la dirección radial.

La fuerza gravitatoria está dada por:

$$
\vec{F} = - G \frac{m M}{r^2} \hat{r}
$$

Donde:
- $G$ es la constante de gravitación universal.
- $r$ es la distancia desde la masa $M$.
- $\hat{r}$ es el vector unitario radial apuntando hacia afuera de $M$.

Al sustituir $\vec{F}$ en la expresión del trabajo, obtenemos:

$$
W = -\int_{\infty}^{r} \left( - G \frac{m M}{r'^2} \hat{r} \right) \cdot d\vec{r}'
$$

Aquí, usamos $r'$ como variable de integración para distinguirla de $r$.

Como $d\vec{r}'$ y $\hat{r}$ tienen la misma dirección (radial), su producto escalar es:

$$
\hat{r} \cdot d\vec{r}' = dr'
$$

Entonces, la expresión del trabajo se simplifica a:

$$
W = -\int_{\infty}^{r} \left( - G \frac{m M}{r'^2} \right) dr'
$$

Simplificando los signos negativos:

$$
W = \int_{\infty}^{r} G \frac{m M}{r'^2} dr'
$$

Procedemos a calcular la integral:

1. **Extraemos las constantes:**

  $$
  W = G m M \int_{\infty}^{r} \frac{dr'}{r'^2}
  $$

2. **Calculamos la integral indefinida:**

  $$
  \int \frac{dr'}{r'^2} = -\frac{1}{r'}
  $$

3. **Aplicamos los límites de integración:**

  $$
  W = G m M \left[ -\frac{1}{r'} \right]_{\infty}^{r} = G m M \left( -\frac{1}{r} - \left( -\frac{1}{\infty} \right) \right)
  $$

4. **Simplificamos teniendo en cuenta que $\frac{1}{\infty} = 0$:**

  $$
  W = G m M \left( -\frac{1}{r} - 0 \right) = -\frac{G m M}{r}
  $$

Por lo tanto, el trabajo realizado es:

$$
W = -\frac{G m M}{r}
$$

Este trabajo es igual al cambio en la energía potencial gravitatoria, por lo que la energía potencial en función de $r$ es:

$$
U(r) = -\frac{G m M}{r}
$$

**Interpretación:**

- La energía potencial es negativa, lo que indica que se requiere trabajo para separar las masas hasta el infinito.
- A medida que $r$ disminuye, $U(r)$ se vuelve más negativa, lo que significa que el sistema es más estable cuando las masas están más cerca.
- Esta expresión es fundamental para entender fenómenos como la atracción de planetas y satélites.

**Aplicación Práctica:**

Esta fórmula es esencial para calcular los requerimientos energéticos en viajes espaciales:

- **Al aproximarse a un cuerpo celeste:** Un objeto gana energía cinética mientras su energía potencial disminuye.
- **Conservación de la energía mecánica:** Si no hay fuerzas no conservativas (como fricción), la energía mecánica total permanece constante: $E = K + U$.

Esto permite diseñar trayectorias y maniobras orbitales eficientes en exploración espacial.


### **2.6. Potencia**

#### **Definición de Potencia**

La **potencia** es una medida de la rapidez con la que se realiza un trabajo o se transfiere energía. Se define como el trabajo realizado dividido por el intervalo de tiempo durante el cual se realiza:

$$
P_{\text{media}} = \frac{W}{\Delta t}
$$

Donde:
- $P_{\text{media}}$: Potencia media (en watts, W).
- $W$: Trabajo realizado (en julios, J).
- $\Delta t$: Intervalo de tiempo (en segundos, s).

#### **Potencia Instantánea**

Si el trabajo varía con el tiempo, la potencia en un instante específico se expresa como la derivada del trabajo respecto al tiempo:

$$
P = \frac{dW}{dt}
$$

Esta expresión representa la **potencia instantánea**, es decir, la tasa en la cual se realiza el trabajo en un momento dado.

#### **Unidades de Potencia**

La unidad de potencia en el Sistema Internacional es el **watt** (W), donde:

$$
1 \ \text{W} = 1 \ \frac{\text{J}}{\text{s}}
$$

Otra unidad común es el **kilowatt** (kW), utilizado para expresar potencias más grandes:

$$
1 \ \text{kW} = 1000 \ \text{W}
$$

El **kilowatt-hora** (kWh) es una unidad de energía que representa el trabajo realizado por una potencia de 1 kilowatt durante una hora:

$$
1 \ \text{kWh} = 1 \ \text{kW} \times 1 \ \text{h}
$$

#### **Relación entre Potencia y Velocidad**

Consideremos un objeto sobre el cual actúa una fuerza constante $\vec{F}$, que produce un desplazamiento en la dirección de la fuerza a una velocidad $\vec{v}$. La potencia instantánea puede expresarse entonces como:

$$
P = \vec{F} \cdot \vec{v}
$$

Donde:
- $\vec{F}$: Fuerza aplicada (en newtons, N).
- $\vec{v}$: Velocidad del objeto (en metros por segundo, m/s).
- El punto ($\cdot$) representa el **producto escalar** entre la fuerza y la velocidad.

**Demostración:**

El trabajo diferencial realizado es:

$$
dW = \vec{F} \cdot d\vec{s}
$$

Dividiendo ambos lados entre $dt$:

$$
\frac{dW}{dt} = \vec{F} \cdot \frac{d\vec{s}}{dt}
$$

Dado que $\frac{d\vec{s}}{dt} = \vec{v}$:

$$
P = \frac{dW}{dt} = \vec{F} \cdot \vec{v}
$$

Esta relación muestra cómo la potencia está directamente ligada a la fuerza aplicada y a la velocidad del objeto.

#### **Aplicaciones Prácticas**

- **Máquinas y Motores:** La potencia es un factor clave en el diseño de máquinas que realizan un trabajo significativo en menor tiempo, como grúas y tuneladoras.
  
- **Eficiencia Energética:** Conocer la potencia permite calcular la eficiencia de sistemas y optimizar el consumo energético.

#### **Ejemplo de Cálculo de Potencia**

Un elevador de masa $m$ sube con velocidad constante $v$ gracias a una fuerza $F$ que equilibra su peso. La potencia necesaria para elevar el elevador es:

$$
P = F \cdot v = m \cdot g \cdot v
$$

Donde:
- $g$: Aceleración de la gravedad (aproximadamente $9.81 \ \text{m/s}^2$).

#### **Consideraciones Finales**

- La potencia nos permite entender no solo cuánto trabajo se realiza, sino cuán rápido se realiza.
- En ingeniería, optimizar la potencia implica mejorar el rendimiento y la eficiencia de máquinas y procesos.
