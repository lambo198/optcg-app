# OPTCG Manager — Instalacion en Android

## Paso 1: Subir a GitHub Pages

1. Ve a **github.com** e inicia sesion
2. Crea un **repositorio nuevo** llamado `optcg-app`
   - Visibilidad: **Public**
   - No inicialices con README
3. Sube estos 4 archivos al repositorio:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - carpeta `icons/` con `icon-192.png` e `icon-512.png`
4. Ve a **Settings → Pages**
5. En "Branch" selecciona **main** y carpeta **/ (root)**
6. Haz clic en **Save**
7. Espera 1-2 minutos. Tu app estara en:
   `https://TU_USUARIO.github.io/optcg-app`

## Paso 2: Instalar en Android

1. Abre **Chrome** en tu movil Android
2. Ve a la URL de arriba
3. Chrome mostrara un banner "Anadir a pantalla de inicio"
   (o ve al menu de tres puntos → "Instalar app")
4. Confirma la instalacion
5. La app aparece en tu pantalla de inicio como cualquier otra app

## Funcionalidades

- **Escaner**: simula escaneo de cartas (demo) o busca por codigo
- **Baul**: guarda tu coleccion localmente en el movil
- **Mazos**: ve que mazos meta puedes armar con tus cartas
- **IA**: asistente de consultas sobre One Piece TCG

## Datos guardados

La coleccion se guarda en el almacenamiento local del movil.
No se pierden al cerrar la app.

## Actualizaciones futuras

Para actualizar la app, simplemente reemplaza los archivos en GitHub.
La app se actualizara automaticamente en el movil.
