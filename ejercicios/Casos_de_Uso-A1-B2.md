## Ejercicio A1.
 
***Nombre:*** Asignar Turno, aulas y profesor responsable 
> _Nota:_ Se puede dividir en tres casos de uso, pero cuando puedes asignarse todo a la vez (mismas características) entonces puede ser uno solo

***Actor:*** Secretario  

***Nombre:*** Solicitar ayuda para vigilar\
***Actor:*** Profesor Responsable

~~Nombre: Notificar solicitud~~\
~~Actor: Sistema~~    
> _Nota:_ cuando el Sistema hace algo sin ninguna solicitud es un caso de uso, en caso contrario no es un caso de uso, sino un paso dentro del sistema  

***Nombre:*** Validar Asignaciones\
***Actor:*** Secretario  

***Nombre:*** Confirmar vigilancia  
>_Nota:_ Se realiza de cara al sistema, si no se realiza de cara al sistema no es un caso de uso   

***Actor:*** Profesor vigilante   

>_Nota General:_ los Requisitos Funcionales; Describe la funcionalidad del sistema, no cambian el estado de mi sistema mientras que un Caso de Uso; Es un subconjunto de los requisitos funcionales, cambian el estado de mi sistema 

>_Nota General:_ Funcionalidad de cara al sistema 

## Ejercicio A2.

***Nombre:*** Inscribirse en el sistema\
***Actor:*** Jugador

***Nombre:*** Registrase en el torneo\
***Actor:*** Jugador
>_Nota:_ Los dos primeros casos de uso pueden unirse en solo uno  

***Nombre:*** Asignar caddie a jugador en torneo\
***Actor:*** Caddie Master 

***Nombre:*** Registrar resultados\
***Actor:*** Secretario

***Nombre:*** Sistema    
***Actor:*** Registrar resultados  
>_Nota:_ En este caso si que se realiza de cara al sistema


## Ejercicio A3.

***Nombre:*** Actualizar información avión e información personal\  
***Actor:*** Propietario
>_Nota:_ Existen dos escenarios, juntarlos en el  mismo procedimiento o se pueden dividir en dos, en caso de que los procedimientos realicen  diferentes acciones.

***Nombre:*** Registrar fallo del avión\
***Actor:*** Piloto 

~~Nombre: Asignar mecanico a fallo de avión~~   
~~Actor: Sistema~~ 
>_Nota:_ No es un caso de uso, es un paso dentro de un caso de uso

## Ejercicio B1.

***Nombre:*** Registrar un nuevo piso\ 
***Actor:*** Guardia   
>_Nota:_ Depende de la decisión del cliente, la asignación del actor

***Nombre:*** Cambiar celdas de vigilancia\
***Actor:*** Guardia 

***Nombre:*** Registar Inspección
>_Nota:_ Una vez realizada esta inspección de forma física, se registra de cara el sistema 
***Actor:*** Guardia

***Nombre:*** Seleccionar castigo para preso ante incidencia\ 
***Actor:*** Alcaide   
>_Nota:_ Si el actor es distinto del sistema entonces no es un paso dentro del caso de uso, sino un caso de uso diferente

***Nombre:*** Seleccionar preso indultado\      
>_Nota:_ Puede interpretarse como que el sistema ha selecionado una lista de presos dentro de este caso de uso  
***Actor:*** Alcaide

***Nombre:*** Cambio de celda\
***Actor:*** Preso

***Nombre:*** Aceptar o Rechazar Solicitud de cambio de celda\
***Actor:*** Supervisor de módulo

## Ejercicio B2.

***Nombre:*** Registar acreditación de trabajador y Asignar trabajador a servicio\ 
***Actor:** Administrador

***Nombre:*** Pedir cita, Pagar cita
>_Nota:_ Procedimiento para pedir una cita normal o visita adicional es el mismo (no hay mucha diferencia)
***Actor:*** Paciente

***Nombre:*** Registrar diagnóstico y tratamientos 
>_Nota:_ No hay mucha diferencia entre registrar el diagnostico o tratamiento del médico y el enfermero
***Actor:*** Facultativo

***Nombre:*** Generar factura\ 
***Actor:*** Sistema  

