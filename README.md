# Calculadora de Consumo y Propinas para Restaurante

Una aplicación REST API desarrollada con JSON Server que permite gestionar pedidos de clientes, calcular el consumo total y la propina. Incluye funcionalidades para agregar, editar y eliminar platillos del pedido, y mostrar un resumen del consumo.

## Instalación

1. Clona este repositorio:

    ```bash
    git clone https://github.com/tu_usuario/nombre_del_proyecto.git
    cd nombre_del_proyecto
    ```

2. Asegúrate de tener Node.js y npm instalados. Puedes verificarlo con:

    ```bash
    node -v
    npm -v
    ```

3. Instala JSON Server globalmente:

    ```bash
    npm install -g json-server
    ```

## Uso

1. Inicia JSON Server con el siguiente comando:

    ```bash
    json-server --watch db.json --port 4000
    ```

2. Abre `index.html` en tu navegador para ver la aplicación en funcionamiento.

## Estructura del Proyecto

- `index.html`: Contiene la estructura HTML de la aplicación.
- `app.js`: Contiene la lógica principal de la aplicación.
- `db.json`: Contiene los datos de los platillos para JSON Server.

## Funcionalidades

- **Gestión de Clientes**: Permite registrar la mesa y la hora de llegada del cliente.
- **Gestión de Pedidos**: Permite agregar, editar y eliminar platillos del pedido.
- **Resumen de Consumo**: Muestra un resumen del consumo total y calcula la propina según el porcentaje seleccionado.

## Dependencias

- [JSON Server](https://github.com/typicode/json-server): Simula una API REST para el manejo de datos.
