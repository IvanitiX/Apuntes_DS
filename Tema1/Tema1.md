# Tema 1. Desarrollo utilizando patrones de diseño

## 1.1 Análisis y diseño basado en patrones

### 1.1.1 > Origen e historia de los patrones software
Los patrones software fueron una adaptación al mundo de las TIC de los *patrones arquitectónicos*.

Según Christopher Alexander, un patrón arquitectónico se define como "la identificación de ideas de diseño arquitectónico mediante descripciones arquetípicas y reusables". 

Teorías como esta, basadas en la naturaleza del diseño, repercutieron en otros campos como la sociología o el software, adaptándolos a su terreno.

Estas ideas fueron presentadas en el ámbito del software por Beck y Cunningham en 1987 en un congreso, y 7 años más tarde se hizo el primer libro sobre el tema, en 1994, por Erich Gamma, Richard Helm, Ralph Johnson y John Vlissides, titulado `Gang of Four (GoF)`, definiendo el concepto de patrón software a partir del patrón arquitectónico:

> "Cada patrón describe un problema que ocurre una y otra vez en nuestro entorno, y luego describe el núcleo de la solución a nuestro problema de manera que puedas aplicar esa solución millones de veces sin tener que hacerlo de la misma manera 2 veces" ~ `Brad Appleton`

En resumidas palabras, "no reinventemos la rueda".

Antes de ello se hizo un "retiro espiritual" en las montañas donde fueron expertos en desarrollo de software para intentar integrar las ideas de los patrones software y los objetos software, logrando con ello otro libro de patrones de más alto nivel en 1996.

### 1.1.2 > Conceptos y clasificación
**Patrón software**: "Un patrón implica una descripción general de una solución recurrente a un problema recurrente con varios objetivos y restricciones. Pero no solo identifica una solución, ¡sino que también explica por qué se necesita una solución!" ~ `Brad Appleton`

Los patrones surgen desde la orientaci ́on a objetos y resuelven problemas a nivel de diseño orientado a objetos. Pero se puede aplicar a cualquier paradigma de programación, aportando soluciones en un espectro mucho más amplio en el nivel de abstracción, bien de forma muy genérica, o bien dentro del código a través de expresiones lingüísticas.

> Así, podemos clasificar los patrones de esta primera forma, según la abstracción:
>- *Patrones arquitectónicos*: Un patrón arquitectónico expresa una organización estructural o esquema para sistemas software. Provee de un conjunto de subsistemas predefinidos, especifica sus responsabilidades, e incluye reglas y guías para relacionarlos entre ellos.
>- *Patrones de diseño*: Un patrón de diseño provee un esquema para refinar los subsistemas o componentes de un sistema software, o las relaciones entre ellos. Describe comúnmente la estructura recurrente de componentes que se comunican de forma que se resuelve un problema de diseño general en un contexto particular
>- *Patrones de código, o idioms*: Es un patrón de bajo nivel específico de un lenguaje de programación. Este describe como implementar aspectos particulares de componentes o relaciones entre estos usando las características de ese lenguaje.
  
Otra clasificación los divide según la fase del ciclo de vida del desarrollo del software:

>Esta sería:
>- *Patrones conceptuales*: Aquel que se describe con términos y conceptos sobre un dominio de la aplicación
>- *Patrones de diseño*: Aquel que se define con constructos del diseño software, como los objetos, clases. herencia...
>- *Patrones de programación*: Aquel que se describe en términos de constructos del lenguaje de programación

La tercera, según el GoF, establece dos criterios:
|Propósito|Ámbito de aplicación|
|---------|--------------------|
|Refleja lo que hace un patrón|Especifica en qué ámbito se aplica el patrón|
| 3 tipos| 2 tipos|
|- Creacional: Relacionados con cómo se crean los objetos|- De clase: El patrón se aplica principalmente a clases. |
|- Estructural: Relacionados con los componentes que forman las clases y los objetos |- De objeto: El patrón se aplica principalmente a objetos. |
|- De comportamiento: Relacionados con la formaen la que los objetos y las clases interactúan entre sí y cómo se reparten las responsabilidades ||

<br>

Así, los patrones se verían así:
![Tabla Patrones](img/TablaPatronesGof.png)

<br>

La última clasificación es cómo los patrones son comprendidos, que se puede ver en este grafo:
![Grafo de patrones](img/GrafoPatrones.png)

### 1.1.3 > ¿Esto no se parece un poco a los *frameworks*?
Parece que hay una relación entre ellos, pero no son lo mismo, no nos confundamos:

**Marco de trabajo / Framework**: Es un conjunto de funcionalidad software YA IMPLEMENTADA útil en un dominio de aplicaciones específico, como un Sistema Gestor de Bases de Datos.

**Patrón software**: Es una guía o "receta" que se puede aplicar en cualquier dominio de aplicaciones, dando la misma solución a distintos problemas con una base similar, abstrayendo la parte común de ellos para llegar a tal solución. NO ESTÁ IMPLEMENTADO. 

### 1.1.4 > Elementos de un patrón de diseño
La GoF definió 4 elementos esenciales en un patrón de diseño:
- *Nombre de patrón* : Hay que hacer que se defina el problema, la solución y las consecuencias en una palabra o dos, que se incluirán en el lenguaje del diseño. Encontrar un nombre es una parte difícil para engrosar el catálogo de patrones.
- *El problema*: Describe cuándo aplicar el patrón y el contexto donde sucede. Puede ser especificar problemas como ,por ejemplo, cómo representar algoritmos u objetos. A veces el problema incluye ciertas condiciones que deben cumplirse para que tenga sentido aplicar el patrón.
- *La solución*: Describe los elementos que confeccionan el diseño, sus relaciones, responsabilidades y colaboraciones. No debe describir un diseño o implementación en sí, sino ser usado como una descripción abstracta de como un conjunto de elementos puede solucinar el problema.
- *Las consecuencias*: Aunque no se digan de ellas, son vitales para evaluar diseños alternativos y para entender los costos y beneficios de implantarse en nuestro sistema. Estas consecuencias conciernen usualmente al espacio y tiempo, la implementación y el lenguaje a usar, y el impacto en la portabilidad, flexibilidad y extensibilidad.

En la actualidad ya se provee de la siguiente plantilla para poder describir un patrón:
![Plantilla](img/Plantilla.png)

### 1.1.5 Un ejemplo práctico : Modelo-Vista-Controlador

## 1.2 ¿Cómo resolvemos problemas de disñeo usando patrones de diseño?



## 1.3 Estudio del catálogo *GoF* de patrones de diseño 