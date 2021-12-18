# deber-react-angular-DAM

# Integrantes
* Alba Jorge
* Dávila Bernabé

# Explicación de creación APK/Bundle con Angular

# Explicación de creacion de APK/Bundle con React

Una vez ejecutados los comandos ionic build y ionic cap add androis se generarán dos directorios, build y android respectivamente. Como se muestra en la siguiente figura.

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




