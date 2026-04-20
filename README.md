# **Autor**: Luciana V Cortizo

# **Curso**: Herramientas Básicas para el Análisis de Datos

# **Cohorte**: 2026

# Título y descripción general
Análisis de los precios vigentes de medicamentos para los afiliados de Pami. Características de los medicamentos más caros y más económicos.

PAMI es la mayor obra social de Argentina y de América Latina. Posee 4,8 millones de afiliados en Argentina, entre jubilados, pensionados, personas con discapacidad, familiares a cargo y veteranos de Malvinas. Debido a la cantidad de afiliados que posee PAMI (alrededor del 70% de los jubilados argentinos se encuentran afiliados a esta obra social), es de interés analizar la información que publica el estado argentino bimestralmente sobre los precios de los medicamentos de PAMI a sus jubilados.
# Objetivo del Proyecto
Analizar las características de los medicamentos más caros y mas económicos para los afiliados de PAMI. Para este fin se descarga el dataset vigente de la fuente oficial del gobierno argentino(1). Se analiza: ¿cuales son los principios activos, el % de cobertura y los laboratorios elaboradores de los 10 medicamentos de mayor y menor costo para el paciente? ¿Cual es el valor promedio del costo de medicamentos? 
## Objetivos:
1) Determinar cuales son los principios activos de los 10 medicamentos mas caros
2) Determinar que % de cobertura al paciente tienen los 10 medicamentos mas caros
3) Determinar cuales son los laboratorios elaboradores de los 10 medicamentos mas caros
4) Determinar cuales son los principios activos de los 10 medicamentos mas baratos
5) Determinar que % de cobertura al paciente tienen los 10 medicamentos mas baratos
6) Determinar cuales son los laboratorios elaboradores de los 10 medicamentos mas baratos
7) Determinar cual es el valor promedio de los medicamentos
# Dataset utilizado
-Fuente de Datos:
(1): https://www.datos.gob.ar/dataset/pami-listado-precios-medicamentos-para-afiliados

-Formato: xlsx con 6 variables principales (DROGA, MARCA, PRESENTACION, LABORATORIO, COBERTURA, COPAGO)

-Cantidad de registros: 8037 filas x 6 columnas.

# Herramientas utilizadas
-**Python** (pandas, matplotlib, seaborn, numpy)

-**Google Colab**

-**Power BI**

-**GitHub**

# Dashboard
<img width="1443" height="821" alt="image" src="https://github.com/user-attachments/assets/81c66670-2550-4773-810a-3be794c5d20b" />

# Estructura del proyecto
-data/ datasets limpios

-notebooks/ análisis en Phyton

-figs/ gráficos exportados

-dashboard/ Tablero Power BI

# Licencia y autoría
-Proyecto académico realizado por Luciana V. Cortizo

-Creative Commons Attribution 4.0


## **Conclusión del Análisis**

El análisis de los precios de medicamentos para afiliados de PAMI ha permitido obtener las siguientes conclusiones en relación con los objetivos planteados:

### 1. y 4. Principios activos de los 10 medicamentos más caros y más baratos

- **Medicamentos más caros:** Los principios activos de los 10 medicamentos con mayor COPAGO incluyen una variedad de tratamientos para enfermedades crónicas y complejas, lo que sugiere que los costos elevados pueden estar asociados a la especialización y novedad de los tratamientos.
- **Medicamentos más baratos:** Los principios activos de los 10 medicamentos con menor COPAGO, incluyendo aquellos con COPAGO cero, suelen corresponder a medicamentos genéricos, de uso común o aquellos con cobertura del 100% (en su mayoría tratamiento convencional de la diabetes)por políticas específicas de PAMI.

### 2. y 5. Porcentaje de cobertura al paciente de los 10 medicamentos más caros y más baratos

- **Medicamentos más caros:** A pesar de su alto costo, el porcentaje de cobertura para los medicamentos más caros varía, oscilando entre el 40% y el 80% (entre estos rangos estan los medicamentos para tratamientos convencionales de enfermedades crónicas, como la hipertensión). Esto indica que, incluso para tratamientos costosos, PAMI ofrece una cobertura significativa, aunque el COPAGO resultante para el paciente sigue siendo elevado.
- **Medicamentos más baratos:** Muchos de los medicamentos con COPAGO más bajo (incluyendo 0) tienen coberturas del 100%, lo que los hace completamente accesibles para el afiliado. Esto es consistente con la provisión de medicamentos esenciales o tratamientos prioritarios.

### 3. y 6. Laboratorios elaboradores de los 10 medicamentos más caros y más baratos

- **Laboratorios de los medicamentos más caros:** Los laboratorios asociados a los medicamentos más caros son principalmente grandes farmacéuticas, muchas de las cuales son líderes en investigación y desarrollo, lo que puede influir en el precio de sus productos.
- **Laboratorios de los medicamentos más baratos:** Los laboratorios que producen los medicamentos más baratos también son variados, incluyendo tanto grandes como pequeñas empresas, y en muchos casos se corresponden con productores de genéricos o medicamentos con mayor competencia en el mercado.

### 7. Valor promedio del costo de los medicamentos

- **Costo promedio general:** El valor promedio del COPAGO de los medicamentos analizados es de $14435.03. Este promedio es influenciado por la gran dispersión en los precios, donde pocos medicamentos de muy alto costo pueden elevar significativamente la media, mientras que una gran cantidad de medicamentos de bajo costo tiran el promedio hacia abajo.

### Observaciones Adicionales:

- La diferencia porcentual del COPAGO entre el laboratorio más caro y el más barato es notablemente alta, indicando una gran variabilidad en los costos dependiendo del laboratorio y el tipo de medicamento.
- Existe una relación inversa esperada entre la cobertura y el COPAGO, donde a mayor cobertura de PAMI, menor es el COPAGO para el afiliado, aunque la distribución muestra que incluso con altas coberturas, algunos medicamentos pueden tener un COPAGO considerable debido a su precio base.

En resumen, PAMI ofrece un amplio rango de coberturas, desde el 100% para muchos medicamentos y accesorios destinados al tratamiento convencional de la diabetes hasta coberturas parciales que van del 40 al 80% para tratamientos más especializados y costosos. Los medicamentos de alto costo están asociados a principios activos específicos y de reciente desarrollo. Es el caso de la semaglutida, también utilizado para la diabetes y obesidad. 




