# Análisis Estadístico de Tarifas – Megaline

## Descripción del Proyecto

Este proyecto fue desarrollado como parte del Sprint 5 del bootcamp de análisis de datos de TripleTen. El objetivo es analizar el comportamiento de los clientes de la empresa de telecomunicaciones **Megaline**, que ofrece dos planes de prepago: **Surf** y **Ultimate**. A partir de los datos de 500 clientes, se busca determinar cuál de las dos tarifas genera más ingresos y cómo varía el comportamiento de los usuarios según su ubicación.

---

## Etapas del Proyecto

### 1. Carga y Exploración de Datos
- Lectura de cinco archivos CSV: `users`, `calls`, `messages`, `internet`, `plans`.
- Revisión de estructura, tipos de datos y primeras observaciones.

### 2. Preprocesamiento
- Conversión de tipos de datos.
- Identificación y tratamiento de valores ausentes y duplicados.
- Cálculo mensual por usuario de:
  - Minutos utilizados
  - SMS enviados
  - Datos consumidos (en GB)
  - Ingresos generados según el plan

### 3. Análisis Descriptivo
- Comportamiento mensual de usuarios por tarifa.
- Cálculo de media, varianza y desviación estándar.
- Visualización de distribuciones mediante histogramas.

### 4. Pruebas de Hipótesis
- ¿El ingreso promedio difiere entre los planes Surf y Ultimate?
- ¿El ingreso promedio difiere entre usuarios de Nueva York/Nueva Jersey y otras regiones?
- Formulación de hipótesis nula y alternativa.
- Pruebas estadísticas con valor alfa definido.

---

## Diccionario de Datos

| Tabla       | Descripción                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `users`     | Información de clientes (edad, ciudad, plan, fechas de alta y baja)         |
| `calls`     | Registros de llamadas realizadas (fecha, duración, usuario)                |
| `messages`  | Registros de SMS enviados (fecha, usuario)                                  |
| `internet`  | Sesiones web (fecha, MB usados, usuario)                                    |
| `plans`     | Detalles de los planes Surf y Ultimate (límites y tarifas por excedente)   |

---

## Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- SciPy (para pruebas estadísticas)  
- Jupyter Notebook

---

## Resultados

- Se identificaron diferencias claras en el comportamiento de usuarios según el plan.
- El plan **Ultimate** mostró ingresos más estables, mientras que **Surf** generó ingresos variables por excedentes.
- Las pruebas estadísticas permitieron validar si las diferencias observadas eran significativas.
- Se ofrecieron recomendaciones basadas en datos para optimizar el presupuesto de publicidad.

---

## 📫 Contacto

Paz Emmanuel Balderas Cerezo  
📧 pazemmanuel24032005@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/paz-emmanuel-balderas-cerezo-dataanalyst)
