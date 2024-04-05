# TP-DSW-2024
# Propuesta TP DSW

## Grupo
### Integrantes
* 50979 - María Clara Genovese
* 50977 - Pennice Lucas Agustin
* 50235 - Bruno Pacienzia

### Repositorios
* [frontend app](https://github.com/LucasPennice/TP-DSW-FRONT.git)
* [backend app](https://github.com/LucasPennice/TP-DSW-BACK.git)

## Tema
### Descripción
Servicio para calificar la experiencia con el docente en distintas asignaturas de la carrera de sistemas de la UTN Rosario

### Modelo
![imagen del modelo]()

*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Catedra<br>2. CRUD Usuario Administrador<br>3. CRUD Usuario|
|CRUD dependiente|1. CRUD Review {depende de} CRUD Catedra <br>2. CRUD Profesor {depende de} CRUD Catedra y CRUD Turno|
|Listado<br>+<br>detalle| 1. Listado de reviews filtrado por profesor, muestra calificacion y comentario => detalle de la review<br> 2. Listado de catedras filtrado por nombre de catedra y turno, muestra nombre profesor, profesor mejor calificado, calificacion promedio de profesor de la catedra  => detalle de la catedra|
|CUU/Epic|1. Escribir una review<br>2. Dar de alta un profesor|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Catedra<br>2. CRUD Usuario Administrador<br>3. CRUD Usuario<br>4. CRUD Turno<br>5. CRUD Review<br>6. CRUD Profesor|
|CUU/Epic|1. Escribir una review<br>2. Dar de alta un profesor<br>3. Dar de alta una catedra<br> 4. Consultar reviews de un profesor/catedra|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Eliminar reviews que no cumplan <br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
