# Equilibra

Aplicación personal instalable para organizar alimentación, compra, entrenamientos y progreso. Los datos se conservan en el navegador y pueden exportarse desde **Ajustes**.

## Desarrollo

```bash
npm ci
npm run dev
```

La compilación de producción se comprueba con `npm run build`.

## Publicación en GitHub Pages

El repositorio incluye el flujo `.github/workflows/deploy.yml`.

1. Abre **Settings → Pages** en GitHub.
2. En **Build and deployment**, selecciona **GitHub Actions**.
3. Cada cambio enviado a `main` compilará y publicará la aplicación automáticamente.

Para instalarla en el móvil, abre el enlace publicado y selecciona **Añadir a pantalla de inicio**.

## Privacidad

No requiere cuenta ni servidor. Comidas, pesos y mediciones permanecen en el navegador del dispositivo. Usa la copia de seguridad antes de borrar datos o cambiar de dispositivo.
