# Café Nostro Bourbon — 3D + Realidad Aumentada

Este proyecto contiene un modelo 3D del empaque de Café Nostro Bourbon, usando la fotografía proporcionada como textura frontal y una geometría de bolsa tipo pouch con cierre superior.

## Archivos
- `index.html` — visor web 3D y botón de realidad aumentada.
- `cafe_nostro_bourbon.glb` — modelo 3D listo para web/AR.
- `textures/bag_atlas.jpg` — atlas de textura usado por el modelo.
- `textures/cafe_nostro_front.jpg` — textura frontal derivada de la fotografía original.
- `textures/cafe_nostro_kraft_back.jpg` — textura kraft para la parte posterior.

## Subir a GitHub
1. Crea un repositorio nuevo, por ejemplo `cafe-nostro-3d-ar`.
2. Sube **todos** los archivos conservando la estructura de carpetas.
3. En GitHub abre **Settings → Pages**.
4. En *Build and deployment*, selecciona **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
5. Guarda y espera a que GitHub Pages publique el sitio.
6. Abre la URL que GitHub te entregue.

## Probar AR
- Android compatible: Chrome/Scene Viewer o WebXR según el dispositivo.
- iPhone/iPad compatible: Safari/Quick Look.
- Si AR no aparece, prueba con HTTPS (GitHub Pages ya usa HTTPS) y un dispositivo compatible.

## Importante
La fotografía disponible muestra principalmente el frente del empaque. Por eso el frente conserva el diseño real y la parte posterior/laterales usan una textura kraft aproximada. Para un modelo 3D físicamente exacto de todo el empaque, conviene aportar fotos del frente, reverso, laterales, parte superior e inferior.
