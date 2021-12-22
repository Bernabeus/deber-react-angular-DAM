# deber-react-angular-DAM

# Integrantes
* Alba Jorge
* Dávila Bernabé

# Explicación de creación APK/Bundle con Angular
Al ejecutar el comando ionic build se crea la app para la aplicacion web del proyecto, posterior a ello se ejecuta el comando ionic cap add android para generar la carpeta andriod que nos servira para la ejecucion de la aplicacion en android, como se muestra en la siguiente figura:

![image](https://user-images.githubusercontent.com/58036212/146658889-9f963bc6-9d2c-4255-a152-da93e5f23b10.png)

Luego se ejecuta el comando ionic cap open android para abrir el proyecto en Android Studio para poder ser ejecutado con un emulador o directamente en el celular, al dar en Run instalamos la aplicacion en el movil. El funcionamiento se vera en la siguiente imagen:

![image](https://user-images.githubusercontent.com/58036212/146658906-03438c6d-19cc-4ec8-8cd0-0136f97ab33a.png)

Por ultimo se crea los archivos APK y Bundle como se vera en las siguientes imagenes:

![image](https://user-images.githubusercontent.com/58036212/146658930-18321e7b-ee0b-4f1a-aa49-f4b83fa346a8.png)
![image](https://user-images.githubusercontent.com/58036212/146658932-b2537d0f-e1fa-462b-b95b-3d20615d6029.png)

# Explicación de creacion de APK/Bundle con React

Una vez ejecutados los comandos ionic build y ionic cap add android se generarán dos directorios, build y android respectivamente. Como se muestra en la siguiente figura.

![image](https://user-images.githubusercontent.com/66254573/146658481-2881bd46-76e1-40d1-b769-103ae8c71fb3.png)

Dentro del archivo Manifest que se encuentra en android/app/src/main/AndroidManifest.xml se colocan las respectivas líneas de comando de permisos como se muestra en la siguiente figura.

![image](https://user-images.githubusercontent.com/66254573/146658511-e3cac04a-220e-48a3-8b4d-a0cd2eacd3ab.png)


Una vez realizado los pasos anteriores se procede a ejecutar el comando ionic cap open android, esto ejecutara automaticamente la aplicación de Android Studio y depues de cargar todos los archivos correspondientes, la aplicación se instalará y ejecutará en el dispositivo seleccionado en este caso un celular físico como se muestra en la siguiente figura.

![image](https://user-images.githubusercontent.com/66254573/146658583-e4825a0c-22a0-4d3c-b049-9ec2427dfd15.png)

Como último paso para la generación de APK o Bundle se selecciona la opción de Build, y build APK/bundle esto generará los correspondientes elementos los cuales estaran disponibles para su uso, en las siguientes figuras se muestran los elementos en su respectiva ruta de almacenamiento.

* APK
![image](https://user-images.githubusercontent.com/66254573/146658614-03097b93-7621-483c-9337-c519067d5faf.png)

* Bundle
![image](https://user-images.githubusercontent.com/66254573/146658617-0e4e3659-37b8-4e30-92ba-18fd60274f38.png)

# Diferencias entre Angular y React 

* Una de las principales diferencias se presentan en el momento de ejecutar el comando de ionic build puesto que en Angular crea una carpeta denominada como www . Por otro lado, en React se genera la carpeta build. 

* Ambas tecnologías trabajan muy bien en relación con ionic, ambas permiten trabajar e implementar las mismas funcionalidades por lo cual en modo de conclusión se puede decir que ninguna tecnologia es mejor que otra, sino que depende del tipo de proyecto para saber que tecnología puede ser usada para un mejor desarrollo.



