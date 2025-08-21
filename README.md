# Análisis de Pérdida de Clientes de TelecomX - Parte 2

Esta es la continuación del análisis predictivo de churn en TelecomX, enfocada en la preparación de datos para modelado.

## 📂 Datos Utilizados

Los datos provienen del archivo JSON procesado y convertido a CSV:

- **`TelecomX_Data_Clean.csv`** - Dataset limpio y preparado para análisis

El archivo contiene 20 columnas depuradas:

- **`Churn`**: Indicador si el cliente dejó o no el servicio
- **`gender`**: Género del cliente (masculino/femenino)
- **`SeniorCitizen`**: Indicador si el cliente es adulto mayor (65+ años)
- **`Partner`**: Si el cliente tiene pareja
- **`Dependents`**: Si el cliente tiene dependientes
- **`tenure`**: Meses de permanencia del cliente
- **`PhoneService`**: Suscripción al servicio telefónico
- **`MultipleLines`**: Suscripción a múltiples líneas telefónicas
- **`InternetService`**: Tipo de servicio de internet contratado
- **`OnlineSecurity`**: Suscripción adicional de seguridad en línea
- **`OnlineBackup`**: Suscripción adicional de respaldo en línea
- **`DeviceProtection`**: Suscripción adicional de protección de dispositivo
- **`TechSupport`**: Suscripción adicional de soporte técnico prioritario
- **`StreamingTV`**: Suscripción de televisión por streaming
- **`StreamingMovies`**: Suscripción de películas por streaming
- **`Contract`**: Tipo de contrato (mensual, anual, bienal)
- **`PaperlessBilling`**: Preferencia por facturación digital
- **`PaymentMethod`**: Método de pago preferido
- **`Charges.Monthly`**: Cargos mensuales totales
- **`Charges.Total`**: Total histórico gastado por el cliente

## 🛠 Tecnologías Utilizadas

- **Python 3.x** como lenguaje de programación principal
- **Pandas** para manipulación y limpieza de datos
- **JSON** para manejo del formato original de datos
- **Matplotlib/Seaborn** para visualizaciones estáticas
- **Jupyter Notebook/Google Colab** para ejecución y documentación

## 📋 Proceso de Preparación de Datos

### 1. **Carga y Exploración Inicial**
   - Carga del dataset JSON original
   - Análisis de estructura y dimensiones iniciales
   - Identificación de tipos de datos y valores únicos

### 2. **Limpieza y Depuración**
   - Eliminación de columnas no predictivas (`customerID`)
   - Simplificación de nombres de columnas
   - Verificación de valores nulos o inconsistentes

### 3. **Transformación de Datos**
   - Normalización de nombres de columnas
   - Preparación para encoding de variables categóricas
   - Estructuración para análisis predictivo

### 4. **Exportación del Dataset Limpio**
   - Guardado en formato CSV para fácil acceso
   - Documentación del proceso de limpieza
