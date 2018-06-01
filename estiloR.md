# Algunos elementos de estilo de programación en R

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
