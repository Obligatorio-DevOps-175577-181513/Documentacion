<div align="center" >
    <img src="ort.png" width="300">
    
</div>

<!-- Esto es un espaciado usando una línea en blanco -->

<div align="center">
   
   # Obligatorio DevOps
</div>


<div align="center" style="margin-bottom: 30px;">

#### Integrantes del equipo:

Damián Ariztimuño - Hugo Borgiani

Tutor: Federico Barceló

2024
</div>

## Caso de Estudio

Durante la transformación digital de una empresa líder en retail, surgió un desafío significativo que reveló una brecha en la comprensión y comunicación entre los equipos de desarrollo y operaciones. Este problema se hizo evidente cuando los lanzamientos de una nueva aplicación, destinada a mejorar la experiencia de compra, resultaban en errores y caídas del sistema, afectando la experiencia del usuario y la reputación de la empresa. El conflicto no era técnico, sino cultural y organizativo, debido a la falta de colaboración entre los equipos que mantenían roles separados y prioridades conflictivas. La dirección ejecutiva reconoció que la solución al problema requería un cambio cultural profundo para alinear a todos los equipos bajo objetivos y prácticas comunes, más allá de meros ajustes técnicos.

## Planteamiento para la resolución del problema
Para resolver el problema, el equipo pretende adoptar una metodología DevOps, así, de esta forma, podrá integrar los diferentes flujos de trabajo de los equipos de desarrollo y operaciones, automatizarlos, y de esta forma disminuir la cantidad de errores sufridos durante los variados procesos y mejorando su time-to-market.

El mayor desafío se presenta en relación a gran variedad de herramientas existentes y la elección de las mismas y al correcto uso de estas.

## Objetivos generales y específicos
Se plantea como objetivos generales desplegar la infraestructura del proyecto en la nube, de manera que esta quede alojada de manera pública y accesible, y a su vez, aprovechando las bondades que esta brinda, como pueden ser la escalabilidad, la estabilidad y la eficiencia.

#### Como objetivos específicos podemos destacar:
- Estudiar las diferentes herramientas existentes en pos de seleccionar cuáles de estas son las que más se adecúan a las necesidades del cliente y a las complejidades que conlleva disponibilizar la infraestructura en la nube.
- Optimiazar los procesos de deploy para todos los aplicativos con el objectivo de disminuir el time-to-market y disponibilizarlos de manera continua para el usuario final
- Realizar análisis de código estático en pos de poseer un código limpio y mantenible, reduciendo los code smells y la repetición de código, y a su vez fomentando la detección temprana de bugs.
- Utilizar la metodología GitOps. A través de ella pretendemos utilizar el versionado de Git como la única fuente confiable de código y realizar deploys de manera automatizada.
- Aplicar testing automatizado con un enfoque end-to-end para verificar flujos funcionales a nivel de toda la aplicación, y reduciendo los tiempos de regresión para el equipo de testing manual, previo a la las salidas a producción.

El mayor desafío se presenta en relación a gran variedad de herramientas existentes y la elección de las mismas y al correcto uso de estas.

## Herramientas utilizadas
A continuación se detallan las tecnologías y herramientas utlilizadas para elaborar la solución

-**Git**: Se utilizará Git como tecnología de control y versionado de archivos
-**GitHub**: El uso de GitHub implica el almacenamiento de los diferentes repositorios en la nube, facilitando un acceso directo a los mismos.
-**GutHub Actions**: Se considera el uso de GitHub Actions para la implemantación de las estrategias de CI/CD, además de ya estar integrada con GitHub, lo cual facilita su uso.
-**Sonar Cloud**: El uso de Sonar Cloud estára limitado al análisis de código estático contenido en los diferentes repositorios.
-**Terraform**: Se plantea el uso de terraform para definir la infraestructura como código (IaC).
-**Playwright**: Plawright será usado como herramienta de testing E2E (End to End), debido a su fácil despliegue e integración con GitHub Actions.
