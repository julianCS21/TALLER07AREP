# AREP07 : APLICACIÓN DISTRIBUIDA SEGURA EN TODOS SUS FRENTES

Proyecto para construir servicios web seguros por medio del protocolo HTTPS

### Prerequisitos

Para elaborar este proyecto se requirio de : 


Maven: Apache Maven es una herramienta que maneja el ciclo de vida del programa.



Git: Es un sistema de control de versiones distribuido (VCS).



Java 17: Java es un lenguaje de programación de propósito general orientado a objetos, portátil y muy versátil.



AWS : Es una colección de servicios de computación en la nube pública que en conjunto forman una plataforma de computación en la nube, ofrecidas a través de Internet por Amazon.com

### Instalación

Instalamos Java en nuestras instancias EC2, tambien Git y Maven


---

	 sudo yum install java-17-amazon-corretto.x86_64
  
	
---


---

	 sudo yum install git
  
	
---


---

	 sudo yum install maven
  
	
---

Clonamos el repositorio

---

     git clone https://github.com/julianCS21/TALLER07AREP.git
---
  

Accedemos a la carpeta raiz del proyecto


---

     cd TALLER07AREP
---

Hacemos la construcción del proyecto

---

	 mvn clean install
  
	
---



### Corriendo


![image](https://github.com/julianCS21/TALLER07AREP/assets/96396177/1f066786-5897-4ef0-a2f0-d9c4b242a1b0)



Corremos el proyecto Java en sus respectivas instancias


---

	 java -cp "target/classes:target/dependency/*" org.example.controllers.Login
  
	
---

---

	  java -cp "target/classes:target/dependency/*" org.example.controllers.MainPage
  
	
---



Y a traves de nuestro navegador de confianza accedemos a la url

---

	  {DnspublicodelaEC2delLoginService}:5000/login.html
  
	
---

y nos debe aparecer algo asi

![image](https://github.com/julianCS21/TALLER07AREP/assets/96396177/fe539ddd-ce24-4711-88ec-0d4e6f809740)


Una vez iniciamos sesion

![image](https://github.com/julianCS21/TALLER07AREP/assets/96396177/8c7cf082-91bf-4384-b273-6eab842239df)


Usuario usado

Usuario : admin



Contraseña : tiktak




### Corriendo test

Ejecutamos el comando

	mvn test
	
---


### Arquitectura del programa.


![image](https://github.com/julianCS21/TALLER07AREP/assets/96396177/4556ac70-b7eb-4799-baa5-bbc5d92e6f94)








## Video prueba del despliegue 

https://www.youtube.com/watch?v=IfK-iaqFWG8&ab_channel=JulianCastillo

El video demuestra que esta desplegado en la nube de AWS, ademas muestrala conexion entre los dos backend a traves del protocolo HTTPS



## Construido con

* [Maven](https://maven.apache.org/): Apache Maven es una herramienta que estandariza la configuración del ciclo de vida del proyecto.
* [Git](https://rometools.github.io/rome/):  Es un sistema de control de versiones distribuido (VCS).
* [Intellj](https://www.jetbrains.com/es-es/idea/): IntelliJ IDEA es un IDE que ayuda a los desarrolladores a escribir, depurar y administrar código de manera más eficiente y efectiva, con muchas características que facilitan el proceso de desarrollo de software.
* [Java 17](https://www.java.com/es/): Lenguaje de programación de propósito general con enfoque a el paradigma de orientado a objetos, y con un fuerte tipado de variables.
* [Html](https://developer.mozilla.org/es/docs/Learn/Getting_started_with_the_web/HTML_basics): es un lenguaje de marcado que estructura una página web y su contenido.
* [JavaScript](https://developer.mozilla.org/es/docs/Learn/JavaScript/First_steps/What_is_JavaScript): lenguaje de programación que los desarrolladores utilizan para hacer paginas web dinamicas.
* [CSS](https://developer.mozilla.org/es/docs/Web/CSS) Lenguaje para darles estilos a paginas web.
* [AWS](https://aws.amazon.com/es/free/?trk=8fa18207-f2c2-4587-81a1-f2a3648571b3&sc_channel=ps&ef_id=CjwKCAjwseSoBhBXEiwA9iZtxmEwAgfk7jPE4NlzdkF60BOim6V2loEW5eNT7e8yJcbyO0g8dZpJaBoCRIEQAvD_BwE:G:s&s_kwcid=AL!4422!3!647999789205!e!!g!!aws!19685287144!146461596896&gclid=CjwKCAjwseSoBhBXEiwA9iZtxmEwAgfk7jPE4NlzdkF60BOim6V2loEW5eNT7e8yJcbyO0g8dZpJaBoCRIEQAvD_BwE&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all) colección de servicios de computación en la nube pública que en conjunto forman una plataforma de computación en la nube


## Autor
* **[Julián David Castillo Soto](https://www.linkedin.com/in/julián-david-castillo-soto-118856216/)**  - [julianCS21](https://github.com/julianCS21)

## Licencia
**©** Julián David Castillo Soto, Estudiante de Ingeniería de Sistemas de la Universidad Escuela Colombiana de Ingeniería Julio Garavito.
