# EmptyProyect

#FORMATO DE ENTREGA

 - Entrega de APK firmado una vez definido el paquete.
 - Verificar que apunte a las URLs de prueba o producción

 - Nombre del archivo:
    - [Projecto]-[QA|DEMO]-[YYYYMMDD].apk
 - Subir el KeyStore al repositorio y agregar la clave en el README.md
    - Alias: Nombre del proyecto todo minuscula
    - Password: Nombre del proyecto todo minuscula
    - File Name Key: Proyecto + KeyStore (como palabra)
 - Crear una release por cada update en producción
 - Cuando se hace la demo, tener todo en develop
 - Subir al Drive del proyecto en la parte de Builds/Android/Sprint X
 - Chequear que funcione actualizar sobre la app de producción

Ejemplo:

Proyecto: Cosquin Rock

Alias: cosquinrock
Password: cosquinrock

File Name: CosquinRockKeyStore

#LIBRERIAS

Carga de imagenes:

  - Picasso => http://square.github.io/picasso/
  - Universal Image Loader => https://github.com/nostra13/Android-Universal-Image-Loader
  
Base de datos:

  - Active Android => http://www.activeandroid.com/
  - ORMLite => http://ormlite.com/javadoc/ormlite-core/doc-files/ormlite_1.html#Getting-Started
  - SQLite
 
JSon:
  
  - GSon => https://github.com/google/gson
  - Jackson => https://github.com/FasterXML/jackson
  - nativo
  
Servicios:

  - Volley => https://github.com/mcxiaoke/android-volley
  
Fuentes Customisadas:

  - PixlUI => https://github.com/neopixl/PixlUI
  
Carga de Imagen:

  - EasyImage => https://github.com/jkwiecien/EasyImage
  
Circular Pager Indicator:

  - CircleIndicator => https://github.com/ongakuer/CircleIndicator
  - ViewPagerIndicator => https://github.com/JakeWharton/ViewPagerIndicator
