### Hola! Gracias por visitarme 😊
### A continuación encontrarás los proyectos más interesantes que he desarrollado.

# Girasol

Aplicación para el conteo de plantas de girasol en cultivos en hileras a partir de imágenes UAV.

El conteo de plantas de girasol se realiza mediante modelos de regresión a partir de descriptores de forma y tamaño sobre los objetos que son segmentados como plantas. Los modelos se generan a partir del entrenamiento de conjuntos de puntos marcados sobre los centros de las plantas y son realizados desde la misma aplicación.

![screenshot1](https://user-images.githubusercontent.com/75378876/176986446-b894df29-db65-4c27-9a5c-f9be1cf801aa.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/176986449-479e3feb-9b25-4efa-b0ec-7543ccdcd853.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/176986451-da5a1398-7c3c-49f9-be13-571aad8ab11a.png)

![screenshot4](https://user-images.githubusercontent.com/75378876/176986452-cba227e9-190c-4684-bbb3-036bc742bff8.png)

## Características

* Detección y corrección de la orientación de las hileras
* Detección de cada hilera
* Estimación de la cantidad de plantas.
* Zoom y ROI (región de interés) para trabajar más cómodo
* Creación de conjuntos de puntos marcados
* Entrenamiento de nuevos modelos

## Tecnologías

* Python, PyQt5, OpenCV, pandas, scikit-learn, PIL, SciPy

# Ventas2012

Sistema de facturación, contabilidad, y control de stock

![screenshot1](https://user-images.githubusercontent.com/75378876/176060409-bb010301-6841-4b8b-b585-54d2eea3dd98.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/176060412-19d319c1-f7fb-416a-b833-04c081867dd5.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/176060414-85de7556-0658-43e1-83bc-6003e41a096c.png)

![screenshot4](https://user-images.githubusercontent.com/75378876/176060415-ab73cd01-66db-42ea-8bc9-22f7808cf8e9.png)

![screenshot5](https://user-images.githubusercontent.com/75378876/176060417-8623779d-3c34-4a44-ac6f-379394636434.png)

![screenshot6](https://user-images.githubusercontent.com/75378876/176060418-f8394cfd-ba40-4cd1-bbdb-d6a5b5dc9d1a.png)

## Características

### Administración
* Clientes
* Productos
* Cuentas corrientes
* Stock

### Facturación
* Notas de pedido
* Remitos
* Facturas, notas de crédito y débito en papel pre-impreso
* Facturas, notas de crédito y débito electrónicas según resolución AFIP RG3749
* Posibilidad de facturar productos sin cargo
* Descuentos personalizados por cliente
* Mensajes a los clientes mediante leyenda en los comprobantes

### Registros:
* Listado de saldos
* Registro de documentos
* Registro diario, mensual y anual de ventas
* Registro diario, mensual y anual de productos vendidos
* Exportación de registro de ventas según resolución AFIP RG3685

### Otras
* Copias de seguridad
* Incremento masivo de precios
* Exportación de listas de precios


## Tecnologías
* Borland C++ Builder 6
* PyAfipWs


# thread4msx

Librería para programar threads en C para MSX.

Éste proyecto es bastante personal, simplemente quería implementar multitarea apropiativa (preemptive multitasking) en una computadora MSX del año 1983! 😁 con un procesador Z80 y probar algunos problemas típicos de sistemas operativos.

<img src="https://user-images.githubusercontent.com/75378876/175836223-fd2382e8-baa6-4956-8315-03707f2345bc.gif" alt="animacion-counters" width="600">

## Tecnologías

* Compilador de C y asm, SDCC
