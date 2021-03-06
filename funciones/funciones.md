


# Funciones

Este capítulo nos introduce el concepto de función  desde el punto de vista de un programador R e ilustra el rando de acción que las funciones tienen dentro del código R.

## Objetivos

Después de leer este capítulo, deberíamos:

- Conocer el concepto de [función](#que-es-una-funcion).
- Saber que son las [funciones en R](#funciones-en-r).
- Ser capaces de [crear](#funciones-definidas-usuario) nuestras funciones.
- Utilizar RStudio para crear, guardar y [ver](#funciones-rstudio) nuestras funciones.
- [Llamar](#llamada) a funciones definidas en otros scripts.
- Comprender las [llamadas en funciones anidadas](#llamada-funciones-anidadas) en R.
- Entender que son los [argumentos](#argumentos) y sus valores por defecto.
- Saber lo que son y como utilizar las [funciones anónimas](#funciones-anonimas) en R.
- Conocer que R soporta el paradigma de [programación funcional](#programacion-funcional).



## ¿Qué es una Función? {#que-es-una-funcion}

En programación, usamos las funciones conocidas también como subrutinas, procedimientos, métodos etc., para contener un conjunto de instrucciones que queremos usar repetidamente o que, a causa de su complejidad, es mejor que esten independientes en un subprograma y llamarlas cuando sea necesario. 

Dicho de otra manera, una función es una pieza de código escrita para llevar a cabo una tarea específica. A su vez, pueden o no aceptar argumentos y es posible que devuelvan o no uno o mas valores.

De hecho, existen varias definiciones formales de lo que es una función que abarcan desde las matemáticas hasta las ciencias de la computación. De forma general, sus argumentos contituyen la entrada y los valores de retorno la salida.



## Funciones en R {#funciones-en-r}

En R, de acuerdo con la documentación base, definimos una función con la siguiente construcción:

```{}
 function(lista_argumentos) {
  cuerpo_funcion
}
```

dónde el código situado dentro de las llaves constituye el _cuerpo_ de la función.

__Nota__ que cuando usamos funciones definidas, lo único que debemos conocer es la `lista_argumentos` y gestionar el valor o valores de retorno, si los hubiere.





## Funciones Definidas por el Usuario {#funciones-definidas-usuario}

En el caso que necesitemos llevar a cabo una tarea en particular y deseemos crear nuestra propia función usaremos la siguiente plantilla:

```{}
function.name <- function(argumentos) {
  computacion_en_los_argumentos
  otro_codigo
}
```

Así que, en la mayoría de los casos, una función tiene un nombre, argumentos usados como entrada a la función, dentro de `()` a continuación de la palabra reservada "function"; un cuerpo, que se trata de una instrucción o conjunto de instrucciones dentro de las llaves `{}`, que llevan a cabo la tarea en particular; y puede tener uno o mas valores de retorno en la salida de la función.

Además, definiremos las funciones de forma similar a las variables con la ayuda del operador de asignación de la forma:


```{}
nombre_funcion <- function(argumentos) {cuerpo}
```


__Recuerda__ que existen funciones que no disponen de nombres y que son conocidas como [funciones anónimas](#funciones-anonimas) y que analizaremos en un apartado posterior.




## ¿Cómo podemos ver nuestras funciones R en RStudio? {#funciones-rstudio}

## LLamar Funciones R en otros Scripts {#llamada}


## Llamada a Funciones Anidadas en R {#llamada-funciones-anidadas}

## Argumentos y Valores por Defecto {#argumentos}

## Funciones Anónimas en R {#funciones-anonimas}

## Programación Funcional en R {#programacion-funcional}

## Resumen
