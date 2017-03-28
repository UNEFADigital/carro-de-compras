# Requerimientos

## 1. Características Generales del Proyecto

+ Máximo 8 Productos.
+ Máximo 3 Usuarios con saldo y clave serializada en formato MD5.
+ Búsqueda Heurística de productos.
+ Persistencia (usando LocalStorage).
+ Manejo de Sesiones.
+ Manejo de Favoritos por Sesión.
+ Compra contra inventario.
+ Administración de productos.

## 2. Historias de usuario.

+ [ ] Como usuario, quiero ver al menos 8 productos en un orden de 2 filas de 4 productos cada una.
+ [ ] Como usuario, quiero ver de cada producto: *una sola* imagen descriptiva, nombre del producto, precio y cantidad disponible en el inventario.
+ [ ] Como usuario, quiero buscar productos por nombre o categoría de producto, tomando como prioridad los productos que más han sido marcados como favoritos por otros usuarios.
+ [ ] Como usuario registrado, quiero poder manejar el saldo de mi cuenta (en bolívares) para compras futuras de productos en inventario.
+ [ ] Como usuario registrado, quiero listar, incluir y descartar mis productos favoritos en una lista personalizada.
+ [ ] Como usuario registrado, quiero ver mi historial de compras realizadas, listando como prioridad mis productos favoritos.
+ [ ] Como usuario registrado, quiero poder modificar mi información personal: nombre, nombre de usuario y contraseña de acceso, esta última debe estar encriptada.
+ [ ] Como administrador, quiero modificar la información existente en todos los productos (máximo 8 productos), es decir, el costo del producto, el nombre, y la cantidad disponible.
+ [ ] Como administrador, quiero ver los usuarios registrados en el sistema, con su saldo.
+ [ ] Como administrador, quiero poder eliminar del sistema, aquellos productos que **NO** hayan sido marcados como favoritos por ningún usuario.
