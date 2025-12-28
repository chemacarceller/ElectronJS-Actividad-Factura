# ElectronJS-Actividad-Factura

Phased development of an invoice management application (Spanish version).<br />

Phase 1 -> without data persistence (multiple versions) using OOP (UI design testing)<br />

Phase 2 -> with data persistence in files (versions with OOP based on JavaScript import and NodeJS require modules, and also a more advanced version based on the classic Model-View-Controller pattern, which will be used for the following phases).<br />

Phase 3 -> an exercise from Phase 2, MVC version, adding implementation of IPC communication channels using preload.js and incorporation of additional windows, menus, and native dialog boxes, among other things. This phase involves testing the objects provided by ElectronJS.

Phase 4 -> Exercise from Phase 3 (single version) (MVC, IPC, ElectronJS objects) but replacing data persistence in files with data persistence in relational databases (MySQL and SQLite) and NoSQL (MongoDB), changing the classic MVC schema to an Extended Model-View-Controller (with Services and Repositories classes), as well as using the mongoTool module in the NoSQL version. For the MySQL and MongoDB versions, a text file will specify how to set up the remote database and how to configure access to it.

Phase 5 -> Exercise from Phase 4 (single version) implemented with the Vue.js framework. Reactive programming. The advanced MVC framework from Phase 4 is reinterpreted.

Phase 6 -> Phase 4 exercise (single version) adding a data access API to an Express server (client-side project: desktop application / server-side project: provides a data access API). This means setting up an Express server in a virtual machine or container that provides an API to access data from different databases (MySQL and MongoDB) installed in the same virtual machine or container as Express. The application accesses the API using the Fetch API.


===================================================================================================================================


Desarrollo por fases de una actividad de gestión de facturas (aplicación en español).<br />

Fase 01 -> sin persistencia de datos (varias versiones) con POO (pruebas de diseño UI) <br />

Fase 02 -> con persistencia de datos en ficheros (versiones con POO basado en módulos javascript import y NodeJS require y además una version más avanzada basada en el Modelo-Vista-Controlador clásico que será el modelo que se utilizará para las distintas fases siguientes.<br />

Fase 03 -> ejercicio de la Fase 2 version MVC añadiendo implementación de canales de comunicación IPC utilizando preload.js e incorporación de ventanas adicionales, menus y cajas de dialogo nativas entre otras cosas. En esta fase se trata de probar los objetos que nos proporciona ElectronJS<br />

Fase 04 -> ejercicio de la Fase 3 (versión única) (MVC, IPC, objetos Electronjs) pero sustituyendo la persistencia de datos en ficheros por la persistencia de datos en BBDD relacionales (MySQL y SQLite) y No-SQL (MongoDB) cambiando el esquema MVC clásico por un  Modelo Vista Controlador Extendido (con clases Services y clases Repositories), así como la utilización del modulo propio mongoTool en la versión No-SQL. Para la versión MySQl y la versión MongoDB se especificará en un fichero de texto cómo ha de montarse la base de datos remota y como configurar el acceso a ella<br />

Fase 05 -> ejercicio de la Fase 4 (versión única) implementado con framework Vue.js Programación reactiva. Se reinterpreta el MVC avanzado de la fase 4

Fase 06 -> ejercicio de la Fase 4 (versión única) añadiendo un API de acceso a datos en un servidor Express (proyecto parte cliente (aplicación de escritorio) / parte servidora (suministra un API de acceso a datos), es decir se monta un servidor Express en una maquina virtual o un contenedor que nos proporciona un API para acceder a datos de distintas base de datos (MySQL y MongoDB) instalados en la misma máquina virtual o contenedor que Express. La aplicación accede al API mediante el Fetch API
