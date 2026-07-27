# Desarrollo y Operaciones Software

Repositorio general del curso: consolida los temas y conceptos vistos, y agrupa las actividades académicas (laboratorios y parciales) como [submódulos de git](https://git-scm.com/book/en/v2/Git-Tools-Submodules). El proyecto del curso (TechCup Fútbol) se desarrolló como un sistema de microservicios distribuido en dos organizaciones de GitHub independientes, enlazadas más abajo.

## Estructura del proyecto

```
Desarrollo-y-Operaciones-Software/
├── Laboratorios/                                                            # Submódulos
│   ├── DOSW_Lab1_BJJ/                                                       # Lab 1: Git, Git Flow, programación funcional y streams
│   ├── DOSW-Bootcamp-Laboratorio-02/                                        # Lab 2: SOLID, patrones de diseño, UML, Maven
│   ├── DOSW_Lab3_BrayanJuanEJuanS/                                          # Lab 3: Maven, arquetipos y GitHub
│   ├── DOSW_Lab5_JuanE_JuanS_BrayanL/                                       # Lab 5: Scrum, Kanban y estimación
│   └── DOSW_Lab6_BrayanLoaiza_JuanCruz_JuanGuayazan_JuanVillegas_JuanLaverde/  # Lab 7: TDD, cubrimiento y análisis estático
├── Parciales/                                                               # Submódulos
│   ├── DOSW_ParcialT1_JuanGuayazan/
│   └── DOSW_ParcialT2_JuanGuayazan/
└── Proyectos/
    └── TechCup Fútbol (ver enlaces más abajo)
```

## Temas del curso

El curso recorre el ciclo completo de desarrollo y operación de software, desde buenas prácticas de código hasta el despliegue de una aplicación distribuida:

- Git, Git Flow, estructuras de datos y programación funcional con streams.
- Principios SOLID, patrones de diseño y diagramación UML de clases.
- Gestión de dependencias y construcción con Maven.
- Levantamiento de requerimientos y prototipado UX/UI.
- Agilismo: Scrum, Kanban y planeación del trabajo con Jira.
- TDD, pruebas de software, cubrimiento y análisis estático (JUnit, JaCoCo, SonarQube).
- Inversión de dependencias (IoC) y Spring Framework para la construcción de APIs.
- Estándares REST, documentación con Swagger/OpenAPI y manejo de estados.
- Persistencia relacional (JPA, ACID) y seguridad en APIs (OAuth2, JWT, OWASP Top 10).
- Persistencia no relacional (NoSQL, MongoDB) y CI/CD.
- Contenedores, Kubernetes y orquestación de despliegues.
- Desarrollo de frontend con React y TypeScript.

## Cosas a tener en cuenta

- El curso se evalúa en tres tercios (30% / 30% / 40%), cada uno compuesto por quices y talleres, laboratorio, parciales y el avance del proyecto.
- Los laboratorios y talleres de este curso se desarrollaron en equipo; cada repositorio conserva su propio README con las respuestas y el material de esa entrega.
- Los laboratorios 5 y 7 (numerados internamente como Lab5/Lab6 en el nombre del repositorio) están alojados bajo la cuenta de un compañero de equipo (`brloa05`), ya que el repositorio se creó desde su cuenta.
- El proyecto del curso, **TechCup Fútbol**, es una aplicación de gestión de torneos de fútbol construida como un sistema de microservicios (backend en Spring Boot, frontend en React, base de datos relacional y no relacional, autenticación/identidad, API Gateway). Su código vive en dos organizaciones de GitHub distintas a la cuenta personal:
  - [CodeForge-DOSW](https://github.com/CodeForge-DOSW) — versión inicial del proyecto (backend, frontend y servicio de base de datos/imágenes).
  - [techcup-futbol-dosw](https://github.com/techcup-futbol-dosw) — versión final migrada a microservicios independientes (identidad, usuarios/jugadores, competencias, torneos, equipos, API Gateway, frontend, imágenes).

## Herramientas

- **Java** con **Spring Framework / Spring Boot** — backend y APIs.
- **Maven** — gestión de dependencias y construcción.
- **React con TypeScript** — frontend.
- **JUnit y JaCoCo** — pruebas y cubrimiento; **SonarQube** — análisis estático.
- **Jira** — planeación ágil (Scrum/Kanban).
- **MongoDB** — persistencia no relacional; JPA — persistencia relacional.
- **Docker / Kubernetes** — contenedores y orquestación.

## Cómo clonar

```bash
git clone --recurse-submodules https://github.com/JuanGuayazanC/Desarrollo-y-Operaciones-Software.git
```

Si ya clonaste el repositorio sin submódulos:

```bash
git submodule update --init --recursive
```
