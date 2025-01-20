# Tabla de Contenidos

1. [Descripción General](#descripción-general)
2. [Ejemplo de Sombreros](#ejemplo-de-sombreros)
3. [Actividades](#actividades)
   - [Materiales Necesarios](#materiales-necesarios)
   - [Timeline de la Actividad](#timeline-de-la-actividad)
     - [Primera Hora](#primera-hora)
     - [Segunda Hora](#segunda-hora)
     - [Tercera Hora](#tercera-hora)
     - [Cuarta Hora](#cuarta-hora)
4. [Flexiones](#flexiones)
   
# Técnica de Innovación: Sombreros de Roles

## Descripción General
Esta técnica utiliza sombreros con etiquetas específicas para representar diferentes roles dentro de un equipo de trabajo. Los roles son:
- **PM** (Project Manager)
- **PO** (Product Owner)
- **DEV** (Developer)
- **SRE** (Site Reliability Engineer)
- **QA** (Quality Assurance)
- **SUPPORT** (Soporte)
- **DevOps**

### Ejemplo de Sombreros
<details>
<summary>Ver 30 combinaciones de roles</summary>

1. PM, PO, DEV  
2. SRE, QA, SUPPORT  
3. DEV, DevOps, QA  
4. PO, SUPPORT, SRE  
5. DevOps, SRE, QA  
6. PM, DevOps, SUPPORT  
7. PO, QA, DEV  
8. PM, SRE, SUPPORT  
9. DevOps, QA, DEV  
10. PO, DevOps, SRE  
11. SUPPORT, QA, PM  
12. DEV, SRE, DevOps  
13. PO, PM, QA  
14. SUPPORT, DevOps, DEV  
15. QA, SRE, DEV  
16. PM, SUPPORT, QA  
17. DEV, PO, DevOps  
18. SRE, PM, DEV  
19. QA, PO, SUPPORT  
20. DevOps, SRE, PM  
21. QA, DEV, SUPPORT  
22. PM, PO, DevOps  
23. SRE, DevOps, QA  
24. DEV, PM, SUPPORT  
25. PO, QA, SRE  
26. SUPPORT, DEV, DevOps  
27. QA, PM, SRE  
28. DevOps, PO, DEV  
29. PM, SUPPORT, QA  
30. SRE, DEV, QA

</details>

## Actividades

### Materiales Necesarios
- Sombreros con las etiquetas de roles.
- Sharpies de colores.
- Papel peródico.
- Cinta adhesiva para la pared.

### Timeline de la Actividad

#### **Primera Hora**
- **30 minutos**: 
  - Diseño de la calculadora en línea.  El cliente desea una calculadora en línea para que los diferentes equipos puedan realizar sus procesos contables. Algunos equipos tienen sus costos registrados en Excel. Es necesario que la calculadora permita dividir el costo correspondiente a cada empleado. 
  - Preguntas clave a los Product Owners (PO): 
    - ¿Cuánto cuesta?
    - ¿Qué es lo primero que harían para diseñarla?
  - Lluvias de ideas y bocetos de la aplicación.

- **30 minutos**: 
  - Preguntas a los Project Managers (PM):
    - ¿Cuánto cuesta? ¿Cuánto dura?
    - ¿Cómo estimarían el esfuerzo y los recursos necesarios?
    - ¿Cuántos Devs, QAs, SREs y DevOps se necesitan?
  - Preguntas adicionales a otros roles:
    - **Devs**: ¿Qué necesitan?
    - **QAs**: ¿Qué necesitan?
    - **DevOps y SREs**: ¿Qué necesitan?

#### **Segunda Hora**
- **30 minutos**:
  - Inicio del primer sprint (semana 1, sin código).
  - Preguntas clave para cada rol:
    - **PMs**: ¿De dónde obtienen los User Stories y tareas?
    - **Devs**: ¿Cómo estiman las historias de usuario?
    - **QA, DevOps y SREs**: ¿Qué están haciendo mientras los Devs completan el primer build?
      - QA: Los TC.
      - SRE: SLOs. Den ejemplos de SLOs.
      - DevOps: Aprovisionamiento del ambiente de QA y PROD.

- **30 minutos**:
  - Inicio del segundo sprint (semana 2, ya hay un build).
  - Preguntas clave:
    - **QAs**: ¿Qué están haciendo?
    - **SREs**: ¿Qué están haciendo si no hay build en producción?
      - Ir creando dashboards para los SLI que salieron de los SLOs. Si es posible, alarmas también.
      - ¿Ejemplos de los monitores que pusieron? 
    - **PMs**: ¿Cómo manejar los defectos reportados por QA?
      - Llegaron 50 defectos de QA. ¿Cómo van a confirmar la fecha de entrega si ahora los devs tienen la misma cantidad de tiquetes y defectos?
    - **POs**: ¿Cómo están trabajando?
      - Validación de usuario en el software.

#### **Tercera Hora**
- **30 minutos**:
  - Sprint N, semana 2 (build en producción, llegan incidentes).
  - Preguntas clave:
    - **Support**: ¿Cómo priorizan y gestionan los incidentes?
      - Llegaron 20 incidentes el primer día:
        - 10 de que el usuario no puede ingresar.
        - 3 de que la app no carga.
        - 7 de que calcula mal.
      - ¿Cómo priorizan como uno? ¿Y qué acciones toman para cada grupo?
    - **SREs**: ¿Cómo solucionan problemas de CPU y monitorización?
      - De los 10 incidentes de que el usuario no puede cargar, hay un grupo que ocurre porque el CPU llega al 100%.
        - ¿Ya habían puesto un monitor para eso?
        - ¿Cómo lo arreglan?
        - ¿Cambia la estimación de costos que dieron?
    - **PMs y POs**: ¿Cómo gestionan cambios en estimaciones de costos?
      - QA reporta que no puede reproducir el problema de los resultados incorrectos, ¿qué procede?
    - **SREs**: ¿PM y Support les piden que agreguen las traces, logs o métricas que tengan de las pruebas de QA o cuando reportaron el incidente?
      - ¿Estimaron eso?
      - ¿Cambiaron el costo inicial?
     
- **30 minutos**:
  - Sprint N, semana 3 (build en producción, más llegan incidentes).
  - Preguntas clave:
    - **Support**: ¿Cómo priorizan y gestionan los incidentes?
      - Llegaron 7 incidentes el primer día:
        - 7 de que calcula mal.
    - **Devs**: ¿Cómo calculan los totales y qué tipo de variables usan?


## Flexiones
- Las actividades de soporte y SRE generalmente son una tarea de soporte que se negocia aparte del costo del producto.

- En las fases de diseño se hacen los Jobs to be Done (JTBD).
- En las fases del proyecto proyecto se hacen los user stories(US) basados en los Jobs to be done.
- En las fases del proyecto se hacen los SLO´s... basados en los US ?  o en los JTBD ?

- En desarrollo (Dev), las buenas prácticas como Clean Code y los principios de diseño de interfaces de usuario (UI) son fundamentales. En aseguramiento de calidad (QA), se destacan los casos de prueba (TC), las pruebas funcionales y las automatizadas. En DevOps, la automatización de procesos y el aprovisionamiento son clave.

- Finalmente, en SRE, conceptos como los SLOs, SLIs y SLAs, así como las métricas, son solo un medio para lograr el objetivo real: garantizar que el software funcione correctamente y que el usuario final experimente calidad y confianza.

