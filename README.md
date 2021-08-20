<html>

<head> Las grandes consecuencias de los pequeños patógenos: 
 <b>Coinfección por pátogenos respiratorios y su impacto en el pronóstico de mortalidad de pacientes con COVID-19. </b></head>
    
 <body>
     
<p align= justify>
 Para abordar el tema principal, es necesario tener conceptos que seran la clave para una comprensión idónea. 

Iniciaremos con la definición de la microbiología, la cual es el estudio de los microorganismos y sus actividades, además de su forma, estructura, fisiología, reproducción, metabolismo etc. Su objetivo principal es comprender las reacciones que pueden ser buenas o malas en un húesped, haciendo que  se busque una forma de aumentar los beneficios y disminuir los daños que este provocan.

                                         ¿qué es un patógeno?                


Bueno, estos pequeños amiguitos nuestros son unos súper agentes infecciosos que nos pueden provocar  diferentes enfermedades en nuestro cuerpo.
Así como existen diferentes tipos de helado, también hay diferentes tipos de patógenos como las siguientes:</p>

* Bacterias: son procariotas, lo que quiere decir que tienen una membrana celular y  tienen una forma esférica o cilíndrica.
* Parásitos: Pueden ser uni o multicelulares, pequeños microorganismos necesitan de un huésped para sobrevivir, además que su modo de reproducirse es de manera sexual y asexual.
* Virus: son organismos infecciosos  los cuales no son considerados células y que al igua que los parásitos, necesitan d un húesped para sobrevivir. Esta compuesto por ADN y ARN.
* Hongos: Son eucariotas, causan infecciones a nivel superficial o profundo. También como los parásitos, pueden ser  uni o multicelulares ya que son seres heterótrofos; su forma de reproducirse es por medio de esforas.


Un panel de patógenos respiratorios (también llamado perfil PR) busca si hay patógenos en las vías respiratorias, que recordemos que el sistema respiratorio son  las partes del cuerpo que participan en la respiración, incluyendo pulmones, nariz y garganta.

Teniendo esto en cuenta, vamos a empezar con la problemática que hemos abordado.
Actualmente,para el mundo experimenta un desafío sanitario de gran envergadura, que exige hasta el extremo las estructuras sanitarias, productivas y sociales en todo el mundo.[1]

La coinfección por dos o más patógenos respiratorios comunes podría dificultar un diagnóstico de recuperación de la infección producida por el virus SARS-CoV-2.
Es por ello que nos vamos a enfocar en dar posibles soluciones y contribuir a uno de los 17 Objetivos de Desarrollo Sostenible (ODS) pertenecientes a la Organización de las Naciones Unidas(ONU). Pero tú que estás leyendo esto te preguntarás, ¿Cómo relacionan el tercer objetivo: SALUD Y BIENESTAR con la coinfección por pátogenos respiratorios y su impacto en el pronóstico de mortalidad en pacientes con COVID-19? [2][3]
Sencillo. Este tercer objetivo tiene como fin garantizar una vida sana y promover el bienestar para todos en todas las edades y es que actualmente, estamos viviendo una crisis mundial trayendo consigo el sufrimiento en el cambio radical en nuestras vidas.
Para la organización mundial de la salud (OMS) y la Organización de las naciones Unidas, la COVID-19 es una emergencia sanitaria causada por un pequeño patógeno, entonces teniendo esto en cuenta, este proyecto busca tener enfoque en disminuir la tasa de mortalidad por COVID-19.[4]


Es curioso, porque es cierto el nombre de nuestro club: "Las grandes consecuencias de los pequeños patógenos". 
¿Quién pensaría que un pequeño microorganismo fue capaz de hacer una pandemia que llevaría a confinarnos hasta la actualidad?

Es ahí donde esos pequeños patógenos son de gran importancia y como jóvenes debemos tenemos esa curiosidad por ayudar a la ciencia a resolver uno de los 17 ODS.


### Métodología

Cada vez que empezamos un proyecto, siempre viene con nosotros aquellas preguntas sobre: ¿Que problématica me es interesante?,¿Cómo afecta esa problemática a nuestra sociedad?,¿Que han hecho ante tal problematica?,¿De dónde se obtendrá información para completar el proyecto?, ¿Quiénes serán los beneficiarios del proyecto?, por nombrar algunas preguntas.

