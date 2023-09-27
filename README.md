## Capítulo IV: Solution Software Design
### 4.1. Strategic-Level Domain-Driven Design
A continuación, el equipo explicará el proceso de toma de decisiones a nivel estratégico siguiendo el enfoque  Domain-Driven Design.
 - 4.1.1. EventStorming<br><br>
	El EventStorming es una técnica colaborativa para comprender procesos de negocio complejos y, en el contexto de Domain-Driven Design, puede utilizarse para identificar y definir Bounded Contexts, delimitando áreas lógicas de un sistema con modelos de dominio específicos.
	Para observar el Eventstorming, ingrese a este link: https://miro.com/app/board/uXjVPEw1bPU=/?share_link_id=127518100018
	- 4.1.1.1. Candidate Context Discovery.<br><br>
		Para el desarrollo del EventStorming, el equipo ha desarrollado los siguientes pasos:<br><br>
			●	Step 1: Unstructured Exploration<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%201.jpg" width="600"><br><br>
 			●	Step 2: Timelines<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%202.jpg" width="600"><br><br>
   			●	Step 3: Paint Points<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%203.jpg" width="600"><br><br>
   			●	Step 4: Pivotal Points<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%204.jpg" width="600"><br><br>
   			●	Step 5: Commands<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%205.jpg" width="600"><br><br>
   			●	Step 6: Policies<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%206.jpg" width="600"><br><br>
   			●	Step 7: Read Models<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%207.jpg" width="600"><br><br>
   			●	Step 8: External Systems<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%208.jpg" width="600"><br><br>
   			●	Step 9: Aggregates<br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%209.jpg" width="600"><br><br>
   			●	Step 10: Bounded Contexts<br>
   				**User Management Context**<br>
       			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011.jpg" width="600"><br><br>
	  			**Health Records and Expertise Context**<br>
       			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(1).jpg" width="600"><br><br>
	  			**Physiotherapist Selection and Review Management Context**<br>
       			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(4).jpg" width="600"><br><br>
	  			**Patient Engagement and Therapy Coordination Context**<br>
       			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(2).jpg" width="600"><br><br>
	  			**Payment Management Context**<br>
       			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(3).jpg" width="600"><br><br>
			<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2010.jpg" width="600"><br><br>

   - 4.1.1.2. Domain Message Flows Modeling<br><br>
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(5).jpg" width="600"><br><br>
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(6).jpg" width="600"><br><br>
  		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(7).jpg" width="600"><br><br>
    		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(8).jpg" width="600"><br><br>
      		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(9).jpg" width="600"><br><br>
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(10).jpg" width="600"><br><br>
  		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(11).jpg" width="600"><br><br>
    		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2011%20(12).jpg" width="600"><br><br>

      	- 4.1.1.3. Bounded Context Canvases.<br><br>
       		A continuación presentamos los Bounded Context Canvas que nos permiten conocer a mayor detalle cómo se relacionan los bounded context.<br>
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2012.jpg" width="600"><br><br>
  		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2012%20(1).jpg" width="600"><br><br>
    		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2012%20(2).jpg" width="600"><br><br>
      		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2012%20(3).jpg" width="600"><br><br>
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Bound%20Contexts/EventStorming%20-%20Frame%2012%20(4).jpg" width="600"><br><br>

  - 4.1.2. Context Mapping.<br><br>
	- **User Management Context - Health Records and Expertise Management Context:** <br> 
	**Conformist:** La relación entre los contextos es "conformist" (conformista) porque los conceptos "patient" y "physiotherapist" se ajustan o conforman a las definiciones de usuario que existen en el contexto "users". En otras palabras, comparten una similitud en su modelo de usuario, y los perfiles de "paciente" y "fisioterapeuta" son variaciones o extensiones de la entidad de usuario central en el contexto "users". <br> Esta relación "conformist" sugiere que el contexto "profile" se basa en el modelo de usuario definido en el contexto "users". Los perfiles de pacientes y fisioterapeutas pueden incluir atributos y comportamientos adicionales específicos de su función, pero heredan la base común de la entidad de usuario del contexto "users". Esto puede simplificar la gestión de usuarios y la consistencia de datos en el sistema al reutilizar la definición central de usuario en lugar de duplicarla en varios contextos.<br>
   	<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Conformist.jpg" width="100"><br><br>
	
 	- **User Management Context - Physiotherapist Selection and Review Management Context:** <br>
	**Customer-Supplier (Cliente-Proveedor):** En este patrón, uno de los contextos actúa como el cliente que consume servicios o información del otro, que actúa como el proveedor. En este caso, "Physiotherapist Selection and Review Management Context" podría ser el cliente que necesita información de usuarios (posiblemente para autenticación, autorización o gestión de perfiles), y "User Management Context" sería el proveedor que suministra esa información.<br>
	<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Customer%20spullier.jpg" width="400"><br><br>

	- **User Management Context - Patient Engagement and Therapy Coordination Management Context:** <br>
	**Customer-Supplier (Cliente-Proveedor):** Similarmente, este contexto también actuaría como cliente y requeriría información de usuarios, posiblemente para gestionar perfiles de pacientes u otros propósitos relacionados con la gestión de pacientes. Nuevamente, "User Management Context" podría ser el proveedor de esta información. <br> Esta estructura de cliente-proveedor permite una separación de preocupaciones y una reutilización eficiente de la funcionalidad relacionada con la gestión de usuarios, ya que "User Management Context" se encargaría de proporcionar esta información centralizada a los otros contextos que la necesiten.<br>
	<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Customer%20spullier.jpg" width="400"><br><br>

	- **Patient Engagement and Therapy Coordination Management Context - Payment Management Context:** <br>
	**Partnership (Asociación):** Este patrón se utiliza cuando dos contextos trabajan juntos en una relación de colaboración cercana, donde ambos se benefician mutuamente y comparten información de manera bidireccional. En este caso, "Patient Engagement and Therapy Coordination Management Context" y "Payment Management Context" pueden ser considerados socios, ya que trabajan en conjunto para coordinar la terapia y gestionar los pagos relacionados con los servicios de atención médica.<br>
	<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/paterniship.jpg" width="400"><br><br>
 
 - 4.1.3. Software Architecture.<br><br>
 	En esta parte, el equipo muestra y describe la representación de la Arquitectura de Software de la solución, utilizando el enfoque del modelo C4
	- 4.1.3.1. Software Architecture System Landscape Diagram.<br><br>
		Ofrece una visión integral de la interacción entre los usuarios (Patients y Physiotherapists), sistemas externos como el correo electrónico y la pasarela de pagos, y la API de Terapia dentro de la arquitectura de software. Este diagrama permite comprender cómo estos componentes se conectan y contribuyen al funcionamiento general de la aplicación o plataforma de software, facilitando la toma de decisiones y la comunicación efectiva en el desarrollo del sistema
	<img src="https://media.discordapp.net/attachments/1016712858240823300/1149662283140710470/image.png?width=742&height=662" width="400"><br><br>

	- 4.1.3.2. Software Architecture Context Level Diagrams.<br><br>
		El diagrama de contexto C4 muestra cómo nuestro sistema interactúa con elementos externos, proporcionando una visión clara de su entorno y las conexiones fundamentales. A continuación mostramos nuestro diagrama de contexto.
	<img src="https://media.discordapp.net/attachments/1016712858240823300/1149601271758733323/image.png?width=1001&height=662" width="400"><br><br>

 	- 4.1.3.3. Software Architecture Container Level Diagrams.<br><br>
		Son representaciones visuales de la arquitectura de software a nivel de contenedores, mostrando cómo los diferentes componentes y servicios se agrupan y se comunican entre sí dentro de un sistema o aplicación. Estos diagramas ofrecen una vista detallada de la organización de los contenedores de software, lo que facilita la comprensión de la estructura y las interacciones en la arquitectura general. A continuación, mostramos nuestro diagrama de contenedores:
	<img src="https://media.discordapp.net/attachments/1016712858240823300/1149666464241045575/image.png?width=908&height=662" width="400"><br><br>

   	- 4.1.3.4. Software Architecture Deployment Diagrams.<br><br>
    		Son representaciones visuales que muestran cómo los componentes de software se despliegan y se ejecutan en la infraestructura de hardware o en un entorno de producción. A continuación, presentamos nuestro diagrama:
	<img src="https://media.discordapp.net/attachments/1016712858240823300/1149668010601238579/image.png?width=880&height=662" width="400"><br><br>


