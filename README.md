Para agregar el: 

. Splash Screen

. Icono personalizado

Primero nos vamos a ionic Docs con el siguiente enlace https://ionicframework.com/docs/native/splash-screen 
En la documentacion se indica que para la pantalla de bienvenida hay que ejecutar el siguiente comando. "npm install @capacitor/splash-screen" una vez realiazado nos vamos al archivo "capacitor.config.ts" 
en donde agregaremos los plugins necesarios para la pantalla de bienvenida como el color, showSpinner. Para finalizar nos dirigimos al archivo "app.component.ts" donde colocamos una funcion para la duracion de la pantalla.

![image](https://github.com/user-attachments/assets/b1883103-6812-4218-88b7-92da30d53428)
![image](https://github.com/user-attachments/assets/84799288-7316-4e2c-b2ab-02c220d8fa7d)
![image](https://github.com/user-attachments/assets/9535bd17-0fe7-4d73-834c-2a1f0a5b9ff1)


Continuando la pantalla y el icono personalizado nos dirigimos a capacitor DOCS con el siguiente enlace https://capacitorjs.com/docs/guides/splash-screens-and-icons
En la documentación se indica que se debe installar las herramientas y eso se hace con el siguiente comando "npm install @capacitor/assets --save-dev" una vez finalizado creamos una carpeta llamada "assets" en el directorio
raiz con las imagenes para le icono y para la bienvenida con un formato definido como se nos indica en la documentacion. Por último se ejecuta el siguiente comando "npx capacitor-assets generate" que genera un archivo de manifiesto PWA 

![image](https://github.com/user-attachments/assets/86bd5bb2-8023-4b3c-93d5-fc89d1a7bef3)
![image](https://github.com/user-attachments/assets/c7af0a08-c9f2-413f-9c7e-0da6ee8a4879)
![image](https://github.com/user-attachments/assets/ed934765-887d-4123-a3b7-0cf15ba0baa3)

Para finalizar creamos la APK y la probamos desde el dispositivo.
![image](https://github.com/user-attachments/assets/f30fa363-7748-422c-978d-ba6dec045e91)
![image](https://github.com/user-attachments/assets/7fbe67e8-a07e-4168-a048-9f92b419eb35)

Como se puede visualizar se cambio el icono y se agrego la pantalla de bienvenida.


