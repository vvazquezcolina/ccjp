# CCJP – Arte, Tecnología y Comunidad

Presentación del proyecto del Centro Cultural Juvenil Playa (CCJP) para el Diplomado en Gestión Estratégica de la Universidad Anáhuac Cancún.

## 🚀 **Despliegue en Vercel**

### **Opción 1: Despliegue Automático (Recomendado)**
1. Haz fork o clona este repositorio
2. Ve a [vercel.com](https://vercel.com) y conéctate con tu cuenta de GitHub
3. Haz clic en "New Project"
4. Selecciona este repositorio
5. Vercel detectará automáticamente la configuración y desplegará la presentación

### **Opción 2: Despliegue Manual**
```bash
# Instalar Vercel CLI
npm i -g vercel

# Desplegar
vercel

# Para producción
vercel --prod
```

## 📸 **IMÁGENES**
- **Actualizado:** Ahora usa imágenes reales en lugar de SVGs con degradados
- **Carpeta:** `images/` - Coloca aquí las 7 imágenes requeridas
- **Guía:** Consulta `images/README-IMAGENES.md` para detalles específicos
- **Fallback:** Si no hay imágenes, se muestran automáticamente los SVGs originales

## 🖼️ **IMÁGENES NECESARIAS**
1. `playa-del-carmen-banner.jpg` (1200x675px) - Vista panorámica de Playa del Carmen
2. `arte-talleres.jpg` (600x400px) - Talleres de arte para jóvenes
3. `tecnologia-laboratorio.jpg` (600x400px) - Laboratorio de tecnología
4. `juventud-actividades.jpg` (600x400px) - Jóvenes en actividades culturales
5. `cine-club-sala.jpg` (600x400px) - Sala de proyección
6. `musica-ensayo.jpg` (600x400px) - Sala de música e instrumentos
7. `makerspace-taller.jpg` (600x400px) - Taller con herramientas digitales

## 📋 **FUENTES DE IMÁGENES**
- Unsplash.com, Pexels.com, Pixabay.com (gratuitas)
- Fotos propias de espacios culturales similares

## 🎮 **Controles de Navegación**
- **Teclas:** ← → (flechas izquierda/derecha)
- **Clic:** Haz clic en cualquier parte de la slide para avanzar
- **Imprimir/PDF:** Presiona `P` o usa el botón "PDF"
- **Botones:** Usa los controles en la esquina inferior derecha

## 🏗️ **Estructura del Proyecto**
```
ccjp_slides_v3/
├── index.html              # Presentación principal
├── images/                 # Carpeta de imágenes
├── vercel.json            # Configuración de Vercel
├── package.json           # Metadatos del proyecto
├── .gitignore            # Archivos a ignorar
└── README.md             # Este archivo
```

## 🌐 **URL de Despliegue**
Una vez desplegado en Vercel, tu presentación estará disponible en:
`https://[tu-proyecto].vercel.app`

## 📱 **Características**
- ✅ Diseño responsive
- ✅ Imágenes optimizadas
- ✅ Navegación por teclado
- ✅ Modo de impresión/PDF
- ✅ Fallback automático para imágenes
- ✅ Carga rápida con Vercel Edge Network

## 🎨 **Tecnologías**
- HTML5 + CSS3
- JavaScript vanilla
- Google Fonts (Inter)
- Optimización para Vercel

## 📄 **Licencia**
MIT License - Libre para uso académico y comercial
