# Temario Modular con Bloques y Plantillas

Este proyecto es una página web simple y modular para organizar el temario de una asignatura. Está pensado para que puedas escribir y estructurar el temario fácilmente en Visual Studio u otro editor, usando plantillas HTML.

---

## Características

- Menú lateral fijo a la izquierda con botones para navegar entre secciones.
- Área principal para mostrar contenido modular dividido en bloques (tarjetas blancas).
- Footer fijo abajo a la derecha, con información de autor y enlace a Instagram.
- Plantillas definidas en `<template>` para organizar el contenido y facilitar su mantenimiento.
- Navegación dinámica que carga contenido al pulsar los botones del menú.
- Diseño responsivo y limpio con colores contrastados.

---

## Estructura del Proyecto

- `nav`: Menú lateral con botones para cargar distintas plantillas.
- `main`: Contenedor principal donde se cargan los bloques de contenido.
- `footer`: Pie de página con derechos y redes sociales.
- Plantillas en el HTML con id único, que contienen bloques `<section class="bloque">` con contenido modular.
- Script en la parte inferior que gestiona el cambio de plantillas y la interacción del menú.

---

## Cómo usar

1. **Editar contenido:** Modifica o añade nuevas plantillas dentro del HTML en los elementos `<template>` con un id único.
2. **Añadir bloques:** Dentro de cada plantilla puedes añadir tantos bloques `<section class="bloque">` como necesites para organizar la información.
3. **Navegación:** Los botones del menú lateral deben tener el atributo `data-template` con el id de la plantilla que quieres mostrar.
4. **Abrir en navegador:** Abre el archivo `.html` en cualquier navegador moderno para ver y navegar el temario.

---

## Personalización

- Puedes cambiar colores y estilos CSS en la sección `<style>`.
- Añade nuevas secciones o temas duplicando y modificando los bloques `<template>`.
- Puedes mejorar la navegación añadiendo animaciones, scroll suave o submenús.
- Para hacer la página multi-idioma o editable, se pueden añadir funcionalidades JavaScript avanzadas.

---

## Requisitos

- Navegador moderno con soporte para `<template>` y Flexbox (Chrome, Firefox, Edge, Safari…).
- No necesita servidor ni backend, es una página estática.

---

## Autor

Miguel Cox Caballero  
[Instagram @miguelcoxcaballero](https://www.instagram.com/miguelcoxcaballero)

---

## Licencia

Este proyecto es libre para uso personal y educativo.

---

¡Disfruta organizando tu temario de forma sencilla y modular!

