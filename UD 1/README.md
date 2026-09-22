# Documentación UD1 Lenguaje de Marcas 

## Introducción a Lenguaje de marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas.

### Clasificación de Lenguajes de marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar formato a documentos de texto|HTML, CSSS|
|Intercambio de información|Almacenar información de forma ordenada|XML, RSS|
|Documentación|Documentar proyectos|Markdown, WikiTex|

## Instalación y configuración del entorno

1. Instalamos [**VS Code**](https://code.visualstudio.com/)
2. Instalamos **plugins**
    - [**HTML CSS Support**](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
    - [**Live Preview**](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
    - [**Markdown All in One**](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    - [**XML**](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml)

3. Instalamos **Git**
```bash
sudo apt install git
```

1. Configurar repositorio git (en la carpeta principal del proyecto)
```bash
git init
git add
git commit -m "comentario descriptivo"
```
1. Conectar con GitHub
```bash
git remote add origin https://github.com/christian-cabaleiro/LM-Christian.git
git branch -M main
git push -u origin main
```


  
### Descripción de plugins:
    
|Plugin|Imagen|Uso|
|------|-------------|---|
|**HTML CSS Support**|![](img/Microsoft.VisualStudio.Services.Icons.png)|Plugin complementario de HTML para facilitar sintaxis y autocompletado de CSS.|
|**Live Preview**|![](img/liveprev.png)|Previsualizador web en directo.|
|**Markdown All in One**|![](img/markdown.png)|Visualizador de Markdown formateado.|
|**XML**|![](img/xml.png)|Facilitar sintaxis y autocompletado de XML.|