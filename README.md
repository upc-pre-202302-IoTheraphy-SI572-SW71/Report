## Capítulo VI: Product Implementation, Validation & Deployment
### 6.1. Software Configuration Management.
A continuación, se presentan las decisiones y convenciones que permitirán al equipo mantener la consistencia durante el ciclo de vida de desarrollo de nuestra solución.

#### 6.1.1. Software Development Environment Configuration.
En esta sección se incluye los links de las aplicaciones, productos de software realizadas durante el ciclo del proyecto en los programas que se utilizaron. 
Para ello se clasificará en las siguientes secciones:
<li> Project Management
<li> Requirements Management
<li> Product UX/UI Design 
<li> Software Development
<li> Software Testing
<li> Software Documentation
  
Y clasificar los elementos de las secciones si es ruta de referencia (para software basado en modelos SaaS) o ruta de descarga (para productos que se ejecutan en el computador del miembro del equipo) de cada uno de los productos de software. 

**Project Management**<br>
Es la disciplina basada en la gestión de los proyectos, la cual tiene como objetivo principal mejorar los procesos y su entorno para alcanzar los resultados esperados.
<li> En el ciclo digital del proyecto se implementará un producto software con un modelo SaaS que se ejecutará a través de un navegador; sin embargo, no se creará su versión de aplicación móvil.

**Requirements Management**<br>
Es el proceso de garantizar que una organización documente verifique y satisfaga las necesidades, expectativas de sus clientes con las partes interesadas internas o externas.
<li> Pivotal Tracker: Esta herramienta se define como una plataforma en la que se realiza la gestión de user stories, agrupándoles en epics y clasificando su presencia en el programa, por puntaje. Se usó porque permite que cada miembro del equipo comparte la misma vista en tiempo real de lo que está sucediendo con cada proyecto, ya sea aportando con diferentes secciones o corrigiendo el flujo del proyecto. 

**Product UX/UI Design**<br>
Esta herramienta permite desarrollar el modelo en nuestro producto de manera digital y forme parte de la vida del consumidor.  En este caso realizar un modelo de sitio web para computadoras y celulares.<br>
<li> Uxpressia: es una herramienta en línea para el mapeo de la trayectoria del cliente que crea mapas de impacto y personas. Sus herramientas nos permitieron establecer las bases del modelado de User Persona, Empathy Map y Journey Map.<br>
https://uxpressia.com/ <br><br>
<li> MIRO: es una pizarra digital colaborativa en línea, que puede ser usada para la investigación, la ideación, la creación de lluvias de ideas, mapas mentales y una variedad de otras actividades colaborativas.<br>
https://miro.com/app/dashboard/ <br><br>
<li> Figma: es una herramienta de prototipo web y editor de gráficos vectorial, que, a diferencia de las otras herramientas, se aloja en la web, permitiendo establecer los modelos para versión en Web Browser y Mobile Browser.<br>
https://www.figma.com/design/ <br><br>
<li> Lucid Chart: es una herramienta de diagramación basada en la web, que permite a los usuarios colaborar y trabajar juntos en tiempo real, creando diseños UML, mapas mentales, prototipos de software y muchos otros tipos de diagrama.<br>
https://lucid.app/lucidchart/ <br><br>
<li> Overflow: es una herramienta de diagramación que otorga la posibilidad de trabajar de manera colaborativa en tiempo real. Con este artefacto creamos los diagramas de los Userflows. <br>
https://userflow.com/app/ <br><br>

**Software Development**<br>
Es una estructura aplicada al desarrollo de un producto de software. Se utiliza para el establecimiento de un proceso para el desarrollo de software, cada uno de los cuales describe un enfoque diferente para diferentes actividades que tienen lugar durante el proceso.
<li> Github: Es un repositorio comunitario cuya función es almacenar los avances de un proyecto elaborado por un grupo de personas. <br> 
https://github.com/DigitAlholics-3-0<br><br>
<li> Web Storm: Es un entorno de JetBrains, empresa desarrolladora de Software, orientado en el desarrollo web en JavaScript. Este nos ofrece facilidad en probar nuestro entorno web en navegadores como Google. Para el proyecto se implementará la ayuda de los lenguajes HTML, CSS y JavaScript.<br>
https://www.jetbrains.com/webstorm/promo/?source=google&medium=cpc&campaign=9641686239&term=webstorm&gclid=CjwKCAjwv-GUBhAzEiwASUMm4ncU-aP3HPxUWVYTPMthApgSMowOvvfEAoJMFvwf1O_gQdv0HtWOrhoCdacQAvD_BwE <br><br>
<li> HTML: Es un lenguaje que sirve como desarrollador de plataformas web que trabaja con hipertextos, que enlace a otros documentos. Este lenguaje ofrece herramientas para el diseño del sitio web. Asimismo, la disponibilidad de trabajar HTML junto con CSS y JavaScript. Este lenguaje será utilizado en el presente proyecto para implementar la documentación de la página web.<br>
https://www.jetbrains.com/help/webstorm/editing-html-files.html <br><br>
<li> CSS: Es un lenguaje de diseño para el entorno web. Permite elaborar el interfaz de usuario diseñada anteriormente, agregando colores, tamaños entre otros elementos. Además, se puede diseñar un estilo en CSS y compartirlo en el web elaborado en HTML. Este lenguaje se utilizará para la implementación del diseño de nuestra plataforma web.<br>
https://www.jetbrains.com/help/webstorm/style-sheets.html#ws_css_completion <br><br>
<li> JavaScript: Es un lenguaje de programación que es analizado por otros programas. Este trabaja en POO (programación orientada en objetos) para prototipos sin implementación con clases. Este programa permite realizar dinámicas para el usuario a través de la lógica de la programación. Se utilizará para la elaboración de las dinámicas de la plataforma web.<br>
https://www.jetbrains.com/help/webstorm/javascript-specific-guidelines.html <br><br>

**Software Testing**<br>
Es el acto de examinar los artefactos y el comportamiento del software bajo prueba mediante validación y verificación.
<li> Lenguaje Gherkins: Es un DSL o Lenguaje Específico de Dominio (Domain-Specific Languaje), es decir, un lenguaje que está creado para resolver un problema. Además de ser interpretado en código, se puede agregar los users stories del programa con sus respectivas partes: Feature, Scenario, Example, Scenario Outline, Given, When, Then y And.

**Software Documentation**<br>
Es un tipo de texto escrito o ilustración que acompaña al software de computadora o está incrustado en el código fuente. La documentación explica cómo funciona el software o cómo usarlo.

#### 6.1.2. Source Code Management.
A continuación, se presenta la gestión de código fuente o como es conocido por sus siglas en ingles SCM (Source Code Management). Su función principal es realizar un seguimiento de las modificaciones que el equipo realizara a lo largo del desarrollo de sus proyectos en los repositorios de código fuente. Se empleará como un sistema de control de versiones que permite dar seguimiento a los cambios que cada integrante o desarrollador realice en el proyecto. Asimismo, cabe resaltar que para el sistema de control de versiones emplearemos GitHub.

URL de la Organización: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71 <br>
URL del Repositorio del Landing Page: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/IoTheraphy-LandingPage <br>
URL del Repositorio del Frontend: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Web-Theraphy <br>
URL del Repositorio del Backend: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/API-IoTheraphy <br>

**GitFlow** <br>
Es el modelo alternativo de creación de ramas en Git que en los últimos años se ha vuelto una herramienta indispensable para muchos desarrolladores. Este flujo de trabajo de control de versiones utiliza ramas y fue publicado y popularizado por Vincent Driessen. Su principal función es ayudar en la organización de la versión de un código, permitiendo la creación de nuevos Features y Hotfixes de manera organizada. <br>

<img src="https://c1.staticflickr.com/6/5293/5488984404_4f693eec32_b.jpg" width="550"><br>

Como se mencionó anteriormente, GitFlow trabaja con branches o ramas. A continuación, se muestran las ramas que se emplearan en el flujo de trabajo de nuestro proyecto.<br>

**Main Branches**<br>
    	<li> Master: es la rama principal, a partir de ella se recorrerán todas las ramas y contendrá la última versión y las anteriores creadas por los desarrolladores. Almacenara el historial de publicación oficial.
      <li> Develop: Esta rama puede ser creada a partir de la master Branch, contara con todos los Features estables. Esto significa que a través de esta rama el equipo podrá integrar las funciones. 

**Support Branches** <br>
A diferencia de las ramas principales, estas branches tienen un tiempo de vida limitado, ya que se eliminar al realizar el merge con sus ramas primarias.<br>
<li> Feature: <br>
      Se ramifica de: develop<br>
      Debe fusionarse de nuevo en: develop<br><br>
                                        
Se emplean para desarrollar las nuevas funciones que se integraran en una versión siguiente. Cabe resaltar, que esta rama existe mientras este en proceso de desarrollo. Sin embargo, cuando el desarrollador culmine con esa función, se fusionará nuevamente a develop. 

**Convenciones para nombrar los Features:** <br><br>
**Feature Branch:** feature/name <br>
**Example:** <br>
<li> feature/welcome, 
<li> feature/about, 
<li> feature/myfeature

**Conventional Commits** <br><br>
El commit debe estructurarse de la siguiente manera:<br>
**<type>[optional scope]: <description>** <br>
**[optional body]** <br>
**[optional footer(s)]** <br><br>
Cabe recalcar que debe estar en “lower case”.

**Type:** <br>
feat: Cuando se agrega un nuevo feature.<br>
fix: cuando corriges un error.<br>
build: cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.<br>
chore: modificaciones privadas del código.<br>
docs: commits que afectan solo a la documentación.<br>
refractor: commits que reescriben o reestructura el código, pero no cambia el comportamiento.<br>
perf: commits especiales que mejoran el rendimiento. <br>
style: commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).<br>
test: commits que agregan pruebas.<br><br>

**Scope**<br>
Proporciona información contextual adicional, si bien es opcional, es bueno colocarlo para que el desarrollador lea un commit más específico. <br><br>
**[description]** <br><br>
Es una parte obligatoria del formato de los commits, siempre debemos usar imperativo y no escribir en mayúsculas. <br><br>
**[optional body]** <br><br>
Debe incluirse la motivación para el cambio y contrastarse con el comportamiento anterior. Es opcional y si lo usa debe usar el imperativo y es ideal para mencionar los identificadores de problemas y sus relaciones.<br><br>
**[optional footer(s)]**<br><br>
Cualquier información sobre cambios importantes. Es opcional, puede incluir referencia al problema por su id y en esta sección se incluyen los BREAKING CHANGES: seguido de un espacio o dos satos de línea.<br><br>

Ejemplos:
<li> feat(welcome): add welcome section
<li> build(release): bump version to 1.0.0
<li> style: remove empty line
<li> feat(sign up): add the button to sign up
<li> feat ! : send an email to the costumer when product is shipped
<li> feat: remove ticket list endpoint

Asimismo, como ya se ha mencionado, la gestión de nuestro código fuente se realizará a través de GitHub. Los IDEs tilizados serán WebStorm y IntelliJ IDEA, estos deberán vincularse directamente con el repositorio creado por la empresa, Digitalholics. De esta manera, cada commit que realice un participante será subido y cargado directamente al GitHub de la organización. A continuación, se indicarán las pautas para realizar el proceso de vinculación de manera correcta: <br><br>

**Compartir Proyecto al Repositorio Github** <br><br>
Dado que se empleará GitHub para esta gestión, debemos crear el proyecto y luego subirlo al repositorio respectivo en Github. Para realizar esto, debe dirigirse a la pestaña de ‘GIT’ dentro de WebStorm. Después, seleccionar la opción de ‘Manage Remotes’ y luego la opción ‘+’.<br>

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ide%20config.jpg" width="550"><br><br>

Seguidamente añadimos el url del repositorio respectivo en Github.<br>

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ide%20config%202.jpg" width="550"><br><br>

A continuación, seleccionamos el botón de felcha verde en la parte superior para realizar Push el proyecto hacia la rama master del repositorio.<br>

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ide%20config%203.jpg" width="550"><br><br>

Ahora el proyecto esta en la rama master de nuestro repositorio en github.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ide%20config%204.jpg" width="550"><br><br>

#### 6.1.3. Source Code Style Guide & Conventions.
En esta sección se mostrarán las pautas, convenciones, estilos y principios que se utilizarán para cada uno de los lenguajes que se emplearán en la creación de nuestra aplicación, Theraphy. La práctica de este conjunto de reglas es de suma importancia, ya que estas tienen el propósito de conservar la calidad estructural del software, dar una mayor legibilidad al código fuente y facilitar el mantenimiento del código.

Dado que en este proyecto se utilizarán HTML, CSS, JavaScript, Java y TypeScript parala codificación de la plataforma web y Gherkins para el proceso de prueba del programa; a continuación, se nombrarán y describirán las reglas y recomendaciones generales que tomaremos en cuenta al momento de usarlos.

