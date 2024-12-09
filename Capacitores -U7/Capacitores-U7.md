# Capacidad eléctrica, capacitores

## Capacitores y Capacitancia

Un **capacitor** es un dispositivo que almacena energía eléctrica y estabiliza la corriente eléctrica. Consiste en dos conductores separados por un material aislante o dieléctrico.

La **capacitancia** ($C$) es una medida de la capacidad de un capacitor para almacenar carga eléctrica por unidad de diferencia de potencial. Se define como:

$$ C = \frac{Q}{V} $$

Donde:
- $Q$ es la carga eléctrica en coulombios (C).
- $V$ es la diferencia de potencial en voltios (V).
- $C$ es la capacitancia en faradios (F).

## Capacitancia en la Construcción de Capacitores

La capacitancia depende de la geometría del capacitor y del medio entre los conductores.

### Capacitor de Placas Paralelas

Para un capacitor de placas paralelas en vacío:

$$ C = \varepsilon_0 \frac{A}{d} $$

Donde:
- $\varepsilon_0$ es la permitividad del vacío ($8.85 \times 10^{-12} \, \text{F/m}$).
- $A$ es el área de cada placa en metros cuadrados ($\text{m}^2$).
- $d$ es la distancia entre las placas en metros (m).

## Capacitores en Serie y en Paralelo

### Capacitores en Serie

La capacitancia equivalente ($C_{\text{eq}}$) de capacitores en serie se calcula como:

$$ \frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3} + \dotsb $$

Esto ocurre porque la carga $Q$ es igual en todos los capacitores, pero el voltaje total es la suma de los voltajes individuales.

## Demostración: Capacitores en Serie

Cuando varios capacitores se conectan en **serie**, la carga eléctrica $\ ( Q )$ en cada capacitor es la misma, pero la diferencia de potencial total ($\  V_{\text{total}}$ ) es la suma de las diferencias de potencial individuales.

### Paso 1: Comprender la Configuración en Serie

- **Carga en cada capacitor**: $\ ( Q_1 = Q_2 = Q_3 = \dotsb = Q )$
- **Diferencia de potencial total**: $\ ( V_{\text{total}} = V_1 + V_2 + V_3 + \dotsb )$

### Paso 2: Relacionar Capacitancia y Voltaje en Cada Capacitor

La relación entre carga, capacitancia y voltaje para cada capacitor es:

$$
C_i = \frac{Q}{V_i}
$$

Despejando $\ ( V_i )$:

$$
V_i = \frac{Q}{C_i}
$$

### Paso 3: Expresar el Voltaje Total

Sustituimos $\ ( V_i )$ en la expresión del voltaje total:

$$
V_{\text{total}} = V_1 + V_2 + V_3 + \dotsb = \frac{Q}{C_1} + \frac{Q}{C_2} + \frac{Q}{C_3} + \dotsb
$$

### Paso 4: Definir la Capacitancia Equivalente en Serie

La capacitancia equivalente $\ ( C_{\text{eq}} )$ es aquella que cumple:

$$
C_{\text{eq}} = \frac{Q}{V_{\text{total}}}
$$

Despejando $\ ( V_{\text{total}} )$:

$$
V_{\text{total}} = \frac{Q}{C_{\text{eq}}}
$$

### Paso 5: Igualar las Expresiones de $\ ( V_{\text{total}} )$

Igualamos las dos expresiones de $\ ( V_{\text{total}} )$:

$$
\frac{Q}{C_{\text{eq}}} = \frac{Q}{C_1} + \frac{Q}{C_2} + \frac{Q}{C_3} + \dotsb
$$

### Paso 6: Simplificar la Ecuación

Dividimos ambos lados entre $\ ( Q )$ (asumiendo $\ ( Q \ne 0 )$):

$$
\frac{1}{C_{\text{eq}}} = \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3} + \dotsb
$$

**Conclusión**: La fórmula para capacitores en serie es:

$$
\frac{1}{C_{\text{eq}}} = \sum_{i} \frac{1}{C_i}
$$

---

### Capacitores en Paralelo

La capacitancia equivalente de capacitores en paralelo es la suma directa de las capacitancias:

$$ C_{\text{eq}} = C_1 + C_2 + C_3 + \dotsb $$

