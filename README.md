# Baseball-Modification-Stats-

Realizar un programa en C++, utilizando clases y TDA, que acepte la siguiente información para cada equipo de la liga nacional 
de béisbol de USA:
Nombre del equipo: string (sólo puede contener caracteres alfabéticos) Ciudad sede: string 
(sólo puede contener caracteres alfabéticos)   Fecha de inicio de la temporada: Fecha
Fecha de finalización de la temporada: Fecha
Número de victorias: entero
Número de derrotas: entero 
Número de bolas bateadas con éxito: entero Número de carreras: entero 
Número de errores: entero
El programa debe ser capaz de realizar las siguientes actividades:
• AGREGAR_EQUIPO: Permite introducir por medio del teclado, todos los datos de un equipo de la liga nacional de béisbol. 
Se debe validar que no se agreguen datos de un equipo de manera duplicada, indicándole al usuario, de darse el caso, que 
este equipo ya se encuentra registrado.
• ELIMINAR_EQUIPO: Dado el nombre de un equipo por medio del teclado, permite eliminar todos los datos de un equipo de 
la liga nacional de béisbol. Se debe validar que este equipo exista; si no existe, se debe escribir el mensaje correspondiente.
• MODIFICAR_EQUIPO: Dado el nombre de un equipo por medio del teclado, permite modificar cualquiera de los datos de un equipo 
de la liga nacional de béisbol. Se debe validar que este equipo exista; si no existe, se debe escribir el mensaje correspondiente.
• BUSCAR_EQUIPO: Dado el nombre de un equipo por medio del teclado, permite buscarlo y escribir todos sus datos. Se debe validar 
que este equipo exista; si no existe, se debe escribir el mensaje correspondiente.
El programa debe utilizar una estructura para la definición de un tipo de datos en donde se pueda almacenar cada una de las fechas 
(inicio y finalización), las cuales contienen los datos del día, mes y año. Además, el programa debe validar que las fechas sean 
correctas, que la fecha de inicio sea menor que la fecha de finalización y que la fecha de inicio y de finalización de la temporada 
sea la misma para todos los equipos liga nacional de béisbol que participan en la temporada.
La clase TDA equipo debe incluir el o los constructores de la clase, así como el destructor de la misma. Además, debe incluir 
las funciones miembro obtener (get) y fijar (set) para cada una de las variables miembros de la clase. Se deben sobrecargar 
los operadores de asignación, lectura y escritura para la clase TDA equipo.
El programa debe utilizar la clase TDA equipo con funciones miembros y variables miembros, funciones amigas, sobrecarga de 
operadores, strings para nombre de equipo y ciudad sede, funciones ordinarias, archivos de entrada y salida, 
un ARREGLO UNIDIMENSIONAL DINÁMICO DE OBJETOS para implementar la lista de equipos de la liga nacional de béisbol que participan 
en la temporada, así como cualquier otra estructura de datos que usted considere necesario. Además, debe proveer un menú para 
que el usuario pueda seleccionar la acción que desea realizar, el cual debe contener una opción que le permita al usuario terminar 
la ejecución del programa cuando así lo desee. Todas las salidas deben ser por pantalla y en el archivo salida.txt, a excepción 
del menú, el cual no debe escribirse nunca en el archivo de salida.
