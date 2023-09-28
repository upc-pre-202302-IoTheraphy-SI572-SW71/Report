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



