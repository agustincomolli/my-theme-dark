# My Modern Dark Theme para Visual Studio Code

![Banner de Mi Tema Oscuro Moderno](icons/icon.png)

Mi Tema Oscuro Moderno es un tema personalizado para Visual Studio Code, basado en el popular tema Modern Dark. Ha sido modificado para incluir fuentes en cursiva y está optimizado para su uso con la fuente Victor Mono.

## Características

- **Estética Moderna Oscura:** Mi Tema Oscuro Moderno se basa en el diseño elegante y moderno del tema Modern Dark, proporcionando una experiencia visualmente agradable mientras codificas.

- **Fuentes en Cursiva:** Este tema incluye fuentes en cursiva para una presentación del código más elegante y distintiva visualmente.

- **Fuente Victor Mono:** Mi Tema Oscuro Moderno está optimizado para su uso con la fuente Victor Mono, mejorando la experiencia general de codificación.

## Instalación

1. Abre Visual Studio Code.

2. Ve a la vista de Extensiones haciendo clic en el icono cuadrado en la barra lateral izquierda o presionando `Ctrl+Shift+X`.

3. Busca "my-modern-dark-theme".

4. Haz clic en el botón "Instalar" para instalar el tema.

5. Una vez instalado, selecciona el tema en el menú desplegable de Tema de Color en la Paleta de Comandos (`Ctrl+K Ctrl+T`) o haciendo clic en el icono de engranaje en la esquina inferior derecha de la ventana y seleccionando "Tema de Color".

## Capturas de Pantalla

![Captura de Pantalla 1](images/screenshot1.png)

![Captura de Pantalla 2](images/screenshot2.png)

## Personalización

Puedes personalizar aún más el tema modificando tu archivo `settings.json`. Aquí tienes un ejemplo de configuración que puedes usar:

```json
{
  "editor.fontFamily": "Victor Mono",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "keyword",
          "variable.language"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      }
    ]
  }
}
