#  Apuntes_ED
## Introducción
### 1. **Software de Sistema:**
---
`Sistema operativo` Controla el hardware y permite que otros programas se ejecuten.

Controladores de Dispositivos: Facilitan la comunicación entre el sistema operativo y el hardware.
Herramientas de Utilidad: Proporcionan funciones útiles para la administración y el mantenimiento del
sistema.
     
---
 `Software de Aplicación`

* Software de Productividad: Incluye procesadores de texto, hojas de cálculo, programas de presentación,
etc.

* Software de Comunicación: Incluye navegadores web, clientes de correo electrónico, programas de chat,
etc.

* Software de Entretenimiento: Juegos, reproductores multimedia, software creativo, etc.
Software Educativo: Diseñado para la enseñanza y el aprendizaje.

* Software de Negocios: Aplicaciones específicas para empresas, como software de contabilidad o gestión
de proyectos.
---
 `Software de Desarrollo`
  Entornos de Desarrollo Integrados (IDE): Ayudan a los programadores a escribir, depurar y compilar
código.

* Herramientas de Control de Versiones: Facilitan la gestión de cambios en el código fuente.

* Herramientas de Diseño Gráfico y Multimedia: Software para diseño web, gráfico y edición de medios.
---
`Software de Seguridad`
  
* Antivirus y Antimalware: Protege contra amenazas informáticas.
  
* Firewalls: Controlan el tráfico de red para proteger contra intrusiones.

* Software de Encriptación: Protege datos confidenciales mediante la encriptación.
 ---
  `Software de Sistema Embebido`
  Está integrado en dispositivos específicos, como electrodomésticos, automóviles, dispositivos médicos,
etc.

---
* `Software de Inteligencia Artificial y Aprendizaje Automático`
  Incluye algoritmos y aplicaciones para el procesamiento de lenguaje natural, visión por computadora,
análisis de datos, etc.

* `Software de Código Abierto y Software Propietario`
   
---
---

## 2. Relación entre los principales componentes del hardware junto el almacenamiento y ejecución

  Los componentes hardware principales de un computador, como la `CPU`, la `memoria RAM` y el
`disco duro`, trabajan juntos para almacenar y ejecutar el software. 
  El software se almacena enel disco duro, y cuando se ejecuta, se carga en la memoria RAM para su procesamiento por la
CPU. 
  La CPU interpreta y ejecuta las instrucciones del software desde la memoria RAM,permitiendo que la computadora realice diversas tareas. 
>El almacenamiento y la ejecución del software dependen de la cooperación de estos componentes para un funcionamiento eficiente
del sistema.

*Conceptos*
* Código fuente: : Conjunto de instrucciones escritas por un programador en
un lenguaje de programación específico que define `cómo un software o programa debe
funcionar`. Es el "texto original" legible por humanos antes de ser traducido a lenguaje de
máquina para la ejecución por una computadora.
* Código objeto. El código objeto es el resultado de la compilación o traducción del código fuente
a un lenguaje de máquina o código binario que la computadora puede entender y ejecutar
directamente. Es la `versión no legible por humanos del software, lista para su ejecución en la
computadora.`
* Código ejecutable.El código ejecutable es el código objeto que ha sido cargado en la memoria
de la computadora y se encuentra en un estado activo, listo para ser ejecutado. Es la forma en
que el `software se ejecuta y realiza sus funciones` en la computadora.

### 3. Ciclo de vida del sofware


El ciclo de vida del software es el proceso que abarca `desde la concepción y desarrollo inicial`
de un programa informático `hasta su despliegue, mantenimiento y eventual retirada`. Incluye
etapas como la planificación, diseño, codificación, pruebas, implementación y mantenimiento
continuo del software.

Fases principales del desarrollo de software 

1. `Planificación` En esta fase se **definen los objetivos del proyecto, los recursos necesarios y el cronograma**.
Se establecen los requisitos del software y se crea un plan de proyecto.
Análisis: Aquí se recopilan y documentan los requisitos del software. Se identifican las necesidades del
usuario y se determina qué debe hacer el software.