Para nosotros, eso fue la base primordial para la elección de un proyecto.
Nos hemos basado en seguir los siguientes pasos de manera cronológica:
1. Seleccionar un tema.
2. Identificar un problema del tema seleccionado.
3. Definir e investiga del problema
4. Investigar antecedentes.
5. Crear una hipotésis.
6. Probar hipotésis mediante algoritmos de dimensión fractal de imagenes de CT de pulmones.
7. Analizar resultados obtenidos.
8. Realizar una conclusión.
9. Hacer un vídeo.




### 4.Antecedentes.
La mortalidad de los pacientes infectados con COVID-19 suele estar alrededor del 5% y, en pacientes hospitalizados, la mortalidad puede llegar al 30%. La variabilidad de este y otros indicadores puede deberse a la presencia de otras condiciones como las coinfecciones respiratorias. Se han reportado la presencia de coinfecciones en alrededor del 10 a 12,5% de pacientes hospitalizados por COVID19. [5]

Objetivo principal: Evaluar la frecuenciade recuperación por  coinfección con patógenos respiratorios bacterianos y virales detectados en  mediante algoritmos de estimación de la dimensión fractal de las imagenes de tomografía computarizada (CT) en pulmones de personas con COVID-19.


### 5.Hipotésis.
Los pacientes que muestran una dimensión fractal más alto del promedio de un pulmón sano, pertenecen a un grupo severo de COVID-19,tendiendo a causar coinfección con más patógenos.


### 6.Comprobación de la hipotésis.
Para comprobar nuestra hipotésis, hemos trabajado con una base de datos extraída de "Towards data science" llamada: COVID-CT-Dataset: A CT Scan Dataset about COVID-19. En la cual, fomenta la investigación de la IA en el uso de las CT para combatir la COVID-19.[6]
La base de datos contiene 349 tomografías  computarizadas  de pulmones positivas para COVID-19 y 396 muestras de pulmones sanos, ambas tienen su correspondiente archivo excel.[7]
Sin embargo, el excel de nuestro mayor interés es el de los pacientes positivos a SARS-COV-2, ya que en él se encuentran datos esenciales para nuestra investigación tales como:
1.Número de dentificación del paciente.
2. Edad.
3. Sexo
4. Lugar
5. Tiempo desde que se presentaron los síntomas.
6. Gravedad del paciente.


Después de tener a nuestra disposición la base de datos, se procedió a calcular la dimensión fractal de nuestros pulmones sanos y pulmones dañados con una programación en Matlab la cuál fue desarrollado por el Doctor Omar Alejandro Olvera Guerrero quien tiene un posgrado en Ciencias y Tecnologías de la Información. Él impartió la materia de procesamiento de señales biomédicas  en la Universidad Politécnica de Chiapas y fue allí donde explicó la importancia del cálculo de las dimensaiones fractales aportados a las ciencias médicas.



### Resultados
Se cálculo el promedio de los pulmones sanos arrojando 1.84615929 además de obtener un valor mínimo de 1.5742 y teniendo un 2.081 como valor máximo de DF de pulmones dañados.

Inició la comparación del promedio de los pulmones sanos con cada resultado obtenido de cada estudio de CT de pacientes con COVID-19. En donde se demostró que 189 de las 349 muestras de CT, estuvieron por encima del promedio haciendo que este sea un 54.15% del total de las muestras.
Dentro de la descripción de gravedad del archivo excel de personas positivas, se encontró a aquellos pacientes quienes lamentablemente habían muerto, en donde su dimensión fractal era mayor al promedio. Sin embargo, también existieron pacientes quienes estaban por abajo del promedio y que tenían en su descripción de gravedad que pertenecían a un grupo de recuperación.

Este es el momento en que nos compartas los resultados obtenidos en tu proyecto. Asegurate de incluir material visual (gráficas, fotos, diagramas, tablas). 

Puedes inster imagenes utilizando Markdown `![](Logo_CdeCMx.png)`.

![](Logo_CdeCMx.png)

