# 📷 El Resourcepack no carga

### _El resoucepack no se carga, aparece un error en el chat_ <a href="#resourcepack-not-loading-i-get-an-error-in-chat" id="resourcepack-not-loading-i-get-an-error-in-chat"></a>

* Si usted tiene **SkinsRestorer** por favor [lea aquí](../compatibility-with-other-plugins/compatible/skinsrestorer.md).
* Verifique si tiene otro plugin que usa **resourcepacks custom**, si lo tiene, **deshabilite** su función de **resourcepack** o ItemsAdder no podrá aplicar el pack correctamente (puede hacerlos compatibles si tiene un conocimiento mínimo sobre cómo fusionar resourcepacks manualmente, asegúrese de no reemplazar los archivos de ItemsAdder y listo. La carpeta del paquete de ItemsAdder es `resouce_pack`)
* Asegúrese de no tener ningun resourcepack en el archivo `server.properties`
* **Minecraft** limita el **tamaño** de los resourcepacks de los servidores a **50MB** en Minecraft **1.14** y **100MB** en **1.15+**, asegúrese de **comprimir** sus **texturas** y archivos de **música** antes de crear el archivo zip.
* Asegúrese de que su`url`sea un enlace de descarga **directa** al archivo zip. Si pega el enlace en su navegador (Firefox/Chrome), debe ver instantáneamente el inicio de descarga , si ve una página de descarga con botones, es incorrecto. [Tutoriales de alojamiento de Resoucepack](../plugin-usage/resourcepack-hosting/).
* Asegúrese de seguir todos los pasos del [tutorial](../plugin-usage/resourcepack-hosting/).
* Asegúrese de que el puerto esté abierto si utiliza el self-host.
* Ejecute el comando `/iainfo` y asegúrese de que se pueda acceder a la **URL** dek oaqyete de recursos desde su navegador y que descargue directamente el archivo `.zip` del resoucepack.

### ¡Mis jugadores no pueden ver las texturas! Pero he seguido todo el tutorial. <a href="#my-players-cant-see-textures-but-ive-followed-the-whole-tutorial" id="my-players-cant-see-textures-but-ive-followed-the-whole-tutorial"></a>

Hay tres formas de solucionar este problema:

* Si sus jugadores no pueden ver los nuevos items, ¡simplemente vincúlelos a estas pantallas simples para solucionarlo! [http://imgur.com/a/SG0AU](http://imgur.com/a/SG0AU)​
* Si aún tiene problemas para **eliminar** el **servidor** de su **lista de servidores**, agréguelo nuevamente y luego **habilite** los **paquete de recursos**.
* Si aún tiene problemas para salir del servidor, vaya a **%appdata%/.minecraft/server-resource-packs** y **elimine todo**. Luego únete al servidor de nuevo.

{% hint style="danger" %}
Asegúrese de no utilizar **MAYÚSCULAS**, **espacios** o **caracteres especiales** en los **nombres** de los items, **namespaces**, archivos de **textura** (png) y archivos de **modelo** (json)
{% endhint %}
