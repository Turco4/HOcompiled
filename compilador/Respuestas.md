1)
_Pre-procesador: `make preprocessing`: se encarga de cargar los ficheros a partir de las directivas #. 
_Compilacion I: `make assembler`: se encarga de pasar de lenguaje C a Assembler. Se organiza en tres procesos sucesivos: 
1ro- El front end que realiza el análisis sintáctico, semántico y léxico. Genera una IR.
2do- El middle end que optimiza la IR del front end.
3r0- El back end que genera el código de assembler y realiza optimizaciones de hardware.
_Compilacion II: `make object`: se encarga de generar los objetos en binario, pasa de assembler a lenguaje maquina.
_Linkeo: `make executable`: genera el ejecutable a partir del codigo binario.

2)
El preprocesador agrega los ficheros y, por consiguiente, todas las funciones incluidas dentro del mismo. En nuestro caso a partir de la instrucción # va a cargar el ficheroe "calculator.h". 
3)
En la rutina de asembler las funciones son: LCO y LFEO
4)

