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
   
