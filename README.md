# Quiosco de Comida y Bebida en ReactJS

El Quiosco de Comida y Bebida es una aplicación web desarrollada en ReactJS que permite a los usuarios realizar pedidos en distintas categorías. La aplicación se conecta a una API Rest para registrar todas las operaciones, e implementa tecnologías como react-router-dom, context, custom hooks, useSWR y Tailwind CSS.

## Características Principales

- **Categorías de Comida y Bebida:** Los usuarios pueden explorar distintas categorías de productos disponibles en el quiosco, como comida rápida, bebidas, postres, etc.

- **Agregar Pedidos:** Los usuarios pueden agregar productos al carrito y realizar pedidos de manera sencilla.

- **Administración de Pedidos:** Los administradores pueden dar seguimiento a los pedidos generados por los usuarios, gestionar el estado de los pedidos y marcarlos como completados.

## Tecnologías Utilizadas

- **ReactJS:** La aplicación cliente está desarrollada utilizando ReactJS para construir interfaces de usuario interactivas y eficientes.

- **React Router Dom:** Se utiliza para gestionar la navegación y habilitar la creación de rutas dentro de la aplicación.

- **Context API:** El Context de React se aprovecha para manejar el estado global de la aplicación y compartir datos entre componentes.

- **Custom Hooks y useSWR:** Se implementan custom hooks y la librería useSWR para gestionar de manera efectiva el estado de la aplicación y las peticiones a la API.

- **Tailwind CSS:** Para el diseño y estilos, se utiliza Tailwind CSS, permitiendo un desarrollo ágil y fácil personalización.

## Instalación

1. **Clonar el Repositorio:**
```sh
git clone https://github.com/diegoT3ck/quiosco-react.git
````

2. **Instalar Dependencias:**    
```sh
cd quiosco-comida-bebida npm install
```
    
3. **Configurar la API:**
    - Asegúrate de tener la API Rest en funcionamiento y actualiza la configuración en archivos como ``/api/user`, `api/pedidos` y `api/productos` según tus endpoints.
    - archivo ``env.local``
```env
//Servidor
VITE_API_URL=http://localhost
```

1. **Iniciar la Aplicación:**
```sh
npm start
```
    
5. **Acceder a la Aplicación:** Abre la aplicación en tu navegador en [http://localhost:3000](http://localhost:3000/).
    

## Contribuciones

¡Contribuciones son bienvenidas! Si encuentras errores o mejoras posibles, siéntete libre de abrir un problema o enviar un pull request.