**Nomenclatura General**<br>

A los nombres de las variables, objetos, elementos y funciones que se utilicen, se les designarán términos en inglés que estén relacionados y puedan describir a lo que están representando. No se usarán mayúsculas porque de acuerdo con W3Schools (s.f.), la mezcla de estas con las letras minúsculas luce mal y, además, el uso exclusivo de minúsculas otorga mayor legibilidad al código.

Ejemplo de nomenclatura estándar según Google (s.f.):

.gallery {}<br>
.video {}<br>
.login {}<br>

**HTML**<br>
Llamado así por las siglas del nombre en inglés HyperText Markup Language. HTML es un lenguaje de marcado que define la estructura de una página web. Además, cuenta con funciones capaces de determinar el comportamiento de distintas partes del contenido de la página, tales como el cambiar el tamaño del texto, aplicar cursiva, entre otros. Nosotros emplearemos HTML5, y las características y pautas a seguir para hacer uso de este lenguaje son las siguientes:

<li> Declare Document Type<br>
El tipo de documento debe declararse en la primera línea de código. De acuerdo con Google (s.f.) HTML5 es de preferencia la mejor sintaxis para todo documento HTML, para declararla sólo es necesario copiar lo siguiente:

    <!DOCTYPE html> 

<li> Blank Lines<br>
Cada vez que, luego de un bloque, lista o tabla de gran longitud se inicie uno nuevo, se debe saltar la siguiente línea y dejarla en blanco para brindar mayor legibilidad y amenidad, así manifiesta W3Schools (s.f.).  

Ejemplo:
    <body>
    
    <h1>Famous Cities</h1>
    
    <h2>Tokyo</h2>
    <p>Tokyo is the capital of Japan, the center of the Greater Tokyo Area, and the most populous metropolitan area in the world.</p>
    
    <h2>London</h2>
    <p>London is the capital city of England. It is the most populous city in the United Kingdom.</p>
    
    <h2>Paris</h2>
    <p>Paris is the capital of France. The Paris area is one of the largest population centers in Europe.</p>
    
    </body>
    
<li> Quote Attribute Values<br>
Para los valores de los atributos se utilizan comillas dobles alrededor. De acuerdo con W3Schools (s.f.) Aunque esta característica no sea obligatoria, le da más legibilidad al código y es muy frecuente entre los desarrolladores.

Ejemplo:

    <table class="striped">

<li> Multimedia Fallback<br>
Asegurar un acceso alterno a los objetos multimedia por si este fallara al cargar. De la misma forma, según la W3Schools (s.f.), es recomendable añadir las dimensiones del elemento porque así los navegadores guardan el espacio que utilizará antes de comenzar a cargarlo.

Ejemplo:

    <img src="html5.gif" alt="HTML5" style="width:128px;height:128px">
    
**CSS** <br>
Llamado así por las siglas del nombre en inglés Cascading Style Sheets. CSS es un lenguaje de marcado que se centra en definir y mejorar la presentación de un documento que se basa en HTML. Las pautas que a seguir al momento de usar CSS son las siguientes:<br>
  
<li> Shorthand Properties<br>
Hay que utilizar abreviación de propiedades, declarar los campos de los elementos en la menor cantidad de líneas posibles. De acuerdo con Google (s.f.), esto aumenta la eficacia del código y lo hace más entendible. De la misma manera, debemos evitar el colocar las unidades luego del valor cero.<br>

Ejemplo:

    border-top: 0;
    font: 100%/1.6 palatino, georgia, serif; 
    padding: 0 1em 2em;

<li> Declaration Stops<br>
Hay que colocar un punto y coma luego de cada declaración al igual que gran parte de lenguajes de programación. Según Google (s.f.). esta característica ayuda a que haya más consistencia en el código. <br>

Ejemplo:

    html {
      background: #fff;
      color: #404;
    }

    
<li> Property Name Stops<br>
Debe existir un espacio entre los dos puntos que están luego del nombre de una propiedad y el valor ingresado. Siempre solo un espacio luego de los dos puntos, mas no antes.<br>

Ejemplo estándar según Google (s.f.):
    
    html {
      background: #fff;
      color: #404;
    }

<li> Declaration Block Separation<br>
El uso de un separador de un espacio es necesario luego del nombre de un elemento seleccionado y la llave que inicia un bloque. Además, esta llave tiene que estar en la misma línea.<br>

Ejemplo estándar según Google (s.f.):
    
    html {
      background: #fff;
      color: #404;
    }

**JavaScript** <br>
Es un lenguaje de programación que otorga la posibilidad de indicar exactamente las acciones que debe ejecutar el navegador, indicando el orden de las tareas y el número de veces que se realizarán. Las indicaciones para usar JavaScript en nuestro proyecto son las siguientes:

<li> Spaces around operators<br>
Se debe colocar un espacio alrededor de cada operador matemático que se introduzca en el código. Esto también aplica a las comas.

Ejemplo estándar según W3Schools (s.f.):

    let x = y + z;
    const myArray = ["Volvo", "Saab", "Fiat"];

<li> Simple Statement’s End<br>
Una indicación simple debe terminar en un punto y coma, esto se cumple también en muchos otros lenguajes de programación.

Ejemplo estándar según W3Schools (s.f.):

    let x = y + z;
    const myArray = ["Volvo", "Saab", "Fiat"];
    
<li> Beginning and End of a Function<br>
Un bloque de función debe contar con una llave al final de la primera línea, para que el cierre de esta se encuentre sola en la última. Una función termina en llave y no en punto y coma. Lo mismo aplica para condicionales o bucles.

Ejemplo estándar según W3Schhol (s.f):

    function toCelsius(fahrenheit) {
      return (5 / 9) * (fahrenheit - 32);
    }

<li>	Object Rules<br>
Para la construcción de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea, pero, esta vez, la llave de cierre debe estar acompañada de un punto y coma. Para las propiedades, se colocan dos puntos y un espacio para indicar su valor, el cual debe estar entre comillas dobles si este es un string.

Ejemplo estándar según W3School (s.f.):

    const person = {
      firstName: "John",
      lastName: "Doe",
      age: 50,
      eyeColor: "blue"
    };

**Gherkin** <br>
Es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que tiene como objetivo la resolución de un problema en específico. Para ello, se generan casos para la validación de la característica en distintos escenarios. Gherkin cuenta con múltiples elementos, de los cuales, los más famosos y, además, más utilizados son Feature, Scenario, Example, Scenario, Given, When y Then. Las indicaciones para tomar en cuenta en el uso de Gherkin en nuestro código son las siguientes.

<li> Discernible Given-When-Then Blocks<br>
Aplicar sangría para los elementos que indiquen pasos a seguir del escenario. En el caso de And, aplicar dos veces. De acuerdo con Keiblinger (2021), Esto ayuda a detectar rápidamente las partes que forman un escenario.

Ejemplo:

    Scenario: Ingreso los requisitos con claridad
        Given que en el formulario de ingreso de oferta laboral
        When escribo claramente los requisitos
        Then se mostrará el mensaje 
        And mi oferta solo aparecerá a quienes cumplan con estos      
        And se habilita la opción

<li> Step with Tables<br>
Según Keiblinger (2021), para las partes del escenario que necesiten la introducción de valores, hay que agregar una tabla o crear un propio formulario que recree esa parte del escenario. Antes de esta representación se deben colocar dos puntos. 

Ejemplo:

        Then se mostrará el mensaje:
    | mensaje                                          |                        
    | Se completaron los requisitos adecuadamente      | 

<li> Scenarios Separator<br>
Para la separación de dos escenarios, se debe insertar un salto de línea y, según Keiblinger (2021), de ser posible, hay que agregar una línea de comentario para facilitar la visualización de estos. De esta forma se halla rápidamente el inicio y fin de un escenario.

Ejemplo:

          #-----------------------------------------------------------------------------------
    Scenario: Ingreso los requisitos con claridad
        Given que en el formulario de ingreso de oferta laboral
        When escribo claramente los requisitos
        Then se mostrará el mensaje 
        And mi oferta solo aparecerá a quienes cumplan con estos      
        And se habilita la opción
 
          #-----------------------------------------------------------------------------------
    Scenario: Ingreso los requisitos con claridad
        Given que en el formulario de ingreso de oferta laboral
        When escribo claramente los requisitos
        Then se mostrará el mensaje 
        And mi oferta solo aparecerá a quienes cumplan con estos      
        And se habilita la opción

**Java**<br>
Java es una plataforma informática de lenguaje de programación creada por Sun Microsystems en 1995. Ha evolucionado desde sus humildes comienzos hasta impulsar una gran parte del mundo digital actual, ya que es una plataforma fiable en la que se crean muchos servicios y aplicaciones. Las indicaciones para usar Java en nuestro proyecto son las siguientes:

<li> Clases e interfaces en Java<br>
Los nombres de las clases deben ser sustantivos, en mayúsculas y minúsculas, con la primera letra de cada palabra interna en mayúscula. El nombre de las interfaces también debe estar en mayúscula (la primera) al igual que los nombres de las clases. Use palabras completas y debe evitar acrónimos y abreviaturas.
  
Ejemplo: 

    Interface  Bicycle
    Class MountainBike implements Bicyle
    Interface Sport
    Class Football implements Sport

<li>	Métodos en Java<br>
Los métodos deben ser verbos, en mayúsculas y minúsculas, con la primera letra de cada palabra interna (a partir de la segunda) en mayúscula.

Ejemplo:

    void changeGear(int newValue);
    void speedUp(int increment);
    void applyBrakes(int decrement);

<li> Variables en Java<br>
Los nombres de las variables deben ser cortos pero significativos.
No debería comenzar con un guión bajo (‘_’) o caracteres, como por ejemplo, un signo de dólar ‘$’.
Debe ser mnemotécnico, es decir, diseñado para indicar al observador casual la intención de su uso.
Se deben evitar los nombres de variable de un carácter, excepto para variables temporales.
Los nombres comunes para las variables temporales son: i, j, k, m y n para enteros; c, d y e para los caracteres.

Ejemplo:

    // variables para la clase MountainBike
    int speed = 0;
    int gear = 1;

<li> Excepciones:<br>
Excepto como se indica a continuación, muy rara vez es correcto no hacer nada en respuesta a una excepción detectada.
Cuando realmente es apropiado no realizar ninguna acción en un bloque catch, la razón por la que esto se justifica se explica en un comentario.
    
    try {
    int i = Integer.parseInt(response);
    return handleNumericResponse(i);
    } catch (NumberFormatException ok) {
    // it's not numeric; that's fine, just continue
    }
    return handleTextResponse(response);

<li> Excepción:<br> 
En las pruebas, una excepción detectada puede ignorarse sin comentarios si su nombre es o comienza con expected. El siguiente es un modismo muy común para garantizar que el código bajo prueba arroja una excepción del tipo esperado, por lo que no es necesario un comentario aquí.
  
  try {
  emptyStack.pop();
  fail();
  } catch (NoSuchElementException expected) {
  }

<li> @Override:<br>
Un método se marca con la @Overrideanotación siempre que sea legal. Esto incluye un método de clase que anula un método de superclase, un método de clase que implementa un método de interfaz y un método de interfaz que vuelve a especificar un método de superinterfaz.

<li> Excepción: @Override se puede omitir cuando el método principal es @Deprecated.

**Typescript** <br<
JavaScript es uno de los lenguajes más populares, en parte porque ha evolucionado y mejorado a pasos agigantados en los últimos años. Las indicaciones para usar Java en nuestro proyecto son las siguientes:<br>
Las variables en typescript deben ser declaradas en minúsculas y el tipo de dato se declara con dos puntos luego de la variable.<br><br>

Definicióin e inicialización separadas

    var edad: number;
    edad = 20;
    
Definición e inicialización en la misma línea.
    
    var edadAitor: number = 18
    
En TypeScript también se utilizan las convenciones son las mismas usadas en JavaScript.

#### 6.1.4. Software Deployment Configuration.
Como ya se ha mencionado, la gestión de nuestro código fuente se realizará a través de GitHub. Asimismo, se utilizará Github Pages para la publicación y despliegue de la página estática y sitio web.<br>
En el caso del Landing Page, en primer lugar, se debe ir al apartado de configuración. Luego, ir ala sección “Pages” para finalmente elegir la rama y desplegar la página.<br>

En el caso del FrontEnd, se deben realizar los siguientes pasos.<br>
<li> Realizar un Build de la versión final de tu proyecto.
<li> Haber hecho commit de todos los cambios realizados.
<li> Descargar última versión de GitPages en tu proyecto con el comando: npm install -g @angular/cli
<li> Añadir lo instalado a tu protecto con: ng add angular-cli-ghpages
<li> Por último, desplegar con el siguiente comando: ng deploy your-angular-project --base-href=/<repositoryname>/
  
