 # Detalles del proyecto

El proyecto es un gestor de alumnos pero con enfoque a ser utilizado por un grupo scout, el sistema tiene como objetivo la gestion de los integrantes de un grupo scout llevando un registro de su jerarquía, asistencia semanal, seguro, ficha medica y progrecion personal

## Equivalencia/Comparacion con escuela
| Entidad Scout                  | Entidad Educativa               | Descripcion breve                                             |
|:------------------------------:|:-------------------------------:|:-------------------------------------------------------|
| Jefe de Grupo                  | Director                       | Maxima autoridad y responsable del grupo o institucion.    |
| Dirigente (de Rama)            | Profesor Titular               | Responsable de un curso o rama     |
| Scout                          | Alumno / Estudiante            | Integrante principal del sistema.   |
| Rama                           | Curso / Nivel Educativo        | Unidad de edad por ej: 4to año = Rama Scout Rovers |
| Patrulla                       | División / Seccion             | Unidad de trabajo interna dentro de la Rama/Curso.    |
| Progresion                     | Materia                        | Contenido o meta educativa a alcanzar.   |
| ScoutProgresion                | Registro de Calificación       | Registro que documenta el logro individual del estudiante/Scout en la materia.|


## Usuario del sistema
El sistema esta diseñado para ser utilizado por el jefe de grupo o por algun dirigente

 ## Tecnologias a utilizar:
 El proyecto implementara las siguientes tecnologias y herramientas:

- ASP.NET Core 8.0 – Framework backend con patrón MVC.

- C# – Lenguaje principal del backend.

- Entity Framework Core – ORM para mapear clases a tablas y manejar relaciones.

- MySQL – Base de datos relacional.

- JWT (JSON Web Tokens) – Autenticacion para APIs.

- Vue.js 

- Bootstrap / TailwindCSS – Estilos 

## Funcionalidades del sistema
- Gestión Jerarquica: Administracion de Ramas y Patrullas y asignacion de Scouts.
- Asistencia: Registro detallado de la presencia semanal, vinculada a una Rama especifica.
- Progresion Personal: Modulo para registrar el avance de cada Scout en sus Etapas y Especialidades (Progresiones), pudiendo ver quien fue el dirigente que aprobo dicha progrecion.
- Seguros y Cuotas: Registro y control de polizas de seguro y seguimiento de las cuotas asociadas.
- Ficha Medica: Almacenamiento seguro de datos vitales (alergias, contactos de emergencia) con acceso solo para dirigentes.


## Caracteristicas Futuras
Las siguentes caracteristicas se planean implementar en el sistema(Aun no estan implementadas en el diagrama de clases):
1. Sistema de Campamentos y ubicacion geografica de los mismos: Se planea implementar el registro de campamentos, con su ubicacion, detalles del lugar y archivos relacionados(Fotos del campamento realizado)

2. Gestión de Cuotas de Seguros: ampliar el modulo de seguro para que sea tratado como un seguro tiene cierta candidad de pagos asociados y asi poder ver que scouts estan al dia y quienes adeudan cuotas(Ya fue implementado en el diagrama de clases)