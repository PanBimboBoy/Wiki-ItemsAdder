# ¡Veo texturas nítidas a lo lejos!

{% hint style="warning" %}
Si ves texturas punteadas y no lisas en la lejanía es un error común del creador de resourcepacks.\
Minecraft tiene un error que deshabilita el mipmap si se establecen las texturas que su tamaño no es un múltiplo de dos.
{% endhint %}

![IZQUIERDA: sin mipmap. DERECHA: con mipmap](<../.gitbook/assets/image (19).png>)

## ¿Cómo solucionarlo**?**

Es muy fácil. Sólo tienes que seguir estos pasos:

* Abre el registro del juego Minecraft, no los registros del servidor (normalmente está en `%appdata%\.minecraft\logs\latest.log`si no, por favor, busque dentro de esta carpeta `%appdata%\.minecraft\logs\`)
* Buscar este texto `limits mip level`
* Identifique la textura problemática, por ejemplo `Texture mcicons:item/icon_toggle_off with size 30x30 limits mip level from 3 to 1`
* Arregla la textura. Para fijarla tienes que redimensionarla a un tamaño de: 16x16, 32x32, 64x64, 128x128, 256x256, tú decides uno de estos.

¡Hecho!