2. `Diseño` En esta fase se crea una estructura o arquitectura para el software. Se definen las interfaces de
usuario, las bases de datos y otros aspectos técnicos del sistema.
Implementación: Se traducen los diseños en código fuente. Los programadores escriben el software de
acuerdo con las especificaciones y el diseño previamente establecido.

3. `Pruebas` Se somete el software a pruebas exhaustivas para detectar errores y asegurarse de que cumple
con los requisitos. Se realizan pruebas de unidad, integración y aceptación.

4. `Despliegue` El software se implementa en el entorno de producción. Se realiza una transición del
software desde el desarrollo al uso real.

5. `Mantenimiento` Se lleva a cabo el mantenimiento continuo del software para corregir errores, realizar
actualizaciones y adaptarse a cambios en los requisitos del usuario.
---
 ### Modelo en cascada en de desarrollo de software.
 
El modelo en cascada es un **enfoque lineal y secuencial** para el desarrollo de software.
Consiste en **dividir el proyecto en fases** claramente definidas, como planificación, análisis,
diseño, implementación, pruebas, despliegue y mantenimiento. Cada fase debe completarse
antes de pasar a la siguiente, y los cambios en etapas anteriores pueden ser costosos o difíciles de incorporar en etapas posteriores.
> Es un enfoque estructurado y predecible, pero
> puede carecer de flexibilidad para adaptarse a cambios en los requisitos del cliente.


* Ventajas del modelo en cascada:

`Estructura clara` Las **fases están bien definidas** y tienen objetivos específicos, lo que facilita el
seguimiento y control del proyecto.

`Documentación completa` Cada fase produce una **documentación completa** que sirve como referencia
para el desarrollo y el mantenimiento del software.

`Facilita la planificación` Es adecuado para proyectos con requisitos estables y bien comprendidos, lo
que facilita la estimación de costos.

*Inconvenientes del modelo en cascada:

`Poca flexibilidad` Dificulta la adaptación a cambios en los requisitos del cliente, ya que los cambios en
etapas anteriores pueden ser costosos y retrasar todo el proyecto.

`Largo tiempo de entrega` Los clientes suelen ver resultados solo al final del ciclo, lo que puede llevar a
insatisfacción si no se cumplen sus expectativas.

`Riesgo de no cumplir con las expectativas del cliente` Debido a la falta de retroalimentación continua,
el software final podría no satisfacer las necesidades reales del cliente.

`No es adecuado para proyectos complejos o innovadores` Puede ser ineficaz para proyectos donde los
requisitos son desconocidos o evolucionan durante el desarrollo.

---
 
### 4. Verificación / validación

`Verificación`
*La verificación se centra en evaluar si el software está siendo desarrollado correctamente, es
 decir, si cumple con las especificaciones y requisitos establecidos.*

> Actividades típicas: Incluye revisiones de código, inspecciones, pruebas de componentes y otros
> métodos para asegurarse de que el software esté siendo construido de acuerdo con el diseño y las
> especificaciones.

`Validación`
*La validación se centra en evaluar si el software es lo que el cliente realmente necesita y si
satisface sus necesidades. Es el proceso de confirmar si el software cumple con los requisitos del usuario
y si es útil y efectivo en el entorno de uso previsto.*

> Actividades típicas: Incluye pruebas de aceptación por parte del usuario, pruebas beta, validación de
> requisitos con los interesados y asegurarse de que el software entregado sea adecuado para el propósito
> previsto

---

### 5. Modelo de desarrollo mediante creación de prototipos.

Es un enfoque iterativo que se utiliza cuando los requisitos del proyecto no están completamente definidos
o cuando es necesario obtener retroalimentación temprana del cliente para refinar los requisitos. A
continuación, se explica cómo funciona este modelo:

`Recolección de Requisitos Iniciales`
Se inicia con una comprensión general de lo que se necesita en el software, pero los requisitos
específicos pueden no estar completamente definidos.

`Desarrollo del Prototipo`
Se crea un prototipo inicial del software que contiene algunas características o funcionalidades clave, lo
suficientemente representativas para permitir al cliente entender cómo funcionará el sistema.

