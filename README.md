
---

# Página de Gestión de Operaciones

Esta página web permite gestionar operaciones financieras, como ingresos y egresos, almacenando y manipulando los datos utilizando una API basada en json-server.

## Funcionalidades

1. **Ingreso de Datos:**
   - Para ingresar un nuevo dato, completa el formulario en la parte superior de la página y haz clic en "Agregar". El dato será almacenado en la API y se mostrará en la tabla.

2. **Modificación de Datos:**
   - Selecciona las filas que deseas modificar marcando las casillas de selección.
   - Haz clic en "Modificar Operación". Para cada operación seleccionada, se te pedirá que ingreses el nuevo monto. Ingresa el monto y haz clic en "Aceptar". Los datos serán actualizados tanto en la tabla como en la API.

3. **Eliminación de Datos:**
   - Selecciona las filas que deseas eliminar marcando las casillas de selección.
   - Haz clic en "Eliminar Operación". Las operaciones seleccionadas serán eliminadas tanto de la tabla como de la API.

4. **Búsqueda de Datos:**
   - Ingresa el ID de la operación que deseas buscar en el campo de búsqueda y haz clic en "Buscar Operación". Si se encuentra, se mostrará un cuadro de diálogo con los detalles de la operación.

## Uso

1. Clona este repositorio en tu máquina local.

    ```bash
    git clone https://github.com/DwightHernandez/PresupuestoCasa2.git
    ```

2. Asegúrate de tener [Node.js](https://nodejs.org) instalado.

3. Instala las dependencias utilizando el siguiente comando en la terminal:

   ```bash
   npm install
   ```

4. Inicia el servidor json-server con el siguiente comando:

   ```bash
   json-server --watch db.json --port 5010
   ```

5. Abre el archivo `index.html` en tu navegador para acceder a la página.

6. Utiliza las funcionalidades de la página según lo explicado anteriormente.

---
