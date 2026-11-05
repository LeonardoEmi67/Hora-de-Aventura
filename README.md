# Hora de Aventura

Sitio web de fans sobre la serie animada **Hora de Aventura**. Presenta a varios de sus personajes con descripciones, galerías de imágenes y un formulario de registro de usuarios.
![Hora de aventura](https://imagenes.elpais.com/resizer/v2/NA6RH5GTFZJU6PRIEXQGXXAOLQ.jpg?auth=cd20c68e5d9cac0b081ad519dd4f46b0bf3cf187c6767f961adfd84729794acd&width=1960&height=1470&smart=true)

## Páginas

- **Inicio (`index.html`)**: imagen principal y tarjetas con los personajes Jake, Dulce Princesa, Mentita y Tronquitos.
- **Finn (`finn.html`)**: galería, descripción, personalidad y espíritu aventurero de Finn. Diseño en tonos azules.
- **B-MO (`bmo.html`)**: galería y descripción de B-MO, el pequeño robot consola de videojuegos. Diseño en tonos turquesa.
- **Registro (`registro.html`)**: formulario para registrar nombre y correo electrónico.

## Funcionalidades

- Menú de navegación adaptable a celular (Bootstrap).
- Páginas de personajes con galería de imágenes, tarjetas informativas y efectos al pasar el mouse.
- Formulario de registro que envía los datos (nombre y correo) mediante el método POST a `php/guardar.php`.

## Tecnologías

- HTML5
- CSS3 (`css/style.css` y estilos propios en cada página)
- [Bootstrap 5.3.8](https://getbootstrap.com/) (vía CDN)
- PHP (para guardar los datos del formulario de registro)

## Estructura del proyecto

```
├── index.html
├── finn.html
├── bmo.html
├── registro.html
├── css/
│   └── style.css
├── img/
│   └── (imágenes de los personajes y logo)
└── php/
    └── guardar.php
```

## Cómo usarlo

1. Descarga o clona el repositorio:
   ```
   git clone https://github.com/LeonardoEmi67/Hora-de-Aventura
   ```
2. Para ver las páginas, abre `index.html` en tu navegador.
3. Para que el formulario de registro funcione, ejecuta el proyecto en un servidor con PHP (por ejemplo XAMPP) y coloca la carpeta dentro de `htdocs`.

Se necesita conexión a internet para cargar Bootstrap.

## Autor

Leonardo Emiliano Moreira, grupo 502 PO.
