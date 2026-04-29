# 🎓 Plataforma de Visualización de Puntos Estudiantiles

Una aplicación web moderna y responsiva para que los estudiantes visualicen sus puntos académicos desde cualquier dispositivo móvil.

## ✨ Características

- 📱 **Diseño 100% Responsivo** - Funciona perfectamente en móviles, tablets y computadoras
- 🔍 **Búsqueda en Tiempo Real** - Encuentra estudiantes por nombre al instante
- 🏆 **Filtros por Grado** - Organiza estudiantes por clase
- 📊 **Estadísticas Automáticas** - Ve el total, promedio, máximo y mínimo de puntos
- 🎨 **Interfaz Moderna y Atractiva** - Diseño limpio y profesional
- 🚀 **Carga Rápida** - Optimizado para el mejor rendimiento

## 🚀 Instalación Rápida

### 1. Habilitar GitHub Pages

1. Ve a tu repositorio: `bceron-cloud/CYT-`
2. Haz clic en **⚙️ Settings**
3. En el menú lateral, selecciona **Pages**
4. Bajo "Build and deployment", selecciona:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (o la rama donde subiste los archivos)
   - **Folder**: `/ (root)`
5. Haz clic en **Save**

### 2. Tu sitio estará disponible en:

```
https://bceron-cloud.github.io/CYT-/
```

⏳ Espera 2-3 minutos para que GitHub compile y despliegue tu sitio.

## 📝 Estructura de Archivos

```
CYT-/
├── index.html              # Aplicación web principal
├── estudiantes.json        # Base de datos de puntos
└── README_PUNTOS.md       # Este archivo
```

## 📊 Formato de `estudiantes.json`

El archivo contiene un array de objetos con esta estructura:

```json
[
  {
    "id": 1,
    "nombre": "Juan García",
    "grado": "10A",
    "puntos": 950,
    "email": "juan.garcia@escuela.edu"
  },
  {
    "id": 2,
    "nombre": "María López",
    "grado": "10A",
    "puntos": 890,
    "email": "maria.lopez@escuela.edu"
  }
]
```

### Campos:
- **id**: Identificador único del estudiante
- **nombre**: Nombre completo del estudiante
- **grado**: Grado o curso (ej: 10A, 11B)
- **puntos**: Puntuación actual
- **email**: Email del estudiante

## ✏️ Cómo Actualizar Puntos

1. Edita el archivo `estudiantes.json` en GitHub
2. Cambia los valores de `puntos` para cada estudiante
3. Guarda los cambios (Commit)
4. La página se actualizará automáticamente en 1-2 minutos

### Agregar un nuevo estudiante:

Simplemente añade un objeto al array en `estudiantes.json`:

```json
{
  "id": 6,
  "nombre": "Nuevo Estudiante",
  "grado": "10A",
  "puntos": 850,
  "email": "nuevo@escuela.edu"
}
```

## 🎨 Personalización

### Cambiar Colores

Edita los colores en `index.html` en la sección `<style>`:

```css
/* Color principal (azul) */
#667eea

/* Color secundario (púrpura) */
#764ba2
```

### Cambiar Título y Subtítulo

En `index.html`:

```html
<h1>🎓 Mis Puntos</h1>
<p class="subtitle">Plataforma de Visualización de Puntos Académicos</p>
```

### Cambiar Idioma

Todos los textos están en español y son fáciles de modificar. Busca en `index.html` y personaliza según sea necesario.

## 📱 Acceso Móvil

Los estudiantes pueden acceder desde:

1. **iPhone/iPad**: Safari
2. **Android**: Chrome, Firefox, Samsung Internet
3. **Cualquier navegador moderno**

Solo necesitan ir a:
```
https://bceron-cloud.github.io/CYT-/
```

## 🔒 Privacidad

Los datos se almacenan en un archivo JSON público en GitHub. Si necesitas proteger información sensible:

1. No incluyas números de identificación reales
2. Usa solo información académica
3. Considera usar autenticación si es crítico

## 🐛 Solución de Problemas

### El sitio no carga
- Espera 5 minutos después de hacer cambios
- Limpia el caché del navegador (Ctrl+Shift+Delete)
- Verifica que GitHub Pages esté habilitado en Settings

### Los datos no se actualizan
- Recarga la página (F5)
- Limpia el caché (Ctrl+Shift+Delete)
- Verifica que `estudiantes.json` tenga JSON válido

### Validar JSON
Copia el contenido de `estudiantes.json` en https://jsonlint.com/ para verificar que esté correcto

## 🚀 Funcionalidades Futuras

- 📈 Gráficos de progreso
- 🏅 Sistema de insignias
- 📧 Notificaciones por email
- 📲 App móvil nativa
- 🔐 Sistema de login

## 📞 Soporte

Si tienes preguntas o problemas:
1. Revisa esta documentación
2. Verifica que los archivos estén en la raíz del repositorio
3. Consulta la documentación oficial de GitHub Pages

---

**¡Tu plataforma está lista para que tus estudiantes vean sus puntos! 🎉**