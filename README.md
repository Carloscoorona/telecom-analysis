# 📞 Análisis de Clientes y Patrones de Uso - ConectaTel

## 📋 Descripción

Proyecto de análisis exploratorio de datos (EDA) realizado sobre la base de clientes de ConectaTel con el objetivo de entender como los clientes usan realmente los servicios moviles (llamadas y mensajes)
---

## 🎯 Objetivos

- Identificar patrones de uso
- Analizar la calidad de los datos.
- Detectar valores faltantes, outliers y sentinels.
- Explorar patrones de uso en mensajes, llamadas y minutos consumidos.
- Segmentar usuarios por edad y nivel de uso.
- Identificar oportunidades de negocio basadas en el comportamiento de los clientes.

---

## 📂 Datasets Utilizados

- users_latam.csv
  - Información demográfica de los usuarios.
  - Edad, ciudad, fecha de registro y plan.

- usage.csv
  - Historial de uso.
  - Mensajes, llamadas y duración de llamadas.

- plans.csv
  - Información de los planes actuales.

---

## 🛠️ Proceso de Análisis

### 1. Limpieza de Datos

- Identificación de sentinels (-999 en edad).
- Tratamiento de valores faltantes.
- Validación de fechas fuera de rango.
- Verificación de registros sin actividad.

### 2. Análisis Exploratorio

- Estadísticos descriptivos.
- Histogramas.
- Boxplots.
- Identificación de outliers.

### 3. Segmentación

#### Segmentos por Edad

- Joven
- Adulto
- Adulto Mayor

#### Segmentos por Nivel de Uso

- Bajo uso
- Uso medio
- Alto uso

### 4. Hallazgos Principales

- La mayoría de los usuarios pertenece al segmento de uso medio.
- Los adultos representan la mayor proporción de clientes.
- Se identificaron usuarios de alto consumo que representan oportunidades de fidelización.
- Los valores atípicos encontrados corresponden a comportamientos reales y fueron conservados.

---

## 📈 Resultados

Los usuarios de alto consumo constituyen el segmento con mayor potencial comercial debido a su elevada actividad en llamadas y mensajería.

La empresa podría beneficiarse de estrategias diferenciadas para:

- Usuarios de alto uso.
- Usuarios de bajo uso.
- Adultos y adultos mayores.

---

## ▶️ Cómo Ejecutar

1. Clonar el repositorio.

git clone https://github.com//telecom-analysis-conectatel.git

2. Abrir el notebook en jupyter notebook.
3. Instala pandas, matplotlib.pyplot, seaborn y nunmpy 
4. Coloca los datasets en:
   plans = pd.read_csv('/datasets/plans.csv')
  users = pd.read_csv('/datasets/users_latam.csv') 
  usage = pd.read_csv('/datasets/usage.csv')
5. Estoy algo perdido con esta parte, espero que quien revise mi proyecto pueda ayudarme con Github, aun se me hace muy complicado.
