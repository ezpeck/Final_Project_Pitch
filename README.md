# Proyecto Final
:rocket: :octocat: 

## Aplicación para administración de tiendas y ventas.


### Resumen
Mi idea consiste en una aplicación de administracion de personal, inventario y ventas para comercios (boutiques, farmacias, papelerias, mueblerias etc). 

### Usuarios
Dueños de pequeños y medianos establecimientos comerciales.

### Beneficios
Facilitar la administración interna y la toma de decisiones de pequeños y medianos comercios con el objetivo mejorar sus ventas. Además, como valor agregado tener la capacidad de recibir retroalimentación directa del cliente acerca del servicio recibido por medio de un blog de comentarios para clientes en el cual podran comentar sobre su experiencia de usuario con el establecimiento y otros clientes.


### Funcionalidad

### Aplicación para el Establecimiento:

_Los Empleados podrán inciar sesión como Administrador o vendedor_


__Los administradores podrán.__

#### Subir la información de los artículos a comercializar como:

* Foto del artículo.
* Descripción.
* Precio.
* Cantidad de artículos.
* Ubicación (almacén o aparador).
* Artículos en oferta.
* etc.

    Una vez que se sube la información, el componente de inventario mostrará una galería en la que se pueden ver los productos clasificados por categorías, además de otorgarle un id unico para cada producto con un código de barras o QR.

#### Subir o actualizar una imagen 360 del almacén y aparadores, además de:

* Señalar sus distintas secciones. 
* Indicar que artículos se almacenan en cada sección.
* Todo esto en forma de comentarios de las imágenes subidas.


#### Acceder a una agenda con la cual podrán organizarse mejor y ralizar actividades como:

* Programar recordatorios para envío de correos electrónicos, llamadas por hacer, citas etc).
* Llevar el control de metas.
* Llevar el control de pedidos.
* Pago a proveedores, empleados, sevicios, hacienda etc.

#### Acceder a interfaz en la cual podran anilizar los datos obtenidos por las ventas realizadas:

* Observar información de ventas por medio de gráficas y tablas.
* Observar estadiísticas del desempeño de los empleados.
* Comparar las metas de ventas con las ventas realizadas y mostrar estadísticas. 
* Por medio de inteligencia artificial realizar recomendaciones al administrador (decirle que comprar y que ya no, o en que epoca del año surtir más de x producto, información reelevante de sus clientes).
* Mos


    *Usando "machine learning" el sistema le podrá hacer recomendaciones al administrador de la tienda para saber los productos mas vendidos, los que no se venden tanto, en que fechas del año se venden ciertos productos, horarios de compra etc. Además de información relacionada a clientes como: método de pago, género, complexion etc. Todo esto con la finalidad de aumentar las ventas del establecimiento.*


__Los vendedores podrán.__

#### Realizar búsquedas personalizadas en el inventario indicando:

* Características de los productos.
* Palabras clave relacionadas al artículo buscado.
* Sgún su uso.

    Una ves realizada la búsqueda la aplicación te mostrará una lista en forma de galería de los artículos relacionados a la busqueda. Cada elemento de la lista te mostrará información básica como su imagen, descripción, precio, ¿Esta en oferta? y su ubicación en el almacén y/o apardor.

    Al seleccionar un artículo de la galería, el componente te mostrará más información del artículo y recomendaciones al cliente sobre que otros artículos le podrian interesar.

#### Scanear de productos por medio de código de barras o QR. 

#### Levantar una orden de venta y una vez cerrada la venta que el inventario se actualice al instante además de almacenar los datos de venta para su futuro análisis ya sea manual o por "machine learning".



### Aplicación para los Clientes

Consiste en una página en la que los clientes podrán dejar sus comentarios para retroalimentar a la tienda sobre su experiencia de compra, o sobre algo que les hubiera gustado comprar pero no lo encontraron en la tienda. En esta pequeña "red social" los clientes podrán interactuar entre ellos, para eso deberan inciar sesión y si quieren compartir su xperiencia de compra, la aplicacion validará sus compras realizadas por medio de su ticket de compra. 



### Requirements

Your project:

- [x] Must have a backend api layer that accesses a database
- [x] Must have authentication OR hook into another api
- [x] Must use React to render views/components
- [x] Must have 'presentable' styles
