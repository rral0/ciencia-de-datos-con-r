



# ¿Qué hace un "Científico de Datos" y por qué es una profesión tan Sexy?

En 2012, __Davenport y Patil__ escribían un [influyente artículo](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) en la Harvard Business Review en la que exponían que el científico de datos era la profesión más sexy del Siglo XXI. Un profesional que combinando conocimientos de matemáticas, estadística y programación, se encarga de analizar los grandes volúmenes de datos. A diferencia de la estadística tradicional que utilizaba muestras, el científico de datos aplica sus conocimientos estadísticos para resolver problemas de negocio aplicando las nuevas tecnologías, que permiten realizar cálculos que hasta ahora no se podían realizar.

Y va ganando en popularidad en los últimos años debido sobre todo al desarrollo de la parte más tecnológica. Las tecnologías de Big Data empiezan a posibilitar que las empresas las adopten y empiecen a poner en valor el análisis de datos en su día a día. Pero, ahí, es cuando se dan cuenta que necesitan algo más que tecnología. La estadística para la construcción de modelos analíticos, las matemáticas para la formulación de los problemas y su expresión codificada para las máquinas, y, el conocimiento de dominio (saber del área funcional de la empresa que lo quiere adoptar, el sector de actividad económica, etc. etc.), se tornan igualmente fundamentales.


