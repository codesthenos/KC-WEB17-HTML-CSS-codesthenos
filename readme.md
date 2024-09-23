# Práctica del modulo HTML-CSS impartido por Kevin Julián Martínez Escobar [@kevinccbsg](https://github.com/kevinccbsg) en KeepCoding

La práctica consiste en crear un portfolio.

**Restricciones**:

- No usar librerias externas, solo vanilla HTML y vanilla CSS

- No usar JavaScript

**Obligaciones**:

- Crear al menos una hoja de estilos CSS para aplicar en la web

- La pagina debe visualizarse en las versiones actuales de Google Chrome, Mozilla Firefox y Microsoft Edge

## Forma de visualizar la práctica

- Para **Clonar** el repositorio usando el comando `git clone`:
  - En nuestro ordenador, nos dirigimos al path donde queramos clonar el repositorio, por ejemplo _/Desktop_
  - Una vez estemos en el path donde queremos que genere la copia del repositorio, abrimos un **terminal**
  - En el terminal escribimos `git clone https://github.com/codesthenos/KC-WEB17-HTML-CSS-codesthenos.git`.
  - Esto creara un repositorio local en nuestro ordenador con el nombre **KC-WEB17-HTML-CSS-codesthenos**
- Para **Visualizar** el portfolio:
  - Instalamos [_visual studio code_](https://code.visualstudio.com/download) y la extensión _Live server_
  - Dentro del repositorio que acabos de crear en local, hacemos click derecho en **index.html** y le damos a la opción _Open with Live Server_
  - Esto nos abrirá una pestaña en nuestro navegador predeterminado con la url `http://localhost:5500/index.html` o `http://127.0.0.1:5500/index.html`

## Descripcion del portfolio

- Crear un **header** con una barra de _navegación_, con **links** a cada elemento del portfolio.

- Los **links** tienen que tener un estado _hover_ suavizado con una _transición_.

- Los **links** NO son necesarios en la versión móvil.

- Una sección con nuestra descripción y nuestras **habilidades**.

- Las **habilidades** han de ser barras de progreso _animadas_ con **CSS**

- **Banner** con una **imagen** de fondo

- La **imagen** ha de ser otra en la versión móvil, usar _media queries_ o _responsive images_

- **Formulario** de contacto con los **inputs** del _tipo_ correcto y con sus _validaciones_
  - **inputs:**
    - **Nombre** _required_
    - **Apellidos** _required_
    - **Teléfono** _required_
    - Lista de **radio inputs** que responden a la pregunta _¿cómo me conociste?_
    - Valor de los **radio inputs**:
      - **Universidad**
      - **Keepcoding kick-off**
      - **Colegio**
      - **En Github**
    - Tag de _github_ usar **regexp** `^@[^\s]+` para _validación_ **@username**
    - Mensaje con información del usuario **textarea** _max 180 char_ _required_
    - Acceso a _newsletter_ **checkbox**
    - Botón de **guardado**
    - Botón de **reset**
- **Footer** con _links_ a nuestras redes sociales
- Nueva página que tenga un **video** que se reproduzca al entrar en la web con una animación _fadeIn_
- Nueva página con un **grid** con nuestros proyectos

### Detalles de la implementación

- La estructura web ha de tener en cuenta las etiquetas _HTML_ de contenido **semántico**
- Incluir las **media queries** necesarias para que el diseño sea _responsive_
- **MOBILE FIRST** y si no, es un **NO APTO**
- Animaciones e interactividad solamente con **CSS** sin librerias externas ni _JavaScript_
- Los apartados **opcionales** que se muestran a continuación no son necesarios para el _Apto_ pero se valoran positivamente
- Se entrega mediante **Github**. Un buen uso de los commits es valorado positivamente

#### Opcional

- Crear menú tipo _burger_ usando **CSS** y un _checkbox_ **SIN** usar _JavaScript_
- _Despliegue_ en **Github pages**
- Página **404**
- Página **500**
