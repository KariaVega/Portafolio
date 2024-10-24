# Proyecto: Urban Scooter

![image](https://github.com/user-attachments/assets/d91160b2-8dfe-41a7-a86f-a368424e95e7)  
### :page_facing_up: *Documentación utilizada:* 
- Requisitos para aplicativo Web de UrbanScooter:  [Link de requisitos](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-final-project/Requisitos_de_aplicaciones_web.pdf)
- Requisitos para aplicativo Móvil de UrbanScooter: [Link de Requisitos](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-final-project/Requisitos_para_la_aplicacin_mvil.pdf)
- Requisitos para Backend de UrbanScooter: [Link de Requisitos](https://practicum-content.s3.us-west-1.amazonaws.com/new-markets/qa-final-project/ESP/1.6_Requisitos_para_el_back-end_de_la_aplicacin.pdf)

### 🛠️ *Lenguajes y herramientas utilizadas:*
<div id="header" align="left">
    
- Jira: Registro y seguimiento de errores.
- Figma: Revisión del diseño del aplicativo (UI).
- Drawio: Elaboración de mapa mental.
- DevTools: Configuración de entornos.
- Consola: Conexión a servidor remoto.
- SQL: Linea de comandos para consulta de datos.
- AVS: Emulador de pruebas y móvil fisico. 
- Apidocs: Revisión de documentación de API's
- Postman: Pruebas manuales.
- MS Office: Documentación de las pruebas.

</a>
<img decoding="async" src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white" alt="Jira"/>
<img decoding="async" src="https://img.shields.io/badge/Figma-black?style=for-the-badge&logo=Figma&logoColor=white" alt="Figma"/>
<img decoding="async" src="https://img.shields.io/badge/Drawio-D85B01?style=for-the-badge&logo=Drawio&logoColor=white" alt="Drawio"/>
<img decoding="async" src="https://img.shields.io/badge/DevTools-D80B01?style=for-the-badge&logo=Drawio&logoColor=white" alt="Drawio"/>
<img decoding="async" src="https://img.shields.io/badge/SQL-009975?style=for-the-badge&logo=mysql&logoColor=white" alt="mysql"/>
<img decoding="async" src="https://img.shields.io/badge/AVS-404040?style=for-the-badge&logo=AVS&logoColor=white" alt="AVS"/>
<img decoding="async" src="https://img.shields.io/badge/Postman-D83B01?style=for-the-badge&logo=Postman&logoColor=white" alt="Postman"/>
<img decoding="async" src="https://img.shields.io/badge/JSON-30D5C8?style=for-the-badge&logo=JSON&logoColor=white" alt="JSON"/>
<img decoding="async" src="https://img.shields.io/badge/Microsoft_Office-D86B01?style=for-the-badge&logo=microsoft-office&logoColor=white" alt="microsoft-office"/>
</a>

### :computer:  *Descripción del Aplicativo Web* 
- El proyecto Urban Scooter es una nueva aplicación que permite a los usuarios alquilar scooters eléctricos. Se realizan las pruebas en el aplicativo Web en entornos que admite estos navegadores: Opera 71 o superior, Chrome 85 o superior, y se admitirán resoluciones de pantalla de 1280x720 y 1920x1080. Para el análisis de los requisitos se realiza mapa mental para explorar todos los elementos posibles y que no se omita ningun detalle para las pruebas. Para el caso del aplicativo Web se realizazan pruebas de Interfaz (IU), validación de data y de funcionalidad. Se realiza lista de comprobación de acuerdo a los requisitos que corresponden a la pantalla *"Estado del pedido"* con 77 items. Finalmente se realiza la validación de datos del *"Formulario del pedido"* con 144 items que permiten explorar la funcionalidad principal. 

### :iphone:  *Descripción del Aplicativo Móvil* 
- El proyecto Urban Scooter para aplicación Móvil permite al usuario recibir y gestionar pedidos, entregas y recogida del alquiler de los scooters eléctricos.  Se realizan las pruebas del aplicativo en dos entornos, emulador *Android Studio* y disposito móvil real Galaxy A10s, SM-A107M, Versión Android 11, Versión de One UI Core 3.1. Modo de red LTE/3G/2G (conexión automática) Pantalla 6” instalando **aplicación nativa**. Se crean los *Casos de Prueba* con un total de 20 items, que realizan pruebas de Interrupción y de Conexión principalmente según requisitos, además de las pruebas funcionales y de interfaz inherentes a las pruebas anteriormente mencionadas.

### :fireworks: *Descripción del Backend (API)*
- El proyecto Urban Scooter para la revisión del Banckend, se realizaron pruebas correspondientes con las solitudes para ambos aplicativos *Web y Móvil* para gestionar pedidos y entregas. Se realizan las pruebas de la **"Creación de un repartidor"** para las solicitudes del aplicativo web, comprobando los campos de *Login, Password y FirstName*.  Se realizan las pruebas para **"Eliminar repartidor"**, **"Obtener un pedido por su número"** con un total de 90 items para la lista de comprobación. En conjunto para la optimización de las pruebas y su revisión, se utulizó la linea de comandos en consola, asi como la conexión a un servidor remoto.
- ####  Endpoints probados
  - [POST]  /api/v1/courier (Crear repartidor o repartidora) Campo **Login**
  - [POST]  /api/v1/courier (Crear repartidor o repartidora) Campo **Password**
  - [POST]  /api/v1/courier (Crear repartidor o repartidora) Campo **firstName**
  - [POST]  /api/v1/courier (Crear repartidor o repartidora) Campo **comprobación generales**
  - [DELETE] /api/v1/courier/:id (Eliminar repartidor o repartidora) **ID** se verifica
  - [GET] /api/v1/orders/track?t={numero del pedido} (Obtener un pedido por su número) Campo **número del pedido**
  
### 🧪 *Resultados de las pruebas:* 
 La documentación de las pruebas se desarrollaro en los siguientes archivos disponibles.
#### :file_folder: Documentación para el aplicativo Web:
  - Mapa Mental: - [Link de Mapa Mental](https://drive.google.com/file/d/1Tlq_nlohLLor2G6BXbiNE60Pcda1g8IR/view?usp=drive_link)
  - Casos de Prueba: - [Link de Casos de Prueba](https://docs.google.com/spreadsheets/d/1hvfwoMpQvsjq_H7bXEM3jE1uttxDR5SV/edit?usp=sharing&ouid=117701476691019254617&rtpof=true&sd=true)
  - Validación de datos: - [Link de Validación de Datos](https://docs.google.com/spreadsheets/d/1hvfwoMpQvsjq_H7bXEM3jE1uttxDR5SV/edit?usp=sharing&ouid=117701476691019254617&rtpof=true&sd=true)
  - Reporte y seguimiento de errores: - [Link de Reporte de Errores](https://arqkarvga.atlassian.net/issues/?jql=project+%3D+%22KV19PF%22+ORDER+BY+created+ASC&atlOrigin=eyJpIjoiOGZlNTdhYjYwYmY3NGNlY2I2MWU0Zjc2NmUxZmIyYzMiLCJwIjoiaiJ9)
#### :file_folder: Documentación para el aplicativo Móvil:
  - Casos de Prueba: - [Link de Casos de Prueba](https://docs.google.com/spreadsheets/d/1hvfwoMpQvsjq_H7bXEM3jE1uttxDR5SV/edit?usp=drive_link&ouid=117701476691019254617&rtpof=true&sd=true)
  - Reporte y seguimiento de errores: - [Link de Reporte de Errores](https://arqkarvga.atlassian.net/issues/?jql=project+%3D+%22KV19PF%22+ORDER+BY+created+ASC&atlOrigin=eyJpIjoiOGZlNTdhYjYwYmY3NGNlY2I2MWU0Zjc2NmUxZmIyYzMiLCJwIjoiaiJ9) 
#### :file_folder: Documentación para el Backend (*API*):
  - Lista de Comprobación: - [Link de Lista de Comprobación](https://docs.google.com/spreadsheets/d/1hvfwoMpQvsjq_H7bXEM3jE1uttxDR5SV/edit?usp=sharing&ouid=117701476691019254617&rtpof=true&sd=true)
  - Reporte y seguimiento de errores: - [Link de Reporte de Errores](https://arqkarvga.atlassian.net/issues/?jql=project+%3D+%22KVAPFS9G1%22+ORDER+BY+created+DESC&atlOrigin=eyJpIjoiZGU1N2M4MWY4MWQ0NGNjOWFjNWQ5Yzk2NWYxM2NlZTYiLCJwIjoiaiJ9)

### :page_facing_up: *Informe resumen:* 
 - Informe del producto:
   
Se realizaron las pruebas del producto **Urban Scooter** para aplicación Web, Móvil (Android) y de Backend;  no se registraron fallas mayores que afecten las funciones principales del aplicativo Web, pero sí en su UI, por lo que habrá que atender las fallas en el diseño.
Para lo que respecta al aplicativo Móvil, se encuentran fallos principales en las funciones de notificación **Notificación Push**, que afecta la gestión y entrega de los alquileres; en cuanto a la revisión del diseño de interfaz aunque son menores en número se debe hacer la corrección correspondiente.
Finalmente para la revisión del Backend, se registran los siguientes fallos en su formulario de creación de ususario o repartidor, que si bien no afectan sus funciones principales, se deben atender para corregir los fallos en los cambios de estados de los pedidos en el aplicativo web, el fallo de las notificaciones del pedido para concluir exitosamente la gestón de los pedidos de alquiler en el aplicativo móvil. Por lo que se notifica un estado no aprobado y de corrección del backend para una calidad y experiencia optima para los usuarios finales de ambos aplicativos.

   <div id="header" align="center"> 
       
 ![image](https://github.com/user-attachments/assets/de266974-4ad8-4c1e-8772-5b14881cd72d)
