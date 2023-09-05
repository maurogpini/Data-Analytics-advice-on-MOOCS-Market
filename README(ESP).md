<h1 align=center> MAURO GONZALO PINI
 <h1 align=center> HENRY LABS - DATA SCIENCE COHORTE 06
 <h1 align=center> PROYECTO INDIVIDUAL º3
  
 



## **Contexto**

El escenario de esta actividad simula un pedido de un cliente que quiere incursionar en la industria de las MOOCS. Pueden leer la consigna en detalle en el archivo CONSIGNA.md, pero en síntesis lo requerido fue realizar un análisis de varias bases de datos, analizar la industria, presentar un análisis de datos y sugerir al cliente un KPI para su utilización.

## **Documentación y descripción del proceso**

Inicialmente realicé un profundo trabajo de análisis exploratorio y transformación de los datos, el cual se puede ver explicado y detallado paso a paso en el archivo EDA.ipynb. Como resultado obtuve las tablas individuales para cada cliente y una tabla general que simula el comportamiento del mercado. 

Tal y como el cliente lo requirió, se entrega en el repositorio la siguiente documentación:

* EDA --> EDA.ipynb
* Dashboard --> Dashboard-maurogpini
* Wordclouds de palabras más repetidas entre los nombres (también está en el archivo EDA) --> archivos.png
* Requerimientos para ejecutar correctamente el .ipynb --> requirements
* Tablas limpias y en condiciones para el análisis --> archivos .csv
* Reporte escrito --> se desarrolla a continuación en el README tal y como fue solicitado.




## **Reporte - Resumen ejecutivo**

Tal y como se puede apreciar en el dashboard, se realizó un análisis de las categorías más relevantes de cada una de las 3 empresas de forma particular, obteniendo indicadores y features de su performance.

Posteriormente se dio lugar a responder las consultas específicas respecto de los montos de las ventas que fueron requeridas, llegando a las siguientes conclusiones puntuales:

#### Precio
* Hay ciertos niveles de precios que tienen aparejado un mayor nivel de cantidad de ventas de los cursos:
200/500/490. Entre esos precios se acapara más del 40% de las ventas del mercado.
* Respecto del nivel de venta medido en USD, son otros los precios asociados a mayores importes recaudados:
990/1990/1490.

Parece ser un rasgo eficaz determinar los precios sobre la cota superior de la centena del guarismo que determina el precio.

#### Idioma

La industria está totalmente dominada por los cursos en idioma inglés, tanto si medimos por cantidad de cursos así como también por facturación bruta. Aproximadamente el 95% del contenido de la muestra está desarrollado en idioma inglés. Pareciera haber un segundo nicho en el mercado de habla hispana, pero sigue muy lejano.

Este efecto se explica por el casi obvio hecho de que la mayoría de la gente del planeta domina el inglés, por lo tanto, cursos en ese idioma tienen mayor alcance y pueden ser consumidos por una mayor variedad de clientes.

Parece ser un rasgo de suma importancia que el contenido de los cursos sea en inglés. Sin embargo, al investigar la profundidad del mercado por fuera de la muestra, creemos que puede haber muchísimo potencial para una plataforma de contenidos hispana.

#### Rating y Nivel

Parece haber una enorme correlación de las ventas, tanto en cantidad como en monto, a mayores niveles de rating dado por los usuarios.
Respecto del nivel de complejidad de los cursos, más del 80% del mercado está destinado a cursos de nivel introductorio y de nivel apto para todos los niveles.
Es de notar que el 15% del contenido está destinado a cursos de nivel intermedio, lo cual también se relación a individuos que tienen más experiencia y están dispuestos a capacitarse más, pagando inclusive mayores precios por esas capacitaciones. Es clave recordar aquí el hecho de que los cursos más caros tienen una participación relativa en el total de facturación mayor a los cursos más baratos.

#### Duración

Este extra feature resultó de interés al analizar la data. Hay una clara evidencia a que los cursos mayores a la media parecen ser los más solicitados. Asimismo, Los cursos extremadamente largos, son los que mayor participación porcentual de los beneficios tienen.
