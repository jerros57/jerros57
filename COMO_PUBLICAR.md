# Cómo publicar este perfil de GitHub

Este paquete está listo para personalizar el perfil público de **@jerros57**.

## Opción 1 — Subir desde la web de GitHub

1. Abre https://github.com/new e inicia sesión como `jerros57`.
2. Crea un repositorio llamado **exactamente `jerros57`** (si ya existe, utiliza ese mismo).
3. Asegúrate de que sea **Public**.
4. Descomprime el ZIP y sube a la **raíz** del repositorio `README.md` y la carpeta `assets/` (que contiene `banner.svg`). Puedes conservar este instructivo si quieres.
5. Confirma los cambios con **Commit changes**.
6. Visita https://github.com/jerros57 para comprobar el resultado.

**Importante:** no subas solamente el ZIP; GitHub necesita el archivo `README.md` descomprimido en la raíz del repositorio de perfil.

## Opción 2 — Desde Git

Si el repositorio `jerros57` ya existe, clónalo y **haz copia de tu README anterior** antes de reemplazarlo. Copia `README.md` y `assets/` en el repositorio, luego ejecuta:

```bash
git add README.md assets/banner.svg
git commit -m "Personaliza perfil profesional GitHub"
git push
```

## Consejos

- En GitHub, ajusta tu bio corta, ubicación general y URL de sitio web desde **Edit profile**.
- Fija los repositorios públicos de `herux_web_project`, `landiCy` y `CotizadorHerbalife` desde **Customize your pins**, si están disponibles.
- Los enlaces a proyectos públicos proceden de tu portafolio adjunto. Si cambias el nombre de un repositorio o su visibilidad, actualiza los enlaces del README.
- Los proyectos privados se describen sin enlazar a código interno.
- El banner SVG es estático, ligero y no necesita librerías, scripts o servicios externos. Los badges externos son decorativos: si el servicio falla, el texto del README sigue siendo legible.
- El perfil README no ejecuta tu página HTML o CSS personalizado; GitHub renderiza Markdown y HTML seguro. Por eso el estilo se implementa con un SVG, badges y contenido estructurado.
