- Universidad Galileo
- Maestría en Inteligencia de negocios y Analítica
- José Ricardo Ortiz Lara
- Carné No.21006920
- Ciencia de Datos en Python, sección V

# SVC, GIT y Github

Kodetop (2019) define que un sistema de control de versiones (SVC) es aquel que permite a los desarrolladores guardar de manera ordenada cambios que se realicen sobre un proyecto o programa, pudiendo mantener un historial de modificaciones con un registro de quién y cuando se alteraron los documentos. 

### ¿Qué tipos de SVC existen?
- Sistema de control de versiones locales: Se encuentra en la máquina local y no es posible colaborar con otros colaboradores
- Sistema de control de versiones centralizado: Existe un único servidor central que contendrá todos los archivos relacionados con el proyecto, y muchos colaboradores extraerán archivos de este único servidor
- Sistema de control de versiones distribuido: Tendrá uno o más servidores y muchos colaboradores con la diferencia que estos no solo revisan la última versión, sino que cada colaborador tendrá una copia exacta del repositorio principal

Existe varias herramientas para el control de versiones pero GIT ha ganado relevancia constante desde su lanzamiento en 2005, convirtiéndose en uno de los programas más populares de VCS que se conoce.

### ¿Qué es Git?
Rubio (2019) define *"Git es una herramienta que realiza una función del control de versiones de código de forma distribuida"*, mientras que Kodetop (2019) lo define como *“un sistema de control de versiones ligero, rápido y con capacidad de manejar grandes proyectos”*.

Este proyecto de código abierto y mantenimiento activo fue desarrollado por Linus Torvalds, quién creó el kernel de Linux. Según menciona bitbucktet (s.f) GIT presenta una arquitectura distribuida en la que la copia de trabajo del código de cada desarrollador es también un repositorio que puede albergar el historial completo de todos los cambios.

### ¿Características de Git?
- No depende de un repositorio central
- Es software libre
- Permite mantener un historial completo de versiones
- Tiene un sistema de trabajo con ramas

#### Características de la terminología de Git
Hay algunas características interesantes enumeradas en la terminología de Git, que son las siguientes:
- **Rama**: Una versión del repositorio que es diferente del proyecto de trabajo principal.  / Sintaxis: git branch
- **Commit**: Registro de cambio registrado en GIT / Sintaxis: git log: se usa para ver los últimos cambios confirmados en el código.
- **HEAD**: Representación de la rama actualmente desprotegida del último código confirmado.
- **índice**: Es un término alternativo para el área de preparación.
- **Repositorio**: Una estructura de datos utilizada para almacenar metadatos para un conjunto de archivos y directorios. Existen diferentes versiones del repositorio que son las siguientes:
1. Depósito local
2. Repositorio remoto
3. Depósito aguas arriba
4. Revisión Representa una versión del código fuente. 
- **Área de preparación** es el lugar para almacenar los cambios en el árbol de trabajo antes de la confirmación.
•	Etiqueta Se usa para marcar la etapa de confirmación como importante.  Hay dos tipos de etiquetas:
1. Etiqueta ligera
2. Etiqueta anotada
- **URL**: Detecta la ubicación del repositorio.
- **Árbol de trabajo**: normalmente contiene el contenido del árbol de confirmación HEAD y cualquier cambio local que haya realizado pero que aún no haya confirmado.
- **Fork** En lugar de utilizar un único repositorio del lado del servidor para actuar como la base de código "central", la bifurcación le da a cada desarrollador un repositorio del lado del servidor

### ¿Qué es GitHub?
GitHub es una plataforma de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git y su uso principal es la creación de código fuente de programas de ordenador.

### ¿Cuál es la diferencia entre Git y GitHub?
Cómo se ha mencionado Git es una herramienta de control de mientras que GitHub es un servicio en la nube basado en la web para alojar su código fuente (un sistema centralizado). CBien se dice que *"Git no requiere GitHub pero GitHub requiere Git.”*

### Bibliografía
- Atlassian Bitbucket. (s.f.). Qué es Git. Obtenido de Tutorials: https://www.atlassian.com/es/git/tutorials/what-is-git
- Garcia, F. (02 de 12 de 2014). Terminología común del control de versiones. Obtenido de NOTAS DE FABIÁN GARCÍA: https://notasdegit.wordpress.com/tag/terminologia/
- https://es.education-wiki.com/. (s.f.). Terminología Git. Obtenido de https://es.education-wiki.com/: https://es.education-wiki.com/8445422-git-terminology
- KODETOP. (21 de 07 de 2019). Tutorial básico de Git. Obtenido de KODETOP: https://www.kodetop.com/tutorial-basico-de-git/#:~:text=Terminolog%C3%ADa%20utilizada%20en%20Git,de%20moverse%20entre%20diferentes%20ramas.
- Udemy. (s.f.). Git, GitHub y GitLab: Uso de repositorios de código. Obtenido de Udemy: https://www.udemy.com/course/git-github-y-gitlab-uso-de-repositorios-de-codigo/?utm_source=adwords&utm_medium=udemyads&utm_campaign=LongTail_la.ES_cc.LATAM&utm_term=_._ag_121424001579_._ad_515898216164_._kw__._de_c_._dm__._pl__._ti_dsa-1237025622372_._li_

