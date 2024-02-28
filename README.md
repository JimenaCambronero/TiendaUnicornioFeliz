# Proyecto Tienda Unicornio Feliz 👩‍💻🦄📊⁣
<h2>📊Análisis Financiero & Tráfico Web - Ecommerce </h2>

<h3>📋Descripción del Proyecto</h3> 
En este proyecto estaremos trabajando con una base de datos de retail online que se dedica a la venta de productos a través de su web.

<h3>🎯El objetivo de este proyecto</h3> 
Entender el conjunto de datos y el negocio
Lograr crear queries complejas para responder a las neceidades de negocio

<h3>📝Contexto</h3> 
Te acaban de contratar para la empresa de ecommerce online llamada “tienda_unicornio_feliz”
que se dedica a vender productos online de unicornios. Actualmente cuenta con 4 productos
Como miembro del equipo de la startup, te va a tocar trabajar con el CEO, el director de
marketing y el Gerente de la web para analizar ciertas métricas que queremos medir.
Tu objetivo será analizar la situación actual de la empresa. Medir la conversión de la web y usar
datos para entender las ventas e impacto de los productos.

<h3>🆘 El problema </h3>
Necesitamos responder a distintas preguntas de negocio que tiene el equipo directivo.

<h3>🕵️ Habilidades Adquiridas </h3> 
Creemos que tienes las habilidades necesarias para llevar a cabo este proyecto ya que
concideramos que estas preparado para realizar las siguientes actividades:

✅  Aprender a leer modelos relacionales y tablas en una empresa

✅  Aprender a explorar datos para entenderlos mejora antes de trabajar con los datos

✅  Saber como desglosamos una pregunta de negocio para entenderla

✅  Como traducir preguntas de negocio a lenguaje de SQL

✅  Escribir queries complejas que responden a necesidades de negocio

<h4> 🛠️Herramientas a utilizar  </h4>  En este proyecto utilizaremos lenguaje de SQL y el gestor de base de datos MYSQL 🗃️ Base de datos .sql

# 💡Desarrollo | Ejecución
# PARTE I - TEÓRICO Análisis de modelo relación
Consejo para entender un modelo de entidad relación

Entender un modelo de entidad-relación (ER) de los datos de una empresa puede ser fundamental para analizar y gestionar eficazmente esos datos. Aquí hay una serie de pasos que puedes seguir para comprender un modelo de entidad-relación de datos empresariales:

Reúne la Documentación Existente: Lo primero que debes hacer es reunir cualquier documentación existente relacionada con el modelo de entidad-relación. Esto podría incluir diagramas, descripciones de tablas y relaciones, documentación de base de datos, y cualquier otro material relacionado.

Identifica las Entidades Principales: Comienza identificando las entidades principales en el modelo. Estas suelen ser los objetos clave con los que la empresa trabaja. Por ejemplo, en un modelo de entidad-relación de una tienda en línea, las entidades principales podrían incluir "Clientes", "Productos", "Pedidos" y "Empleados".

Identifica las Relaciones: Una vez que hayas identificado las entidades principales, busca las relaciones entre ellas. ¿Cómo se relacionan estas entidades? Por ejemplo, un cliente realiza pedidos, un producto puede estar en varios pedidos, etc. Identifica estas relaciones y anótalas.

Atributos de las Entidades: Para cada entidad, identifica los atributos asociados. Los atributos son características o propiedades de las entidades. Por ejemplo, para la entidad "Clientes", los atributos podrían incluir "Nombre", "Dirección", "Correo Electrónico", etc.

Cardinalidad de las Relaciones: Determina la cardinalidad de las relaciones. Esto significa cuántos de un tipo de entidad están relacionados con cuántos del otro tipo. Por ejemplo, un cliente puede realizar varios pedidos, pero un pedido generalmente está relacionado con un solo cliente. Esto se expresa como 1:N en términos de cardinalidad.

Restricciones de Integridad: Verifica si hay restricciones de integridad en el modelo, como claves primarias y foráneas. Estas restricciones garantizan que los datos sean coherentes y precisos.

Prueba Consultas SQL: Para asegurarte de que comprendes bien el modelo, crea algunas consultas SQL simples que recuperen datos de las tablas. Esto te ayudará a verificar que las relaciones y atributos sean correctos.

# PARTE II - TEÓRICO Análisis exploratorio de las tablas
Pasos en análisis exploratorio de datos

Revisión de la Estructura de las Tablas:

Utiliza consultas SQL para obtener información sobre la estructura de las tablas, incluyendo nombres de columnas, tipos de datos y restricciones.

Muestreo de Datos:

Si la tabla de la base de datos es grande, puedes utilizar consultas SQL para tomar muestras aleatorias de los datos. Esto te permitirá trabajar con un subconjunto más manejable.

Exploración de Valores Únicos:

Utiliza consultas SQL para contar los valores únicos en columnas específicas. Esto te ayudará a comprender la diversidad de los datos.

Cálculo de Estadísticas Básicas:

Utiliza consultas SQL para calcular estadísticas descriptivas básicas, como promedios, medianas, desviaciones estándar, mínimos y máximos para las columnas numéricas.

Detección de Valores Faltantes:

Utiliza consultas SQL para identificar valores faltantes en las columnas y determinar cuántos registros tienen valores nulos.

# PARTE III - EJECUCIÓN 
Análisis financiero 💸

¿Cuales son las ventas por año?

¿Cuales son las ventas medias de cada mes y año?

¿Cuál es el producto que mas vende en términos monetarios?

¿Cuál es el margen bruto que deja cada producto?

¿Podemos saber cúal es la fecha de lanzamiento de cada producto?

Calcula las ventas por año, asi como el margen numérico. Tambien queremos saber que % representa cada producto sobre las ventas totales.

¿Cuáles son los TOP 3 meses con mayor venta?

¿Cuál es el margen bruto por producto y que porcentaje ocupa del margen total?

¿Cuál es el margen de beneficio bruto promedio por línea de producto en el último trimestre de los datos de la empresa?

¿Cúal es el porcentaje de devolución de artículos?

Análisis de trafico web 🕸️
¿Cúal es la cantidad de sesiones por tipo de dispositivo?

Es lo mismo sesiones que usuarios?¿Cuál es la cantidad de usuarios únicos? ¿Y cúal es la cantidad de sesiones?

¿Cúales son los 5 meses que ha habido más trafico en la web?

¿Cuál es la principal fuente de tráfico?

¿Cúales son las fuentes de tráfico que han dado más ventas?

¿Podrías mostrar las ventas y cantidad de sesiones por fuentes de tráfico asi como el porcentaje del total de cada métrica?

¿Cúal es el porcentaje de conversión de tráfico a ventas?

¿Que porcentaje de usuarios repiten?

Podrias calcular la cantidad de pedidos diferencias por días entre que entra a la web y realiza el pedido?

¿Cúales son las ventas generadas por campaña?