En este caso, la diferencia de potencial $V$ es la misma en cada capacitor, pero la carga total es la suma de las cargas individuales.

## Demostración: Capacitores en Paralelo

Cuando varios capacitores se conectan en **paralelo**, la diferencia de potencial $\ ( V )$ en cada capacitor es la misma, pero la carga total $\ ( Q_{\text{total}} )$ es la suma de las cargas individuales.

### Paso 1: Comprender la Configuración en Paralelo

- **Voltaje en cada capacitor**: $\ ( V_1 = V_2 = V_3 = \dotsb = V )$
- **Carga total**: $\ ( Q_{\text{total}} = Q_1 + Q_2 + Q_3 + \dotsb )$

### Paso 2: Relacionar Capacitancia y Carga en Cada Capacitor

La relación es:

$$
C_i = \frac{Q_i}{V}
$$

Despejando $\ ( Q_i )$:

$$
Q_i = C_i V
$$

### Paso 3: Expresar la Carga Total

Sustituimos $\ ( Q_i )$ en la expresión de la carga total:

$$
Q_{\text{total}} = C_1 V + C_2 V + C_3 V + \dotsb = V (C_1 + C_2 + C_3 + \dotsb)
$$

### Paso 4: Definir la Capacitancia Equivalente en Paralelo

La capacitancia equivalente $\ ( C_{\text{eq}} )$ es:

$$
C_{\text{eq}} = \frac{Q_{\text{total}}}{V}
$$

### Paso 5: Simplificar la Ecuación

Sustituimos $\ ( Q_{\text{total}} )$:

$$
C_{\text{eq}} = \frac{V (C_1 + C_2 + C_3 + \dotsb)}{V} = C_1 + C_2 + C_3 + \dotsb
$$

**Conclusión**: La fórmula para capacitores en paralelo es:

$$
C_{\text{eq}} = \sum_{i} C_i
$$

---

## Demostración Detallada de la Capacitancia de un Capacitor de Placas Paralelas

### Paso 1: Definir el Campo Eléctrico entre las Placas

Para un capacitor de placas paralelas con carga $\ ( Q )$ y área $\ ( A )$, el campo eléctrico $\ ( E )$ entre las placas es uniforme y dado por:

$$
E = \frac{\sigma}{\varepsilon_0} = \frac{Q}{\varepsilon_0 A}
$$

Donde $\ ( \sigma )$ es la densidad de carga superficial.

### Paso 2: Relacionar el Voltaje con el Campo Eléctrico

La diferencia de potencial \( V \) entre las placas es:

$$
V = Ed = \frac{Q d}{\varepsilon_0 A}
$$

Donde \( d \) es la separación entre las placas.

### Paso 3: Calcular la Capacitancia

Usando la definición de capacitancia $\ ( C = \frac{Q}{V} )$:

$$
C = \frac{Q}{V} = \frac{Q}{\frac{Q d}{\varepsilon_0 A}} = \frac{\varepsilon_0 A}{d}
$$

---

## Energía de un Capacitor

La energía potencial eléctrica almacenada en un capacitor cargado es exactamente igual a la 
cantidad de trabajo requerido para cargarlo, osea para separar cargas opuestas y colocarlas 
en los diferentes conductores. Cuando el capacitor se descarga, esta energía almacenada se 
recupera en forma de trabajo realizado por las fuerzas eléctricas.

La energía almacenada ($U$) en un capacitor cargado se puede deducir paso a paso de la siguiente manera:

### Paso 1: Definir el Trabajo Necesario para Mover una Carga

El trabajo diferencial ($dU$) necesario para mover una carga diferencial ($dq$) a través de un diferencial de voltaje ($dV$) es:

$$ dU = V \, dq $$

### Paso 2: Expresar el Voltaje en Términos de la Carga

Despejamos $V$ de la ecuación de la capacitancia:

$$ V = \frac{Q}{C} $$

### Paso 3: Sustituir el Voltaje en la Energía Diferencial

Sustituimos $V$ en la ecuación de la energía diferencial:

$$ dU = \frac{Q}{C} \, dq $$

### Paso 4: Integrar para Encontrar la Energía Total

Integramos ambos lados para encontrar la energía total almacenada en el capacitor:

