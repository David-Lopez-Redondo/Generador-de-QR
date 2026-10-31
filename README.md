# ⚡ Generador de QR Dinámico

Aplicación web ligera para generar códigos QR de forma rápida y sencilla
a partir de cualquier texto o enlace. Incluye actualización automática,
descarga en formato JPG y una interfaz visual con estética neón.

## ✨ Características

-   **Generación dinámica:** crea códigos QR a partir de cualquier
    enlace o texto.
-   **Actualización automática:** el código QR se actualiza mientras
    escribe, sin necesidad de pulsar ningún botón.
-   **Alta resolución:** generación de códigos QR con resolución
    optimizada para su descarga.
-   **Corrección de errores nivel H:** permite recuperar información
    incluso si parte del código QR está dañada.
-   **Descarga JPG:** exporta el código QR como imagen JPG con calidad
    del 95 %.
-   **Pantalla completa:** permite utilizar la aplicación a pantalla
    completa.
-   **Diseño responsive:** interfaz adaptable a diferentes tamaños de
    pantalla.
-   **Estética neón:** diseño oscuro con efectos luminosos en cian y
    magenta.

## 🛠️ Tecnologías utilizadas

  Tecnología               Aplicación
  ------------------------ ------------------------------------------
  HTML5                    Estructura de la aplicación
  CSS3                     Diseño, animaciones y estilos responsive
  JavaScript               Lógica y generación dinámica
  Canvas API               Renderizado del código QR
  qrcode-generator 1.4.4   Generación de códigos QR

## 🚀 Instalación y ejecución

No requiere instalación de dependencias ni configuración de servidor.

1.  Descargue o clone este repositorio:

    ``` bash
    git clone https://github.com/USUARIO/qr-generator.git
    ```

2.  Acceda a la carpeta del proyecto:

    ``` bash
    cd qr-generator
    ```

3.  Abra el archivo `QR Generator.html` directamente en su navegador.

**Requisito:** conexión a Internet para cargar la librería
`qrcode-generator` desde CDN.

## 📖 Cómo utilizarlo

1.  Abra la aplicación en su navegador.
2.  Introduzca o pegue el enlace que desea convertir en código QR.
3.  El código QR se actualizará automáticamente.
4.  También puede pulsar **Generar Código QR** para actualizarlo
    manualmente.
5.  Pulse **Descargar JPG** para guardar la imagen.
6.  Utilice **Pantalla completa** para ampliar la visualización.

## ⌨️ Atajos de teclado

  Tecla     Acción
  --------- --------------------------------------
  `Enter`   Generar código QR
  `F11`     Activar o salir de pantalla completa
  `Esc`     Salir de pantalla completa

## 📸 Vista previa

La aplicación presenta una interfaz minimalista de temática oscura, con
detalles luminosos en cian y magenta, diseñada para ofrecer una
experiencia visual moderna.

## 📂 Estructura del proyecto

``` text
qr-generator/
│
├── QR Generator.html
└── README.md
```

## 📚 Librería externa

Este proyecto utiliza
[qrcode-generator](https://cdnjs.cloudflare.com/ajax/libs/qrcode-generator/1.4.4/qrcode.min.js)
para generar los códigos QR.

## 👨‍💻 Autor

**@3ng1ne_W0lf**

------------------------------------------------------------------------

⭐ Si te resulta útil este proyecto, considera darle una estrella al
repositorio.
