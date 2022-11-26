---
description: Cómo instalar el plugin
---

# ⚙ Primera instalación

{% hint style="info" %}
**Deberas seguir** esta primera configuración **en** tu **servidor de pruebas** en tu PC para **evitar errores** y demasiados reinicios... a los jugadores no les gusta cuando el servidor está desconectado.

Puedes subir los archivos a ttu servidor real después de haber terminado aquí.\

{% endhint %}

{% hint style="danger" %}
**Asegúrese** de que todos sus plugins y el software del servidor están actualizados.
{% endhint %}

## Paso 1 - Instalación del plugin y las API's

* Instalar [**ProtocolLib**](https://ci.dmulloy2.net/job/ProtocolLib/lastSuccessfulBuild/)
* Instalar [**LoneLibs**](https://www.spigotmc.org/resources/lonelibs.75974/)
* (opcional) Instalar **LightAPI** ([1.14, 1.15, 1.16](http://a.devs.beer/lightapi-old) | [1.17, 1.18](http://a.devs.beer/lightapi-new))
* Arrastre el archivo `ItemsAdder.jar` dentro de su carpeta de plugins
* Inicie el servidor
* Deje que ItemsAdder termine de cargar **todo los archivos**

El primer paso está hecho.\
Ahora debes completar el paso 2 para configurar el resourcepack (no te preocupes, no es muy difícil).

## Paso 2 - Primera instalación del Resourcepack

{% hint style="warning" %}
Este paso es importante, el plugin  <mark style="color:red;">**NO FUNCIONARÁ,**</mark> si no completa este paso.
{% endhint %}

Antes de usar el plugin tienes que decirdir el método de alojamiento del resourcepack.\
Haga click aquí para decidir un método de alojamiento para el resourcepack (el mejor método: `self-host`).

{% content-ref url="plugin-usage/resourcepack-hosting/" %}
[resourcepack-hosting](plugin-usage/resourcepack-hosting/)
{% endcontent-ref %}

## Paso 3 - (opcional) Agrege contenido personalizado oficial de ItemsAdder.

![](.gitbook/assets/items\_showcase\_gif.apng)

**ItemsAdder** viene con una gran cantidad de contenido personalizado ya creado para usted.\
No se incluye automáticamente en el complemento descargado por que es posible que algunas personas no deseen que todos items/caracter\[isticas se agreguen automáticamente en su servidor.

### Paquete predeterminado

![](<.gitbook/assets/image (47).png>)

* Descarga la última versión del DefaultPack: [DESCARGAR](https://github.com/ItemsAdder/DefaultPack/releases/latest)
* Extraiga el contenido en la carpeta `ItemAdder` y sobreescriba los archivos si se le solicita
* Ejecute el comando `/iazip` (y siga su método de [método de hospedaje](plugin-usage/resourcepack-hosting/) si no está utilizando el **self-host**).

### Otros packs (opcional)

![](<.gitbook/assets/image (50).png>)

* Si lo desea, puede descargar el **OtherPacks** que agregan aún más contenido: [DESCARGAR](https://github.com/ItemsAdder/OtherPacks/releases/latest)
* Extraiga el contenido en la carpeta `ItemsAdder` y sobrescriba los archivos si se le solicita.
* Ejecute el comando `/iazip` (y siga su método de [método de hospedaje](plugin-usage/resourcepack-hosting/) si no está utilizando el **self-host**).

Si está en 1.17 o inferior, debe cambiar la generación de minerales:

* Abra estos archivos y establezca `enabled: true`.
  * `contents\iaalchemy\configs\worlds_populators_old.yml`
  * `contents\iasurvival\ores\configs\worlds_populators_old.yml`
* Abra estos archivos y establezca `enabled: false`.
  * `contents\iaalchemy\configs\worlds_populators_1_18.yml`
  * `contents\iasurvival\ores\configs\worlds_populators_1_18.yml`

### Eliminar items predeterminados

{% content-ref url="faq/removing-default-stuff/" %}
[removing-default-stuff](faq/removing-default-stuff/)
{% endcontent-ref %}

### Avoid glitched blocks

{% content-ref url="faq/blocks-minerals-issues/custom-blocks-glitch-texture/avoid-glitched-blocks.md" %}
[avoid-glitched-blocks.md](faq/blocks-minerals-issues/custom-blocks-glitch-texture/avoid-glitched-blocks.md)
{% endcontent-ref %}
