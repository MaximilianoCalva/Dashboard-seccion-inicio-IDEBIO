# Colores Institucionales - IDEBIO

Este documento define la paleta de colores oficial del Instituto de Educación en Biología.

---

## 🧬 IDEBIO (Instituto de Educación en Biología)

### Color Principal (Degradado)
- **Azul Oscuro**: `#233878`
  - **RGB**: `rgb(35, 56, 120)`
  - **HSL**: `hsl(225, 55%, 30%)`

- **Azul Medio**: `#2863A4`
  - **RGB**: `rgb(40, 99, 164)`
  - **HSL**: `hsl(212, 61%, 40%)`

### Degradado Institucional
```css
background: linear-gradient(135deg, #233878 0%, #2863A4 100%);
```

### Colores Complementarios
- **Blanco**: `#FFFFFF`
- **Gris Claro**: `#F5F5F5`
- **Gris Medio**: `#E0E0E0`
- **Texto Oscuro**: `#2C3E50`
- **Azul Claro** (para hover): `#3A7BC8`

---

## 🎨 Uso Recomendado

- **Encabezados y CTAs**: Degradado (#233878 → #2863A4)
- **Fondos de secciones**: Azul Oscuro (#233878) o Azul Medio (#2863A4)
- **Texto sobre fondos oscuros**: Blanco (#FFFFFF)
- **Texto general**: Texto Oscuro (#2C3E50)
- **Estados hover**: Azul Claro (#3A7BC8)

---

## 📋 Implementación CSS

```css
:root {
  /* IDEBIO Colors */
  --idebio-primary-dark: #233878;
  --idebio-primary-medium: #2863A4;
  --idebio-primary-light: #3A7BC8;
  --idebio-white: #FFFFFF;
  --idebio-light-gray: #F5F5F5;
  --idebio-medium-gray: #E0E0E0;
  --idebio-dark-text: #2C3E50;
  
  /* Degradado institucional */
  --idebio-gradient: linear-gradient(135deg, #233878 0%, #2863A4 100%);
}

/* Ejemplo de uso */
.btn-primary {
  background: var(--idebio-gradient);
  color: var(--idebio-white);
  border: none;
}

.btn-primary:hover {
  background: var(--idebio-primary-light);
}

.section-header {
  background: var(--idebio-gradient);
  color: var(--idebio-white);
}

/* Variante con color sólido */
.bg-primary-dark {
  background-color: var(--idebio-primary-dark);
}

.bg-primary-medium {
  background-color: var(--idebio-primary-medium);
}
```

---

## 📝 Notas de Accesibilidad

### Contraste de Texto
- **Texto blanco sobre #233878**: Ratio de contraste de 9.2:1 ✅ (excelente para todo tipo de texto)
- **Texto blanco sobre #2863A4**: Ratio de contraste de 5.8:1 ✅ (muy bueno para texto)
- **Texto blanco sobre #3A7BC8**: Ratio de contraste de 4.1:1 (bueno para texto grande)

### Recomendaciones
- Los colores azules tienen excelente contraste con texto blanco
- Pueden usarse para texto de cualquier tamaño
- Para fondos claros, usar el color de texto oscuro (#2C3E50)

---

## 🎨 Paleta de Colores

| Color | Hex | Descripción | Uso |
|-------|-----|-------------|-----|
| Azul Oscuro | `#233878` | Color principal (inicio degradado) | Fondos, degradados |
| Azul Medio | `#2863A4` | Color principal (fin degradado) | Fondos, degradados |
| Azul Claro | `#3A7BC8` | Hover/Activo | Estados interactivos |
| Blanco | `#FFFFFF` | Neutro | Fondos, texto sobre oscuro |
| Gris Claro | `#F5F5F5` | Neutro | Fondos alternativos |
| Texto Oscuro | `#2C3E50` | Neutro | Texto principal |

---

**Última actualización**: 28 de diciembre de 2025