$$ U = \int_0^Q \frac{Q'}{C} \, dQ' $$

Donde $Q'$ es una variable de integración que representa la carga.

### Paso 6: Realizar la Integración

La integral se resuelve como:

$$ U = \frac{1}{C} \int_0^Q Q' \, dQ' = \frac{1}{C} \left[ \frac{(Q')^2}{2} \right]_0^Q = \frac{1}{C} \left( \frac{Q^2}{2} - 0 \right) = \frac{Q^2}{2C} $$

### Paso 7: Expresar la Energía en Términos del Voltaje

Usamos la relación $Q = C \, V$ para expresar la energía en términos del voltaje:

$$ U = \frac{(C \, V)^2}{2C} = \frac{C \, V^2}{2} $$

### Unidades en el Sistema Internacional

- Energía ($U$): Joules (J)
- Capacitancia ($C$): Faradios (F)
- Voltaje ($V$): Voltios (V)

La fórmula final para la energía almacenada en un capacitor es con sus distintas formas usando la relación $Q = C \, V$:

$$ U = \frac{Q^2}{2C} $$
$$ U = \frac{1}{2} C V^2 $$
$$ U = \frac{1}{2} Q V $$

Esta energía se almacena en el campo eléctrico existente entre las placas del capacitor.

## Dieléctricos

Un **dieléctrico** es un material aislante que, al insertarse entre las placas de un capacitor, aumenta su capacitancia al reducir el campo eléctrico efectivo.

La nueva capacitancia con dieléctrico es:

$$ C = \kappa \varepsilon_0 \frac{A}{d} $$

Donde:
- $\kappa$ es la **constante dieléctrica** del material (también denominada permitividad relativa).
  
El dieléctrico aumenta la capacitancia en un factor de $\kappa$ comparado con el mismo capacitor en el vacío.

### Efectos de Agregar o Quitar un Dieléctrico en un Capacitor

La inserción o remoción de un dieléctrico en un capacitor puede ocurrir con la batería conectada o desconectada. Esto afecta las magnitudes eléctricas del capacitor de diferentes maneras.

#### Caso 1: Batería Conectada y se Agrega un Dieléctrico

- **Voltaje ($V$)**: Permanece constante (igual al voltaje de la batería).
- **Capacitancia ($C$)**: Aumenta en un factor de $\kappa$ ($C' = \kappa C$).
- **Carga ($Q$)**: Aumenta ($Q' = C' V = \kappa C V = \kappa Q$).
- **Campo Eléctrico ($E$)**: Disminuye ($E' = \dfrac{E}{\kappa}$).
- **Energía Almacenada ($U$)**: Aumenta ($U' = \dfrac{1}{2} C' V^2 = \kappa U$).

*Explicación*: Al agregar un dieléctrico, la capacitancia aumenta. Como el voltaje se mantiene constante por la batería, el capacitor almacena más carga, incrementando la energía almacenada.

#### Caso 2: Batería Conectada y se Quita el Dieléctrico

- **Voltaje ($V$)**: Permanece constante.
- **Capacitancia ($C$)**: Disminuye ($C' = \dfrac{C}{\kappa}$).
- **Carga ($Q$)**: Disminuye ($Q' = C' V = \dfrac{C V}{\kappa} = \dfrac{Q}{\kappa}$).
- **Campo Eléctrico ($E$)**: Aumenta ($E' = \kappa E$).
- **Energía Almacenada ($U$)**: Disminuye ($U' = \dfrac{1}{2} C' V^2 = \dfrac{U}{\kappa}$).

*Explicación*: Al remover el dieléctrico, la capacitancia disminuye. La batería mantiene el voltaje constante, por lo que el capacitor libera carga, reduciendo la energía almacenada.

#### Caso 3: Batería Desconectada y se Agrega un Dieléctrico

- **Carga ($Q$)**: Permanece constante (no hay camino para que la carga cambie).
- **Capacitancia ($C$)**: Aumenta ($C' = \kappa C$).
- **Voltaje ($V$)**: Disminuye ($V' = \dfrac{Q}{C'} = \dfrac{V}{\kappa}$).
- **Campo Eléctrico ($E$)**: Disminuye ($E' = \dfrac{E}{\kappa}$).
- **Energía Almacenada ($U$)**: Disminuye ($U' = \dfrac{1}{2} Q V' = \dfrac{U}{\kappa}$).

*Explicación*: Sin conexión a la batería, la carga se mantiene. Al aumentar la capacitancia con el dieléctrico, el voltaje disminuye, al igual que la energía almacenada.

#### Caso 4: Batería Desconectada y se Quita el Dieléctrico

- **Carga ($Q$)**: Permanece constante.
- **Capacitancia ($C$)**: Disminuye ($C' = \dfrac{C}{\kappa}$).
- **Voltaje ($V$)**: Aumenta ($V' = \dfrac{Q}{C'} = \kappa V$).
- **Campo Eléctrico ($E$)**: Aumenta ($E' = \kappa E$).
- **Energía Almacenada ($U$)**: Disminuye ($U' = \dfrac{1}{2} Q V' = \kappa U$).
  
*Explicación*: Al quitar el dieléctrico, la capacitancia disminuye. Sin conexión a la batería, el voltaje aumenta, reduciendo la energía almacenada.


---

**Resumen de los Casos**

| Situación                              | $V$            | $C$                   | $Q$                | $E$              | $U$                |
|----------------------------------------|----------------|-----------------------|--------------------|------------------|--------------------|
| Batería conectada, agrega dieléctrico  | Constante      | Aumenta ($\kappa C$)  | Aumenta ($\kappa Q$) | Disminuye ($E/\kappa$) | Aumenta ($\kappa U$) |
| Batería conectada, quita dieléctrico   | Constante      | Disminuye ($C/\kappa$) | Disminuye ($Q/\kappa$) | Aumenta ($\kappa E$) | Disminuye ($U/\kappa$) |
| Batería desconectada, agrega dieléctrico | Disminuye ($V/\kappa$) | Aumenta ($\kappa C$)  | Constante         | Disminuye ($E/\kappa$) | Disminuye ($U/\kappa$) |
| Batería desconectada, quita dieléctrico | Aumenta ($\kappa V$) | Disminuye ($C/\kappa$) | Constante         | Aumenta ($\kappa E$) | Disminuye ($\kappa U$) |


## Cuadro con Constantes Dieléctricas

| Material      | Constante Dieléctrica ($\kappa$) |
|---------------|----------------------------------|
| Vacío         | 1.0                              |
| Aire          | 1.0006                           |
| Agua          | 80                               |
| Vidrio        | 4 - 7                            |
| Mica          | 6                                |
| Papel         | 3.7                              |
| Poliestireno  | 2.6                              |

## Ruptura Dieléctrica

La **ruptura dieléctrica** ocurre cuando el campo eléctrico aplicado supera un valor crítico, llamado **fuerza dieléctrica**, provocando que el dieléctrico se vuelva conductor.

- **Fuerza Dieléctrica**: Es el campo eléctrico máximo que un dieléctrico puede soportar sin romperse, medido en voltios por metro $\ (\frac{V}{m})$.

Ejemplo: El aire tiene una fuerza dieléctrica de aproximadamente $3 \times 10^6 \, \text{V/m}$.

## Líneas de Campo Eléctrico entre Placas de un Capacitor

Entre las placas de un capacitor de placas paralelas, el campo eléctrico es uniforme y perpendicular a las placas. Las líneas de campo eléctrico son rectas, paralelas y equidistantes.

Al introducir un dieléctrico, el campo eléctrico se reduce debido a la polarización del material, pero las líneas de campo mantienen su dirección general.

## Modelo Molecular de la Carga Inducida

En presencia de un campo eléctrico externo, los dieléctricos se polarizan:

- **Moléculas Polares**: Tienen un momento dipolar permanente que se alinea con el campo eléctrico aplicado.
- **Moléculas No Polares**: Experimentan una distorsión en la distribución de sus cargas, generando un momento dipolar inducido.

Esta polarización crea campos eléctricos internos que se oponen al campo externo, reduciendo el campo eléctrico neto dentro del dieléctrico y aumentando la capacitancia del capacitor.

---

## Trabajo al Insertar o Remover un Dieléctrico en un Capacitor

El proceso de insertar o remover un dieléctrico en un capacitor implica la realización de trabajo, ya sea por parte de una fuente externa o entregado al sistema. Este trabajo depende de si el capacitor está conectado o desconectado de una batería.

### Caso 1: Capacitor Conectado a una Batería

#### a) Insertar un Dieléctrico

- **Voltaje ($V$):** Se mantiene constante debido a la batería.
- **Capacitancia ($C$):** Aumenta a $C' = \kappa C$.
- **Carga ($Q$):** Aumenta a $Q' = C' V = \kappa C V$.
- **Energía Inicial ($U$):** $U = \dfrac{1}{2} C V^2$.
- **Energía Final ($U'$):** $U' = \dfrac{1}{2} C' V^2 = \dfrac{1}{2} \kappa C V^2$.

**Trabajo Realizado ($W$):**

El trabajo realizado por la batería es igual al incremento en la energía almacenada:

$$
W = U' - U = \dfrac{1}{2} \kappa C V^2 - \dfrac{1}{2} C V^2 = \dfrac{1}{2} C V^2 (\kappa - 1)
$$

**Unidades:**

- $C$ en Faradios (F)
- $V$ en Voltios (V)
- $W$ en Joules (J)

#### b) Remover un Dieléctrico

- **Capacitancia Final ($C'$):** Disminuye a $C' = \dfrac{C}{\kappa}$.
- **Carga Final ($Q'$):** Disminuye a $Q' = C' V = \dfrac{C V}{\kappa}$.
- **Energía Final ($U'$):** $U' = \dfrac{1}{2} C' V^2 = \dfrac{1}{2} \dfrac{C}{\kappa} V^2$.

**Trabajo Realizado ($W$):**

$$
W = U' - U = \dfrac{1}{2} \dfrac{C}{\kappa} V^2 - \dfrac{1}{2} C V^2 = -\dfrac{1}{2} C V^2 \left( 1 - \dfrac{1}{\kappa} \right)
$$

El trabajo es negativo, indicando que la energía es devuelta a la batería.

### Caso 2: Capacitor Desconectado de una Batería

#### a) Insertar un Dieléctrico

- **Carga ($Q$):** Permanece constante.
- **Capacitancia ($C$):** Aumenta a $C' = \kappa C$.
- **Voltaje Final ($V'$):** Disminuye a $V' = \dfrac{Q}{C'} = \dfrac{V}{\kappa}$.
- **Energía Inicial ($U$):** $U = \dfrac{1}{2} C V^2$.
- **Energía Final ($U'$):** $U' = \dfrac{1}{2} C' V'^2 = \dfrac{1}{2} \kappa C \left( \dfrac{V}{\kappa} \right)^2 = \dfrac{1}{2} \dfrac{C V^2}{\kappa}$.

**Trabajo Realizado ($W$):**

$$
W = U' - U = \dfrac{1}{2} \dfrac{C V^2}{\kappa} - \dfrac{1}{2} C V^2 = -\dfrac{1}{2} C V^2 \left( 1 - \dfrac{1}{\kappa} \right)
$$

El trabajo es negativo, lo que significa que el sistema realiza trabajo externo.

#### b) Remover un Dieléctrico

- **Capacitancia Final ($C'$):** Disminuye a $C' = \dfrac{C}{\kappa}$.
- **Voltaje Final ($V'$):** Aumenta a $V' = \dfrac{Q}{C'} = \kappa V$.
- **Energía Final ($U'$):** $U' = \dfrac{1}{2} C' V'^2 = \dfrac{1}{2} \dfrac{C}{\kappa} (\kappa V)^2 = \dfrac{1}{2} \kappa C V^2$.

**Trabajo Realizado ($W$):**

$$
W = U' - U = \dfrac{1}{2} \kappa C V^2 - \dfrac{1}{2} C V^2 = \dfrac{1}{2} C V^2 (\kappa - 1)
$$

El trabajo es positivo, indicando que se requiere trabajo externo para remover el dieléctrico.

### Verificación de Unidades en el Sistema Internacional

Considerando $C$ en Faradios (F), $V$ en Voltios (V), y $\kappa$ adimensional:

- **Energía ($U$, $U'$):** Joules (J), ya que $1\, \text{F} \times (\text{V})^2 = \text{Coulomb}/\text{Volt} \times \text{Volt}^2 = \text{Coulomb} \times \text{Volt} = \text{Joule}$.
- **Trabajo ($W$):** Joules (J), dado que es la diferencia de energías.