### 4.2. Tactical-Level Domain-Driven Design 
El equipo presenta y detalla su enfoque táctico para diseñar la solución de software en cada uno de los Bounded Contexts. En otras palabras, se explica la estrategia concreta para abordar y desarrollar la implementación técnica de cada contexto delimitado en la solución de software.
 - 4.2.1. Bounded Context: User Management Context <br><br>
 	- 4.2.1.1. Domain Layer.<br><br>
		    **Capa de Dominio (Domain Layer):**
		
		En esta capa, se encuentra el núcleo de la aplicación relacionado con la gestión de usuarios y las reglas de negocio relacionadas con la autenticación y la autorización.
		
	 	Entities (Entidades):
		
			User: Representa un usuario del sistema con atributos como ID, nombre de usuario, contraseña encriptada, roles, etc.
			
			Role: Representa un rol de usuario con atributos como ID, nombre y descripción.
		
		Value Objects (Objetos de Valor):
		
			Email: Un objeto de valor para representar direcciones de correo electrónico válidas.
			
			Password: Un objeto de valor para manejar contraseñas de manera segura.
		
  		Aggregates (Agregados):
		
			UserAggregate: Puede ser un agregado que incluye la entidad de usuario y los roles relacionados.
		
		Factories (Fábricas):
		
			UserFactory: Para crear instancias de usuarios y roles de manera consistente.
		
		Domain Services (Servicios de Dominio):
		
			AuthenticationService: Puede ser un servicio de dominio encargado de la autenticación de usuarios.
			
		Repositories (Repositorios):
		
			UserRepository: Define cómo se accede y se persisten los usuarios y roles.

	- 4.2.1.2. Interface Layer.<br><br>
			**Capa de Interfaz (Interface Layer):**
		
		En esta capa, se encuentran las clases relacionadas con la interacción del usuario y la presentación.
		
		Controllers (Controladores):
		
			UserController: Controla las solicitudes relacionadas con la gestión de usuarios, como registro, inicio de sesión, administración de roles, etc.
   
		Consumers (Consumidores):
		
		Pueden estar presentes si se utiliza una arquitectura de mensajes para la gestión de usuarios, como procesar eventos de registro de usuarios.
		Capa de Aplicación (Application Layer):
		
		Command Handlers (Manejadores de Comandos):
		
			RegisterUserCommandHandler: Maneja el proceso de registro de nuevos usuarios.
			AuthenticateUserCommandHandler: Maneja el proceso de autenticación de usuarios.

	- 4.2.1.3. Application Layer.<br><br>
 		
		Command Handlers (Manejadores de Comandos):

			RegisterUserCommandHandler: Maneja el proceso de registro de nuevos usuarios.
			AuthenticateUserCommandHandler: Maneja el proceso de autenticación de usuarios.
   
	- 4.2.1.4. Infrastructure Layer.<br><br>
	 		**Capa de Infraestructura (Infrastructure Layer):**
	
		En esta capa se encuentran las clases que acceden a servicios externos, bases de datos y otros recursos.
		
		Repositories Implementations (Implementaciones de Repositorios):
		
			UserRepositoryDB: Implementación concreta del repositorio que interactúa con una base de datos para almacenar y recuperar datos de usuarios y roles.
   
		External Services Clients (Clientes de Servicios Externos):
		
		Puede incluir clases para interactuar con servicios externos, como sistemas de correo electrónico para notificaciones.

 	- 4.2.1.6. Bounded Context Software Architecture Component Level Diagrams.<br><br> 
		A continuación, se presenta el diagrama de componentes para este bounded Context:<br> 
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149655617531813989/image.png?width=682&height=662" width="400"><br><br>

	- 4.2.1.7. Bounded Context Software Architecture Code Level Diagrams.<br>
	En esta sección, el equipo muestra y describe diagramas que proporcionan un nivel de detalle más profundo sobre cómo se implementan los componentes dentro del contexto delimitado.<br>
		- 4.2.1.7.1. Bounded Context Domain Layer Class Diagrams.<br><br>  
		A continuación, se presenta el diagrama de clases para este bounded Context:
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149682699930443796/Z4O3rMJECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAgAABAgQIECBAoFuBfwG1J3Oa8vtBsQAAAABJRU5ErkJggg.png?width=866&height=662" width="400"><br><br>
		- 4.2.1.7.2. Bounded Context Database Design Diagram.<br><br> 
		A continuación, se presenta el modelo de base de datos para este bounded Context:
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149663856218615889/ER7bKPWnyXgAAAABJRU5ErkJggg.png?width=1305&height=523" width="400"><br><br>
 - 4.2.2. Bounded Context: Health Records and Expertise Context <br><br>
 	- 4.2.2.1. Domain Layer.<br><br>
		  **Capa de Dominio (Domain Layer):** <br><br>
		
		En esta capa, se encuentra el núcleo de la aplicación relacionado con la gestión de registros de salud y la especialización médica, así como las reglas de negocio relacionadas con estos aspectos.
		
		Entities (Entidades):
		
			HealthRecord: Representa un registro de salud de un paciente con atributos como ID, diagnósticos, tratamientos, medicamentos recetados, etc.
			MedicalSpecialization: Representa una especialización médica con atributos como ID, nombre y descripción.
			Value Objects (Objetos de Valor):
			
			Diagnosis: Un objeto de valor para representar diagnósticos médicos.
			Medication: Un objeto de valor para representar medicamentos recetados.

		Aggregates (Agregados):
		
			HealthRecordAggregate: Puede ser un agregado que incluye la entidad de registro de salud y los diagnósticos, tratamientos, etc., relacionados.
		Factories (Fábricas):
		
			HealthRecordFactory: Para crear instancias de registros de salud de manera consistente.

		Domain Services (Servicios de Dominio):
		
			HealthRecordManagementService: Puede ser un servicio de dominio encargado de la gestión de registros de salud.
			MedicalExpertiseService: Para gestionar y consultar especializaciones médicas.

		Repositories (Repositorios):
		
			HealthRecordRepository: Define cómo se accede y se persisten los registros de salud.
			MedicalSpecializationRepository: Define cómo se acceden y se persisten las especializaciones médicas.

	- 4.2.2.2. Interface Layer.<br><br>
		En esta capa, se encuentran las clases relacionadas con la interacción del usuario y la presentación.
		
		Controllers (Controladores):
		
			HealthRecordController: Controla las solicitudes relacionadas con la gestión de registros de salud, diagnósticos, etc.
			MedicalSpecializationController: Controla las solicitudes relacionadas con la gestión de especializaciones médicas.

		Consumers (Consumidores):
		
			Pueden estar presentes si se utiliza una arquitectura de mensajes para la gestión de registros de salud y especializaciones médicas, como procesar eventos relacionados.
	- 4.2.2.3. Application Layer.<br><br> 
		Command Handlers (Manejadores de Comandos):

			CreateHealthRecordCommandHandler: Maneja la creación de nuevos registros de salud.
			AddDiagnosisCommandHandler: Maneja la adición de diagnósticos a registros de salud.
			Otros manejadores relacionados con la gestión de especializaciones médicas.

	- 4.2.2.4. Infrastructure Layer.<br><br> 
		En esta capa se encuentran las clases que acceden a servicios externos, bases de datos y otros recursos.
		
		Repositories Implementations (Implementaciones de Repositorios):
		
			HealthRecordRepositoryDB: Implementación concreta del repositorio que interactúa con una base de datos para almacenar y recuperar datos de registros de salud.
			MedicalSpecializationRepositoryDB: Implementación concreta del repositorio que interactúa con una base de datos para almacenar y recuperar datos de especializaciones médicas.
   
		External Services Clients (Clientes de Servicios Externos):
		
			Puede incluir clases para interactuar con servicios externos, como sistemas de correo electrónico para notificaciones o consultas de datos médicos externos.
   
 	- 4.2.2.6. Bounded Context Software Architecture Component Level Diagrams. <br><br>
		A continuación, se presenta el diagrama de componentes para este bounded Context: 
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149655663572688937/image.png?width=667&height=662" width="400"><br><br>

	- 4.2.2.7. Bounded Context Software Architecture Code Level Diagrams.<br>
 		En esta sección, el equipo muestra y describe diagramas que proporcionan un nivel de detalle más profundo sobre cómo se implementan los componentes dentro del contexto delimitado.

   		- 4.2.2.7.1. Bounded Context Domain Layer Class Diagrams.<br><br>  
		A continuación, se presenta el diagrama de clases para este bounded Context: 
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/Clases%202.png" width="400"><br><br>
  
		- 4.2.2.7.2. Bounded Context Database Design Diagram.<br><br> 
		A continuación, se presenta el modelo de base de datos para este bounded Context:
		<img src="https://raw.githubusercontent.com/upc-pre-202302-IoTheraphy-SI572-SW71/ReportAssets/main/image.png" width="400"><br><br>

  - 4.2.3. Bounded Context:  Physiotherapist Selection and Review Management Context <br><br>
  	- 4.2.3.1. Domain Layer.<br><br>
		En esta capa, se encuentra el núcleo de la aplicación relacionado con la selección de fisioterapeutas y la gestión de revisiones, así como las reglas de negocio relacionadas con estos aspectos.
		
		Entities (Entidades):
		
			Physiotherapist: Representa un fisioterapeuta con atributos como ID, nombre, especialidades, horarios de trabajo, etc.
			Review: Representa una revisión de un fisioterapeuta con atributos como ID, calificación, comentario, etc.
		
  		Value Objects (Objetos de Valor):
		
			WorkingHours: Un objeto de valor para representar horarios de trabajo.
			Rating: Un objeto de valor para representar calificaciones.

		Aggregates (Agregados):
		
			PhysiotherapistAggregate: Puede ser un agregado que incluye la entidad de fisioterapeuta y las revisiones relacionadas.
		
  		Factories (Fábricas):
		
			PhysiotherapistFactory: Para crear instancias de fisioterapeutas de manera consistente.
			ReviewFactory: Para crear instancias de revisiones de manera consistente.

		Domain Services (Servicios de Dominio):
		
			PhysiotherapistSelectionService: Puede ser un servicio de dominio encargado de la selección de fisioterapeutas.
			ReviewManagementService: Para gestionar las revisiones y calificaciones.
		
  		Repositories (Repositorios):
		
			PhysiotherapistRepository: Define cómo se accede y se persisten los datos de fisioterapeutas.
			ReviewRepository: Define cómo se accede y se persisten los datos de revisiones.
	
 	- 4.2.3.2. Interface Layer.<br><br>
		En esta capa, se encuentran las clases relacionadas con la interacción del usuario y la presentación.
		
  		Controllers (Controladores):
		
			PhysiotherapistController: Controla las solicitudes relacionadas con la selección de fisioterapeutas y la gestión de revisiones.
			ReviewController: Controla las solicitudes relacionadas con la creación y consulta de revisiones.
		
  		Consumers (Consumidores):
		
			Pueden estar presentes si se utiliza una arquitectura de mensajes para la gestión de fisioterapeutas y revisiones.
	
 	- 4.2.3.3. Application Layer.<br><br>
  
		Command Handlers (Manejadores de Comandos):

			SelectPhysiotherapistCommandHandler: Maneja el proceso de selección de fisioterapeutas.
			CreateReviewCommandHandler: Maneja la creación de revisiones y calificaciones.
			Otros manejadores relacionados con la gestión de fisioterapeutas y revisiones
	
 	- 4.2.3.4.  Infrastructure Layer.<br><br>
		
		En esta capa se encuentran las clases que acceden a servicios externos, bases de datos y otros recursos.
		
		Repositories Implementations (Implementaciones de Repositorios):
		
			PhysiotherapistRepositoryDB: Implementación concreta del repositorio que interactúa con una base de datos para almacenar y recuperar datos de fisioterapeutas.
			ReviewRepositoryDB: Implementación concreta del repositorio que interactúa con una base de datos para almacenar y recuperar datos de revisiones.

		External Services Clients (Clientes de Servicios Externos):
			
			Puede incluir clases para interactuar con servicios externos, como sistemas de notificación de citas o servicios de terceros para verificar la información de fisioterapeutas.

 	- 4.2.3.6.  Bounded Context Software Architecture Component Level Diagrams <br><br>
		A continuación, se presenta el diagrama de componentes para este bounded Context:
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149655704655904861/image.png?width=498&height=662" width="400"><br><br>

  	- 4.2.3.7.  Bounded Context Software Architecture Code Level Diagrams. <br><br>
		En esta sección, el equipo muestra y describe diagramas que proporcionan un nivel de detalle más profundo sobre cómo se implementan los componentes dentro del contexto delimitado.
		- 4.2.3.7.1. Bounded Context Domain Layer Class Diagrams. <br><br>
		A continuación, se presenta el diagrama de clases para este bounded Context:
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149683624296316938/5BM9vTdyAAAAABJRU5ErkJggg.png?width=790&height=662" width="400"><br><br>
  
		- 4.2.3.7.2. Bounded Context Database Design Diagram. <br><br> 
		A continuación, se presenta el modelo de base de datos para este bounded Context: 
		<img src="https://media.discordapp.net/attachments/1016712858240823300/1149672129709756446/wPWzvIdJ50VDQAAAABJRU5ErkJggg.png?width=588&height=662" width="400"><br><br>
 
