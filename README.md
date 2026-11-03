# Tock Labs Official Website & app-ads.txt

Este directorio contiene el sitio web oficial de **Tock Labs** y la configuración de verificación de **Google AdMob**.

## Archivos incluidos:
- `index.html`: Landing page moderna y responsive de Tock Labs presentando Afinador Simple.
- `privacy.html`: Política de privacidad oficial exigida por Google Play.
- `app-ads.txt`: Archivo de verificación publicitaria para Google AdMob.
- `img/`: Recursos gráficos e icono de la app.

---

## Cómo publicar en GitHub Pages (Gratis en 2 minutos):

### Opción A (Repositorio independiente para Tock Labs):
1. En GitHub, crea un nuevo repositorio público:
   - Si es con tu usuario: `waldemares.github.io` (o `tocklabs-site`).
   - O crea una organización en GitHub llamada `tocklabs` y el repositorio `tocklabs.github.io`.
2. Sube el contenido de esta carpeta `tocklabs` a la rama `main`.
3. En GitHub > Settings > Pages:
   - Source: `Deploy from a branch` (rama `main`, carpeta `/ (root)`).
4. Tu sitio web quedará disponible en:
   - `https://tuusuario.github.io`
   - Y tu archivo AdMob en: `https://tuusuario.github.io/app-ads.txt`

---

## Qué hacer en Google Play Console:
Una vez publicada la web:
1. Entra a **Google Play Console**.
2. Ve a: **Configuración de la tienda** > **Detalles de contacto de la ficha de Play Store**.
3. En el campo **Sitio web**, pega la URL de tu sitio (ejemplo: `https://tuusuario.github.io`).
4. Haz clic en **Guardar**.
5. En 24-48 horas, Google AdMob rastreará automáticamente `https://tuusuario.github.io/app-ads.txt` y tu estado pasará a verde (Autorizado).

