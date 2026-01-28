# 🎓 Presentación SIGECHIP - Sistema de Identificación y Gestión de Mascotas

<div align="center">

![ECCI](https://img.shields.io/badge/Universidad-ECCI-003B70?style=for-the-badge)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)

**Configuración de un Servidor Web en Raspberry Pi para la Gestión de Identificación de Mascotas**

[Ver Presentación](https://risgan.github.io/presentacion-sigechip) • [Reportar Bug](https://github.com/risgan/presentacion-sigechip/issues) • [Solicitar Función](https://github.com/risgan/presentacion-sigechip/issues)

</div>

---

## 📋 Descripción

Esta es la **presentación interactiva** del proyecto de grado **SIGECHIP**, un sistema innovador de identificación y gestión de mascotas mediante tecnología RFID y un servidor web basado en Raspberry Pi.

La presentación está construida como una **aplicación web moderna** con navegación dinámica, galería de imágenes interactiva, y soporte para pantalla completa, diseñada para mostrar de manera profesional todos los aspectos técnicos y funcionales del proyecto.

---

## ✨ Características

### 🎨 **Diseño Profesional**
- ✅ **20 diapositivas diseñadas** con los colores institucionales de la ECCI
- ✅ Tipografía moderna (Montserrat + Roboto)
- ✅ Iconografía con Font Awesome
- ✅ Animaciones y transiciones suaves
- ✅ Diseño responsive y adaptable

### 🎯 **Navegación Intuitiva**
- ⬅️ ➡️ Navegación con teclas de flecha
- 🖱️ Botones de navegación (Anterior/Siguiente/Inicio/Final)
- 🔢 Salto directo a cualquier diapositiva
- 📊 Barra de progreso visual
- 🖥️ Modo pantalla completa con escala automática

### 🖼️ **Galería de Imágenes Interactiva**
- 🔍 Visualización en modal de imágenes
- 🎨 Navegación entre imágenes con teclas o botones
- 📝 Títulos y descripciones contextuales
- ❌ Cierre con tecla ESC

### 📄 **Funciones Adicionales**
- 💾 Exportación de diapositivas a PDF (individual)
- 🎨 Colores de marca ECCI (#003B70, #D66D00)
- 📱 Compatible con todos los navegadores modernos

---

## 🚀 Demo en Vivo

🌐 **[Ver presentación en vivo](https://risgan.github.io/presentacion-sigechip)**

---

## 🛠️ Tecnologías Utilizadas

<table>
<tr>
<td align="center" width="33%">

### Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

</td>
<td align="center" width="33%">

### Bibliotecas
- **Chart.js** - Gráficos
- **html2pdf.js** - Exportación PDF
- **Font Awesome** - Iconos
- **Google Fonts** - Tipografía

</td>
<td align="center" width="33%">

### Despliegue
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

</td>
</tr>
</table>

---

## 📦 Instalación Local

### Prerrequisitos

- Git instalado
- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Python 3 (opcional, para servidor local)

### Pasos

1. **Clonar el repositorio**
```bash
git clone https://github.com/risgan/presentacion-sigechip.git
cd presentacion-sigechip
```

2. **Opción A: Abrir directamente**
```bash
# Abrir index.html en tu navegador
start index.html  # Windows
open index.html   # macOS
xdg-open index.html  # Linux
```

3. **Opción B: Servidor local (recomendado)**
```bash
# Con Python
python -m http.server 8080

# Con Node.js (npx http-server)
npx http-server -p 8080

# Con PHP
php -S localhost:8080
```

4. **Abrir en el navegador**
```
http://localhost:8080
```

---

## 📖 Guía de Uso

### ⌨️ Atajos de Teclado

| Tecla | Acción |
|-------|--------|
| `→` | Siguiente diapositiva |
| `←` | Diapositiva anterior |
| `F11` | Pantalla completa |
| `ESC` | Salir de pantalla completa / Cerrar galería |
| `1-20` + `Enter` | Ir a diapositiva específica |

### 🖱️ Controles de Navegación

- **Botones de navegación**: En la barra superior
- **Input numérico**: Ingresa el número de diapositiva y presiona Enter
- **Barra de progreso**: Visual del avance en la presentación
- **Botón de pantalla completa**: Oculta controles y escala la presentación

### 🖼️ Galería de Imágenes

1. **Click en cualquier imagen** para abrirla en grande
2. Navega con las flechas `←` `→` o los botones laterales
3. Cierra con `ESC` o el botón `×`

---

## 📐 Estructura del Proyecto

```
presentacion-sigechip/
│
├── index.html              # Archivo principal de la presentación
├── README.md              # Este archivo
├── gallery-config.json    # Configuración de la galería de imágenes
│
└── files/                 # Recursos multimedia
    ├── logoEcci.png
    ├── RaspberryPi.png
    ├── frontend.png
    ├── qr.png
    └── ... (más imágenes)
```

---

## 🎯 Contenido de la Presentación

La presentación cubre los siguientes temas:

1. **Portada** - Introducción al proyecto
2. **Planteamiento** - Contexto y problemática
3. **Objetivos** - General y específicos
4. **Metodología** - Fases del proyecto
5. **Arquitectura** - Diseño del sistema
6. **Tecnologías** - Stack tecnológico
7. **Hardware** - Componentes físicos
8. **Base de Datos** - Modelo de datos
9. **Backend** - API .NET Core
10. **Frontend** - Aplicación Angular
11. **Funcionalidades** - Características del sistema
12. **Interfaz** - Diseño de usuario
13. **Pruebas** - Validación del sistema
14. **Seguridad** - Medidas implementadas
15. **Despliegue** - Puesta en producción
16. **Resultados** - Logros alcanzados
17. **Conclusiones** - Aprendizajes y cierre
18. **Recomendaciones** - Mejoras futuras
19. **Demostración** - QR y acceso al sistema
20. **Agradecimientos** - Cierre

---

## 🌐 Despliegue en la Nube

### GitHub Pages (Gratis)

```bash
# 1. Crear repositorio en GitHub
# 2. Subir código
git add .
git commit -m "Subir presentación"
git push origin main

# 3. Activar GitHub Pages
# Settings > Pages > Source: main branch
```

Tu sitio estará en: `https://tu-usuario.github.io/presentacion-sigechip`

### Vercel (Gratis)

```bash
# Instalar Vercel CLI
npm install -g vercel

# Desplegar
vercel

# Tu sitio estará en: https://presentacion-sigechip.vercel.app
```

---

## 👨‍💻 Autor

**John Alvaro Rueda Forero**
- 🎓 Estudiante de Ingeniería Electrónica
- 🏫 Universidad ECCI
- 📧 Email: [tu-email@ejemplo.com]
- 💼 LinkedIn: [Tu perfil]
- 🐙 GitHub: [@risgan](https://github.com/risgan)

**Director de Proyecto**
- Ing. Ronald S. Rodriguez R.

---

## 📄 Licencia

Este proyecto es parte de un trabajo de grado para la Universidad ECCI y está disponible bajo uso académico.

---

## 🙏 Agradecimientos

- **Universidad ECCI** - Por el apoyo institucional
- **Ing. Ronald S. Rodriguez R.** - Por la dirección del proyecto
- **Facultad de Ingenierías** - Por los recursos y guía
- **Comunidad Open Source** - Por las herramientas utilizadas

---

## 📞 Contacto y Soporte

¿Tienes preguntas o sugerencias?

- 🐛 [Reportar un problema](https://github.com/risgan/presentacion-sigechip/issues)
- 💡 [Sugerir una mejora](https://github.com/risgan/presentacion-sigechip/issues)
- 📧 Email: [tu-email@ejemplo.com]

---

<div align="center">

**⭐ Si te gustó esta presentación, dale una estrella al repositorio ⭐**

Hecho con ❤️ por [John Alvaro Rueda Forero](https://github.com/risgan)

![ECCI Logo](files/logoEcci.png)

---

`Universidad ECCI • Facultad de Ingenierías • Ingeniería Electrónica • 2026`

</div>
