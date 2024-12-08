# Solución del Problema 2

Un bloque de masa $m = 10\, \mathrm{kg}$ se libera desde una altura $h = 3\, \mathrm{m}$ en el punto A. La pista no tiene fricción excepto entre B y C, separados por una distancia $d = 6\, \mathrm{m}$. El bloque llega al resorte de constante $k = 2250\, \mathrm{N/m}$ y lo comprime $x = 0,3\, \mathrm{m}$ hasta que se detiene. Se solicita determinar el coeficiente de fricción $\mu$ entre B y C.

## Paso 1: Energía potencial inicial en A

La energía potencial gravitatoria en A es:

$$
E_{pA} = mgh
$$

Donde:
- $m = 10\, \mathrm{kg}$
- $g = 9,8\, \mathrm{m/s^2}$
- $h = 3\, \mathrm{m}$

Calculamos:

$$
E_{pA} = 10\, \mathrm{kg} \times 9,8\, \mathrm{m/s^2} \times 3\, \mathrm{m} = 294\, \mathrm{J}
$$

## Paso 2: Energía cinética en B

Como no hay fricción entre A y B, toda la energía potencial se convierte en energía cinética en B:

$$
E_{kB} = E_{pA} = 294\, \mathrm{J}
$$

## Paso 3: Trabajo de la fricción entre B y C

El trabajo realizado por la fuerza de fricción es:

$$
W_f = -f_k d = -\mu N d = -\mu m g d
$$

Donde:
- $\mu$ es el coeficiente de fricción
- $N = mg$ es la fuerza normal
- $d = 6\, \mathrm{m}$

## Paso 4: Energía cinética en C

La energía cinética en C es:

$$
E_{kC} = E_{kB} + W_f = E_{kB} - \mu m g d
$$

## Paso 5: Energía potencial elástica del resorte

Cuando el bloque comprime el resorte y se detiene, toda su energía cinética se convierte en energía potencial elástica:

$$
E_{pe} = \frac{1}{2} k x^2
$$

Con:
- $k = 2250\, \mathrm{N/m}$
- $x = 0,3\, \mathrm{m}$

Calculamos:

$$
E_{pe} = \frac{1}{2} \times 2250\, \mathrm{N/m} \times (0,3\, \mathrm{m})^2 = 101,25\, \mathrm{J}
$$

## Paso 6: Igualación de energías

Al detenerse en el resorte:

$$
E_{kC} = E_{pe}
$$

Sustituyendo:

$$
E_{kB} - \mu m g d = E_{pe}
$$

## Paso 7: Despeje del coeficiente de fricción $\mu$

Reordenamos la ecuación para encontrar $\mu$:

$$
\mu = \frac{E_{kB} - E_{pe}}{m g d}
$$

Sustituyendo los valores:

$$
\mu = \frac{294\, \mathrm{J} - 101,25\, \mathrm{J}}{10\, \mathrm{kg} \times 9,8\, \mathrm{m/s^2} \times 6\, \mathrm{m}}
$$

Calculamos el denominador:

$$
m g d = 10\, \mathrm{kg} \times 9,8\, \mathrm{m/s^2} \times 6\, \mathrm{m} = 588\, \mathrm{J}
$$

Entonces:

$$
\mu = \frac{192,75\, \mathrm{J}}{588\, \mathrm{J}} = 0,3275
$$

## Paso 8: Resultado final

El coeficiente de fricción entre B y C es aproximadamente:

$$
\mu \approx 0,328
$$