`Demostración al Cliente`
El prototipo se presenta al cliente para obtener su retroalimentación y validación. El cliente puede
interactuar con el prototipo y sugerir cambios, mejoras o ajustes en los requisitos.

`Refinamiento y Repetición`
Basándose en la retroalimentación del cliente, se refinan los requisitos y se realizan ajustes en el
prototipo. Este proceso se repite en múltiples iteraciones hasta que se logre un consenso en los requisitos
y la visión del software.

`Desarrollo Final`
Una vez que los requisitos están bien definidos y aceptados, se procede al desarrollo final del software.
Los prototipos anteriores pueden haber ayudado a identificar problemas tempranos, lo que ahorra tiempo
y recursos en el desarrollo final.

`Pruebas y Entrega`
El software completo se somete a pruebas exhaustivas y, una vez que se verifica que cumple con los
requisitos validados, se entrega al cliente.


Ventajas del modelo de desarrollo mediante creación de prototipos
* Proporciona una forma efectiva de lidiar con requisitos ambiguos o cambiantes.
* Permite a los clientes visualizar y experimentar con el software temprano en el proceso.
* Facilita la retroalimentación temprana y la adaptación de requisitos según las necesidades del cliente.

Desventajas del modelo de desarrollo mediante creación de prototipos:
* Puede requerir más tiempo y recursos debido a las iteraciones.
* Si no se gestiona adecuadamente, puede llevar a la creación de prototipos que no se convierten en el
producto final.
* No es adecuado para proyectos con requisitos completamente definidos desde el principio.

---

### 6. Modelo espiral en desarrollo orientado a objetos.

* `Determinación de Objetivos` Al inicio del proceso, se establecen los objetivos y se definen las
necesidades del sistema.

* `Identificación de Requisitos` Se identifican y documentan los requisitos del sistema, centrándose en los
objetos, sus atributos y métodos.

* `Diseño de Objetos y Arquitectura` Se crea un diseño inicial del sistema utilizando conceptos de
orientación a objetos, incluyendo la definición de clases, relaciones y arquitectura.

* `Implementación de Objetos` Se comienza la implementación de objetos basados en el diseño,
escribiendo código para las clases y métodos definidos.

* `Pruebas y Validación` Se llevan a cabo pruebas de unidades, pruebas de integración y pruebas de
validación para asegurarse de que los objetos funcionan correctamente y cumplen con los requisitos.

* `Evaluación y Retroalimentación` Después de cada ciclo de desarrollo, se evalúa el progreso y se
obtiene retroalimentación del cliente o del usuario. Esto puede llevar a ajustes en los requisitos o en el
diseño de objetos.

* `Iteración` El proceso se repite en ciclos sucesivos, abordando gradualmente los requisitos y las
características adicionales. Cada iteración puede llevar a una versión mejorada del sistema.

* `Implementación y Mantenimiento` Cuando el sistema satisface plenamente los requisitos, se procede a
la implementación final. El mantenimiento continuo se realiza según sea necesario.
> Este enfoque combina los beneficios de la metodología orientada a objetos, que se centra en la
> reutilización de código y la encapsulación, con el enfoque iterativo y de gestión de riesgos del modelo
> espiral. Permite una adaptación ágil a los cambios en los requisitos y la obtención de un producto de
> software de alta calidad en etapas sucesivas.

---
 ### 7. Cuatro principios que rigen el desarrollo ágil expresados en el maninifiesto Ágil
 
1. `Individuos e interacciones sobre procesos y herramientas` Se enfatiza la importancia de las personas y
su colaboración en el proceso de desarrollo. Es decir, poner a las personas en el centro y priorizar la
comunicación directa sobre las herramientas y los procesos.

2. `Software funcionando sobre documentación exhaustiva` Se destaca la importancia de entregar
software funcional y de alta calidad en lugar de dedicar excesivo tiempo a la documentación detallada.
Aunque la documentación es necesaria, no debe ser una carga excesiva.

3. `Colaboración con el cliente sobre negociación de contratos` Se fomenta la colaboración cercana con
el cliente en lugar de depender de contratos y acuerdos rigurosos. La comunicación constante con el
cliente permite adaptarse a los cambios y satisfacer sus necesidades de manera efectiva.

