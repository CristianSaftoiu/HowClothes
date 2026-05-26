# 👕 HowClothes – ¿Tu prenda combina?

**HowClothes** es una aplicación web inteligente que analiza los colores de una prenda de vestir y te dice si su combinación cromática es acertada o no. Solo sube una foto y el sistema hará el resto.
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

✨ **Prueba la aplicación aquí:** [https://howclothes.onrender.com/](https://howclothes.onrender.com/)

---

## ✨ ¿Qué puedes hacer?

- 📝 **Registrarte** y confirmar tu cuenta mediante un enlace enviado a tu correo.
- 🔐 **Iniciar sesión** de forma segura.
- 🔄 **Recuperar tu contraseña** con un enlace temporal.
- 🖼️ **Subir una imagen** de cualquier prenda.
- 🎨 **Analizar colores predominantes** y saber si la combinación es:
  - Cálida
  - Fría
  - Neutra
  - Mal combinada

---

## 🧠 ¿Cómo funciona por dentro?

- **Seguridad:** contraseñas almacenadas con hash.
- **Correos:** envío automático con Flask-Mail.
- **Imagen:** procesamiento con la librería PIL (Pillow).
- **Análisis de color:** se utiliza **Machine Learning** (algoritmo KMeans) para agrupar los colores principales y evaluar su armonía.

---

## 🛠️ Tecnologías utilizadas

| Área          | Tecnologías                          |
|---------------|--------------------------------------|
| Backend       | Python, Flask                        |
| Base de datos | SQLite + Flask-SQLAlchemy            |
| Autenticación | Flask-Login                          |
| Emails        | Flask-Mail                           |
| Imagen        | Pillow (PIL)                         |
| ML / Colores  | Scikit-learn (KMeans)                |

---
