# Smooth-Dark-Focus-Theme

**Smooth-Dark-Focus-Theme** es un tema para vscode inspirado en **Smooth Dark**. La idea es mantener los colores de código del tema pero cambiando el tema de vscode a uno completamente negro.

## 🛠️ Pasos de instalación:

1. Descargar el repositorio de **GitHub**.

2. Instala **Node.js** desde su pagina en la versión **LTS**: **nodejs.org**

3. Abrir el proyecto en **VS Code**.

4. Abrir el terminar y ejecutar:

```
npm install
```

5. Después nos movemos en el terminal a la carpeta del tema:

```
cd .\smooth-dark-focus\
```

6. Ejecutamos el siguiente comando que nos creara la extensión del tema para instalarlo en vscode:

```
npx vsce package
```

Le decimos a todo `y`.

7. Se nos creara en `.\smooth-dark-focus\` el archivo `smooth-dark-focus-0.0.1.vsix` ahora instalamos con el siguiente comando:

```
code --install-extension .\smooth-dark-focus\smooth-dark-focus-0.0.1.vsix
```
