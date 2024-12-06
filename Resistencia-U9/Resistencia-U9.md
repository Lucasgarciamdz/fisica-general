# Corriente y circuitos

## Corriente eléctrica

> **Definición**: La corriente electrica se define como el flujo de cargas eléctricas que atraviesa por unidad de tiempo la sección transversal de un conductor.
>
> **Unidad**: Amperios ($\text{A} = \text{Coulomb/seg}$)
> **Fórmula**: $I = \frac{\Delta Q}{\Delta t}$

## Resistencia

La resistencia eléctrica mide la oposición que ofrece un material al paso de la corriente eléctrica. Surge debido a las interacciones entre las cargas móviles y los átomos del material, lo que provoca una disipación de energía en forma de calor.

Cuando se aplica un campo eléctrico $E$ en un conductor, las cargas eléctricas experimentan una fuerza que las hace moverse. Esta diferencia de potencial $V$ entre dos puntos se relaciona con el campo eléctrico y la distancia $\Delta L$:

$$
V = E \, \Delta L
$$

La resistencia $R$ se define como el cociente entre la diferencia de potencial y la corriente $I$ que circula:

$$
R = \frac{\Delta V}{I}
$$

La unidad de resistencia en el SI es el ohm ($\Omega$), donde $1\,\Omega = 1\,\frac{\text{V}}{\text{A}}$.

Para un conductor de longitud $\ell$, área de sección transversal $A$ y resistividad $\rho$, la resistencia se calcula mediante:

$$
R = \rho \, \frac{\ell}{A}
$$

* Si se duplica la longitud de un alambre, su resistencia se duplica. Si se duplica su área de sección transversal, su resistencia disminuye a la mitad.

La **resistividad** $\rho$ es una propiedad intrínseca de los materiales que determina cómo se oponen al flujo de corriente eléctrica. Depende de factores como la temperatura y la estructura molecular.

### Resistencia interna de una fuente

En las fuentes de voltaje reales, como las baterías, existe una resistencia interna $r$ que afecta el voltaje suministrado al circuito externo. Esta resistencia interna se modela como una resistencia en serie con una fuente de voltaje ideal de fuerza electromotriz (fem) $\mathcal{E}$.

Cuando se conecta una resistencia externa $R$, la corriente $I$ que circula por el circuito es:

$$
I = \frac{\mathcal{E}}{R + r}
$$

El voltaje terminal $V$ entre los bornes de la fuente es menor que la fem debido a la caída de voltaje en la resistencia interna:

$$
V = \mathcal{E} - I\, r = I\, R
$$

Donde:

- $\mathcal{E}$ es la fuerza electromotriz de la fuente (en voltios).
- $I$ es la corriente que circula por el circuito (en amperios).
- $V$ es el voltaje terminal (en voltios).
- $R$ es la resistencia externa conectada al circuito (en ohmios).
- $r$ es la resistencia interna de la fuente (en ohmios).

La resistencia interna provoca que el voltaje disponible para el circuito disminuya a medida que aumenta la corriente, lo cual es crucial considerar en el diseño y análisis de circuitos eléctricos.

## Ley de Ohm

La ley de Ohm establece que la corriente que circula por un conductor es directamente proporcional a la diferencia de potencial aplicada y es inversamente proporcional a la resistencia del conductor:

$$
\text{"Viva Independiente Rivadavia" }
\\
\Delta V = I \, R \quad \text{o} \quad I = \frac{\Delta V}{R}
$$

Donde:
- $\Delta V$ es la diferencia de potencial en voltios ($\text{V}$).
- $I$ es la corriente en amperios ($\text{A}$).
- $R$ es la resistencia en ohmios ($\Omega$).

## Potencia eléctrica

La potencia eléctrica $P$ es la cantidad de energía que se transfiere por unidad de tiempo en un circuito eléctrico. Para deducir su expresión, consideremos un circuito simple donde una diferencia de potencial $V$ se aplica a un resistor de resistencia $R$, y una corriente $I$ circula por él.

La energía $\Delta U$ transferida al resistor cuando una carga $\Delta Q$ pasa a través de él es:

$$
\Delta U = \Delta Q \, V
$$

La potencia es la tasa de cambio de energía respecto al tiempo:

$$
P = \frac{\Delta U}{\Delta t} = \frac{\Delta Q}{\Delta t} \, V = I \, V
$$

Utilizando la ley de Ohm ($V = I \, R$), la potencia también puede expresarse como:

$$
P = I^2 \, R = \frac{V^2}{R}
$$

Donde:
- $P$ es la potencia en vatios ($\text{W}$).
- $I$ es la corriente en amperios ($\text{A}$).
- $V$ es la diferencia de potencial en voltios ($\text{V}$).
- $R$ es la resistencia en ohmios ($\Omega$).

La potencia eléctrica se puede expresar en términos de la corriente y la resistencia, o en términos de la diferencia de potencial y la resistencia. En ambos casos, la potencia es proporcional al cuadrado de la corriente o de la diferencia de potencial, y es inversamente proporcional a la resistencia.

$$
P = I \, V = I^2 \, R = \frac{\Delta V^2}{R}
$$

## Circuitos en serie y en paralelo

### Circuitos en serie

En un circuito en serie, los elementos están conectados uno tras otro, de modo que la corriente que circula por cada uno es la misma. La resistencia total $R_{\text{total}}$ de un circuito en serie es la suma de las resistencias individuales:

$$
R_{\text{total}} = R_1 + R_2 + \dots + R_n
$$

* La corriente total $I$ que circula por el circuito es la misma en todos los elementos:

$$
I = I_1 = I_2 = cte
$$

* La caída de voltaje en cada resistencia es proporcional a su resistencia:

$$
V = IR_1 + IR_2 + \dots = I(R_1 + R_2 + \dots) = I \, R_{\text{total}}
$$

### Circuitos en paralelo

En un circuito en paralelo, los elementos están conectados de manera que ambos extremos están conectados a un mismo nodo. La corriente total se divide entre las resistencias, y el voltaje es el mismo en todos los elementos.

* La resistencia total de un circuito en paralelo se calcula mediante la fórmula:

$$
\frac{1}{R_{\text{total}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}
$$

* La corriente total se calcula mediante la ley de Ohm:

$$
I = I_1 + I_2 + \dots
$$

* El voltaje es el mismo en todos los elementos:

$$
V = V_1 = V_2 = cte
$$

### Tabla resumen

| Propiedad          | Circuitos en serie                   | Circuitos en paralelo                |
|--------------------|--------------------------------------|--------------------------------------|
| Corriente          | $I = \frac{V}{R_{\text{total}}}=cte$      | $I = I_1 + I_2 + \dots$              |
| Voltaje            | $V = V_1 + V_2 + \dots$              | $V = V_1 = V_2 = cte$              |
| Resistencia total  | $R_{\text{total}} = R_1 + R_2 + \dots$| $\frac{1}{R_{\text{total}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots$|

## Ley de Kirchhoff

Las leyes de Kirchhoff son dos principios fundamentales que rigen el comportamiento de los circuitos eléctricos:

1. **Ley de corrientes de Kirchhoff (LCK)**: La suma algebraica de las corrientes que entran y salen de un nodo es igual a cero.

$$
\sum I_{\text{entrantes}} = \sum I_{\text{salientes}}
$$

2. **Ley de tensiones de Kirchhoff (LTK)**: La suma algebraica de las diferencias de potencial en un circuito cerrado es igual a cero.

$$
\sum \Delta V = 0
$$

Estas leyes son esenciales para analizar circuitos eléctricos complejos, ya que permiten determinar las corrientes y voltajes en cada elemento del circuito.