Pero, si esto es tan sexy ¿qué hace el científico de datos? Y sobre todo, ¿qué tiene que ver esto con el Big Data y el Business Intelligence? Para responder a ello, a continuación mostramos la representación en formato de diagrama de Venn que hizo [Drew Conway en](http://drewconway.com/) 2010:

![Diagrama de Venn "Ciencia de Datos"](https://i.imgur.com/CUDp1ey.png)

Como podemos apreciar, se trata de una agregación de tres disciplinas que se deben entender bien en este nuevo paradigma que ha traído el Big Data:


- __“Hacking skills” o “competencias digitales con pensamiento computacional“:__  estamos al tanto que al traducirlo al Español, pierdo mucho del significado de lo que expresa las “Hacking Skills”. Pero consideramos que se entiende bien también lo que quieren decir las “competencias digitales”. Estamos en una época en la que constante “algoritmización” de lo que nos rodea, el pensamiento computacional que ya hay países que han introducido desde preescolar, haga que las competencias digitales no pasen solo por “saber de Ofimática” o de “sistemas de información”. Esto va más de tener esa mirada hacia lo que los ordenadores hacen, cómo procesan datos y cómo los utilizan para obtener conclusiones. Nosotros a esto lo llamamos “Pensamiento computacional”, como una (mala) traducción de “Computation thinking”, que junto con las competencias digitales (entender lo que hacen las herramientas digitales y ponerlo en práctica), nos parecen fundamentales.
- __Estadística y matemáticas:__ en primer lugar, la estadística, que es una herramienta crítica para la resolución de problemas. Nos dota de unos instrumentos de trabajo de enorme valor para los que trabajamos con problemas de la empresa. Y las matemáticas,la ciencia formal por antonomasía que siguiendo razonamientos lógicos, nos permite estudiar propiedades y relaciones entre las variables que formarán parte de nuestro problema. Si bien las matemáticas se la ha venido a conocer como la ciencia exacta, en la estadística, nos gusta más jugar con intervalos de confianza  y la incertidumbre. Pero, por sus propias particularidades, se nutren mutuamente, y hace que para construir modelos analíticos que permitan resolver los problemas que las empresas y organizaciones nos planteen, necesitemos de ambas.
- __Conocimiento del dominio:__ para poder diseñar y desarrollar la aplicación del análisis masivo de datos a diferentes casos de uso y aplicación, es necesario conocer el contexto. Los problemas se deben plantear acorde a estas características. Podemos sostener, que la Ciencia de los Datos es más una cuestión de plantear bien los problemas que otra cosa, por lo que saber hacer las preguntas correctas con las personas que bien conocen el dominio de aplicación es fundamental.


Estas tres cuestiones (informática y computación, métodos estadísticos y áreas de aplicación/dominio), también fueron citadas por William S. Cleveland en 2001 en su artículo [“Data Science: An Action Plan for Expanding the Technical Areas of the Field of Statistics“](http://onlinelibrary.wiley.com/doi/10.1111/j.1751-5823.2001.tb00477.x/abstract). Por lo tanto, no es una concepción nueva.

# ¿Que Aprenderás con este Libro?

El objetivo de este libro es proporcionarte unos fundamentos solidos en la gran mayoría de herramientas. Nuestro modelo de herramientas necesarias en un proyecto típido de Ciencia de Datos es el que se muestra en la siguiente figura:

![Fases Proyecto Ciencia de Datos](https://i.imgur.com/J7p0Keq.jpg)

En primer lugar, será _importar_ nuestros datos a R. Con esto queremos decir, que nos encontraremos datos almacenados en archivos, bases de datos, o en una API web, y el objetivo de esta tarea será cargar los datos en un dataframe.

Una vez hemos importado nuestros datos, la siguiente tarea será _"tidy"_ nuestros datos. El objetivo de esta tarea es almacenar nuestros datos en un formato consistente en el que coincida la semántica del conjunto de datos con el medo en que están almacenados. En resumen, nuestros datos estarán en formato tidy cuando, cada variable se encuentre en una columna y cada observación en su propia fila.

A continuación, una tarea común es _transformar_ nuestros datos. Transformar nuestros datos incluye filtrar las observaciones de nuestro interés (como por ejemplo, todo la gente en una ciudad, o todos los datos del último año), creación de nuevas variables resultado del cálculo de funciones de variables existentes (como por ejemplo, calcular la velocidad con la velocidad y tiempo) y, calcular un conjunto de indicadores estadísticos en un resumen (como medias o desviaciones típicas).

Después, visualizaremos y modelaremos nuestros datos. En este libro unicamente trataremos la _visualización_.

La visualización es fundamental el la actividad humana. Un visualización bien hecha nos muestra cosas que no esperabamos, o nos conduce a formularnos nuevas cuestiones en nuestros datos. Además, puede indicarnos que no estamos formulando las cuestiones correctas, o que necesitamos recoger  nuevos datos.

El último paso en la ciencia de datos es la _comunicación_, una parte absolutamente crítica en un proyecto de análisis de datos. Indiscutiblemente, no importa lo bien que hayamos modelado o visualizado nuestros datos, si posteriormente no somos capaces de comunicar nuestros resultados con los demás.



# Instalación de las Herramientas

Para seguir este curso haremos uso de tres herramientas: R, RStudio y la colección de paquetes _tidyverse_.

## Instalación de R

Para descargar R, lo haremos desde CRAN, un conjunto de servidores espejo distribuidos a lo largo del mundo y usado para distribuir R y paquetes R. La forma mas fácil de instalar R es desde https://cloud.r-project.org/.

## Instalación de RStudio

RStudio es un entorno integrado de desarrollo, o IDE, para facilitarnos la tarea de programación. Podemos descargo e instalarlo desde http://www.rstudio.com/download.

## Instalacion del Ecosistema Tidyverse

Además, también necesitamos instalar algunos paquetes R. Un _paquete_ R es una colección de funciones, datos y documentación que amplian las capacidades base de R. El uso de paquetes es una pieza clave para usar R satisfactoriamente. La mayoría de paquetes que aprenderemos en este texto son parte del ecosistema tidyverse. Los paquetes en tidyverse comparten la misma filosofía en el formato de datos y programacion, y estan diseñados para trabajar de forma conjunta cubriendo todas las tareas en el anális de un proyecto típico en ciencia de datos.

![Tidyverse para Proyecto Típico Ciencia de Datos](https://i.imgur.com/wwoD7BH.png)

Podemos instalar el ecosistema tidyverse al completo con tan sólo una única línea de código:


```r
install.packages("tidyverse")
```


Para poder hacer uso de las funciones, objetos y archivos de ayuda del paquete necesitaremos además, cargarlo en la sesión R. Esto lo conseguiremos mediante la ayuda de la función `library()`:


```r
library(tidyverse)
```
