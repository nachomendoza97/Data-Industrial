# 🏭 Industrial Data Science Portfolio | Ignacio Mendoza
*Estudiante Avanzado de Ingeniería Industrial - FIQ-UNL  |  Santa Fe, Argentina*

¡Bienvenido! En este repositorio consolido soluciones analíticas aplicadas a la optimización de procesos industriales, logística y mantenimiento preventivo utilizando Python y herramientas de Datos.

## 🚀 Proyectos Destacados

### 1. Cálculo de OEE (Eficiencia Global de Equipos) 
* **Problema:** DFalta de visibilidad sobre el rendimiento real de las líneas de producción y desconocimiento de las causas raíz de las paradas.
* **Solución:** Desarrollo de un script en Python que procesa logs de producción para calcular automáticamente la Disponibilidad, el Rendimiento y la Calidad de los activos.
* **Impacto:** Generación de tableros de control que permiten identificar rápidamente si el cuello de botella es mecánico (disponibilidad) o de proceso (velocidad)


### 2. Análisis de Fallas y Frecuencia
* **Problema:** Mantenimiento reactivo basado en la intuición, lo que genera una distribución ineficiente del presupuesto de reparaciones.
* **Solución:** Análisis estadístico de logs de fallas para categorizar los tipos de averías más frecuentes y su tiempo medio entre fallas (MTBF).
* **Impacto:** Priorización de tareas de mantenimiento preventivo en los componentes que generan el 80% de las horas de parada.


### 3. Optimización de Inventarios (ABC por Valor)
* **Problema:** Capital inmovilizado excesivo y falta de criterios claros para la priorización de compras en el almacén.
* **Solución:** Implementación de un análisis de Pareto (80/20) basado en el valor de consumo anual de los SKUs.
* **Impacto:** Identificación del 20% de artículos críticos que representan la mayor inversión, optimizando el flujo de caja.
* * ![Proyecto3.png]


### 4. Clasificación ABC (por Cantidad de SKUs)
* **Problema:** Dificultad para organizar conteos cíclicos y auditorías de inventario debido a la gran variedad de ítems en stock.
* **Solución:** Algoritmo de clasificación basado en el porcentaje físico de ítems (20% A, 35% B, 45% C) utilizando desempates por tiempo de reposición.
* **Impacto:** Mejora en la eficiencia operativa del depósito al asignar los recursos de control a la minoría de productos de alto movimiento.
* ![Proyecto4.png]

### 5. Mantenimiento Predictivo (RUL - Remaining Useful Life)
* **Problema:** Altos costos operativos por paradas imprevistas en motores y activos críticos (como flotas de camiones o maquinaria agroindustrial).
* **Solución:** Modelo de regresión que utiliza datos de sensores (vibración y temperatura) para predecir cuántos días de vida útil le quedan a un equipo antes de fallar.
* **Impacto:** Transición de un esquema de mantenimiento preventivo (fijo) a uno predictivo (basado en condición), maximizando la vida útil de los componentes y evitando reparaciones de emergencia.
* ![Proyecto5.png]


### 6. OPT & Scheduling (Secuenciamiento con Matriz SDST)
* **Problema:** Retrasos significativos en la producción (Makespan elevado) debido a secuencias de lotes incompatibles que requieren limpiezas profundas o cambios de matriz complejos.
* **Solución:** Simulador de programación de la producción que utiliza matrices de cambio asimétricas (SDST) y reglas de desempate (Short/Long Tail) para encontrar la secuencia óptima.
* **Impacto:** Reducción del tiempo total de fabricación y eliminación de penalizaciones por incompatibilidad técnica entre procesos sucesivos
* ![Proyecto6a.png]

"Este modelo implementa una Matriz de Setups dependientes de la secuencia. Se demuestra cómo una política de desempate (Long Tail vs Short Tail) puede ahorrar hasta un 20% de tiempo de planta al evitar secuencias de producción incompatibles que requieren limpiezas profundas."



---
## 🛠️ Stack Tecnológico
* **Lenguajes:** Python (Pandas, NumPy, Scikit-learn, Matplotlib).
* **Herramientas:** SQL, Google Colab, GitHub, Excel Avanzado.
* **Dominios:** Supply Chain, Automatización OT/IT, Control de Calidad.

---
## 📫 Contacto
* **LinkedIn:** https://www.linkedin.com/in/ignacio-antonio-mendoza-86727a195/
* **Email:** nachomendoza.a97@gmail.com
* **Telefono:** +549-3426139936
* Santa Fe, Santa Fe - Argentina
