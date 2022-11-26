# 🔍 Identificar por qué no se muestran las texturas

### Objetivo

* Se muestra la textura negra y morada
* Su modelo no carga correctamente
* El paquete no se pudo cargar

## Cualquier launcher

Únete al servidor y deja que el paquete se cargue.

Abra su archivo de registro del juego Minecraft, no los registros del servidor. Suele estar en `%appdata%\.minecraft\logs\latest.log` si no, por favor, busque dentro de esta carpeta`%appdata%\.minecraft\logs\`

Puede ver claramente qué archivos no se han cargado y por qué, los errores son claros en la mayoría de los casos.

## Launcher oficial

### Activa el registro de minecraft

![](../.gitbook/assets/image\_\(135\).png)

### Únase al servidor y lea el registro

![](<../.gitbook/assets/json\_errors (1).png>)

### Averigüe qué archivo está roto

Puede ver claramente qué archivos no se cargaron y porqué, los errores son claros en la mayoría de los casos.\
En este ejemplo, tenía dos archivos rotos `gem_vending_machine` y `whitebathroom_sink`.\
El error me dice que los archivos JSON están rotos, probablemente tienen caracteres malos dentro o están dañados.
