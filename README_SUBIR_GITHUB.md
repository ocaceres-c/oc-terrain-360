# OC Terrain 360 - Archivos para GitHub Pages

## Archivos incluidos
- `index.html`: aplicación principal. Este es el archivo que GitHub Pages abrirá en el celular.
- `OC_Terrain_360.html`: copia de respaldo con el mismo contenido.
- `manifest.json`: permite mejor comportamiento al abrir desde celular.
- `oc360-icon.svg`: ícono básico de la aplicación.
- `.nojekyll`: evita que GitHub Pages procese o bloquee archivos.

## Cómo subirlo a GitHub
1. Crear un repositorio nuevo en GitHub, por ejemplo: `oc-terrain-360`.
2. Subir todos los archivos de esta carpeta directamente a la raíz del repositorio.
3. Entrar a **Settings** > **Pages**.
4. En **Build and deployment**, seleccionar:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Guardar.
6. Esperar unos minutos y abrir el link que entrega GitHub Pages.

## Uso en celular
- Abrir el link desde Safari o Chrome.
- En iPhone: Compartir > Agregar a pantalla de inicio.
- Trabajar normalmente desde el navegador.
- Exportar respaldo JSON al cerrar jornada.

## Reglas importantes
- La información se guarda en el navegador/dispositivo mediante IndexedDB.
- Si se usa otro celular, otro navegador o se limpia caché, se debe cargar un respaldo JSON.
- Antes de modificar la aplicación, exportar respaldo.
- Para operación diaria: PC como base principal, celular como apoyo de terreno y respaldo en iCloud Drive.

## Cambios incluidos en esta versión
- Formato ajustado para celular.
- Menos saturación visual en módulos pesados.
- Validación visual de campos obligatorios.
- Validación de RUT chileno y aviso si el dígito verificador no corresponde.
- Corrección de función faltante `updateDepthSummary()`.
