
---

# Registro de Ingresos y Egresos

Este proyecto consiste en una aplicación web que permite llevar un registro de ingresos y egresos. La aplicación utiliza HTML para la estructura de la página y JavaScript para la interactividad y la comunicación con una API de registros.

## Contenido

- [Estructura del Proyecto](#estructura-del-proyecto)
- [Uso](#uso)
- [Funcionalidades](#funcionalidades)
- [API de Registros](#api-de-registros)

## Estructura del Proyecto

El proyecto consta de dos archivos principales:

- **HTML (index.html):** Contiene la estructura de la página web y los elementos de interfaz de usuario.
  
- **JavaScript (main.js):** Implementa la lógica de la aplicación, la interacción con la API de registros y las funcionalidades de manipulación de datos.

## Uso

1. Clona o descarga el repositorio a tu máquina local.

    ```bash
    git clone https://github.com/KevinnHernandez/Pokedex.git
    ```

2. Abre el archivo `index.html` en un navegador web.
   
3. Completa el formulario ingresando el monto y seleccionando si es un ingreso o un egreso.
   
4. Haz clic en "Calcular" para agregar el registro a la tabla.
   
5. Puedes eliminar o modificar registros seleccionándolos y utilizando los botones correspondientes.

## Funcionalidades

- **Agregar Registros:** Permite agregar registros de ingresos y egresos.

- **Eliminar Registros:** Permite eliminar registros seleccionados.

- **Modificar Registros:** Permite modificar el monto de los registros seleccionados.

- **Buscar por ID:** Permite buscar un registro por su ID.

## API de Registros

La aplicación interactúa con una API de registros simulada. La URL de la API es [https://6509e208f6553137159c30bf.mockapi.io/Registros](https://6509e208f6553137159c30bf.mockapi.io/Registros).

- **GET:** Obtiene la lista de registros.

- **POST:** Agrega un nuevo registro.

- **PUT:** Modifica un registro existente.

- **DELETE:** Elimina un registro.

---
