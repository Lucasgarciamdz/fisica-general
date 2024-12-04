# **Fórmulas de Cinemática**

### **Tabla de Unidades**
| **Símbolo**       | **Unidad**               | **Descripción**          |
|-------------------|--------------------------|--------------------------|
| $\Delta x$        | metros ($\text{m}$)       | Desplazamiento           |
| $\Delta t$        | segundos ($\text{s}$)     | Intervalo de tiempo      |
| $v_{\text{prom}}$ | metros/segundo ($\text{m/s}$) | Velocidad promedio   |
| $v(t)$            | metros/segundo ($\text{m/s}$) | Velocidad instantánea  |
| $s$               | metros ($\text{m}$)       | Distancia recorrida      |
| $a_{\text{prom}}$ | metros/segundo² ($\text{m/s}^2$) | Aceleración promedio |
| $a(t)$            | metros/segundo² ($\text{m/s}^2$) | Aceleración instantánea |
| $\vec{r}(t)$      | metros ($\text{m}$)       | Vector de posición       |
| $\Delta \vec{r}$  | metros ($\text{m}$)       | Vector de desplazamiento |
| $g$               | metros/segundo² ($\text{m/s}^2$) | Aceleración gravitatoria |
| $v_0$             | metros/segundo ($\text{m/s}$) | Velocidad inicial      |
| $\theta$          | grados ($^\circ$)         | Ángulo de lanzamiento    |
| $T$               | segundos ($\text{s}$)     | Tiempo de vuelo          |
| $H_m$             | metros ($\text{m}$)       | Altura máxima            |

---

## **1. Desplazamiento**
$$
\Delta x \, (\text{\small m}) = x_f \, (\text{\small m}) - x_i \, (\text{\small m})
$$

---

## **2. Velocidad Promedio**
$$
v_{\text{prom}} \, \left(\frac{\text{\small m}}{\text{\small s}}\right) = \frac{\Delta x \, (\text{\small m})}{\Delta t \, (\text{\small s})}
$$

---

## **3. Velocidad Instantánea**
$$
v(t) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) = \frac{dx}{dt} \, \left(\frac{\text{\small m}}{\text{\small s}}\right)
$$

---

## **4. Aceleración Promedio**
$$
a_{\text{prom}} \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) = \frac{\Delta v \, \left(\frac{\text{\small m}}{\text{\small s}}\right)}{\Delta t \, (\text{\small s})}
$$

---

## **5. Aceleración Instantánea**
$$
a(t) \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) = \frac{dv}{dt} \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right)
$$

---

## **6. Movimiento Rectilíneo Uniforme (MRU)**
### **Posición en Función del Tiempo**
$$
x(t) \, (\text{\small m}) = x_0 \, (\text{\small m}) + v \, \left(\frac{\text{\small m}}{\text{\small s}}\right) t \, (\text{\small s})
$$

---

## **7. Movimiento Rectilíneo Uniformemente Variado (MRUV)**

### **Ecuación Horaria**
$$
x(t) \, (\text{\small m}) = x_0 \, (\text{\small m}) + v_0 \, \left(\frac{\text{\small m}}{\text{\small s}}\right) t \, (\text{\small s}) + \frac{1}{2} a \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) t^2 \, (\text{\small s}^2)
$$

### **Velocidad en Función del Tiempo**
$$
v(t) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) = v_0 \, \left(\frac{\text{\small m}}{\text{\small s}}\right) + a \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) t \, (\text{\small s})
$$

### **Velocidad en Función de la Posición**
$$
v^2 \, \left(\frac{\text{\small m}^2}{\text{\small s}^2}\right) = v_0^2 \, \left(\frac{\text{\small m}^2}{\text{\small s}^2}\right) + 2 a \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) (x \, (\text{\small m}) - x_0 \, (\text{\small m}))
$$

---

## **8. Caída Libre**

### **Posición en Función del Tiempo**
$$
y(t) \, (\text{\small m}) = y_0 \, (\text{\small m}) - \frac{1}{2} g \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) t^2 \, (\text{\small s}^2)
$$

### **Velocidad en Función del Tiempo**
$$
v(t) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) = v_0 \, \left(\frac{\text{\small m}}{\text{\small s}}\right) - g \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) t \, (\text{\small s})
$$

---

## **9. Tiro Parabólico**

### **Ecuaciones de Movimiento**
1. **Eje Horizontal**: 
   $$
   x(t) \, (\text{\small m}) = v_0 \cos(\theta) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) t \, (\text{\small s})
   $$
2. **Eje Vertical**:
   $$
   y(t) \, (\text{\small m}) = v_0 \sin(\theta) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) t \, (\text{\small s}) - \frac{1}{2} g \, \left(\frac{\text{\small m}}{\text{\small s}^2}\right) t^2 \, (\text{\small s}^2)
   $$

### **Velocidad Total**
$$
v(t) \, \left(\frac{\text{\small m}}{\text{\small s}}\right) = \sqrt{v_x^2 + v_y^2}
$$

---

## **10. Fórmulas Clave del Tiro Parabólico**

| **Variable**          | **Fórmula**                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Tiempo de vuelo**    | \( T = \frac{2 v_0 \sin(\theta)}{g} \, (\text{\small s}) \)                 |
| **Alcance horizontal**| \( \Delta x = \frac{v_0^2 \sin(2\theta)}{g} \, (\text{\small m}) \)          |
| **Altura máxima**      | \( H_m = \frac{v_0^2 \sin^2(\theta)}{2g} \, (\text{\small m}) \)            |

---
