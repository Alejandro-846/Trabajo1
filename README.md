# Proyecto_Python_PabonVictor

# CampusLands ERP

CampusLands ERP es un sistema diseñado para facilitar la gestión académica de los campers matriculados en el programa intensivo de programación de CampusLands. Este sistema permite realizar el seguimiento de inscripciones, gestión de rutas de entrenamiento, asignaciones de trainers y campers, evaluaciones, y generación de reportes académicos.

## Tabla de Contenidos

- [Descripción General](#descripción-general)
- [Objetivos del Proyecto](#objetivos-del-proyecto)
- [Roles en el Sistema](#roles-en-el-sistema)
- [Funcionalidades Principales](#funcionalidades-principales)
  - [Gestión de Campers](#gestión-de-campers)
  - [Gestión de Rutas de Entrenamiento](#gestión-de-rutas-de-entrenamiento)
  - [Gestión de Matrículas](#gestión-de-matrículas)
  - [Evaluaciones y Rendimiento Académico](#evaluaciones-y-rendimiento-académico)
  - [Módulo de Reportes](#módulo-de-reportes)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Requisitos Previos](#requisitos-previos)
- [Cómo Ejecutar el Proyecto](#cómo-ejecutar-el-proyecto)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Descripción General

El sistema ERP permitirá a CampusLands gestionar de manera eficiente las inscripciones, asignaciones y rendimiento académico de los campers, así como la administración de trainers y rutas de entrenamiento.

## Objetivos del Proyecto

1. Centralizar la gestión académica de CampusLands.
2. Mejorar el seguimiento y asignación de rutas de entrenamiento.
3. Automatizar la evaluación y generación de reportes de desempeño académico.
4. Facilitar la toma de decisiones con información precisa sobre campers, trainers y rutas.

## Roles en el Sistema

- *Camper*: Usuario que participa en las rutas de entrenamiento.
- *Trainer*: Responsable de dirigir y evaluar a los campers en las rutas asignadas.
- *Coordinador*: Encargado de gestionar inscripciones, asignaciones y evaluaciones.

## Funcionalidades Principales

### Gestión de Campers

- Registro de información personal:
  - Número de identificación, nombres, apellidos, dirección, acudiente, teléfonos de contacto.
  - Estado del camper (En proceso de ingreso, Inscrito, Aprobado, Cursando, Graduado, Expulsado, Retirado).
  - Nivel de riesgo (alto, bajo).
- Actualización del estado del camper según el progreso académico.
- Listado de campers en estado "inscrito" o "aprobado".

### Gestión de Rutas de Entrenamiento

- Rutas disponibles:
  - NodeJS
  - Java
  - NetCore
- Creación de nuevas rutas con módulos:
  - Fundamentos de programación.
  - Programación Web.
  - Programación Formal.
  - Bases de datos.
  - Backend.
- Gestión de capacidades (máximo 33 campers por área).
- Asignación de campers a rutas según disponibilidad y capacidad.

### Gestión de Matrículas

- Asignación de campers aprobados a rutas de entrenamiento.
- Registro de trainer encargado, fechas de inicio y finalización, y salón de entrenamiento.
- Verificación de horarios para evitar conflictos entre rutas.

### Evaluaciones y Rendimiento Académico

- Evaluaciones periódicas para cada módulo:
  - Prueba teórica (30% del peso).
  - Prueba práctica (60% del peso).
  - Quizzes y trabajos (10% del peso).
- Aprobación de módulos con nota final ≥ 60.
- Registro de bajo rendimiento para notas < 60.
- Identificación de campers en riesgo académico.

### Módulo de Reportes

- Listar:
  - Campers en estado "inscrito".
  - Campers que aprobaron el examen inicial.
  - Trainers activos.
  - Campers con bajo rendimiento.
  - Campers y trainers asociados a una ruta.
- Mostrar:
  - Número de campers que aprobaron o reprobaron cada módulo por ruta y trainer.

## Tecnologías Utilizadas

- Lenguaje: *Python*
- Frameworks: (por definir)
- Base de Datos: (por definir)
- Otras herramientas: (por definir)

## Requisitos Previos

- Python 3.8 o superior.
- Gestor de paquetes pip.
- Base de datos compatible (por definir).

## Cómo Ejecutar el Proyecto

1. Clona el repositorio:
   ```bash
