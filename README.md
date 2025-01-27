**INTEGRANTES**  
Daniel Alejandro Diaz Camelo.  
Vicente Garzon Rios.  

**INVESTIGACION**
1. El parametro "package" es una fase, es decir un paso en el ciclo de vida del desarrollo. Tiene como objetivo tomar el codigo compilado y lo empaqueta en un formato distribuible, como JAR. Otros parametros que se pueden enviar al comando mvn son: validate, compile, test, integration-test, verify, install, deploy, clean, site.

**PASOS**
1. Verificamos la version de Maven
![alt text](assets/VersionMaven.png)
2. Creamos el proyecto en Maven
![alt text](assets/creation_maven.png)
3. Verificamos el conjunto de archvios y directorios del proyecto creado
![alt text](assets/cmd_tree.png)
4. Creamos el entorno
![alt text](assets/creacion_entorno.png)
5. Modificamos las propiedades del archvio Pom
![alt text](assets/properties_pom.png)
6. Compilamos el proyecto Maven 
![alt text](assets/mvn_package.png)  
7. Añadimos el plugin para el ejecutable en pom 
![alt text](assets/plugin_pom.png)  
8. Ejecutamos el archvio de Java App
![alt text](assets/mvn_clean_package.png)  
![alt text](assets/mvn_package2.png)  
![alt text](assets/mvn_exec.png) 