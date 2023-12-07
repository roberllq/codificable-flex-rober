# Codificable Flex Components

## Asignación

Desarrollar nuevos componentes para la web de Codificable e implementar mejoras a ciertos componentes actuales utilizando Flexbox

- <a href="https://www.figma.com/file/KdM1M43yFmCSdrYKGKlViX/Codificable-UI?type=design&node-id=0%3A1&mode=design&t=KvbQk0JxcdWkqD5j-1" target="_blank">Diseño en Figma</a>

## Container adaptable

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1692472811/illustrations/media_t40f8z.svg" />
  <figcaption>Contenedor con diferente padding según tamaño de pantalla</figcaption>
</figure>

### Requerimiento

- Modificar el objeto `container` para que su padding cambie según el tamaño de la pantalla siguiendo las instrucciones de la lección **Media Queries**

## Componente Button

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693344748/illustrations/button_knmwdd.png" />
  <figcaption>Componente Button y sus variantes</figcaption>
</figure>

### Requerimiento

- Crear el componente **Button** siguiendo las especificaciones de Figma
- Utilizar BEM para el nombre de las clases
- Utilizar Flexbox para centrar el contenido del botón y separar el texto del ícono en caso haya un ícono presente.

## Header Flexible

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693344982/illustrations/header_e1zpi7.png" />
  <figcaption>Header flexible con acción a la derecha</figcaption>
</figure>

### Requerimiento

- Modificar el Header actual para que incorpore un botón de "Login" (usando el componente **Button** previamente construido)
- En pantallas pequeñas el botón de "Login" debe desaparecer y un botón con un ícono de "Menu" debe aparecer en su lugar.

## Hero con acciones

<figure>
  <img src="https://res.cloudinary.com/dwdgpw20b/image/upload/v1693345347/illustrations/herolflex_bp2yiz.png" />
  <figcaption>Hero con acciones</figcaption>
</figure>

### Requerimiento

- Modificar el Hero para que incluya un botón de Login adicional el link del blog.
- El link debe incluir un ícono de flecha
- Usa flexbox para distribuir los elementos.
