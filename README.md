# Tienda Black Diamond

Este proyecto es una simulación de una tienda llamada "Black Diamond Store" que gestiona productos en un inventario y permite la compra y venta de estos productos. El proyecto está desarrollado en Java y sigue los principios de la programación orientada a objetos, incluyendo interfaces, herencia y encapsulamiento.

## Estructura del Proyecto

El proyecto está compuesto por varias clases que representan diferentes tipos de productos y funcionalidades de la tienda. A continuación, se detalla la estructura principal:

- `Product`: Clase base abstracta que representa un producto genérico con atributos comunes como ID, descripción y precio.

- `Packaged`: Clase que hereda de `Product` y representa productos envasados con información adicional como tipo de empaque, fecha de vencimiento y descuento.

- `Drink`: Clase que hereda de `Product` y representa bebidas con atributos específicos como contenido de alcohol y contenido calórico.

- `CleaningProduct`: Clase que hereda de `Product` y representa productos de limpieza con detalles como tipo de limpieza.

- `ShoppingCart`: Clase que modela el carrito de compras para agregar productos antes de la venta.

- `Store`: Clase principal que gestiona la tienda y sus operaciones, como comprar productos, vender y mantener el inventario.

- Interfaces `IDiscount`, `IEatable`, `ISalesMagnament`: Definen métodos relacionados con descuentos, propiedades comestibles y manejo de ventas.

## Pruebas Unitarias

El proyecto incluye pruebas unitarias para verificar el funcionamiento correcto de las clases y métodos. Las pruebas se encuentran en las clases de prueba correspondientes:

- `ProductTest`: Pruebas relacionadas con la clase base `Product`.

- `PackagedTest`: Pruebas para la clase `Packaged`.

- `DrinkTest`: Pruebas para la clase `Drink`.

- `CleaningProductTest`: Pruebas para la clase `CleaningProduct`.

- `StoreTest`: Pruebas para la clase `Store`.

Las pruebas validan el comportamiento esperado de los métodos y la interacción entre las clases.


