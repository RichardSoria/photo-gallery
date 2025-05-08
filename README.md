# 📸 Proyecto Galería de Fotos

Este repositorio contiene una aplicación de galería de fotos desarrollada con Ionic, con diferentes funcionalidades. Cada funcionalidad está implementada en una rama distinta, según lo solicitado.

---

## 🔀 Estructura del repositorio

Cada funcionalidad (literal) tiene su propia rama:

- `Mostrar-las-fotos-y-además-mostrar-el-nombre-del-archivo-debajo-de-cada-foto-`
- `Mostrar-las-fotos-previamente-guardadas-en-el-tab3-en-lugar-del-tab2`
- `No-mostrar-las-fotos-automáticamente,-implementar-un-botón-que-me-permita-cargar-las-fotos-(en-cualquier-tab)-`
- `Implementar-un-botón-adicional-que-tome-las-fotos-al-50%-de-calidad-`

---

## ✅ Literal A – Mostrar fotos con nombre del archivo

**Rama:** `Mostrar-las-fotos-y-además-mostrar-el-nombre-del-archivo-debajo-de-cada-foto-`

**¿Qué se hizo?**  
Se muestra cada imagen junto con su nombre de archivo debajo. Para lograr esto, se utilizó uno de los componentes gráficos que ofrece Ionic, permitiendo incluir el texto del nombre debajo de cada imagen.

---

## ✅ Literal B – Mostrar fotos en Tab 3

**Rama:** `Mostrar-las-fotos-previamente-guardadas-en-el-tab3-en-lugar-del-tab2`

**¿Qué se hizo?**  
Originalmente, las fotos se mostraban en el Tab 2. Se modificó la lógica para que las fotos se muestren exclusivamente en el Tab 3. Esto implicó mover la funcionalidad de carga al componente correspondiente a esa pestaña.

---

## ✅ Literal C – Botón para cargar fotos manualmente

**Rama:** `No-mostrar-las-fotos-automáticamente,-implementar-un-botón-que-me-permita-cargar-las-fotos-(en-cualquier-tab)-`

**¿Qué se hizo?**  
Se eliminó la carga automática de fotos al iniciar la aplicación. En su lugar, se implementó un botón con ícono de ojo que permite mostrar las fotos solo cuando el usuario lo desee. Este botón modifica una propiedad que controla la visibilidad del componente en el DOM.

---

## ✅ Literal D – Botón para tomar fotos al 50% de calidad

**Rama:** `Implementar-un-botón-adicional-que-tome-las-fotos-al-50%-de-calidad-`

**¿Qué se hizo?**  
Se añadió un botón extra llamado `"Tomar foto (50%)"`. Este utiliza la misma función existente para capturar fotos, pero se le pasa un parámetro `quality` con valor `50`, lo que permite reducir la calidad al capturar la imagen.

---

## 📦 Requisitos para ejecutar

- Tener instalado Node.js (si se usa servidor)
- Tener un proyecto inicializado con Ionic
- Instalar las librerías necesarias para acceder a la cámara
- Configurar correctamente el servicio de cámara
- Conceder los permisos adecuados para usar la cámara en dispositivos Android y iOS
