# Desarrollo y Operaciones Software (DOSW)

Repositorio general del curso Desarrollo y Operaciones Software (ISIS DOSW-301), que agrupa —mediante submódulos de git— las actividades académicas (laboratorios, parciales y talleres) y los proyectos del curso, incluyendo dos intentos: 2025-2 y 2026-1.

Cada submódulo es un repositorio independiente con su propio historial de commits y README. Para clonar este repositorio junto con todo su contenido, ver [Cómo clonar](#cómo-clonar).

## Estructura del proyecto

```
Desarrollo-y-Operaciones-Software/
├── Laboratorios/                                                            # Submódulos
│   ├── Laboratorio-1/                                                       # Lab 1: Git, Git Flow, programación funcional y streams
│   │   ├── DOSW_Lab1_BJJ/                                                   #   Intento 2026-1
│   │   └── Lab1-DOSW/                                                       #   Intento 2025-2
│   ├── DOSW-Bootcamp-Laboratorio-02/                                        # Lab 2: SOLID, patrones de diseño, UML, Maven (2026-1)
│   ├── Laboratorio-2-CVDS-DOSW-01/                                          # Lab 2 (2025-2) — repo de un compañero de equipo, no propio
│   ├── Laboratorio-3/                                                       # Lab 3: TDD, pruebas, Agilismo/Scrum
│   │   ├── DOSW_Lab3_BrayanJuanEJuanS/                                      #   Intento 2026-1
│   │   └── Lab3-DOSW/                                                       #   Intento 2025-2
│   ├── DOSW_Lab5_JuanE_JuanS_BrayanL/                                       # Lab 5: Scrum, Kanban y estimación (alojado en cuenta de compañero)
│   └── DOSW_Lab6_BrayanLoaiza_JuanCruz_JuanGuayazan_JuanVillegas_JuanLaverde/  # Lab 7: TDD, cubrimiento y análisis estático (alojado en cuenta de compañero)
├── Parciales/                                                               # Submódulos
│   ├── Parcial-1/                                                           # Primer corte
│   │   ├── DOSW_ParcialT1_JuanGuayazan/                                     #   Intento 2026-1
│   │   └── Parcial-Primer-Corte-DOSW/                                      #   Intento 2025-2
│   └── DOSW_ParcialT2_JuanGuayazan/                                         # Segundo corte (solo intento 2026-1)
├── Talleres/                                                                # Submódulos
│   └── Taller-de-recuperacion-DOSW/                                        # Caso de estudio API de recetas (semana de receso, 2025-2)
└── Proyectos/                                                               # Submódulos — proyecto del curso, carpeta = "Proyecto (Equipo)"
    ├── TechCup-Futbol-DOSW (CodeForge)/                                     # Equipo CodeForge — versión inicial (monolito por servicio)
    │   ├── TECHCUP-FUTBOL-BackEnd/
    │   ├── TECHCUP-FUTBOL-FrontEnd/
    │   ├── TECHCUP-FUTBOL-Database-and-image-service/
    │   └── TECHCUP-FUTBOL-BackEnd-SpringBoot/
    ├── TechCup-Futbol-DOSW (Animal-Crossing)/                               # Equipo Animal Crossing — versión final (microservicios)
    │   ├── techcup-front/
    │   ├── techchup-users/
    │   ├── techcup-identity/
    │   ├── techcup-apigateway/
    │   ├── techcup-competitions/
    │   ├── techcup-tournaments/
    │   ├── techcup-teams/
    │   └── techcup-image-service/
    ├── SIRHA-DOSW (LeanCode)/                                               # Equipo LeanCode — proyecto SIRHA
    │   ├── SIRHA-BackEnd/
    │   └── SIRHA-FrontEnd/
    └── DOSW2025/wise/                                                       # Proyecto Wise (equipo DOSW2025, 2025-2)
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

- El curso se vio dos veces: la primera en el semestre 2025-2 (sección ISIS DOSW-3/DOSW-301) y la segunda en 2026-1. Cuando una actividad tiene versión en ambos intentos, ambas quedan agrupadas en la misma carpeta.
- El curso se evalúa en tres tercios (30% / 30% / 40%), cada uno compuesto por quices y talleres, laboratorio, parciales y el avance del proyecto.
- Los laboratorios y talleres de este curso se desarrollaron en equipo; cada repositorio conserva su propio README con las respuestas y el material de esa entrega.
- Los laboratorios 5 y 7 (numerados internamente como Lab5/Lab6 en el nombre del repositorio) están alojados bajo la cuenta de un compañero de equipo (`brloa05`), ya que el repositorio se creó desde su cuenta.
- El laboratorio 2 del intento 2025-2 (`Laboratorio-2-CVDS-DOSW-01`) está alojado en la cuenta de otro compañero de equipo (`AlejandroHenao2572`), no en la propia.
- El proyecto del curso en 2026-1, **TechCup Fútbol**, es una aplicación de gestión de torneos de fútbol construida como un sistema de microservicios (backend en Spring Boot, frontend en React, base de datos relacional y no relacional, autenticación/identidad, API Gateway). Su código vive en 12 repositorios repartidos en dos organizaciones de GitHub, construidos por dos equipos distintos:
  - **Equipo CodeForge** ([CodeForge-DOSW](https://github.com/CodeForge-DOSW)) — versión inicial del proyecto (backend, frontend y servicio de base de datos/imágenes).
  - **Equipo Animal Crossing** ([techcup-futbol-dosw](https://github.com/techcup-futbol-dosw)) — versión final migrada a microservicios independientes (identidad, usuarios/jugadores, competencias, torneos, equipos, API Gateway, frontend, imágenes).
- El proyecto del curso en 2025-2, **SIRHA** (Sistema de Reasignación de Horarios Académicos), fue construido por el **equipo LeanCode** ([LeanCode-DOSW](https://github.com/LeanCode-DOSW)).
- También en 2025-2 se trabajó el proyecto **Wise**, del equipo DOSW2025 ([DOSW2025](https://github.com/DOSW2025)).
- Los repositorios de organización (CodeForge-DOSW, techcup-futbol-dosw, LeanCode-DOSW, DOSW2025) y el laboratorio de Alejandro Henao no son propiedad de esta cuenta — se referencian como submódulos, pero no se editan sus READMEs.
- `LAb5_API_CRUD_POINT` (dentro de la organización CodeForge-DOSW) se excluyó de este repositorio: es un laboratorio de otro curso (Arquitecturas de Software), de otro autor (`brloa05`), sin participación de esta cuenta — no pertenece a TechCup Fútbol.

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
