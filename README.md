# 📱 SocialGit – Aplicación de Reportes Ciudadanos

SocialGit es una aplicación móvil desarrollada en **Android Studio (Kotlin)** que permite a los usuarios registrar reportes ciudadanos, subir fotografías, visualizar estadísticas mediante gráficas y administrar información mediante un backend en **PHP + MySQL**.

---

## 🚀 Características principales

### ✅ Registro de usuarios y autenticación
- Inicio de sesión mediante API REST.
- Validación de credenciales.
- Manejo de sesiones seguras.

### ✅ Creación de reportes
- Captura de fotografías desde la cámara o galería.
- Subida de imágenes comprimidas al servidor.
- Envío de reportes mediante peticiones POST a PHP.
- Campos: título, descripción, categoría, fecha, ubicación (opcional).

### ✅ Visualización de estadísticas
- Gráficas creadas con **MPAndroidChart**.
- Colores dinámicos (high/medium/low).
- Obtención de datos desde el backend.

### ✅ Backend integrado
- API en PHP.
- Base de datos MySQL.
- Carpeta `/uploads` para recibir imágenes.

---

## 🗂️ Estructura del proyecto

