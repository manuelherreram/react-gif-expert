# Gift Expert App

Esta aplicación web, desarrollada con React y Vite, permite a los usuarios buscar y visualizar GIFs de manera interactiva. Forma parte del curso "React: De cero a experto" de Fernando Herrera (devtalles.com).

## Características principales

- Búsqueda de GIFs por categorías
- Visualización de GIFs en una cuadrícula
- Interfaz de usuario intuitiva y responsive

## Tecnologías utilizadas

- React
- Vite
- Yarn (gestor de paquetes)
- CSS para estilos
- API de Giphy para la obtención de GIFs

## Estructura del proyecto

El proyecto está organizado en varios componentes y utiliza hooks personalizados:

- `GifExpertApp`: Componente principal que maneja el estado de las categorías.
- `AddCategory`: Permite al usuario añadir nuevas categorías de búsqueda.
- `GifGrid`: Muestra la cuadrícula de GIFs para una categoría específica.
- `GifItem`: Representa un GIF individual en la cuadrícula.
- `useFetchGifs`: Hook personalizado para manejar la carga de GIFs desde la API.

## Instalación

1. Clona este repositorio
2. Navega al directorio del proyecto
3. Instala las dependencias con Yarn:

```bash
yarn install
```

## Ejecución

Para iniciar la aplicación en modo desarrollo:

```bash
yarn dev
```

La aplicación estará disponible en `http://localhost:5173` (o el puerto que Vite asigne).

## Construcción para producción

Para construir la aplicación para producción:

```bash
yarn build
```

Los archivos de construcción se generarán en el directorio `dist`.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue para discutir cambios mayores antes de crear un pull request.

## Demo en Github Pages y Netlify

[Github_Pages](https://manuelherreram.github.io/react-gif-expert/)
[Netlify](https://gift-expert-mh.netlify.app/)

## Licencia

[MIT](https://choosealicense.com/licenses/mit/)

---

Desarrollado como parte del curso "React: De cero a experto" de Fernando Herrera (devtalles.com).
