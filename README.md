# PruebaTecnica
PARA EJECUTAR EN ENTORNO ECLIPSE USAR PREFERIBLEMENTE UN NUEVO WORKSPACE:

1.- IMPORTAR EL ARCHIVO WAR DESDE CARPETA PROBLEMA2, SIN INCLUIR LIBRERIAS
2.- UNA VEZ IMPORTADO, CONVERTIRLO A MAVEN PROJECT: SOBRE EL PROYECTO > CONFIGURE > CONVERT MAVEN..
3.- EN EL POM AGREGAR LA DEPENDENCIA CONTENIDA EN EL TXT DENTRO DE LA CARPETA EJEMPLO2
4.- AGREGAR LA LIBRERIA DE LA LISTA SIMPLE ENLAZADA AL PROYECTO EN EL BUILD PATH, SE ENCUENTRA EN LA CARPETA PROBLEMA1
5.- CONFIGURAR EL SERVIDOR DE PREFERENCIA (SE USO APACHE TOMCAT 9.0)
6.- CREAR UN NUEVO WEB SERVICE DESDE FILE > NEW > WEB SERVICE > SELECCIONAR CLIENTESERVICEIMPL > EL SERVICIO DEBERIA ESTAR FUNCIONANDO
EN LA URL GENERADA (EN MI CASO http://localhost:8080/WebService/services/ClienteServiceImpl?wsdl)
7.- IMPORTAR EL CLIENTE DESDE UNA CARPETA, SELECCIONAR EL DIRECTORIO PROBLEMA1, UBICADO DENTRO DE LA CARPETA PROBLEMA1
8.- EJECUTAR EL MAIN DEL CLIENTEWEB COMO UNA JAVA APLICATION, DEBERIA FUNCIONAR CORRECTAMENTE, DESPLEGAR EN LA CONSOLA 
LA INFORMACION QUE SE AÑADIO A LA LISTA SLL.