En el caso del BackEnd, hosteamos una base de datos en RailWay y simplemente seleccionamos el repositorio a desplegar, el proceso es automático.


### 6.2 Landing Page, Services & Applications Implementation.
#### 6.2.1 Sprint 1
##### 6.2.1.1 Sprint Planning 1.
A continuación se presenta el Sprint Planning realizado para esta iteración.<br><br>

| Sprint #                              | Sprint 1                           |
|---------------------------------------|-----------------------------------|
| Sprint Planning Background             |                                   |
| Date                                  | 2023-08-26                        |
| Time                                  | 11:30 am                          |
| Location                              | Reunión virtual por Discord       |
| Prepared By                           | Luis Pineda, Cristhian Gómez      |
| Attendees (to planning meeting)       |                                   |
| - Arrieta Huaman Leonardo Santos      | - Pineda Ugás, Luis Alberto       |
| - Gómez De la Cruz, Cristhian Gabriel | - Ahuanari Murayari, Maria Alexandra |
| - Del Carpio Lopez, José Fabricio Jared  |    |
| Sprint 0 Review Summary               | No aplica                         |
| Sprint 0 Retrospective Summary        | No aplica                         |
| Sprint Goal & User Stories            |                                   |
| Sprint 1 Goal                         | Durante este sprint el equipo se encargará de desarrollar las User Stories establecidas para la Langin Page y el Web Application |
| Sprint 1 Velocity                     | 20 story points                    |
| Sum of Story Points                   | 19 story points                    |

<br><br>
##### 6.2.1.2 Sprint backlog 1

| Sprint # | Sprint 1 | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story | Work-item/Task | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Id | Tittle | Id | Tittle | Description | Estimation (Hours) | Assigned To | Status (To-do /In-Process /To-Review /Done) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183109786  | HU24: Información sobre las funciones para los pacientes  | TA01  | Añadir títulos  | Se añadirán títulos que indiquen las funciones con las que cuenta la aplicación para nuestros usuarios pertenecientes al segmento pacientes.  | 2 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir descripción  | Se añadirán párrafos que describan las funciones para los pacientes con más detalles.  | 3 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir imágenes  | Se añadirán imágenes representativas por cada función para paciente nombrada  | 3 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA04  | Añadir sección hero  | Añadir sección inicial en la que se describa brevemente a la plataforma.  | 3 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- |
| #183109788  | HU26: Información sobre las funciones para los fisioterapeutas  | TA01  | Añadir títulos  | Se añadirán títulos que indiquen las funciones con las que cuenta la aplicación para nuestros usuarios pertenecientes al segmento fisioterapeutas.  | 2 |  Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir descripción  | Se añadirán párrafos que describan las funciones para los fisioterapeutas con más detalles.  | 3 |  Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir imágenes  | Se añadirán imágenes representativas por cada función para fisioterapeuta nombrada  | 3 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA04  | Añadir botón de unirse  | Se añadirá un botón que traslade al fisioterapeuta a la aplicación web.  | 4 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- |
| #183109794  | HU28: Sección comentarios  | TA01  | Añadir cuadros para los testimonios  | Se añadirán 3 cuadros para mostrar los testimonios dados por pacientes usuarios de la aplicación.  | 2 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir comentarios   | Se añadirán los comentarios como tal en los cuadros correspondiente.  | 2 | Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir fotos de los comentarios  | Se añadirán las fotos de las pacientes que brindaron su comentario.  | 2 |  Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
| #183136085  | HU30: Desplazamiento en el sitio web estático  | TA01  | Añadir lista de etiquetas  | Se añadirán las etiquetas de Home, Services, Pricing, Testimonials y About Us correspondientes a las secciones dentro de la landing page  | 1 |  María Ahuanari | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Aplicar estilo de etiquetactiva  | Se aplicará la pseudo clase hover para mostrar qué etiquetas se encuentran activas.  | 2 |  María Ahuanari | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Vincular etiquetas con secciones   | Se vinculará las etiquetas a través de los id para facilitar el desplazamiento del usuario dentro de la landing page.  | 1 |  María Ahuanari | Done  |
| --- | --- | --- | --- | --- | --- |
| #183136086  | HU31: Canalesde contacto  | TA01  | Añadir íconos de redes sociales  | Se añadirán los íconos de las diferentes redes sociales utilzadas por Theraphy  | 1 |  María Ahuanari | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir enlace a los íconos  | Se añadirán los enlaces correspondientes a las cuentas de las redes sociales para que los usuarios puedan acceder fácilmente a ellas.  | 1 |  Cristhian Gómez | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir correo electrónico  | Se añadirá el correo para contacto con Theraphy  | 1 |  Cristhian Gómez | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA04  | Añadir dirección y número de teléfono  | Se añadirá la dirección y número telefónico de Teraphy  | 1 |  Cristhian Gómez | Done  |
| --- | --- | --- | --- | --- | --- |
| #183136087  | HU13: Reserva de consulta médica  | TA01  | Agregar botón de agendamiento de cita en el perfil de doctor  | Se agregará un botón que permita iniciar el proceso de reserva de cita médica  | 1  | Cristhian Gómez   | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir calendario de selección de fecha  | Se añadirá la vista de un calendario donde el usuario podrá seleccionar la fecha en que se realizará la cita médica.  | 2  | Jose Del Carpio | To Do  |
|     |     | TA03  | Añadir sección de pago de la reserva de cita médica  | Se añadirá una sección que el usuario rellenará con los datos de su tarjeta para realizar el pago de la cita médica   | 2   | María Ahuanari  | Done   |
| #183136088  | HU08:  Visualización de ejercicios   | TA01  | Agregar sección para la visualización de las sesiones de ejercicios  | Se añadirá una sección que presente los videos de ejercicios a realizar para cada tratamiento.  | 2  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02   | Añadir video de la sesión   | Se añadirá el video que contenga los ejercicios a realizar en la sesión que se ha seleccionado.   | 1  | Luis Pineda  | Done  |
|     |     | TA03  | Añadir botones de cambio de sesión  | Se añadirán los botones que permitan movilizarse a una siguiente sesión o a una anterior.  | 3  | Leonardo Arrieta  | Done  |
| #183136089 | HU09: Publicación de videos de ejercicios   | TA01  | Añadir sección para la publicación de un nuevo video de ejercicios  | Se agregará una sección que presenta el formulario para la publicación de un video de ejercicios  | 2  | Cristhian Gómez   | To-do  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183136090 | HU07: Búsqueda de tratamientos     | TA01  | Añadir sección de tratamientos  | Se añadirá una sección que presentará la lista de tratamientos publicados en la aplicación   | 2  | Jose Del Carpio  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir caja de búsqueda | Se añadirá un input que permita ingresar el nombre de un tratamiento | 2  | Jose Del Carpio  | Done  |
|     |     | TA03  | Agregar lista de resultados por coincidencia  | Se enlistarán cada uno de los tratamientos que coincidan con el nombre ingresado en la barra de búsqueda  | 3  | Jose Del Carpio  | Done  |
| #183136091 | HU18: Visualización de horario de consultas   | TA01  | Agregar lista de citas médicas agendas  | Se agregará una lista que muestre a todas las citas agendadas para el doctor  | 3  | Cristhian Gómez   | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir vista de detalles de cita médica    | Se añadirá una vista que presentará la información de cada cita médica reservada.  | 2  | Maria Ahuanari  | Done  |
| #183136092 | HU19: Envío de diagnóstico y recomendaciones     | TA01  | Añadir botón de nuevo diagnóstico  | Se añadirá un botón en la vista de una cita médica que permita iniciar el proceso de envío de diagnóstico a un paciente.  | 2  | Luis Pineda  | Done |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02 | Añadir caja de texto | Se añadirá input para ingresar el diagnóstico que se le brindará al paciente | 2  | Luis Pineda  | Done  |
| #183136093 | HU20: Visualización de los resultados de la consulta   | TA01  | Agregar botón | Se añadirá un botón que permita al usuario direccionarse a la vista de resultados de consultas médicas  | 2  | Leonardo Arrieta  | Done |
|     |     | TA02  | Añadir vista de los resultados de las consultas médicas  | Se añadirá una sección que presentará los resultados de cada consulta médica realizada.  | 3  | Leonardo Arrieta  | Done |
| #183136094 | HU21: Calificación de fisioterapeutas  | TA01  | Añadir título de reseñas  | Agregar título que indique que se presentarán las reseñas del profesional  | 1  | Cristhian Gomez  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir lista de reseñas dadas  | Mostrar las reseñas realizadas previamente al fisioterapeuta  | 2  | Cristhian Gomez  | Done  |
|     |     | TA03  | Añadir botón de nueva reseña  | Añadir botón que lleve al formulario de nueva reseña  | 1  | Cristhian Gomez  | Done  |
| #183109753  | HU01: Registro de cuenta  | TA01  | Añadir título  | Añadir título que indique que se encuentra en el registro  | 1  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir Input de nombre  | Añadir Input que permita ingresar el nombre con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA03  | Añadir Input de apellido  | Añadir Input que permita ingresar el apellido con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA04  | Añadir Input cumpleaños  | Añadir Input que permita ingresar el cumpleaños con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA05  | Añadir Input de rol  | Añadir Input que permita ingresar el rol con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA06  | Añadir Input email  | Añadir Input que permita ingresar el email con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA07  | Añadir Input de contraseña  | Añadir Input que permita ingresar la contraseña con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA08  | Añadir botón de registro  | Añadir botón que permita el registro y vuelva al login  | 1  | Luis Pineda  | Done  |
| #183136090  | HU32 Registro de usuario en la base de datos  | TA01  | Crear colección de la base de datos  | Crear una colección que contenga los datos de los usuarios  | 2  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Crear consulta  | Generar una consulta POST que añada un elemento a la colección  | 1  | Luis Pineda  | Done  |
| #183109755  | HU02: Inicio de sesión  | TA01  | Añadir título  | Añadir título que indique en qué vista se encuentra  | 1  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir Input de email  | Añadir un Input para el email y validarlo  | 2  | Luis Pineda  | Done  |
|     |     | TA03  | Añadir Input de contraseña  | Añadir un Input para la contraseña y validarlo  | 2  | Luis Pineda  | Done  |
|     |     | TA04  | Añadir botón de ingreso  | Añadir botón que ingrese a la plataforma  | 1  | Luis Pineda  | Done  |
| #183136092  | HU33: Obtención de credenciales de usuario  | TA01  | Realizar consulta  | Agregar una consulta GET que permita obtener las credenciales de los usuarios y comprobarlas en el login  | 3  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183109758  | HU03: Visualización de perfil  | TA01  | Añadir cuadro de datos  | Añadir un cuadro que contenga los datos principales del usuario como nombre, nacimiento, celular y correo  | 1  | Cristhian Gomez  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir foto del usuario  | Añadir la foto del usuario en el cuadro  | 2  | Cristhian Gomez  | Done  |
|     |     | TA03  | Añadir íconos  | Añadir íconos la información del usuario  | 1  | Cristhian Gomez  | Done  |
|     |     | TA04  | Añadir lista de opciones rápidas  | Añadir las opciones de visualizar mis sesiones, citas e historial médico.  | 2  | Cristhian Gomez  | Done  |
|     |     | TA05  | Vincular las opciones  | Vincular las opciones a sus respectivas vistas  | 3  | Cristhian Gomez  | Done  |
| #183136099  | HU34: Obtención de datos personales del usuario  | TA01  | Realizar consulta  | Realizar consulta GET que obtenga los datos de los usuarios de la base de datos  | 3  | Cristhian Gomez  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Guardar información  | Generar una variable que guarde los datos obtenidos del usuario para mostrarlos de manera ordenada en la vista  | 3  | Cristhian Gomez  | Done  |
|   |   |   |   |   |   |   |   |   |


##### 6.2.1.3 Development Evidence for Sprint Review

Para este segundo sprint, conseguimos desarrollar y desplegar las siguientes secciones de nuestra aplicación web:  Treatments, Treatments-info, Treatments-sessions, Physiotherpists, Physiotherpist-profile, Schedule-appointment, Payment, Appointments, Log-in y Sign-up

