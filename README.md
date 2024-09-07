
# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
Ez.vet tiene como meta principal ofrecer un sistema seguro para locales de veterinaria que facilite el servicio para los usuarios y clientes.
<strong>Identidad por segmento:</strong>


### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tag
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
Se presentan tres niveles del modelo C4 en el proyecto para tener un mejor enfoque del proyecto que se desarrolla.
### 4.6.1. Software Architecture Context Diagram
El diagrama de contexto presenta una visión global de ez.vet, destacando las principales interacciones entre el sistema y los actores externos. ez.vet cuenta con dos tipos de usuarios principales: dueños de mascotas y veterinarios. Además, interactúa con dos sistemas externos clave: Payment System para realizar pagos y Email System para enviar emails de verificación.
(falta imagen)
### 4.6.2. Software Architecture Container Diagrams
 El diagrama de contenedores detalla los principales componentes del sistema y cómo se relacionan entre sí. ez.vet consta de los siguientes elementos clave: Aplicación Web y la landing page. Además  realizan llamadas a una API central (Api Application), que sirve como el motor que procesa las solicitudes y gestiona la lógica de negocio. También se visualizan las tecnologías específicas que se usarán en el desarrollo de la aplicación web, como frameworks front-end, back-end, bases de datos, entre otros.
(falta imagen) 

### 4.6.3. Software Architecture Components Diagrams
Este diagrama profundiza en la API Application, mostrando sus diferentes Bounded Contexts. Cada contexto delimitado representa un área funcional del sistema, con responsabilidades claras y separadas. Proporciona una vista más detallada de cómo se organiza la lógica de negocio dentro de la aplicación y cómo los distintos módulos interactúan entre sí para cumplir con los requisitos funcionales del sistema.
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
## 4.8.1. Database Diagram