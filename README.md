# 🚀 Ejecutar proyecto React

Guía rápida para **levantar un proyecto React** usando `npm run dev`.

---

## 📋 Requisitos

- **Node.js** (incluye npm)

### 🔧 Instalación de Node.js y npm

#### Windows / macOS

1. Descarga el instalador desde el sitio oficial:
    - https://nodejs.org
2. Instala la versión **LTS** siguiendo el asistente.

### ⚙️ Permitir instalación global de paquetes (Windows)

En **Windows**, para evitar errores de permisos al usar `npm -g`, ejecuta en **PowerShell como Administrador**:

```bash
npm config set prefix "$env:APPDATA\npm"
```

Luego agrega npm al PATH (si no se agregó automáticamente):

```text
C:\Users\TU_USUARIO\AppData\Roaming\npm
```

Reinicia la terminal.

Verifica la instalación:

```bashbash
node -v
npm -v
```

#### Linux (Ubuntu / Debian)

```bash
sudo apt update
sudo apt install nodejs npm
```

Verifica:

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