| **Repository** | **Branch** | **Commit ID** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
| --- | --- | --- | --- | --- | --- |
|    [https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Web-Theraphy](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Web-Theraphy)  | Feature/ physiotherapist-sidenav  | 2c72c073b139b17835797d6263196f7db4decac2  | feat(physiotherapists-sidenav)  | added sidenav to physiotherapists sections   | 20/09/2023 04:30 p.m     |
|  | --- | --- | --- | --- | --- |
|     | feature/ profile-Physiotherapist  | 790d7e823f8bd88729dcfa9530b06e377139feeb   |            feat(physiotherapists-profile)       |                                                                                        added physiotherapist profile section  | 20/09/2023 07:20 p.m    |
|  | --- | --- | --- | --- |
|     |     | 1f59ba0a92a86b5e3c30f41da6b878c36d5b6254  | feat(physiotherapists-profile-education)  | added education section to physiotherapist profile   | 21/09/2023 09:00 p.m     |
|  | --- | --- | --- |
|     | feature/ my-patients  | 4ccfe0f80a86413683f525db09bfd8048b6f968c  | feat(patients)  | added list of patients and filter function for physiotherapists   |  22/09/2023 09:10 p.m     |
|  | --- | --- | --- | --- |
|     |     | 203f638f1fd3e7a8b0a89edeb797bad13cbf5a64  | fix  |  routing fixed  |                   24/09/2023 09:40 p.m     |
|  | --- | --- | --- |
|     | feature/diagnosis  | 46e84895e7a28b77c05b975f39d4ab484e7dae74  | feat(diagnosis)  |  added diagnosis component  | 25/09/2023 04:40 p.m  |
|     |     | 087248f3e2a3ce9c53ec905978980f9699b8f6e3  | feat(diagnosis)   | modified diagnosis component  | 25/09/2023 06:10 p.m   |
|     |     | c2917c76487526295ea8402aba94b6e4dfb28e87  | feat(diagnosis)   | modified diagnosis' html component  | 26/09/2023 06:50 p.m   |
|     | feature/treatments-physiotherapist  | 08850c8cc59763eb1c3bc8adc23dd8a2f3e31888  | feat(physiotherapists-treatments)  | added section of all uploaded treatments   | 26/09/2023 07:00 p.m   |
|     | feature/medical-appointments-physiotherapist   | bc0a2e699f5faeef842ed2e98075c17f4b4ee7ac  | feat(physiotherapists-appointments)  | added appointments section for physiotherapists  | 26/09/2023 09:00 p.m  |
|      | Master  | bab45a3e52b36b0baa08924f3a9b45a42196b799  | [Initial commit](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/bab45a3e52b36b0baa08924f3a9b45a42196b799) | Se creó el proyecto   | 17/09/2023 17:17 PM  |
|      | Master  | ad863169160ed38ba6c74bdbb88a8a20bb24c692  | feat(project): add project folders | Se agregaron las carpetas del proyecto  | 17/09/202317:20 PM  |
|      | Develop  | 26ac6d3171a92ee3d5e08656b824cacb1835ea16  | [feat(head): add meta tags and link styles](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/26ac6d3171a92ee3d5e08656b824cacb1835ea16) | Se agregaron los meta tags y se enlazó el html con el css  | 15/09/2023 18:21 PM  |
|      | Develop  | 5c9d3d3ec4522e9d6223c21eafaea4b1b06bf8f4  | [feat(hero): add styles for hero](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/5c9d3d3ec4522e9d6223c21eafaea4b1b06bf8f4) | Se añadieron los estilos para el hero  | 15/09/2023 18:28 PM  |
|      | Develop  | a2f210fc8df313228420902318ef4ad9150e5431  | [feat(hero): add html](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/a2f210fc8df313228420902318ef4ad9150e5431) | Se añadieron los textos e imágenes para el hero  | 16/09/2023 18:25 PM  |
|      | Develop  | a7e110deb6b77b0577efc45efc0240a14eb5ceba  | [feat(patient-services): add section of patient services](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/a7e110deb6b77b0577efc45efc0240a14eb5ceba) | Se añadió la sección para el paciente y su contenido  | 16/09/2023 18:35 PM  |
|      | Develop  | b8cafcb227fb13697f77a9401cbd34078ad8bce2  | [feat(patient-services): add styles to patient services](https://github.com/DigitAlholics-2-0/LandingPage-Theraphy/commit/b8cafcb227fb13697f77a9401cbd34078ad8bce2) | Se agregaron los estilos para la sección de servicios para pacientes  | 16/09/2023 18:50 PM  |
|      | Develop   | 09b67dca96a15d559c27dfaaccb8111090cb2a5c  | feat(about-product): add section about the product | Se agregó el contenido  de la sección About The Product  | 16/09/2023 20:04 PM  |
|      | Develop   | 6365f2264ae44ca6b6d096e54cf2797abfa7e22a  | feat(about-product): add styles for about the product section | Se agregaron los estilos para la sección About The Product  | 16/09/2023 20:14 PM   |
|      | Develop   | db665ba536f875ae0a0897d5d0bdb0e48170a08a  | feat(physiotherapist): add section physiotherapist | Se agregó el contenido para la sección Physiotherapist   | 16/09/2023 20:40 PM   |
|      | Develop  | 7be6ae84fdfb04d547eca4bc21d1ddd0511a0996  | feat(physiotherapist): add styles to physiotherapist section | Se agregaron los estilos para la sección Physiotherapist  | 16/09/2023 20:48 PM   |


##### 6.2.1.4 Testing Suite Evidence for Sprint Review

En está sección presentamos el conjunto de Acceptance Test relacionados con las User Stories seleccionadas para el desarrollo del Sprint 1. Para dichos criterios de aceptación se utilizó el lenguaje Gherkin bajo el enfoque BDD.

| **Repository**    | **Branch**    | **Commit ID**    | **Commit Message**    | **Commit Message Body**    | **Commited on (Date)**   |
| --- | --- | --- | --- | --- | --- |
|  [https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Acceptance-Test](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Acceptance-Test)   |  main    | 7763fda7c542dc0a693e619f0873a667c0205737  |    feat(testing)  | Added acceptance criteria: HU07, HU08, HU09,HU13,HU18,HU19,HU20,HU21,HU44  | 27/09/2023  8:50 PM  |

##### 6.2.1.5 **Execution Evidence for Sprint Review**

Para este segundo sprint, conseguimos desarrollar y desplegar el Landin Page y las siguientes secciones de nuestra aplicación web:  Treatments, Treatments-info, Treatments-sessions, Physiotherpists, Physiotherpist-profile, Schedule-appointment, Payment y Appointments.

Se presentan screenshots del desarrollo del Landing Page:

Se muestra el Header donde se encuentran los botones de Home, Services, Pricing, Testimonials, About Us y el botón para cambiar de idioma English-Spanish para que puedan desplazarse a la sección que quieran visualizar.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/execution%20evidence%20for%20sprint%20review/header.jpg?raw=true" width="600">
Ilustración 1: Encabezado y botones de desplazamiento

Se muestra la sección de Hero, donde se muestra una breve descripción y frase representativa de Theraphy. Además, de permitir empezar a utilizar el servicio web y brinda una imagen relacionada a ello.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/hero.jpg" width="600">
Ilustración 2: Sección de Hero

Se muestra la sección testimonials, donde se muestran tarjetas de información que contienen los comentarios de los clientes satisfechos con el servicio otorgado por parte de Theraphy

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/testimonials.jpg" width="600">

Ilustración 3: Sección de Testmonials

Se muestra la sección servicios, donde se integra texto y un fondo coherente para que permita su visualización. Cuando el mouse sobrepase el área del cuadro, se descubrirá la imagen que contiene cada bloque. Asimismo, se presentan COT acordes a cada segmento objetivo para que proceda a la descarga de la aplicación.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/servicios.jpg" width="600">
lustración 4: Sección de servicios 1

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/servicios%202.png" width="600">
Ilustración 5: Sección de servicios 2

Finalmente, se muestra la sección footer con nuestras redes sociales y botones que le permitirán volver a las secciones que desee el usuario.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/footer.jpg" width="600">
Ilustración : Sección de contáctanos

Evidencia:

- **Treatments:** Muestra los tratamientos que se encuentran disponibles en la plataforma a nuestros pacientes.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/treatments.jpg" width="600">



- **Treatments-info:** Presenta la información detallada de los tratamientos ofrecidos dentro de la aplicación.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/treatments%20info.jpg" width="600">

- **Treatments-session:** Muestra la sesión; es decir, el video de rutina que le toca al paciente en el tratamiento elegido.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/execution%20evidence%20for%20sprint%20review/treatment%20secction.jpg?raw=true" width="600">

-   **Physiotherapists:** Muestra los fisioterapeutas que se encuentras registrados en la aplicación.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/execution%20evidence%20for%20sprint%20review/physiotherapist.jpg?raw=true" width="600">

- **Physiotherapists-profile:** Muestra la información que el fisioterapeuta ha registrado en su perfil.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/execution%20evidence%20for%20sprint%20review/physiotherapists%20profile.png?raw=true" width="600">



- **Schedule-Appointment:** Muestra el calendario de días disponibles del fisioterapeuta, estos pueden ser seleccionados por el usuario para reservar una cita médica.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/schedule%20appointment.jpg" width="600">

- **Payment:** Muestra el formulario de pago para financiar la cita médica con el fisioterapeuta.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/payment.jpg" width="600">

- **Appointments:** Muestra las consultas médicas que tiene reservadas el usuario.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/medical%20appointments.jpg" width="600">

Link video de demostración: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202020341_upc_edu_pe/ERLUTNLJq8FOoLYB8qjQTQUBaU-Nq5QGDWktjQFh8R8oqw?e=1WVrOh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19 

##### 6.2.1.6 Services Documentation Evidence for Sprint Review

En este Sprint 1 se ha desarrollado únicamente el Front-end. Por lo tanto, no se han realizado operaciones con la API. Sin embargo, se ha utilizado una fake-API, con la que hemos implementado la aplicación web. Además, utilizamos la plataforma My Json Server para publicar esta fake-API. A continuación, se mostrarán los endpoints desarrollados en este sprint.

| **Endpoint**   | **HTTP Verb**   | **Action**   |
| --- | --- | --- |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/allPatients |  GET  | Obtiene como respuesta a todos los pacientes que se han ingresado en el sistema. |
| [https://api-iotheraphy-production.up.railway.app/api/v1/allPhysiotherapist](https://api-iotheraphy-production.up.railway.app/api/v1/allPhysiotherapist)    | GET  | Obtiene como respuesta a todos los fisioterapeutas que se han ingresado en el sistema. |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/allAppointments |  GET  | Obtiene como respuesta a todas las citas médicas que se han ingresado en el sistema. |
| [https://api-iotheraphy-production.up.railway.app/api/v1/allTheraphies](https://api-iotheraphy-production.up.railway.app/api/v1/allTheraphies)    | GET  | Obtiene como respuesta a todas las terapias que se han ingresado en el sistema. |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/allTreatment |  GET  | Obtiene como respuesta a todos los tratamientos que se han ingresado en el sistema. |
| [https://api-iotheraphy-production.up.railway.app/api/v1/create-treatment](https://api-iotheraphy-production.up.railway.app/api/v1/create-treatment)    | POST  | Ingresa un nuevo tratamiento a la base de datos de Theraphy |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/create\_appointment | POST | Ingresa una nueva cita médica a la base de datos de Theraphy |
| [https://api-iotheraphy-production.up.railway.app/api/v1/create-theraphy](https://api-iotheraphy-production.up.railway.app/api/v1/create-theraphy)   | POST  | Ingresa una nueva terapia a la base de datos de Theraphy |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/registration-physiotherapist | POST | Ingresa un nuevo fisioterapeuta a la base de datos de Theraphy |
| [https://api-iotheraphy-production.up.railway.app/api/v1/registration-patient](https://api-iotheraphy-production.up.railway.app/api/v1/registration-patient)    | POST  | Ingresa un nuevo paciente a la base de datos de Theraphy |
| [https://api-iotheraphy-production.up.railway.app/api/v1](https://api-iotheraphy-production.up.railway.app/api/v1)/auth/registration | POST | Ingresa un nuevo usuario a la base de datos de Theraphy y brinda un Token de acceso a permisos |
| [https://api-iotheraphy-production.up.railway.app/api/v1/auth/authentication](https://api-iotheraphy-production.up.railway.app/api/v1/auth/authentication)    | POST  | Comprueba la existencia de un usuario en la base de datos de Theraphy y brinda un token de acceso |


##### 6.2.1.7 Software Deployment Evidence for Sprint Review

Para el despliegue de la aplicación web utilizamos la plataforma GitHub Pages.

Link de la web application desplegada: [https://digitalholics.github.io/Front-End-Theraphy-Exp/login](https://digitalholics.github.io/Front-End-Theraphy-Exp/login)

Para el despliegue de la API utilizada empleamos el servicio de Railway; sin embargo, como este no soporta SDK 20, tuvimos que cambiarlo a JDK 17 para ente entregable.

Link de la API desplegada: [https://api-iotheraphy-production.up.railway.app](https://api-iotheraphy-production.up.railway.app/)

##### 6.2.1.8 Team Collaboration Insights during Sprint

Para evidenciar la colaboración de todos integrantes del equipo DigitAlholics en el desarrollo del presente sprint, mostramos a continuación la sección Insights del repositorio donde se encuentra almacenada nuestra aplicación web.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/team%20collaboration%20insights.jpg" width="600">

En la imagen se puede visualizar el número de pull requests realizados por todo el equipo. También se presenta en la parte inferior un gráfico con la cantidad de commits realizados por cada integrante.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/pull%20requets.jpg" width="600">

En la imagen se evidencia el número de cambios realizados por cada integrante y el intervalo de fechas en que estos se efectuaron.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/cambios%20realizados%201.jpg" width="600">

En este gráfico se puede visualizar el número de clonaciones que se le ha realizado al repositorio. Además, presenta el tráfico de visitantes que ha tenido el repositorio.

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/execution%20evidence%20for%20sprint%20review/clonaciones.jpg" width="600">

En la presente imagen se muestran las ramas que se desprenden de nuestra rama principal. Asimismo, se puede visualizar los features realizados en cada respectivo commit.


#### 6.2.2 Sprint 2
##### 6.2.2.1 Sprint Planning 2.
A continuación se presenta el Sprint Planning realizado para esta iteración.<br><br>

| Sprint #                              | Sprint 2                           |
|---------------------------------------|-----------------------------------|
| Sprint Planning Background             |                                   |
| Date                                  | 2023-10-07                        |
| Time                                  | 11:30 am                          |
| Location                              | Reunión virtual por Discord       |
| Prepared By                           | Luis Pineda, Cristhian Gómez      |
| Attendees (to planning meeting)       |                                   |
| - Arrieta Huaman Leonardo Santos      | - Pineda Ugás, Luis Alberto       |
| - Gómez De la Cruz, Cristhian Gabriel | - Ahuanari Murayari, Maria Alexandra |
| - Del Carpio Lopez, José Fabricio Jared  |    |
| Sprint 1 Review Summary               | Se concretó correctamenta la implementación del FrontEnd y BackEnd de Therapy                         |
| Sprint 1 Retrospective Summary        | Por la intensidad del trabajo, las horas de sueño del equipo de desarrollo se vieron afectadas. Por ello, la carga para el siguiente Sprint será menor. |
| Sprint Goal & User Stories            |                                   |
| Sprint 2 Goal                         | Durante este sprint el equipo se encargará de desarrollar las User Stories establecidas para la Aplicación Móvil y construir dispositivo IoT |
| Sprint 2 Velocity                     | 20 story points                    |
| Sum of Story Points                   | 19 story points                    |

<br><br>
##### 6.2.2.2 Sprint backlog 2

| Sprint # | Sprint 2 | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story | Work-item/Task | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Id | Tittle | Id | Tittle | Description | Estimation (Hours) | Assigned To | Status (To-do /In-Process /To-Review /Done) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183109786  | HU15: Visualización del perfil de los pacientes  | TA01  | Mostrar datos del paciente  | Se mostrará el nombre de los pacientes, asimismo las características ingresadas por este mismo.  | 2 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Abrir foto  | Se dispondrá de una foto referencial del paciente elegido. Esta deberá expandirse para una mejor visualización.  | 3 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Controlar historial médico  | Añadir opción que permite editar la información presentada del apciente  | 3 | Luis Pineda   | Done  |
| --- | --- | --- | --- | --- | --- |
| #183109788  | HU14: Control de solicitudes de consultas médicas  | TA01  | Añadir cards para cada consulta  | Serán agregadas cards con información importante de cada consulta que se le ha solicitado al fisioterapeuta.  | 2 |  Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir foto  | Se añadirá la foto del paciente que ha solicitado la cita médica en cada card.  | 3 |  Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir caja de búsqueda  | Se permitirá ingresar en un input el nombre de un paciente para que su cita aparezca de manera inmediata.  | 3 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA04  | Concretar cita  | Se añadirá la opción de concretar cita médica para que el fiisoterapeuta ingrese un diagnístico y esta figure como hecha.  | 4 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- |
| #183109794  | HU13: Reservación de consulta médica  | TA01  | Añadir botón de agendar cita  | Dentro de la terapia de un paciente se dispondrá de un botón de añadir cita cuando el día seleccionado no tenga contenido.  | 2 |   Jose Del Carpio | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir inputs   | Se añadirá la hora de inicio dela cita médica en un textfield.  | 2 | Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Mostrar cita  | Cambiará la vista de la terpa en el dia designado a mostrar la cita médica agendada.  | 2 |  Leonardo Arrieta | Done   |
| --- | --- | --- | --- | --- | --- |
| #183136085  | HU18: Visualización de horario de consultas  | TA01  | Añadir cajas de horas  | Se añadirán las horas en las que estarán disponibles los fisioterapeutas en una caja.  | 1 |  María Ahuanari | Done   |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir botón de editar  | Se añadirá un botón que permita editar los horarios fijados.  | 2 |  María Ahuanari | Done   |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir Dialog   | Aparecerá un Dialog que contenga un formulario de edición de horas.  | 1 |  María Ahuanari | Done  |
| --- | --- | --- | --- | --- | --- |
| #183136086  | HU12: Visualización del perfil de los fisioterapeutas  | TA01  | Añadir foto   | Se añadirá una foto expandible del fisioterapetua  | 1 |  María Ahuanari | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir información | Se presentará los datos generales ingresados por el doctor.  | 1 |  Cristhian Gómez | Done  |
| --- | --- | --- | --- | --- | --- |
|     |     | TA03  | Añadir botón de edición  | Se añadirá el botón que permita editar.  | 1 |  Cristhian Gómez | Done  |
| --- | --- | --- | --- | --- | --- |
| #183136088  | HU08:  Visualización de ejercicios   | TA01  | Agregar sección para la visualización de las sesiones de ejercicios  | Se añadirá una sección que presente los videos de ejercicios a realizar para cada tratamiento.  | 2  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02   | Añadir video de la sesión   | Se añadirá el video que contenga los ejercicios a realizar en la sesión que se ha seleccionado.   | 1  | Luis Pineda  | Done  |
|     |     | TA03  | Añadir botones de cambio de sesión  | Se añadirán los botones que permitan movilizarse a una siguiente sesión o a una anterior.  | 3  | Leonardo Arrieta  | Done  |
| #183136089 | HU09: Publicación de videos de ejercicios   | TA01  | Añadir sección para la publicación de un nuevo video de ejercicios  | Se agregará una sección que presenta el formulario para la publicación de un video de ejercicios  | 2  | Cristhian Gómez   | To-do  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183136090 | HU07: Búsqueda de tratamientos     | TA01  | Añadir sección de tratamientos  | Se añadirá una sección que presentará la lista de tratamientos publicados en la aplicación   | 2  | Jose Del Carpio  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir caja de búsqueda | Se añadirá un input que permita ingresar el nombre de un tratamiento | 2  | Jose Del Carpio  | Done  |
|     |     | TA03  | Agregar lista de resultados por coincidencia  | Se enlistarán cada uno de los tratamientos que coincidan con el nombre ingresado en la barra de búsqueda  | 3  | Jose Del Carpio  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183136092 | HU19: Envío de diagnóstico y recomendaciones     | TA01  | Añadir botón de nuevo diagnóstico  | Se añadirá un botón en la vista de una cita médica que permita iniciar el proceso de envío de diagnóstico a un paciente.  | 2  | Luis Pineda  | Done |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02 | Añadir caja de texto | Se añadirá input para ingresar el diagnóstico que se le brindará al paciente | 2  | Luis Pineda  | Done  |
| #183136093 | HU20: Visualización de los resultados de la consulta   | TA01  | Agregar botón | Se añadirá un botón que permita al usuario direccionarse a la vista de resultados de consultas médicas  | 2  | Leonardo Arrieta  | Done |
|     |     | TA02  | Añadir vista de los resultados de las consultas médicas  | Se añadirá una sección que presentará los resultados de cada consulta médica realizada.  | 3  | Leonardo Arrieta  | Done |
| #183109753  | HU01: Registro de cuenta  | TA01  | Añadir título  | Añadir título que indique que se encuentra en el registro en  dispositivo móvil.  | 1  | Luis Pineda  | Done  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|     |     | TA02  | Añadir Input de nombre  | Añadir Input que permita ingresar el nombre con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA03  | Añadir Input de apellido  | Añadir Input que permita ingresar el apellido con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA04  | Añadir Input cumpleaños  | Añadir Input que permita ingresar el cumpleaños con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA05  | Añadir Input de rol  | Añadir Input que permita ingresar el rol con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA06  | Añadir Input email  | Añadir Input que permita ingresar el email con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA07  | Añadir Input de contraseña  | Añadir Input que permita ingresar la contraseña con sus validaciones  | 2  | Luis Pineda  | Done  |
|     |     | TA08  | Añadir botón de registro  | Añadir botón que permita el registro y vuelva al login  | 1  | Luis Pineda  | Done  |
|   |   |   |   |   |   |   |   |   |

##### 6.2.2.3 Development Evidence for Sprint Review

Para este segundo sprint, conseguimos desarrollar y desplegar las siguientes secciones de nuestra aplicación web:  Treatments, Treatments-info, Treatments-sessions, Physiotherpists, Physiotherpist-profile, Schedule-appointment, Payment, Appointments, Log-in y Sign-up

| **Repository** | **Branch** | **Commit ID** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
| --- | --- | --- | --- | --- | --- |
|    https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/MobileApp-Theraphy | Feature/therapy  | 2c72c073b139b17835797d6263196f7db4decac2  | feat(therapy)  | added dates to every day of a therapy   | 20/10/2023 04:30 p.m     |
|  | --- | --- | --- | --- | --- |
|     | Feature/therapy  | 790d7e823f8bd88729dcfa9530b06e377139feeb   |            feat(treatment)       |                                                                                      added post of a treatment  | 20/10/2023 07:20 p.m    |
|  | --- | --- | --- | --- |
|   Feature/therapy  |     | 1f59ba0a92a86b5e3c30f41da6b878c36d5b6254  | feat(firebase)  | Added Firebase Config   | 21/10/2023 09:00 p.m     |
|  | --- | --- | --- |
|     | feature/security  | 4ccfe0f80a86413683f525db09bfd8048b6f968c  | feat(security)  | Views For Register and Loging   |  22/10/2023 09:10 p.m     |
|  | --- | --- | --- |
|     | feature/available-hour  | 46e84895e7a28b77c05b975f39d4ab484e7dae74  | feat(ProfilePhysiotherapist)  |   Added available hour in profile   | 25/20/2023 04:40 p.m  |
|  | --- | --- | --- |
|     |  Feature/patients-list   | 087248f3e2a3ce9c53ec905978980f9699b8f6e3  | feat(patients-list)   | created patients-list.dart  | 25/10/2023 06:10 p.m   |
|     |     | c2917c76487526295ea8402aba94b6e4dfb28e87  | feat(patients)   | modified http helper  | 26/10/2023 06:50 p.m   |
| --- | --- | --- | --- | --- | --- |
|  https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Theraphy-Device   | main  | 08850c8cc59763eb1c3bc8adc23dd8a2f3e31888  | feat(IoT)  | Added IoT Device   | 26/10/2023 07:00 p.m   |
|     |    | bc0a2e699f5faeef842ed2e98075c17f4b4ee7ac  | feat(IoT)  | Added description for therapy device  | 26/10/2023 09:00 p.m  |
|      |   | ad863169160ed38ba6c74bdbb88a8a20bb24c692  | feat(IoT)  | added image arduino wokwi.  | 17/10/202317:20 PM  |
|      |   | 26ac6d3171a92ee3d5e08656b824cacb1835ea16  | feat(IoT)  | added connetion to wifi with Esp32  | 15/10/2023 18:21 PM  |
| --- | --- | --- | --- | --- | --- |
|   https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/API-IoTheraphy   | Feature/IotDevice  | a2f210fc8df313228420902318ef4ad9150e5431  | feat(IoT) |  Repository and Service implementation for IoTDevice  | 16/10/2023 18:25 PM  |
|      | Feature/available-hours  | a7e110deb6b77b0577efc45efc0240a14eb5ceba  | feat(AvailableHours) | added API Available Hour.  | 16/10/2023 18:35 PM  |
|      | Feature/stripe  | b8cafcb227fb13697f77a9401cbd34078ad8bce2  | feat(Payment)  | added payment method with stripe  | 16/10/2023 18:50 PM  |
|      | Feature/therapy   | 09b67dca96a15d559c27dfaaccb8111090cb2a5c  | feat(therapy) | added method to get active therapy  | 16/10/2023 20:04 PM  |
|      |    | 6365f2264ae44ca6b6d096e54cf2797abfa7e22a  |  feat(therapy)) | added method to get treatment for a spceific day   | 16/10/2023 20:14 PM   |
|      |    | db665ba536f875ae0a0897d5d0bdb0e48170a08a  |  feat(Update and Added) |  Update creation of Patient and Registered   | 16/10/2023 20:40 PM   |
|      |    | 7be6ae84fdfb04d547eca4bc21d1ddd0511a0996  |  feat(therapy) | added method to get all appointments of a therapy  | 16/10/2023 20:48 PM   |
| --- | --- | --- | --- | --- | --- |

##### 6.2.2.4 Testing Suite Evidence for Sprint Review

En está sección presentamos el conjunto de Acceptance Test relacionados con las User Stories seleccionadas para el desarrollo del Sprint 2. Para dichos criterios de aceptación se utilizó el lenguaje Gherkin bajo el enfoque BDD.

| **Repository**    | **Branch**    | **Commit ID**    | **Commit Message**    | **Commit Message Body**    | **Commited on (Date)**   |
| --- | --- | --- | --- | --- | --- |
|  [https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Acceptance-Test](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Acceptance-Test)   |  main    | 7763fda7c542dc0a693e619f0873a667c0205737  |    feat(testing)  | Added acceptance criteria: HU15, HU14, HU13,HU18,HU12,HU08,HU07,HU20,HU01  | 27/09/2023  8:50 PM  |

##### 6.2.3.5 **Execution Evidence for Sprint Review**

Para este segundo sprint, conseguimos desarrollar y desplegar la aplicación web, como también se desarrolló la aplicación móvil:

Se presentan screenshots del desarrollo de la aplicacion Web:

- **Patient Profile:** Podrás acceder a tu perfil de paciente en la plataforma. Aquí encontrarás información personal y detalles relevantes, como tu historial médico.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/PatientProfile.png?raw=true" width="600">

- **My consultations:** La sección donde podrás ver y gestionar tus consultas médicas. Aquí encontrarás información detallada sobre tus próximas y pasadas consultas.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/Myconsultations.png?raw=true" width="600">

- **Book Consultation:**  Podrás acceder a la sección de reservas de consultas médicas. Aquí podrás programar una cita médica con el fisioterapeuta de tu elección, eligiendo la fecha y hora que mejor te convenga.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/bookConsultation.png?raw=true" width="600">

-   **Physiotherapists:** Muestra los fisioterapeutas que se encuentras registrados en la aplicación.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/physiotherapisProfile.png?raw=true" width="600">

- **Physiotherapists-profile:** Muestra la información que el fisioterapeuta ha registrado en su perfil.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/physiotherapistList.png?raw=true" width="600">

- **You don't have therapies:**  La sección que muestra que actualmente no tienes terapias registradas o disponibles en tu perfil.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/Youdon'thavetherapies.png?raw=true" width="600">

- **Therapy View:** Podrás acceder a la vista de terapia. Aquí encontrarás información detallada sobre tu tratamiento actual, incluyendo los detalles específicos de la terapia, la duración, los ejercicios recomendados y cualquier otra información relevante.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/therapyView.png?raw=true" width="600">

- **Appointment Fisio Standar:**  La sección que muestra las consultas médicas estándar con tu fisioterapeuta. Aquí podrás acceder a la información de tus citas médicas regulares, incluyendo fechas, horas y detalles relacionados con tus consultas .

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/WebTheraphyPhotos/appointmentFisioStandar.png?raw=true" width="600">

Se presentan screenshots del desarrollo de la aplicacion móvil:

- **Patient Profile:** Se podra acceder al perfil del paciente. Aquí encontrarás información personal y detalles relevantes, de su historial médico.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/patientProfile.png?raw=true" width="280">

- **Treatment creation:**  Aquí podrás diseñar y personalizar tratamientos específicos según las necesidades médicas de tu paciente.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/Treatment%20creation.png?raw=true" width="280">

- **Book Consultation:**  La sección de creación de terapias. Aquí podrás diseñar y personalizar terapias específicas según las necesidades médicas de tu paciente.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/Theraphy%20creation.png?raw=true" width="280">

-   **Physiotherapist home:**  Podrás acceder al inicio de la página de inicio del fisioterapeuta. Aquí encontrarás información y recursos destinados a los fisioterapeutas registrados en la plataforma.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/Physiotherapist%20home.png?raw=true" width="280">

- **Patients List:**  podrás acceder a la lista de pacientes. Aquí encontrarás información detallada sobre los pacientes que un fisioterapeuta atiende o gestiona.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/PatientsList.png?raw=true" width="280">

- **Appointment or Treatment Creation:**  Podrás acceder a la sección donde puedes programar una cita médica para un paciente o crear un nuevo tratamiento.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/mobileTheraphyPhotos/Appointment%20or%20Treatment%20Creation.png?raw=true" width="280">

Link video de demostración: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e705_upc_edu_pe/EWJKf9eQ6y5NnWfwas095EkBkBM6k4GdFNaPkPGetlRkVw?e=PJBKB9&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19

##### 6.2.2.6 Services Documentation Evidence for Sprint Review

En este Sprint 2 se ha desarrollado únicamente el Front-end. Por lo tanto, no se han realizado operaciones con la API. Sin embargo, se ha utilizado una fake-API, con la que hemos implementado la aplicación web. Además, utilizamos la plataforma My Json Server para publicar esta fake-API. A continuación, se mostrarán los endpoints desarrollados en este sprint.

| **Endpoint**   | **HTTP Verb**   | **Action**   |
| --- | --- | --- |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/available-hours](https://api-iotheraphy-production-909e.up.railway.app/api/v1)/available-hours |  GET  | Obtiene las horas disponibles de los fisioterapeutas. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/consultations](https://api-iotheraphy-production-909e.up.railway.app/api/v1)/consultations    | GET  | Obtiene todas las consultas del fisioterapeuta. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1/therapies)/activeTherapyByPatientId |  GET  | Obtiene las terapias iniciadas por el paciente. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production.up.railway.app/api/v1)/medical-histories    | GET  | Obtiene todo el historial médico del paciente. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production.up.railway.app/api/v1)/diagnoses |  GET  | Obtiene el último diagnóstico que tuvo el paciente. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1)/iotDevice    | GET  | Obtiene los datos del dispositivo IoT que se usa en la terapia |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1/available-hours)    | POST  | Crea las horas disponibles de los fisioterapeutas |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1/consultations) | POST | Crea las consultas del fisioterapeuta |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1/therapies)   | POST  | Crea las terapias iniciadas por el paciente. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production.up.railway.app/api/v1/medical-histories) | POST | Crea el historial médico del paciente. |
| [https://api-iotheraphy-production-909e.up.railway.app/api/v1/](https://api-iotheraphy-production-909e.up.railway.app/api/v1/iotDevice) | POST | Genera la información dispositivo IoT que se usa en la terapia |


##### 6.2.2.7 Software Deployment Evidence for Sprint Review

Para el despliegue de la aplicación web utilizamos la plataforma Firebase.

Link de la web application desplegada: (https://theraphy-2b472.web.app/login)

Para el despliegue de la API utilizada empleamos el servicio de Railway; sin embargo, como este no soporta SDK 20, tuvimos que cambiarlo a JDK 17 para ente entregable.

Link de la API desplegada: (https://api-iotheraphy-production-909e.up.railway.app/)

##### 6.2.2.8 Team Collaboration Insights during Sprint

Para evidenciar la colaboración de todos integrantes del equipo DigitAlholics en el desarrollo del presente sprint, mostramos a continuación la sección Insights del repositorio donde se encuentra almacenada nuestra aplicación web.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/colaborationTB2/FrontendColaboration.png?raw=true" width="600">

Para evidenciar la colaboración de todos integrantes del equipo DigitAlholics en el desarrollo del presente sprint, mostramos a continuación la sección Insights del repositorio donde se encuentra almacenada nuestra Web Services.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/colaborationTB2/backendColaboration.png?raw=true" width="600">

Para evidenciar la colaboración de todos integrantes del equipo DigitAlholics en el desarrollo del presente sprint, mostramos a continuación la sección Insights del repositorio donde se encuentra almacenada nuestra aplicación móvil.

<img src="https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/blob/main/colaborationTB2/mobileColaboration.png?raw=true" width="600">


#### 6.2.3 Sprint 3
En la tercera iteración del proyecto, se planteó como meta el vincular el dispositivo IoT con las aplicaciones web y móvil a través de nuestro BackEnd.<br>
Repositorio Web App https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Web-Theraphy<br>
Repositorio BackEnd: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/API-IoTheraphy<br>
Repositorio App Flutter: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/MobileApp-Theraphy<br>
Repositorio IoTheraphy: https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Theraphy-Device<br> 

##### 6.2.3.1 Sprint Planning 3.
A continuación se presenta el Sprint Planning realizado para esta iteración.<br><br>

| Sprint #                              | Sprint 3                           |
|---------------------------------------|-----------------------------------|
| Sprint Planning Background             |                                   |
| Date                                  | 2023-10-21                        |
| Time                                  | 11:30 am                          |
| Location                              | Reunión virtual por Discord       |
| Prepared By                           | Luis Pineda, Cristhian Gómez      |
| Attendees (to planning meeting)       |                                   |
| - Arrieta Huaman Leonardo Santos      | - Pineda Ugás, Luis Alberto       |
| - Gómez De la Cruz, Cristhian Gabriel | - Ahuanari Murayari, Maria Alexandra |
| - Del Carpio Lopez, José Fabricio Jared  |    |
| Sprint 2 Review Summary               | Se concretó correctamenta la implementación del IoT y Mobile App de Therapy                         |
| Sprint 2 Retrospective Summary        | Después de superar un período intenso de trabajo, el equipo de desarrollo ha restablecido su equilibrio y ha retomado su ritmo normal. Como resultado, la carga para el siguiente Sprint se ha ajustado para garantizar un mejor equilibrio entre productividad y bienestar del equipo. |
| Sprint Goal & User Stories            |                                   |
| Sprint 3 Goal                         | Durante este sprint el equipo se encargará de vincular las aplicaciones creadas y dar fundiones extras a los productos |
| Sprint 3 Velocity                     | 20 story points                    |
| Sum of Story Points                   | 19 story points                    |

<br><br>
##### 6.2.2.2 Sprint Backlog 3

| Sprint # | Sprint 3 | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- |
| User Story | Work-item/Task | --- | --- | --- | --- | --- | --- |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Id | Title | Id | Title | Description | Estimation (Hours) | Assigned To | Status (To-do / In-Process / To-Review / Done) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| #183136069 | Registro de cuenta | TA01 | Añadir vista de registro para móvil | Se programará la vista diseñada en Figma para el registro de usuarios en la aplicación móvil. | 3 | Jose del Carpio | Done |
|     |     | TA02 | Validar rol de usuario | Se dispondrá de la elección del rol dentro de la aplicación para validar las acciones que pueda realizar. | 1 | Jose del Carpio | Done |
|     |     | TA03 | Validar campos ingresados | Validar que los datos son los que se solicitan en el Backend | 3 | Jose del Carpio | Done |
| #183109782 | Inicio de sesión | TA01 | Añadir vista de inicio de sesión para móvil | Se programará la vista diseñada en Figma para el inicio de sesión de usuarios en la aplicación móvil. | 3 | Jose del Carpio | Done |
|     |     | TA02 | Validar rol de usuario | Se leerá el rol que cumple el usuario dentro de la aplicación cuando inicie sesión | 1 | Jose del Carpio | Done |
|     |     | TA03 | Validar datos ingresados | Se validará si los datos ingresados pertenecen a una cuenta ya creada o no. | 2 | Jose del Carpio | Done |
| #183136069 | Visualización del registro de progreso | TA01 | Se añadirá vista de lectura de IoT | Se añadirá una vista en la aplicación móvil diseñada exclusivamente para móvil. | 1 | Gabriel Gomez | Done |
|     |     | TA02 | Se añadirá gráfico de MAP | Se leerá del backend los datos de Muscular Action Potential y se mostrará en un gráfico de líneas en la vista. | 4 | Gabriel Gomez | Done |
|     |     | TA03 | Se añadirá gráfico de BPM | Se leerá del backend los datos de Heartbeat y se mostrará en un corazón con el promedio del pulso. | 2 | Gabriel Gomez | Done |
|     |     | TA04 | Se añadirá gráfico de temperatura | Se leerá del backend los datos de temperatura y se mostrará en un termómetro con el promedio de temperatura. | 2 | Gabriel Gomez | Done |
|     |     | TA05 | Se añadirá gráfico de tiempo | Se leerá del backend los intervalos de tiempo de duración de cada MAP y se mostrará en un gráfico de barras en la vista. | 4 | Gabriel Gomez | Done |
|     |     | TA06 | Se añadirá gráfico de humedad | Se leerá del backend los datos de humedad y se mostrará en un círculo con el promedio de humedad. | 2 | Gabriel Gomez | Done |
| #183109768 | Visualización del perfil | TA01 | Añadir vista de perfil de fisioterapeuta | Añadir vista de perfil propio del usuario ingresado en la aplicación móvil. | 1 | Leonardo Arrieta | Done |
|     |     | TA02 | Mostrar datos del fisioterapeuta | Se mostrará datos como nombre, especialización, foto de perfil y correo. | 1 | Leonardo Arrieta | Done |
| #183136121 | Selección de foto de perfil | TA01 | Abrir foto | Expandir la foto de perfil cuando se seleccione | 1 | Leonardo Arrieta | Done |
|     |     | TA02 | Cambiar foto | Abrir biblioteca del móvil y subir la foto en firebase para que se guarde en la base de datos. | 3 | Jose del Carpio | Done |
| #183136123 | Ingreso de historial médico | TA01 | Añadir formulario de ingreso | Se añadirá un formulario para ingresar los datos de género, estatura, peso, lugar de nacimiento, enfermedades hereditarias, historial no patológico e historial patológico para un paciente seleccionado. | 4 | Gabriel Gomez | Done |
|     |     | TA02 | Visualización de datos | Se añadirán secciones desplegables en el perfil del paciente con los datos ingresados. | 2 | Gabriel Gomez | Done |
| #183109753 | Visualización de ejercicios | TA01 | Añadir vista de terapia | Se añadirá vista de terapia actual para paciente en la web, mostrando el título de esta y su descripción. | 2 | Luis Pineda | Done |
|     |     | TA02 | Añadir carousel de días | Se añadirá un carousel de días permitiendo seleccionar cada elemento para observar los tratamientos virtuales de cada día. | 3 | Luis Pineda | Done |
|     |     | TA03 | Añadir card de video | Se leerá según el día elegido el tratamiento solicitado, mostrándose el video en cuestión junto a los datos de este en una card. | 3 | Luis Pineda | Done |
| #183136090 | Publicación de videos de ejercicios | TA01 | Añadir vista de terapia | Se añadirá vista de terapia actual para el fisioterapeuta en la app móvil según el paciente elegido, mostrando el título de esta y su descripción. | 1 | Luis Pineda | Done |
|     |     | TA02 | Añadir carousel de días | Se añadirá un carousel de días permitiendo seleccionar cada elemento para observar los tratamientos virtuales de cada día. | 3 | Luis Pineda | Done |
|     |     | TA03 | Añadir card de video | Se leerá según el día elegido el tratamiento solicitado, mostrándose el video en cuestión junto a los datos de este en una card. | 3 | Luis Pineda | Done |
|     |     | TA04 | Añadir formulario de ingreso | Se añadirá un formulario de ingreso de nuevo tratamiento en caso de que no haya uno para el día seleccionado, con los campos, nombre, descripción y la subida de archivo multimedia. | 5 | Luis Pineda | Done |
| #183109755 | Control de solicitudes de consultas médica | TA01 | Añadir formulario de horario de atención | Añadir opción en el perfil de fisioterapeuta de editar horario de consultas, lo que abrirá un formulario de día y hora para mostrar su disponibilidad. | 4 | Leonardo Arrieta | Done |
|     |     | TA02 | Añadir visualización de horas | Se mostrarán los datos ingresados en un carousel dentro del perfil. | 2 | Leonardo Arrieta | Done |
|     |     | TA03 | Validar disponibilidad de fisioterapeuta | En la aplicación web se validará a la hora de agendar una cita con el fisioterapeuta si este está disponible en las horas seleccionadas. | 2 | Leonardo Arrieta | Done |
| #183136092 | Visualización del perfil de los pacientes | TA01 | Añadir carousel de pacientes | Se añadirá atajos en el home con una lista horizontal de los pacientes de un fisioterapeuta. | 5 | Maria Ahuanari | Done |
|     |     | TA02 | Añadir vista de lista de pacientes | Se añadirá la vista de Figma de lista de pacientes que permita filtrar de acuerdo a nombre, consultas y terapias. | 3 | Gabriel Gomez | Done |
|     |     | TA03 | Añadir perfil del paciente | Se añadirá vista de perfil de paciente donde se muestren sus datos. | 2 | Gabriel Gomez | Done |
| #183109758 | Comunicación entre fisioterapeutas y pacientes | TA01 | Añadir llamada al paciente | Se añadirá la opción de llamar al número registrado del paciente. | 2 | Luis Pineda | Done |
|     |     | TA02 | Añadir ubicación en mapa | Se añadirá un mapa con el camino a la ubicación del paciente para la cita médica. | 7 | Luis Pineda | Done |
| #183136099 | Registro de consultas médicas | TA01 | Se añadirá lista de últimas consultas | Añadir en el home una lista de últimas consultas separadas por pacientes. | 3 | Maria Ahuanari | Done |
|     |     | TA02 | Se añadirá lista de últimas citas médicas | Añadir en el home una lista de últimas citas médicas separadas por fisioterapeutas. | 3 | Maria Ahuanari | Done |
|     |     | TA03 | Se añadirá vista de historial de consultas y citas médicas | Añadir vista de lista de citas médicas permitiendo filtrar según paciente, y quien agendó. | 4 | Maria Ahuanari | Done |
|     |     | TA04 | Se añadirá vista de historial de terapias | Se añadirá vista de lista de todas las terapias que ha designado un fisioterapeuta. | 4 | Maria Ahuanari | Done |
| #183109775 | Envío de diagnóstico y recomendaciones | TA01 | Añadir formulario de ingreso de diagnóstico | Se añadirá vista que permita ingresar diagnóstico para el paciente seleccionado. | 2 | Luis Pineda | Done |
|     |     | TA02 | Añadir diagnósticos enviados | Se añadirá historial de diagnósticos por paciente en cada perfil de paciente. | 2 | Gabriel Gomez | Done |

##### 6.2.3.3 Development Evidence for Sprint Review 
| **Repository** | **Branch** | **Commit ID** | **Commit Message** | **Commit Message Body** | **Committed on (Date)** |
| --- | --- | --- | --- | --- | --- |
| [MobileApp-Theraphy](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/MobileApp-Theraphy) | Feature/therapy | abc123 | feat(therapy) | added dates to every day of a therapy | 17/11/2023 |
|  | Feature/therapy | abc124 | feat(treatment) | added post of a treatment | 16/11/2023 |
|  | Feature/therapy | abc125 | feat(firebase) | Added Firebase Config | 15/11/2023 |
|  | feature/security | abc126 | feat(security) | Views For Register and Loging | 14/11/2023 |
|  | feature/available-hour | abc127 | feat(ProfilePhysiotherapist) | Added available hour in profile | 14/11/2023 |
|  | Feature/patients-list | abc128 | feat(patients-list) | created patients-list.dart | 14/11/2023 |
|  | Feature/patients-list | abc129 | feat(patients) | modified http helper | 14/11/2023 |
| [Theraphy-Device](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/Theraphy-Device) | main | abc130 | feat(IoT) | Added IoT Device | 14/11/2023 |
|  | main | abc131 | feat(IoT) | Added description for therapy device | 14/11/2023 |
|  | main | abc132 | feat(IoT) | added image arduino wokwi. | 14/11/2023 |
|  | main | abc133 | feat(IoT) | added connetion to wifi with Esp32 | 14/11/2023 |
| [API-IoTheraphy](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/API-IoTheraphy) | Feature/IotDevice | abc134 | feat(IoT) | Repository and Service implementation for IoTDevice | 14/11/2023 |
|  | Feature/available-hours | abc135 | feat(AvailableHours) | added API Available Hour. | 14/11/2023 |
|  | Feature/stripe | abc136 | feat(Payment) | added payment method with stripe | 14/11/2023 |
|  | Feature/therapy | abc137 | feat(therapy) | added method to get active therapy | 14/11/2023 |
|  | Feature/therapy | abc138 | feat(therapy) | added method to get treatment for a specific day | 14/11/2023 |
|  | Feature/therapy | abc139 | feat(Update and Added) | Update creation of Patient and Registered | 14/11/2023 |
|  | Feature/therapy | abc140 | feat(therapy) | added method to get all appointments of a therapy | 14/11/2023 |
| [MobileApp-Theraphy](https://github.com/upc-pre-202302-IoTheraphy-SI572-SW71/MobileApp-Theraphy) | develop | abc150 | fix: android version fixxed | - | 14/11/2023 |
|  | develop | abc151 | feat(direction) | added address and distance of points | - | 14/11/2023 |
|  | develop | abc152 | fix: changed zoom | - | 14/11/2023 |
|  | develop | abc153 | feat(map) | added way in maps to your patient | - | 14/11/2023 |
|  | develop | abc154 | feat: Update Phone Calls for android | - | 14/11/2023 |
|  | develop | abc155 | fix: autoplay removed | - | 14/11/2023 |
|  | develop | abc156 | fix: fixed sidebox card | - | 14/11/2023 |
|  | develop | abc157 | feat(diagnosis) | added diagnosis updating | - | 14/11/2023 |
|  | develop | abc158 | feat(appointment) | added cell phone button | - | 14/11/2023 |
|  | develop | abc159 | fix: appointment card changed | - | 14/11/2023 |
|  | develop | abc160 | fix: fixed all | - | 14/11/2023 |
|  | develop | abc161 | fix: fixed everything | - | 14/11/2023 |
|  | develop | abc162 | fix: fixed upload video | - | 14/11/2023 |
|  | develop | abc163 | fix:fixed http helper | - | 14/11/2023 |
|  | develop | abc164 | feat(home) | home widget | - | 14/11/2023 |
|  | develop | abc165 | feat(home) | modified login widget | - | 14/11/2023 |
|  | develop | abc166 | feat(home) | modified main for home widget | - | 14/11/2023 |
|  | develop | abc167 | feat(home) | modified pubspec yaml and lock | - | 14/11/2023 |
|  | develop | abc168 | feat(home) | added home widget | - | 14/11/2023 |
|  | develop | abc169 | feat(home) | modified and added methods in httphelper | - | 14/11/2023 |
|  | develop | abc170 | feat(home) | modified model for user | - | 14/11/2023 |
|  | develop | abc171 | feat(home) | added model for a therapy | - | 14/11/2023 |



### 6.3. Validation Interviews.
En esta sección mostraremos las entrevistas realizadas a los usuarios objetivos de Theraphy, estas tuvieron como objetivo el generar una interacción entra la aplicación y el público al que va dirigida para realizar su respectiva validación. 

#### 6.3.1. Diseño de Entrevistas.
Las entrevistas se realizaron para todos los segmentos objetivos de Theraphy; es decir, tanto para pacientes como para fisioterapeutas. A continuación, se presentará los flujos que se mostraron a los entrevistados: 

#### Theraph Web App

•	Pacientes: 
  -  Como usuario, deseo crear una cuenta para registrarme en la aplicación<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/registrar%20cuenta.jpg" width="600"><br><br> 
  - Como usuario, deseo iniciar sesión con mi cuenta previamente creada <br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/iniciar%20sesion.jpg" width="600"><br><br> 
  - Como usuario, deseo ingresar a mi perfil<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/ingresar%20a%20perfil.jpg" width="600"><br><br> 
  - Como paciente, deseo ingresar a mi historial médico<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/ingresar%20a%20historial%20medico.jpg" width="600"><br><br> 
  - Como paciente, deseo encontrar mi terapia física<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/encontrar%20terapia.jpg" width="600"><br><br> 
  - Como paciente, deseo visualizar los avances que he conseguido<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/registrar%20avances%20de%20la%20terapia.jpg" width="600"><br><br> 
  - Como paciente, deseo buscar fisioterapeutas por su nombre<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/buscar%20fisioterapeutas.jpg" width="600"><br><br> 
  - Como paciente, deseo visualizar el perfil de los fisioterapeutas<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/visualizar%20perfil%20de%20fisioterapeuta.jpg" width="600"><br><br> 
  - Como paciente, deseo separar una cita médica<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/reservar%20cita.jpg" width="600"><br><br> 
  - Como paciente, deseo visualizar las reseñas de un fisioterapeuta<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/visualizar%20reseñas.jpg" width="600"><br><br> 
  - Como paciente, deseo crear una nueva reseña al fisioterapeuta<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/ingresar%20calificacion.jpg" width="600"><br><br>  
  - Como paciente, deseo visualizar mis propias citas médicas<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20web/userflows/visualizar%20citas%20medicas.jpg" width="600"><br><br><br> 

#### Theraph Mobile App

•	Fisioterapeutas: 
  - Como usuario, deseo crear una cuenta para registrarme en la aplicación<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/crear%20cuenta.png" width="600"><br><br> 
  - Como usuario, deseo iniciar sesión con mi cuenta previamente creada<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/iniciar%20sesion.jpg" width="600"><br><br> 
  - Como fisioterapeuta, deseo buscar pacientes por su nombre <br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/physiotherapists/lista%20de%20pacientes.jpg" width="600"><br><br> 
  - Como fisioterapeuta, deseo visualizar los tratamientos de terapia físicade la apliacación.<br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/physiotherapists/visualizar%20terapias%20subidas.jpg" width="600"><br><br> 
  -	Como fisioterapeuta, deseo publicar un nuevo tratamiento <br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/physiotherapists/subir%20nueva%20terapia.jpg" width="600"><br><br> 
  - Como fisioterapeuta, deseo ver el historial médico de mi paciente <br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/patients/ingreso%20perfil%20paciente.jpg" width="600"><br><br> 
  - Como fisioterapeuta, deseo visualizar mis proximas citas médicas <br>
  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Userflows%20moviles/physiotherapists/lista%20citas.jpg" width="600"><br><br> <br>

  
#### 6.3.2. Registro de Entrevistas.

Segmento 1: Pacientes  

Entrevistada 1:<br><br>
Nombres y Apellidos: Mireya Mercedes Oyarce Bustamante <br> 
Edad: 34 años <br>
Distrito: San Miguel - Lima <br>
URL: https://web.microsoftstream.com/video/aa495125-98ad-4172-99c1-dc78da57e6ab <br>
Timing:  8:30 min<br>
Duración: 6:53 min <br><br>

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem7.png" width="600"><br>


Resumen sobre la entrevista:  <br>
La entrevista fue realizada a Mireya Oyarce. En el proceso de interacción con el Landing Page y la aplicación web, ella se sintió conforme con todo lo que ofrece el producto. Mireya señaló que cada una de las funciones son muy intuitivas y brindan un gran beneficio al usuario, en este caso ella habla del paciente. No obstante, hay un punto que no le agradó, este es que una vez que ingresas con tu cuenta al servicio, no puedes cambiar de a otra porque no existe un botón de cerrar sesión. Ella comentó que los demás apartados son perfectos. <br><br><br>



Entrevistado 2:<br> <br>

Nombres y Apellidos: Flavia Bravo Estrada  <br>
Edad: 67 años<br> 
Distrito: Madre de Dios <br>
URL:  https://upcedupe-my.sharepoint.com/:v:/r/personal/u202020239_upc_edu_pe/Documents/Patient.mp4?csf=1&web=1&e=2GS04S&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19 <br>
Duración: 5:21 min <br><br>

 <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/vd5.png" width="600"><br> 	 

Resumen sobre la entrevista: <br> 
 
Esta entrevista fue realizada a Flavia Bravo. Actualmente, está pasando por un proceso de recuperación debido a una lesión en la rodilla.Cuando se le presentó la plataforma, lo que más le llamó la atención fue la sección dedicada a los fisioterapeutas. Apreció la posibilidad de conocer las especialidades de cada profesional, lo que le ayudó a tomar decisiones informadas sobre su atención médica. También se sintió intrigada por la sección de tratamientos, ya que le gustaría mejorar su recuperación incluso cuando está en casa. Por último, Flavia expresó su deseo de que la comunicación con su fisioterapeuta fuera más directa. Para ella, es de vital importancia poder resolver sus dudas o preocupaciones de inmediato, especialmente cuando siente molestias o dolor debido a su lesión. Esta comunicación efectiva es fundamental en su proceso de recuperación. <br><br><br>



Entrevistada 3: <br><br>

Nombres y Apellidos: Ceciel Gomez Rengifo <br>
Edad: 20 años <br>
Distrito: Villa <br>
URL: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201a836_upc_edu_pe/EQvXk01Gjm5KkB1MEV7lrGsBOBdNCYif7_I9biX01ih0NQ?e=DTH0Oe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19<br>
Duración: 5:73 min <br><br>

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/vd3.png" width="600"><br>

Resumen sobre la entrevista: <br>
La entrevista fue Ceciel Gómez Rengifo quien tiene 20 años y corresponde al segmento objetivo de pacientes. Ceciel manifiesta que la aplicación le parece muy útil y cumple con el funcionamiento de ayudar a la pronta recuperación física desde casa. La reserva de citas les parece interesante. Asimismo, considera que la información está muy bien organizada, ya que puede encontrar lo que busca de forma fácil. <br><br><br>



Segmento 2: Profesionales de salud <br><br><br>

Entrevistada 1: <br><br>

Nombres y Apellidos: Alexandra Flores Farro <br> 
Edad: 34 años <br>
Distrito: San Isidro - Lima <br>
URL: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201a836_upc_edu_pe/EdM77BJH8bBEmfSurAFEEhsBgUs6TJjAEhThZWrIWS-QCg?e=DS8s7l&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19 <br>
Duración: 5:33 min<br><br>

  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/vd1.png" width="600"><br>

Resumen sobre la entrevista:  <br>
La entrevista fue realizada a Alexandra Flores Farro, quien actualmente labora como Médico Rehabilitador en el MINSA. Con respecto al Landing Page de Theraphy, la doctora aclama que no hay una pisca de desperfectos en la página, por lo que podemos concluir que este sitio estático cumple su finción a la perfección. Por otro lado, al momento de mostrar el FrontEnd de nuestro producto, la especialista se mostró conforme con la mayotía de procesos y utilidades con las que cuenta. Sin embargo, existen ciertos criterios que añadió para mejorar el servicio que se le ofrece al usuario, en este caso al perteciente a su segmento objetivo, los fisioterapeutas. El primer punto a tomar en cuenta que ella mencionó, es que hace falta que se indique el tipo de fisioterapia que se está aplicando en los tratamientos subidos a la plataforma, el otro es que en el apartado de historial médico, es importante añadir los antecedentes patológicos que son de suma importancia para los doctores.<br><br><br>  


 
Entrevistada 2: <br><br>

Nombres y Apellidos: Valery Giovanna Gómez De la Cruz <br>
Edad: 26 años <br>
Distrito: San Miguel - Lima <br>
URL: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201a836_upc_edu_pe/EdRQSerGTkVMuTGNif4BLEYB_BUWNDg3stKJUWpQIM0RbA?e=WQbFIx&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19<br>
Duración: 6:35 min<br><br>
 <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/vd2.png" width="600"><br>
    
Resumen sobre la entrevista:  <br>
La entrevistada afirma que, a primera vista, la aplicación le resulta muy util e intuitiva. Asimismo, señala que estaría dispuesta a pagar por el uso de esta aplicación ya que podria solucionar muchos de los problemas que actualmente tiene en relación con el control de los avances terapeuticos de sus pacientes. Por otro lado, indica que se deberian realizar algunas correcciones. En primer lugar, nos señala que el nombre elegido para el campo de Diagnosticos no es el correcto, puesto que la información que contiene esta más relacionada con las prescripciones terapeuticas que son entregadas comumente a los pacientes. Del mismo modo, comunica que la creación de tratamientos podria ser más personalizada, ya que estos ejercicios siguen distintas características dependiendo de la condición física del paciente. Por ultimo, señala que podría ser de mucha ayuda implementar un campo que muestre al fisioterapeuta. <br><br><br>
 


Entrevistada 3: <br><br>

Nombres y Apellidos: Leidianny Lizet Coronel Soto  <br>
Edad: 33 años <br>
Distrito: Jesús María- Lima <br>
URL: https://upcedupe-my.sharepoint.com/:v:/r/personal/u202020239_upc_edu_pe/Documents/Physiotherapy.mp4?csf=1&web=1&e=LAmaSr&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19 <br>
Duración:   3:04 min<br><br>

  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/vd4.png" width="600"><br>	 
Resumen sobre la entrevista:  La entrevista fue realizada a Leidianny Coronel Soto, quién actualmente labora como médico anestesiólogo en el hospital Sergio Bernales. Ella indicó que el sitio estático le parece bien, y le gusta que muestre los beneficios de la aplicación de manera explícita. Asimismo, le encanta que se pueda acceder desde un botón al servicio en sí. De este último, tuvo algunos comentarios, tales como que la presencia del botón llamado “Download” es innesaria, puest oque este no lleva a nada. El resto de procesos le parecieron interesantes y adecuados para las tareas a las que van efocados, <br><br><br>


#### 6.3.3. Evaluaciones según heurísticas.
A continuación, se mostrará el proceso de validación en base a heurísticas de nuestra aplicación, Theraphy. 
 
TABLA RESUMEN: 

| #   | Problema                                               | Escala de severidad | Heurística/Principio violada(o) |
| --- | ------------------------------------------------------ | ------------------- | ------------------------------ |
| 1   | No hay un botón que permita regresar al inicio de sesión | 3                   | Usability: Libertad y control de uso |
| 2   | Se repiten constantemente algunas opciones           | 1                   | Usability: Consistencia y estándares |
| 3   | Incluye un botón “Download”, pero no cumple ni una función | 3                   | Information Architecture: Is it usable? |
| 4   | No incluye información de los ingresos exactos que se pueden obtener | 2                   | Information Architecture: Is it findable? |
| 5   | La opción Diagnósticos tiene un nombre inadecuado    | 1                   | Information Architecture: Is it findable? |
| 6   | No hay mensaje que confirme tu proceso de separación de cita | 2                   | Usability: Libertad y control de uso |
| 7   | El botón “English - Spanish” no realiza ninguna función | 1                   | Information Architecture: Is it usable? |



DESCRIPCIÓN DE PROBLEMAS: 
  
**PROBLEMA #1:** No hay un botón que permita regresar al inicio de sesión <br>
**Severidad:** 3<br> 

**Heurística violada:** Usability: Libertad y control de uso <br>

**Problema:** <br>
Al momento de ingresar a la aplicación y entrar con tu cuenta, esta te lleva al home de Theraphy y te dispone de las múltiples opciones con las que cuenta la aplicación. Sin embargo, se es incapaz de volver al login porque no se encuentra un botón que permita cerras sesión. <br>

 <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem3.png" width="600"><br><br>
  
 
**PROBLEMA #2:** Se repiten constantemente algunas opciones <br>

**Severidad:** 1 <br>

**Heurística violada:** Usability: Consistencia y estándares <br> 

**Problema:** <br> 
Algunas opciones que se encuentran en el menú lateral, tales como mis tratamientos y mis citas médicas, también se encuentran como botones en el perfil de usuario. Esto genera que se encuentren múltiples diversas formas de realizar una acción en la misma vista, lo que puede confundir al usuario. <br> 

 <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem2.png" width="600"><br><br>
  
**PROBLEMA #3:** Incluye un botón “Download”, pero no cumple ni una función <br>

**Severidad:** 3  <br>

**Heurística violada:** Information Architecture: Is it usable? <br>

**Problema:** <br> 
En la sección de perfil de fisioterapeuta, se encuentran diversos botones “Download”; sin embargo, estos no tienen una función en específica, ya que toda la información de lo muestra el producto Theraphy.<br> 

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem3.1.png" width="600"><br><br>  
 
**PROBLEMA #4:** No incluye información de los ingresos exactos que se pueden obtener <br> 

**Severidad:** 2<br>  

**Heurística violada:** Information Architecture: Is it findable? <br> 

**Problema:** <br> 
En el Landing Page, se menciona el plan para fisioterapeutas donde se muestra que este puede generar ingresos a través de la aplicación. No obstante, no se indica cuánto es el monto exacto o aproximado que se pude obtener. <br> 
  
<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem4.png" width="600"><br><br>
 
**PROBLEMA #5:** La opción Diagnósticos tiene un nombre inadecuado <br> 

**Severidad:** 1<br>  

**Heurística violada:** Information Architecture: Is it findable?<br>  

**Problema:** <br> 
El nombre otorgado a la vista Diagnósticos no es del todo correcto. El término que encaja a la perfección es “Prescripciones”. Por ello, el usuario puede confundir la función de esta pestaña o incluso no encontrar la vista que está buscando por la confusión del nombre. <br> 

 <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem5.png" width="600"><br><br>


**PROBLEMA #6:** No hay mensaje que confirme tu proceso de separación de cita<br>  

**Severidad:** 2<br>  

**Heurística violada:** Usability: Libertad y control de uso<br>  

**Problema:** <br>  
Al momento de finalizar una separación de cita médica, no se confirma si el proceso fue exitoso o no, lo que genera confusión en el usuario. Puesto que, Theraphy lo redirecciona automáticamente a las citas médicas generales, por lo que el paciente no sabe si finalizó el proceso o no, lo que le quita el control total de la aplicación.<br>  

  <img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem6.png" width="600"><br><br>
 
**PROBLEMA #7:** El botón “English - Spanish” no realiza ninguna función<br>  

**Severidad:** 1 <br> 

**Heurística violada:** Information Architecture: Is it usable?<br>  

**Problema:** <br>  
En el Landing Page de Theraphy, exista el botón de cambio de lenguaje. Sin embargo, este no realiza ninguna función actualmente, por lo que su existencia no tiene un significado en la actual versión de la plataforma.<br>  
  
<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ValidateInterviews/Problem7.png" width="600"><br><br>



### 6.4. Video About-the-Product.
A continuación, se presenta el video About The Product. Este tiene como objetivo presentar nuestro producto al público, por lo que en él se mostrarán las principales características con las que cuenta Theraphy. Asimismo, se añadió la experiencia de un usuario con su interacción con el software desarrollado. 
Imagen del video: 

<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/ATP.png" width="600"><br><br>

Link: https://upcedupe-my.sharepoint.com/personal/u20201a836_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201a836_upc_edu_pe%2FDocuments%2Fabout%20the%20product%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview

