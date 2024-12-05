# Capacidad eléctrica, capacitores

## Condensadores

Los condensadores de un circuito electrónico cumplen la función de almacenamiento 
y estabilización de la corriente eléctrica

## Capacitores y Capacitancia

Un **capacitor** es un dispositivo que almacena energía eléctrica en forma de campo eléctrico. Consiste en dos conductores separados por un material aislante o dieléctrico.

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

Cuando varios capacitores se conectan en **serie**, la carga eléctrica (\( Q \)) en cada capacitor es la misma, pero la diferencia de potencial total (\( V_{\text{total}} \)) es la suma de las diferencias de potencial individuales.

### Paso 1: Comprender la Configuración en Serie

- **Carga en cada capacitor**: $\ ( Q_1 = Q_2 = Q_3 = \dotsb = Q )$
- **Diferencia de potencial total**: $\ ( V_{\text{total}} = V_1 + V_2 + V_3 + \dotsb )$

### Paso 2: Relacionar Capacitancia y Voltaje en Cada Capacitor

La relación entre carga, capacitancia y voltaje para cada capacitor es:

$$
C_i = \frac{Q}{V_i}
$$

Despejando \( V_i \):

$$
V_i = \frac{Q}{C_i}
$$

### Paso 3: Expresar el Voltaje Total

Sustituimos \( V_i \) en la expresión del voltaje total:

$$
V_{\text{total}} = V_1 + V_2 + V_3 + \dotsb = \frac{Q}{C_1} + \frac{Q}{C_2} + \frac{Q}{C_3} + \dotsb
$$

### Paso 4: Definir la Capacitancia Equivalente en Serie

La capacitancia equivalente \( C_{\text{eq}} \) es aquella que cumple:

$$
C_{\text{eq}} = \frac{Q}{V_{\text{total}}}
$$

Despejando \( V_{\text{total}} \):

$$
V_{\text{total}} = \frac{Q}{C_{\text{eq}}}
$$

### Paso 5: Igualar las Expresiones de \( V_{\text{total}} \)

Igualamos las dos expresiones de \( V_{\text{total}} \):

$$
\frac{Q}{C_{\text{eq}}} = \frac{Q}{C_1} + \frac{Q}{C_2} + \frac{Q}{C_3} + \dotsb
$$

### Paso 6: Simplificar la Ecuación

Dividimos ambos lados entre \( Q \) (asumiendo \( Q \ne 0 \)):

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

Cuando varios capacitores se conectan en **paralelo**, la diferencia de potencial (\( V \)) en cada capacitor es la misma, pero la carga total (\( Q_{\text{total}} \)) es la suma de las cargas individuales.

### Paso 1: Comprender la Configuración en Paralelo

- **Voltaje en cada capacitor**: \( V_1 = V_2 = V_3 = \dotsb = V \)
- **Carga total**: \( Q_{\text{total}} = Q_1 + Q_2 + Q_3 + \dotsb \)

### Paso 2: Relacionar Capacitancia y Carga en Cada Capacitor

La relación es:

$$
C_i = \frac{Q_i}{V}
$$

Despejando \( Q_i \):

$$
Q_i = C_i V
$$

### Paso 3: Expresar la Carga Total

Sustituimos \( Q_i \) en la expresión de la carga total:

$$
Q_{\text{total}} = C_1 V + C_2 V + C_3 V + \dotsb = V (C_1 + C_2 + C_3 + \dotsb)
$$

### Paso 4: Definir la Capacitancia Equivalente en Paralelo

La capacitancia equivalente \( C_{\text{eq}} \) es:

$$
C_{\text{eq}} = \frac{Q_{\text{total}}}{V}
$$

### Paso 5: Simplificar la Ecuación

Sustituimos \( Q_{\text{total}} \):

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

Para un capacitor de placas paralelas con carga \( Q \) y área \( A \), el campo eléctrico \( E \) entre las placas es uniforme y dado por:

$$
E = \frac{\sigma}{\varepsilon_0} = \frac{Q}{\varepsilon_0 A}
$$

Donde \( \sigma \) es la densidad de carga superficial.

### Paso 2: Relacionar el Voltaje con el Campo Eléctrico

La diferencia de potencial \( V \) entre las placas es:

$$
V = Ed = \frac{Q d}{\varepsilon_0 A}
$$

Donde \( d \) es la separación entre las placas.

### Paso 3: Calcular la Capacitancia

Usando la definición de capacitancia \( C = \frac{Q}{V} \):

$$
C = \frac{Q}{V} = \frac{Q}{\frac{Q d}{\varepsilon_0 A}} = \frac{\varepsilon_0 A}{d}
$$

---

## Energía de un Capacitor

La energía almacenada ($U$) en un capacitor cargado es:

$$ U = \frac{1}{2} C V^2 $$

Esta energía se almacena en el campo eléctrico existente entre las placas del capacitor.

## Dieléctricos

Un **dieléctrico** es un material aislante que, al insertarse entre las placas de un capacitor, aumenta su capacitancia al reducir el campo eléctrico efectivo.

La nueva capacitancia con dieléctrico es:

$$ C = \kappa \varepsilon_0 \frac{A}{d} $$

Donde:
- $\kappa$ es la **constante dieléctrica** del material (también denominada permitividad relativa).
  
El dieléctrico aumenta la capacitancia en un factor de $\kappa$ comparado con el mismo capacitor en el vacío.

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

- **Fuerza Dieléctrica**: Es el campo eléctrico máximo que un dieléctrico puede soportar sin romperse, medido en voltios por metro (V/m).

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
