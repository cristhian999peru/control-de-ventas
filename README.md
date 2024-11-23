# control-de-ventas
Descripción del Modelo de Base de Datos para un Sistema de Control de Ventas en una Ferretería

Usuarios: Esta tabla almacena la información de los usuarios que tienen acceso al sistema. Incluye campos como el ID del usuario, nombre de usuario, correo electrónico, contraseña y la fecha de creación del usuario.

Productos: Aquí se registran todos los productos disponibles en la ferretería. Los campos incluyen el ID del producto, nombre del producto, descripción, precio, cantidad en stock y la fecha de registro del producto.

Clientes: Esta tabla contiene la información de los clientes de la ferretería. Los campos incluyen el ID del cliente, nombre del cliente, teléfono, dirección, correo electrónico y la fecha de registro del cliente.

Ventas: En esta tabla se registran las ventas realizadas. Incluye el ID de la venta, el ID del cliente que realizó la compra, el ID del usuario que procesó la venta, el total de la venta y la fecha de la venta. También establece relaciones con las tablas de Clientes y Usuarios.

DetalleVentas: Esta tabla almacena los detalles de cada venta, especificando los productos vendidos en cada transacción. Incluye el ID del detalle, el ID de la venta, el ID del producto, la cantidad vendida y el subtotal de cada producto. Establece relaciones con las tablas de Ventas y Productos.

Este modelo de base de datos permite gestionar eficientemente las ventas, el inventario y la información de los clientes y usuarios, proporcionando una estructura sólida para el funcionamiento del sistema de control de ventas de la ferretería.
![image](https://github.com/user-attachments/assets/99534768-47aa-450a-a51e-728429dfda79)
