# Benja

## Descripción

**Benja** es una aplicación de escritorio construida con Electron. Esta aplicación incluye una ventana principal personalizada y un widget de TradingView que muestra información sobre varios activos financieros. 

El proyecto está configurado para ser empaquetado en un ejecutable usando `electron-builder`, lo que permite crear instaladores para Windows, macOS, y Linux.

## Estructura del Proyecto

- **main.js**: Archivo principal de la aplicación Electron que configura la ventana y carga el contenido HTML.
- **index.html**: Archivo HTML que define la interfaz de usuario.
- **build/**: Carpeta que contiene los íconos utilizados para los instaladores generados por `electron-builder`.
- **dist/**: Carpeta donde se generan los ejecutables e instaladores (no incluida en el repositorio).
- **node_modules/**: Carpeta que contiene todas las dependencias de Node.js (no incluida en el repositorio).

## Características

- **Ventana personalizada**: Se ha configurado una ventana de 1200x130 píxeles sin la barra de menú predeterminada.
- **Widget de TradingView**: Se ha añadido un widget para mostrar información financiera con un tema oscuro.
- **Empaquetado con electron-builder**: El proyecto está configurado para generar instaladores para diferentes plataformas.

## Instalación y Ejecución

1. **Clonar el repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/benja.git
    cd benja
    ```

2. **Instalar las dependencias**:
    ```bash
    npm install
    ```

3. **Ejecutar la aplicación**:
    ```bash
    npm start
    ```

4. **Construir el instalador**:
    ```bash
    npm run build
    ```

## .gitignore

Este proyecto incluye un archivo `.gitignore` para asegurar que las carpetas `node_modules` y `dist` no sean subidas al repositorio. También se ignoran archivos de configuración del entorno y logs.

## Requisitos

- **Node.js** (v12.x o superior)
- **Electron** (v31.3.1)
- **electron-builder** para empaquetar la aplicación.

## Contribuir

Si deseas contribuir a este proyecto, por favor, haz un fork del repositorio, crea una rama (`feature/nueva-caracteristica`), realiza los cambios y envía un pull request.

## Licencia

Este proyecto está bajo la licencia ISC.
