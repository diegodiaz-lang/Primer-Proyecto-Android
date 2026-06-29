# Primer proyecto Android

Proyecto base en Java que cumple con la actividad:

- Español como idioma predeterminado.
- Traducciones para inglés, francés y alemán.
- Fondo convertido a `fondo_android.9.png`.
- El marcianito central queda fuera de las zonas estirables del Nine-Patch.
- Layout para orientación vertical y horizontal.
- Dimensiones alternativas para teléfonos, tabletas y pantallas grandes.
- Botón funcional que muestra un mensaje traducido.

## Carpetas importantes

- `res/values/strings.xml`: español.
- `res/values-en/strings.xml`: inglés.
- `res/values-fr/strings.xml`: francés.
- `res/values-de/strings.xml`: alemán.
- `res/layout/activity_main.xml`: orientación vertical.
- `res/layout-land/activity_main.xml`: orientación horizontal.
- `res/values-sw600dp/`: medidas para tabletas.
- `res/values-sw600dp-land/`: medidas para tabletas en horizontal.
- `res/drawable-mdpi/fondo_android.9.png`: fondo Nine-Patch.
- `referencia/fondo_original.png`: imagen original usada para crear el fondo.

## Cómo usarlo

1. Abre la carpeta `PrimerProyectoAndroid` desde Android Studio.
2. Espera la sincronización de Gradle.
3. Ejecuta la aplicación en un emulador o dispositivo.
4. Cambia el idioma del dispositivo para revisar las cuatro traducciones.
5. Prueba orientación vertical, horizontal, teléfono y tableta.