O utilizando codigo html `<img src="Logo_CdeCMx.png" width=200>`, la ventaja de utilizar html es que le puedes modificar el tamaño utilizando **width**.
<img src="Logo_CdeCMx.png" width=200>


### Conclusiones

A nuestra consideración como equipo y como antes se explicó, podría existir una posibilidad de hacer notar una mejoría hacia la recuperación del paciente y poder observar también un posible grado de mortalidad, esto de acuerdo a la comparación del promedio de las pruebas de pulmón con covid. Con esto, se podría comprobar la hipótesis el cual, si la DF de la imagen es mayor al del promedio, podría estar en una situación severa, ya que los alveolos estarían  llenos de flujos provocando que sean propensos a nuevos patógenos respiratorios como: neumonía,  y se obtendría una frecuencia respiratoria baja, en caso contrario, existe una recuperación y tendríamos a nuestros alveolos débiles provocando una frecuencia respiratoria mucho más inestable.
Por último, debemos de tomar en cuenta de que para hacer una amplia investigación deberíamos comprobar las imágenes con los diferentes equipos pertenecientes al gabinete de imagenología y de laboratorio, ya que no debemos descartar ciertos posibles diagnósticos porque cada uno muestra diferentes resultados y hacen un mejor diagnóstico.

Hay que agregar que el cálculo de las dimensiones fractales en las ciencias médicas aún no es un campo completamente amplio, por lo que se sugiere seguir investigando y probando diferentes métodos para poder obtener mejores resultados.

### Referencias bibliográficas.
[1] Cruz, M. P., Santos, E., Cervantes, M. V., & Juárez, M. L. (2021). COVID-19, una emergencia de salud pública mundial. Revista Clínica Española, 221(1), 55-61.
[2] Quiñones-Laveriano, D. M., Soto, A., & Quilca-Barrera, L. (2021). Frecuencia de coinfección por patógenos respiratorios y su impacto en el pronóstico de pacientes con COVID-       19. Revista de la Facultad de Medicina Humana, 21(3).
[3] Xing, Q. (2020, 1 enero). Precautions are Needed for COVID-19 Patients with Coinfection of Common Respiratory Pathogens. MedRxiv.                                                   https://www.medrxiv.org/content/10.1101/2020.02.29.20027698v2.full
[4] Moran, M., Moran, M., Moran, M., & M. (s. f.). Salud. Desarrollo Sostenible. Recuperado 19 de agosto de 2021, de https://www.un.org/sustainabledevelopment/es/health/
[5] Tarazona, S. T., & Valdivia, A. V. (2020, 1 mayo). Coinfección por patógenos respiratorios virales y bacterianos detectados por métodos moleculares en pacientes hospitalizados por COVID-19 y su impacto en la mortalidad y desenlaces desfavorables. Universidad Ricardo Palma. https://repositorio.urp.edu.pe/handle/URP/3035
[6] Xie, P. (2020b, abril 5). COVID-CT-Dataset: A CT Scan Dataset about COVID-19 - Towards Data Science. Towards Data Science.
    https://towardsdatascience.com/covid-ct-dataset-a-   ct-scan-dataset-about-covid-19-fb391de55ae6
[7] U. (s. f.-a). GitHub - UCSD-AI4H/COVID-CT: COVID-CT-Dataset: A CT Scan Dataset about COVID-19. GitHub. Recuperado 19 de agosto de 2021, de
    https://github.com/UCSD-AI4H/COVID-CT


### Video
 1. Para insertar un video de YouTube, en la página de YouTube del video selecciona compartir y selecciona el código de html.
 <iframe width="560" height="315" src="https://www.youtube.com/embed/PLj1-CMNERM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 2. Insertar el link de tu video en YouTube, [nuestro video](https://youtu.be/rmXvlBPq24Q).
 4. Puedes subir el archivo de tu video directamente a Github [instrucciones aquí](https://stackoverflow.com/questions/4279611/how-to-embed-a-video-into-github-readme-md)
 
### Equipo

* Estudiante 1: Nancy Solís Grajales.
* Estudiante 2: Lilián Michelle Lopez Carrasco
    </body>
</htlm>
