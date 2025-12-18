# 🚀 Ejecutar proyecto React

Guía rápida para **levantar un proyecto React** usando `npm run dev`.

---

## 📋 Requisitos

- **Node.js** (incluye npm)

### 🔧 Instalación de Node.js y npm

#### Windows (usando instalador .msi — recomendado)

1. Entra a la página oficial de Node.js.
2. En la sección de descargas, selecciona:
   - **Sistema operativo:** Windows
   - **Arquitectura:** x64
3. Descarga el archivo **Windows Installer (.msi)**.

> ✅ **Importante:** Debes descargar el archivo **`.msi`**, no el `.zip`.

4. Ejecuta el archivo `.msi` descargado.
5. Sigue el asistente de instalación dejando las opciones por defecto.
   - Asegúrate de que esté marcada la opción **“Add to PATH”**.
6. Finaliza la instalación.

Verifica la instalación abriendo una nueva terminal:

```bash
node -v
npm -v
```

---

## 📂 Ubicación del proyecto

Abre una terminal y entra a la carpeta del proyecto:

```bash
cd ruta/del/proyecto
```

Ejemplo:

```bash
cd Documentos/mi-proyecto-react
```

---

## 📦 Instalar dependencias

> ⚠️ Solo la **primera vez** o después de clonar el proyecto

```bash
npm install
```

---

## ▶️ Ejecutar el proyecto

```bash
npm run dev
```

---

## 🌐 Abrir en el navegador

Cuando el servidor inicie, verás algo como:

```text
Local: http://localhost:5173/
```

Abre en tu navegador:

```text
http://localhost:5173
```

---

## ⏹️ Detener el servidor

En la terminal presiona:

```text
Ctrl + C
```

---

## ❗ Problemas comunes

- **`npm` no reconocido** → Node.js no está instalado o no está en el PATH
- **Puerto ocupado** → Cierra otras apps o reinicia la terminal

---

✅ Proyecto React ejecutándose correctamente.