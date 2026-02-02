# Agropaul.es - Web Responsiva

Sitio web profesional para Agropaul.es - Gestión Agrícola y Cursos de Formación.

## Estructura de Archivos

```
agropaul.SL web resp admin/
├── index.html          # Página principal
├── script.js           # Funcionalidad JavaScript
├── images/             # Carpeta de imágenes
│   ├── equipo.jpg
│   ├── poda-tecnica.jpg
│   ├── poda-caquis.jpg
│   ├── caquis-arbol.jpg
│   ├── arbol-naranjas.jpg
│   ├── gestion-fincas.jpg
│   ├── aclareo-recoleccion.jpg
│   └── curso-naranjas.svg
└── README.md           # Este archivo

```

## Características

- ✅ Diseño responsive (móvil, tablet, desktop)
- ✅ Secciones: Servicios, Cursos de Formación, Contacto
- ✅ Panel de Administración con autenticación
- ✅ Gestión de horas de trabajadores
- ✅ Formulario de contacto
- ✅ Optimizado para SEO

## Cómo Usar

### Desarrollo Local
Para ejecutar localmente con Python:
```bash
python -m http.server 8080
```
Luego abre en tu navegador: `http://localhost:8080`

### Deploy en Servidor
1. Sube todos los archivos al servidor web
2. Asegúrate de que `images/` esté en el mismo directorio que `index.html`
3. Verifica que `script.js` esté en la raíz

## Requisitos

- Navegador moderno (Chrome, Firefox, Edge, Safari)
- No requiere dependencias adicionales
- HTML5, CSS3, JavaScript vanilla

## Secciones Principales

- **Hero Section**: Banner principal
- **Servicios**: Poda técnica y servicios agrícolas
- **Cursos**: Formación profesional (Caquis, Naranjas)
- **Beneficios**: Ventajas de elegir Agropaul
- **Contacto**: Formulario de contacto
- **Panel Admin**: Gestión de trabajadores (requiere login)

## Notas

- Los datos se almacenan en `localStorage` (navegador del cliente)
- El formulario de contacto puede estar conectado a un servidor backend
- Las imágenes están optimizadas en formato JPG y SVG

---
**Versión**: 1.0  
**Última actualización**: Febrero 2026
