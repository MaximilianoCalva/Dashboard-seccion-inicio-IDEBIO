# Dashboard Sección Inicio - IDEBIO

## 📋 Descripción

Colección de componentes HTML para la sección de inicio del dashboard de **IDEBIO (Instituto de Educación en Biología)**. Estos componentes están diseñados para ser integrados en WordPress usando widgets HTML personalizados.

## 🎨 Colores Institucionales

IDEBIO utiliza un esquema de colores azul que representa profesionalismo, confianza y ciencia:

### Paleta Principal
- **Azul Oscuro**: `#233878` - Color primario institucional
- **Azul Medio**: `#2863A4` - Color secundario institucional
- **Azul Claro**: `#3A7BC8` - Estados hover e interactivos

### Degradado Institucional
```css
background: linear-gradient(135deg, #233878 0%, #2863A4 100%);
```

### Variables CSS
```css
:root {
  --idebio-primary-dark: #233878;
  --idebio-primary-medium: #2863A4;
  --idebio-primary-light: #3A7BC8;
  --idebio-gradient: linear-gradient(135deg, #233878 0%, #2863A4 100%);
}
```

## 📁 Estructura de Archivos

```
Dashboard-seccion-inicio-IDEBIO/
├── 01-dashboard-inicio-IDEBIO.html          # Cápsula de navegación "Dashboard > Inicio"
├── 02-bienvenida-IDEBIO.html                # Mensaje de bienvenida personalizado
├── 03-reglamento-IDEBIO.html                # Visor de reglamento institucional
├── 04-plataforma-inactiva-IDEBIO.html       # Aviso de cuenta inactiva
├── 05-informacion-chatbot-IDEBIO.html       # Información sobre recursos del chatbot
├── 06-oferta-activa-IDEBIO.html             # Widget de oferta educativa activa
├── 07-accesos-rapidos-IDEBIO.html           # Enlaces de acceso rápido
├── Logo-idebio.png                          # Logo institucional
├── colores-institucionales-IDEBIO.md        # Guía de colores institucionales
└── README.md                                # Este archivo
```

## 🚀 Componentes

### 1. Dashboard Inicio (01)
Cápsula compacta de navegación que muestra "Plataforma IDEBIO | DASHBOARD > Inicio" con animación de flecha.

**Características:**
- Diseño tipo píldora con bordes redondeados
- Degradado azul institucional
- Animación sutil de rebote
- Responsive para móviles

### 2. Bienvenida (02)
Mensaje de bienvenida personalizado para estudiantes.

### 3. Reglamento (03)
Visor de reglamento institucional con navegación por páginas.

**Características:**
- Navegación entre páginas del reglamento
- Botones con colores institucionales azules
- Diseño limpio y profesional

### 4. Plataforma Inactiva (04)
Aviso informativo sobre posibles razones de cuenta inactiva.

**Características:**
- Diseño de tarjeta con fondo azul claro
- Iconos informativos
- Secciones para "Baja Temporal" y "Adeudo en Mensualidad"
- Footer con degradado azul institucional

### 5. Información Chatbot (05)
Información sobre los recursos disponibles del chatbot IA.

**Características:**
- Tarjetas con títulos en azul institucional
- Botones con degradado azul
- Diseño modular y escalable

### 6. Oferta Activa (06)
Widget para mostrar ofertas educativas activas.

**Características:**
- Sistema de variables CSS con colores institucionales
- Diseño adaptable
- Estados hover optimizados

### 7. Accesos Rápidos (07)
Enlaces rápidos a recursos importantes de la plataforma.

**Características:**
- Tarjetas con iconos coloridos
- Botones con colores institucionales
- Diseño responsive

## 💻 Uso en WordPress

### Integración con Elementor

1. **Agregar Widget HTML**
   - Arrastra un widget "HTML" a tu sección
   - Copia el contenido completo del archivo `.html`
   - Pega en el editor HTML del widget

2. **Configuración Recomendada**
   - Ancho: 100% del contenedor
   - Padding: Ajustar según necesidad
   - Margen: 10px superior e inferior

### Integración con Bloques de WordPress

1. **Bloque HTML Personalizado**
   - Añade un bloque "HTML personalizado"
   - Pega el código del componente
   - Previsualiza y publica

## 🎯 Características Técnicas

### Responsive Design
- Todos los componentes son responsive
- Breakpoint móvil: `max-width: 600px`
- Ajustes automáticos de tamaño y espaciado

### Tipografía
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
```

### Accesibilidad
- Contraste de colores optimizado (WCAG 2.1)
- Texto blanco sobre `#233878`: Ratio 9.2:1 ✅ (excelente)
- Texto blanco sobre `#2863A4`: Ratio 5.8:1 ✅ (muy bueno)
- Estructura semántica HTML5

## 🔧 Personalización

### Cambiar Colores
Los colores están centralizados en variables CSS. Para personalizarlos:

```css
:root {
  --idebio-primary-dark: #TU_COLOR_OSCURO;
  --idebio-primary-medium: #TU_COLOR_MEDIO;
  --idebio-primary-light: #TU_COLOR_CLARO;
}
```

### Ajustar Tamaños
Modifica las variables de tamaño en cada componente:

```css
.component {
  font-size: 18px;  /* Ajustar según necesidad */
  padding: 6px 22px; /* Ajustar espaciado */
}
```

## 📱 Compatibilidad

- ✅ Chrome/Edge (últimas versiones)
- ✅ Firefox (últimas versiones)
- ✅ Safari (últimas versiones)
- ✅ Dispositivos móviles iOS/Android
- ✅ WordPress 5.0+
- ✅ Elementor 3.0+

## 📝 Notas de Desarrollo

### Versión
- **Actual**: 1.0.0
- **Última actualización**: 28 de diciembre de 2025

### Cambios Recientes
- ✅ Aplicación de colores institucionales oficiales (#233878, #2863A4)
- ✅ Implementación de degradado azul institucional
- ✅ Actualización de variables CSS
- ✅ Mejora de accesibilidad y contraste (ratios 9.2:1 y 5.8:1)

## 🤝 Contribución

Para mantener la consistencia visual:
1. Usa siempre los colores institucionales definidos
2. Mantén la estructura de archivos
3. Prueba en diferentes navegadores
4. Verifica la accesibilidad

## 📄 Licencia

Uso interno de IDEBIO - Instituto de Educación en Biología

---

**Desarrollado para IDEBIO** | Última actualización: Diciembre 2025
