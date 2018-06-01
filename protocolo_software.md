# Protocolo de desarrollo de software

* * *

# Objetivo y alcance

**Objetivo:** Definir los lineamientos generales para el desarrollo de software como parte de las actividades del LANCIS.

**Alcance:** Aplica para todos los colaboradores internos y externos del LANCIS.

* * *

# Protocolo

Este protocolo pretende guiar a los colaboradores en el desarrollo de software hacia la adopción del estándar del LANCIS. Este documento describe este estándar.

* * *

# Actividades

## 1. Crear un repositorio en GitHub

## 2. Generar un Readme
El Readme.md deberá responder a las preguntas ¿qué? y ¿cómo?. Deberá presentar con claridad el objetivo y alcance del software, las variables y unidades que lo componen, así como información sobre cómo instalar el software y cómo correrlo. Debe escribirse en formato Markdown o Restructured Text.

## 3. Adoptar la licencia GPL3
En [este video](https://youtu.be/YGbMbF0mdPU) Stephen Fry explica por qué software libre.

## 4. Adoptar el esquema de nombramiento de carpetas y archivos

## 4.1 Aportar datos de prueba
Es importante asegurarse de que los datos que acompañan el software sean de libre acceso. En caso de que los datos tengan restricciones, crear datos "dummy" que reporuzcan la estructura de los datos de entrada y que sean suficientes para correr el modelo.

## 5. Documentar el código

El uso de un sistema como [Sphinx](http://www.sphinx-doc.org/en/stable/) ayuda a crear documentación a partir del código fuente.

## 6. Adoptar estilo del código

Programas escritos en Python deben considerar la guía sugerida en [PEP 8](https://www.python.org/dev/peps/pep-0008/).

## (a) Nombres de los archivos:
Los nombres de los archivos deberán ser claros y relevantes y llevar la extensión .R
Ej. CORRECTO :  calcular_encharcamientos.R
      INCORRECTO : foo.R
## (b) Identificadores: 
La manera preferente de asignar nombres a las variables en con minúsculas y separados con un punto (nombre.variable). Los nombres de las funciones deben tener mayúsculas al inicio (NombreFuncion). 
Las constantes se nombran como las funciones pero deben contener una k al inicio.
Variables
Ej. CORRECTO :  prom.enchar
    INCORRECTO : prom_enchar
Nombre de funciones
Ej. CORRECTO :  CalcularPromedioEnchar
    INCORRECTO : calcular_promedio_enchar
Nombre de constantes
Ej. CORRECTO :  kNombreConstante
## (c) Longitud: 
La longitud máxima por línea es de 80 caracteres
## (d) Sangría: 
Utilizar dos espacios. No utilizar tabulador. 
## (e) Espacios: 
Utilizar espacios alrededor de todos los operadores binarios (=, +, -,<-, etc.).
No poner espacios antes de las comas, pero siempre habrá un espacio después de la coma
Ej. CORRECTO :  total <- sum(x[ , 1])
    INCORRECTO : total <- sum(x[ ,1])
## (f) LLaves: 
Una apertura de llaves nunca debe ir sola en una línea; un cierre de llave debe ir siempre en una línea independiente.
## (g) Organización general y orden: 
Si todos utilizan este esquema general de orden, se facilitará el entendimiento y legibilidad del código:
1)	Comentarios sobre derechos de autor
2)	Comentarios del autor
3)	Descripción general del archivo
4)	Descripción de las librerías (library())
5)	Definición de funciones


## 7. Redactar viñeta para su publicación en la página web del LANCIS

## 8. Publicar en repositorios oficiales de software

* * *
# Referencias
[Ten simple rules for effective computational research](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003506)

* * *
