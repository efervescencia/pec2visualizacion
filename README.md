# PEC2 Visualización

Este es un proyecto de visualización de datos disponible públicamente a través de GitHub Pages.

## 🌐 Acceso Público

El sitio está disponible en: `https://efervescencia.github.io/pec2visualizacion/`

**No se requiere autenticación** - El sitio es completamente público y accesible para todos.

## 🚀 Despliegue

El proyecto se despliega automáticamente a GitHub Pages mediante GitHub Actions cada vez que se hace push a la rama principal.

### Configuración de GitHub Pages

1. Ve a Settings → Pages en el repositorio de GitHub
2. En "Source", selecciona "GitHub Actions"
3. El despliegue se ejecutará automáticamente

## 📁 Estructura del Proyecto

- `index.html` - Página principal del sitio
- `styles.css` - Estilos CSS
- `script.js` - JavaScript para interactividad
- `.github/workflows/deploy.yml` - Workflow de despliegue automático

## 🛠️ Desarrollo Local

Para visualizar el sitio localmente:

```bash
# Opción 1: Usar Python
python -m http.server 8000

# Opción 2: Usar Node.js
npx http-server
```

Luego abre `http://localhost:8000` en tu navegador.

## 📝 Características

- ✅ Acceso público sin autenticación
- ✅ Diseño responsive
- ✅ Despliegue automático con GitHub Actions
- ✅ Interfaz moderna y accesible