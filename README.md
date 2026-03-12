# ⏱ LeanTakt - Estudio de Tiempos & Balanceo de Líneas

Aplicación web enfocada en **Ingeniería Industrial y Manufactura Esbelta (Lean Manufacturing)** para realizar estudios de tiempos, calcular **Takt Time**, analizar **capacidad**, detectar **cuellos de botella**, y visualizar el **balanceo de líneas** mediante gráficos **Yamazumi** y **Heijunka**.

La herramienta está pensada para usarse directamente en piso de producción o en análisis de ingeniería, sin dependencias de backend, funcionando 100% en el navegador.

---

## 🚀 Funcionalidades principales

### 📏 Estudio de tiempos
- Cronómetro integrado con captura de **hasta 10 observaciones por operación**
- Cálculo automático de:
  - Promedio observado
  - **Tiempo Normal** (método Westinghouse)
  - **Tiempo Estándar** (incluyendo suplementos)
- Soporte para **múltiples operaciones** en un mismo estudio
- Guardado automático en **LocalStorage**

---

### ⚙️ Factores y suplementos
- Método **Westinghouse**:
  - Habilidad
  - Esfuerzo
  - Condiciones
  - Consistencia
- Suplementos:
  - Constantes (género)
  - Variables (postura, esfuerzo físico, ambiente, fatiga, etc.)

---

### 🧮 Datos de línea y costos
- Captura de:
  - **Jornada diaria (minutos)**
  - **Sueldo semanal**
  - **Demanda diaria**
- Cálculo automático de:
  - **Takt Time** (min y segundos por unidad)
  - **Costo por minuto**
  - Ritmo objetivo (unidades por hora)

---

### 📊 Balanceo de línea
Para cada operación:
- Comparación **Tiempo Estándar vs Takt**
- Identificación automática de:
  - ✅ Operación balanceada
  - ⚠️ Operación al límite
  - ❌ **Cuello de botella**
- Cálculo de:
  - Capacidad por operador (unid/día)
  - **Operadores requeridos**
  - Costo unitario directo
  - Costo unitario considerando staffing

---

### 📈 Visualizaciones Lean

#### Yamazumi
- Gráfico de barras por operación
- Línea de referencia de **Takt Time**
- Resalta visualmente los cuellos de botella

#### Heijunka (nivelación de producción)
- Distribución de la demanda diaria por intervalos de tiempo
- Intervalos configurables (15 / 20 / 30 / 60 min)
- Reparto automático de unidades por intervalo
- Visualización clara tipo **Heijunka Box**
- Diseño sin desbordes, con distribución en filas

---

### 📤 Exportación profesional
- **CSV** (rápido)
- **Excel XLSX** con estilos (ExcelJS):
  - Parámetros de línea
  - Detalle de ciclos
  - Resumen por operación
  - Balanceo de línea completo

---

## 🖥️ Tecnologías usadas
- HTML5 / CSS3 (UI moderna tipo glassmorphism)
- JavaScript puro (sin frameworks)
- Canvas API (gráfico Yamazumi)
- ExcelJS (exportación avanzada)
- LocalStorage (persistencia)

---

## 🎯 Casos de uso
- Estudios de tiempos en piso
- Balanceo de líneas de producción
- Análisis de capacidad y costos
- Identificación de cuellos de botella
- Nivelación de producción (Heijunka)
- Ingeniería de métodos y mejora continua

---

## ✅ Ventajas
- No requiere servidor
- Funciona offline
- Diseño responsive (desktop / tablet / móvil)
- Orientada a uso real en manufactura
- Código claro y extensible

---

## 📌 Nota
Este proyecto está en constante evolución y puede ampliarse para:
- Balanceo por estaciones
- Heijunka por mix de productos
- Simulación de escenarios
- Integración con datos reales de producción

---

👷‍♂️ Desarrollado con enfoque práctico para ingeniería industrial y mejora continua.