4. `Responder al cambio sobre seguir un plan` Se reconoce que los requisitos y las circunstancias pueden
cambiar, y se valora la capacidad de adaptación del equipo de desarrollo. En lugar de aferrarse a planes
rígidos, se debe responder de manera flexible a los cambios a lo largo del proyecto.

---

### 8. Historia de usuario
Es una `representación de un requisito` escrito en una o dos frases
utilizando el lenguaje común del usuario.
Son **utilizadas en las metodologías de desarrollo ágiles** para la especificación de requisitos (acompañadas de
las discusiones con los usuarios y las pruebas de validación).
Cada historia de usuario debe ser **limitada**, esta debería poderse escribir sobre una nota adhesiva pequeña. Dentro de
la metodología XP las historias de usuario deben ser escritas por los usuarios.

Son una forma rápida de administrar los requisitos de los usuarios sin
tener que elaborar gran cantidad de documentos formales y sin requerir de mucho tiempo para
administrarlos. 
> Las historias de usuario permiten responder rápidamente a los requisitos
> cambiantes.

> [Historisa de usuario.Wikipedia](https://es.wikipedia.org/wiki/Historias_de_usuario)

* * * 

Lean Software Development (Desarrollo de Software Lean) se basa en los principios de Lean
Manufacturing y Lean Thinking y tiene como objetivo eliminar el desperdicio, mejorar la eficiencia y
entregar un software de alta calidad. Los principios que rigen Lean Software Development incluyen la
eliminación de desperdicio, la amplificación del aprendizaje, la toma de decisiones tardías, la entrega
rápida, el respeto a las personas, la optimización de todo el proceso y el incremento de la integridad del
software.

> En resumen, busca crear un proceso de desarrollo más eficiente y orientado
> a entregar valor al cliente, eliminando desperdicio, fomentando la colaboración y la mejora continua, y
> priorizando la entrega rápida y de alta calidad del software.

> [Lean Software](https://es.wikipedia.org/wiki/Lean_software_development)

---

### 9. Ventajas e inconvenientes de tener una pizarra web digital para la metodología Kanban.

`Ventajas`
* Accesibilidad: Puedes acceder a la pizarra digital desde cualquier ubicación con conexión a internet, lo
que facilita el trabajo remoto y la colaboración en equipos distribuidos.

* Colaboración en tiempo real: Varios miembros del equipo pueden ver y actualizar la pizarra Kanban al
mismo tiempo, lo que mejora la colaboración y la visibilidad del trabajo en curso.

* Facilita la gestión del flujo de trabajo: Las tarjetas se pueden mover con facilidad entre columnas para
reflejar el progreso y cambiar las prioridades, lo que ayuda a mantener el flujo de trabajo en movimiento.
Automatización: Algunas herramientas de pizarra web digital ofrecen automatización de tareas, como
notificaciones y recordatorios, que ayudan a mantener el equipo informado y en sincronización.

* Historial y seguimiento: Se registra un historial de cambios, lo que permite hacer un seguimiento de la
evolución de las tareas y facilita el análisis de métricas y el proceso de mejora continua.

`Inconvenientes`
* Dependencia de la tecnología: Las pizarras web digitales requieren una conexión a internet y dispositivos
compatibles, lo que puede generar problemas si hay interrupciones de red o si algunos miembros del
equipo no tienen acceso a la tecnología.

* Curva de aprendizaje: Puede llevar tiempo que los miembros del equipo se adapten a la nueva
herramienta, lo que puede afectar la productividad al principio

* Costo: Algunas herramientas de pizarra web digital pueden tener costos asociados, lo que puede ser una
consideración para equipos o empresas con presupuestos limitados.

* Personalización limitada: Algunas herramientas pueden tener limitaciones en cuanto a la personalización
de la pizarra, lo que podría no adaptarse a las necesidades específicas de ciertos equipos.

* Posible falta de tangibilidad: Para algunos, la sensación física de las tarjetas y tableros Kanban
tradicionales puede ser más tangible y satisfactoria, lo que podría perderse con una pizarra digital

> [trello](https://trello.com/es)

---

### 10. KANBAN y sus diferencias frente a SCRUM.


`Kanban`
* **Gestión Visual**: Utiliza tableros Kanban para visualizar el flujo de trabajo y las tareas en forma de
tarjetas.

* **Flexibilidad**: No tiene roles fijos ni un conjunto de reglas predeterminadas. Se adapta a las necesidades
del equipo.

* **Limitación del Trabajo en Curso (WIP)**: Establece límites en la cantidad de tareas permitidas en cada
columna del tablero para evitar la sobrecarga y mejorar el flujo.
Enfoque en el Flujo Continuo: Prioriza la entrega constante de trabajo en lugar de ciclos de tiempo
fijos.

* **No hay Sprints**: No tiene sprints ni planificaciones fijas. Las tareas se abordan según su prioridad.
  
* **Gestión del Cambio**: Permite cambios y ajustes en tiempo real.
  
* **Optimización del Flujo de Trabajo**: Busca la mejora continua a través de la eliminación de cuellos de
botella y la identificación de ineficiencias.

> [KANBAN.Definición](https://es.atlassian.com/agile/kanban)

`SCRUM`
* Roles Definidos: Tiene roles específicos, como Scrum Master, Product Owner y miembros del equipo.
Eventos Fijos: Utiliza eventos como Sprint Planning, Daily Standup y Sprint Review que siguen un
cronograma regular.

* Sprints: Trabaja en iteraciones de tiempo fijo llamadas sprints, generalmente de 2 a 4 semanas.
  
* Compromiso de Equipo: Los miembros del equipo se comprometen a entregar un conjunto específico
de funcionalidades dentro de un sprint.

* Priorización en el Sprint Planning: Las tareas se seleccionan y planifican al comienzo de cada sprint.
  
* Cambio Controlado: Los cambios en el sprint se limitan durante la iteración actual para mantener la
estabilidad.

* Reuniones Estructuradas: Se siguen reuniones específicas, como la Daily Standup, Sprint Review y
Sprint Retrospective.

> En resumen, Kanban se enfoca en la visualización del flujo de trabajo y la mejora continua sin roles ni
> eventos fijos, mientras que SCRUM tiene roles definidos, eventos regulares y sprints con entregas fijas al
> final de cada iteración. La elección entre ambas metodologías depende de las necesidades y la dinámica
> específica del equipo o proyecto.
> 
--- 

## SCRUM 

### Roles Clave

* `Product Owner` Representa al cliente y define los requisitos del producto.
  
*` Scrum Master` Facilita el proceso Scrum y elimina obstáculos para el equipo.

* `Equipo de Desarrollo` Realiza el trabajo para entregar el producto.
  
* `Backlog de Producto` El Product Owner crea una lista de requisitos priorizados llamada "Backlog de
  
Producto", que es la lista de tareas pendientes.

* `Planificación del Sprint` En una reunión de planificación de Sprint, el equipo selecciona un conjunto de
elementos del Backlog de Producto para trabajar durante el próximo Sprint (una iteración de tiempo fijo).

* `Sprint` Durante el Sprint, el equipo trabaja en las tareas seleccionadas con un objetivo claro.
Reuniones Diarias: Se llevan a cabo reuniones diarias de 15 minutos (Daily Standup) para mantener al
equipo informado sobre el progreso y discutir obstáculos.

* `Revisión del Sprint` Al final del Sprint, se realiza una revisión donde se muestra el trabajo completado y
se obtiene retroalimentación del cliente.

* `Retrospectiva del Sprint` El equipo reflexiona sobre el Sprint, identifica mejoras y ajusta su proceso.
Iteración: El ciclo se repite con nuevos elementos del Backlog de Producto en el siguiente Sprint.


> [Qué es Scrum](https://proyectosagiles.org/que-es-scrum/)
> [Còmo funciona Scrum](https://proyectosagiles.org/como-funciona-scrum/)

*SCRUM. Define los siguientes términos*

`Product Backlog` Lista priorizada de todos los elementos que
se deben desarrollar en un proyecto. Estos elementos pueden ser funcionalidades,
características, mejoras, correcciones o cualquier otro tipo de trabajo necesario para el
producto.
El Product Backlog se crea y mantiene a lo largo del proyecto, y el Product
Owner es el responsable de definir y priorizar estos elementos en función de su valor
para el cliente y el negocio. Los elementos más importantes y de alta prioridad se
encuentran en la parte superior del Product Backlog, mientras que los menos
importantes están en la parte inferior. Durante la planificación de cada Sprint, el equipo
selecciona un conjunto de elementos del Product Backlog para trabajar en el próximo
Sprint.

`Sprint Backlog` Lista de elementos seleccionados del Product Backlog
que el equipo se compromete a completar durante un Sprint específico. Durante la reunión de
planificación de Sprint, el equipo elige los elementos del Product Backlog que pueden ser
entregados dentro de la duración del Sprint. El Sprint Backlog es una lista más detallada que se
crea al desglosar los elementos en tareas y actividades concretas que se deben abordar durante el
Sprint. El equipo se compromete a completar todas las tareas del Sprint Backlog durante el
Sprint y no se deben agregar nuevos elementos durante el Sprint a menos que el equipo lo
acuerde.

*SCRUM. Sinónimos de:*
Jefe de proyecto.
Cliente.
Equipo de desarrollo.
Jefe de proyecto = "Product Owner".
Cliente = "Stakeholders"
Equipo de desarrollo = equipo de proyecto.

---

### Requisitos para poder utilizar Scrum


1. Formar un equipo Scrum con roles definidos: Product Owner, Scrum Master y Equipo de
Desarrollo.

2. Crear y mantener un Product Backlog que refleje el trabajo pendiente.
3. Dividir el proyecto en iteraciones llamadas Sprints, generalmente de 2 a 4 semanas de duración.
4. Antes de cada Sprint, seleccionar elementos del Product Backlog y crear un Sprint Backlog con
tareas específicas.
5. Realizar reuniones clave, como la Planificación de Sprint, la Reunión Diaria, la Revisión de
Sprint y la Retrospectiva de Sprint.
6. Mantener la transparencia en la información sobre el trabajo, el progreso y los obstáculos.
7. Colaborar estrechamente con el cliente o los stakeholders para definir y priorizar elementos del
Product Backlog.
8. Ser flexible y permitir cambios en los requisitos y prioridades.
9. Comprometer al Equipo de Desarrollo a completar las tareas del Sprint y asumir responsabilidad
por la calidad del trabajo.
10. Fomentar la mejora continua a través de la reflexión y la adaptación

[Requisitos para usar scrum](https://proyectosagiles.org/requisitos-de-scrum/)

---
## 11. Programación Extrema
`Valores de la Programación Extrema`

1. Comunicación: Promueve la comunicación constante entre el equipo y los stakeholders.
2. Simplicidad: Prioriza soluciones simples y funcionales.
3. Retroalimentación: Busca obtener retroalimentación constante del software.
4. Coraje: Implica tomar decisiones difíciles y asumir riesgos calculados.
5. Respeto: Fomenta el respeto mutuo y la diversidad de perspectivas en el equipo.

### Características distintivas de XP frente a otras metodologías ágiles

* Programación en Parejas: En XP, los programadores trabajan en parejas, lo que promueve la revisión constante del código, el
aprendizaje compartido y la mejora de la calidad.
* Desarrollo Dirigido por Pruebas (TDD): XP enfatiza la creación de pruebas antes de escribir el código, lo
que garantiza una mayor confiabilidad y calidad del software.
* Integración Continua: Se realiza una integración constante del código para detectar errores
tempranamente y mantener el software siempre en un estado funcional.
* Pequeñas Entregas Frecuentes: Aboga por entregas frecuentes de funcionalidades completas y
probadas, lo que permite obtener retroalimentación constante del cliente.
* Cliente en el Sitio: Se requiere la presencia frecuente del cliente o representantes para facilitar la
comunicación y la toma de decisiones rápidas.
* Planificación de Juego: Se utiliza una técnica de planificación llamada "planificación de juego" que
involucra al equipo y al cliente en la estimación y priorización de tareas.

[Características de la programación Extrema](http://www.davidvalverde.com/blog/introduccion-a-la-programacion-extrema-xp/)

---

# 12. Lenguajes de programación

## Diferencias entre lenguajes declarativos e imperativos.
 `Declarativos`
 Enfoque: Los lenguajes declarativos se centran en "qué" se debe lograr y describen el resultado
deseado, pero no especifican cómo lograrlo.

> Ejemplos:

> *  SQL (Structured Query Language): Se utiliza para realizar consultas y
> manipular bases de datos. Los usuarios especifican qué datos desean recuperar
> o modificar, pero no cómo realizar la operación.
> * HTML (Hypertext Markup Language): Se utiliza para crear páginas web. Los
> diseñadores declaran la estructura y el contenido de una página, pero no
> controlan la lógica de la interacción.

`Lenguajes Imperativos`
Enfoque: Los lenguajes imperativos se centran en "cómo" se deben realizar las acciones. Los
programadores especifican una serie de pasos detallados para alcanzar un resultado.

> Ejemplos:

> * C: Un lenguaje de programación imperativo ampliamente utilizado que se
> utiliza para escribir programas de bajo nivel. Los programadores especifican
> las instrucciones paso a paso.
> * Python: Aunque Python es un lenguaje de alto nivel y admite programación
> declarativa en ciertos casos, generalmente se considera un lenguaje imperativo.
> Los programadores indican cómo se deben realizar las tareas mediante
> instrucciones secuenciales.

>> En resumen, la principal diferencia radica en la forma en que se aborda la programación.
>> Los lenguajes `declarativos` se centran en los resultados deseados sin preocuparse por los detalles de implementación,
>> mientras que los lenguajes `imperativos` se centran en las instrucciones detalladas sobre cómo lograr un
>> resultado.
>> 
---
 
## Compilar e interpretar

`Compilar` es el proceso de traducir el código fuente de un programa (escrito por el
programador en un lenguaje de alto nivel) a un código objeto o ejecutable (en lenguaje de
máquina) que la computadora puede entender y ejecutar. El resultado es un archivo
ejecutable que se puede ejecutar sin necesidad del código fuente original. Ejemplos de
lenguajes compilados incluyen C, C++ y Java.

`Interpretar` es el proceso de ejecutar un programa línea por línea utilizando un intérprete. En
lugar de compilar previamente el código fuente, el intérprete traduce y ejecuta el código a medida que se
lee. Esto significa que el código fuente original se necesita cada vez que se ejecuta el programa.
Ejemplos de lenguajes interpretados incluyen Python, JavaScript y Ruby

### Ventajas de los lenguajes compilados.

* Mayor Velocidad de Ejecución: Los programas compilados suelen ser más rápidos en la
ejecución, ya que el código se traduce a lenguaje de máquina de antemano, eliminando
la necesidad de traducción en tiempo real.

* Mayor Optimización: Los compiladores pueden realizar optimizaciones avanzadas en el código,
lo que resulta en un rendimiento más eficiente.

* Mayor Privacidad del Código Fuente: Dado que el código fuente original se traduce a un formato
que no es legible por humanos, se protege la propiedad intelectual y la privacidad del código.

* Portabilidad: Los programas compilados pueden ejecutarse en diferentes plataformas si se
compilan para cada una de ellas.

* Menor Dependencia del Entorno de Ejecución: Los programas compilados suelen requerir menos
dependencias del entorno en comparación con los lenguajes interpretados.

* Detección de Errores en Etapa Temprana: Los errores de programación se detectan durante la
fase de compilación, lo que facilita la corrección antes de la ejecución.

* Ejecución Offline: Una vez compilado, el programa puede ejecutarse sin necesidad de acceso al
código fuente o a un intérprete.

### Ventajas de los lenguajes interpretados.

* Portabilidad: Los programas escritos en lenguajes interpretados son altamente portátiles, ya que el código
fuente se puede ejecutar en múltiples plataformas sin necesidad de recompilación.

* Facilidad de Desarrollo: La escritura y prueba de código es más rápida y sencilla en lenguajes
interpretados, lo que acelera el desarrollo de software.

* Depuración Interactiva: Los lenguajes interpretados suelen ofrecer herramientas de depuración
interactivas que facilitan la identificación y corrección de errores en tiempo real.

* Flexibilidad: Los cambios en el código fuente se reflejan inmediatamente, lo que facilita la adaptación a
requisitos cambiantes o pruebas rápidas de concepto.

* Mayor Legibilidad del Código Fuente: El código fuente en lenguajes interpretados suele ser más legible
para los programadores, lo que facilita la colaboración y el mantenimiento del software.

* Interoperabilidad: Los lenguajes interpretados suelen ser excelentes para la integración con otros
sistemas y lenguajes.

* Menos Recursos del Sistema: Los programas interpretados a menudo requieren menos recursos de
hardware en comparación con los compilados.

> Ejemplos lenguajes compilados e interpretados
>> Compilados:C y C++
>> Interpretados: PHP y Python

---

### ¿Puede considerarse código objeto el bytecode generado en Java tras la compilación? Explica la respuesta.
Sí, el bytecode generado en Java tras la compilación puede considerarse una forma de
código objeto. En Java, el código fuente se compila en bytecode en lugar de código de
máquina directamente ejecutable. El bytecode es un código intermedio que está
diseñado para ser ejecutado por la Máquina Virtual de Java (JVM) en lugar de la
arquitectura específica de una máquina.

### Ejemplos de lenguajes por niveles
`Bajo nivel` Ensamblador

`Nivel medio` C

`Alto nivel` Java

---

## Ejemplos de diferentes paradigmas de programación en estos lenguajes



`C`Principalmente imperativo y estructurado, con ciertas características de bajo nivel
que permiten programación procedural.

`C++` Combina programación orientada a objetos (POO) con programación imperativa y
estructurada.

`SQL` Lenguaje de consulta de bases de datos, centrado en el paradigma declarativo.
Java: Principalmente orientado a objetos (POO), con soporte para programación imperativa.
JavaScript: Orientado a objetos, pero también admite programación funcional y orientada a
eventos.

`Lisp`Conocido por ser un lenguaje de programación funcional, pero también admite
programación orientada a objetos.

`Prolog` Paradigma principal es la programación lógica, específicamente lógica inductiva

[Paradigma de programación](https://es.wikipedia.org/wiki/Paradigma_de_programaci%C3%B3n)

---

## Criterios a la hora de elegir un lenguaje de de programación para el desarrollo software

* `Adecuación al Problema`  El lenguaje debe ser apropiado para la naturaleza del problema a resolver. Algunos lenguajes son mejores para aplicaciones web, mientras que otros son más adecuados para el
procesamiento de datos o la programación de sistemas.

* `Experiencia del Equipo` Si el equipo de desarrollo tiene experiencia en un lenguaje en particular, puede
ser más eficiente utilizar ese lenguaje.

* `Rendimiento` Algunas aplicaciones requieren un alto rendimiento, por lo que la elección del lenguaje
puede depender de su capacidad para optimizar el rendimiento.

* `Disponibilidad de Bibliotecas y Frameworks` La disponibilidad de bibliotecas y frameworks puede
acelerar el desarrollo. Es importante elegir un lenguaje compatible con las herramientas que se necesitan.

* `Seguridad` Si la seguridad es una preocupación importante, es crucial seleccionar un lenguaje con
características de seguridad robustas y buenas prácticas de seguridad.

* `Portabilidad` Si se requiere que la aplicación se ejecute en múltiples plataformas, es importante
considerar la portabilidad del lenguaje.

* `Comunidad y Soporte` La comunidad de usuarios y el soporte en línea pueden ser valiosos para resolver
problemas y obtener ayuda.

* `Costo` Algunos lenguajes y herramientas son de código abierto y gratuitos, mientras que otros pueden
requerir licencias costosas.

* `Escalabilidad` Si se espera que la aplicación crezca con el tiempo, es importante elegir un lenguaje que
sea escalable y pueda manejar aumentos en la carga de trabajo.

* `Facilidad de Mantenimiento` La legibilidad del código y las buenas prácticas de programación pueden
facilitar el mantenimiento a largo plazo
