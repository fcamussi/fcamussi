### Hola! Gracias por visitarme 馃槉
### A continuaci贸n encontrar谩s los proyectos m谩s interesantes que he desarrollado.

# Girasol

Aplicaci贸n para el conteo de plantas de girasol en cultivos en hileras a partir de im谩genes UAV.

El conteo de plantas de girasol se realiza mediante modelos de regresi贸n a partir de descriptores de forma y tama帽o sobre los objetos que son segmentados como plantas. Los modelos se generan a partir del entrenamiento de conjuntos de puntos marcados sobre los centros de las plantas y son realizados desde la misma aplicaci贸n.

![screenshot1](https://user-images.githubusercontent.com/75378876/176992989-09f57342-1a8d-42a3-9367-551aa8e23258.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/176992992-e0fbc3d9-0dec-40bb-a94d-3574d7844a22.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/176992993-514854b1-94a8-4b17-bf1c-8b2aac9d39cc.png)

![screenshot4](https://user-images.githubusercontent.com/75378876/176992994-8f557fd7-aa66-40b7-920f-316ca3756911.png)

## Caracter铆sticas

* Detecci贸n y correcci贸n de la orientaci贸n de la imagen
* Detecci贸n de cada hilera
* Estimaci贸n de la cantidad de plantas
* Zoom y ROI (regi贸n de inter茅s) para trabajar m谩s c贸modo
* Creaci贸n de conjuntos de puntos marcados
* Entrenamiento de nuevos modelos

## Tecnolog铆as

* **Python**
* **PyQt5 (QT)**
* **OpenCV**
* **pandas**
* **scikit-learn**
* **PIL**
* **SciPy**

# Ventas2012

Sistema de facturaci贸n, contabilidad, y control de stock

![screenshot1](https://user-images.githubusercontent.com/75378876/176060409-bb010301-6841-4b8b-b585-54d2eea3dd98.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/176060412-19d319c1-f7fb-416a-b833-04c081867dd5.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/176060414-85de7556-0658-43e1-83bc-6003e41a096c.png)

![screenshot4](https://user-images.githubusercontent.com/75378876/176060415-ab73cd01-66db-42ea-8bc9-22f7808cf8e9.png)

![screenshot5](https://user-images.githubusercontent.com/75378876/176060417-8623779d-3c34-4a44-ac6f-379394636434.png)

![screenshot6](https://user-images.githubusercontent.com/75378876/176060418-f8394cfd-ba40-4cd1-bbdb-d6a5b5dc9d1a.png)

## Caracter铆sticas

### Administraci贸n
* Clientes
* Productos
* Cuentas corrientes
* Stock

### Facturaci贸n
* Notas de pedido
* Remitos
* Facturas, notas de cr茅dito y d茅bito en papel pre-impreso
* Facturas, notas de cr茅dito y d茅bito electr贸nicas seg煤n resoluci贸n AFIP RG3749
* Posibilidad de facturar productos sin cargo
* Descuentos personalizados por cliente
* Mensajes a los clientes mediante leyenda en los comprobantes

### Registros:
* Listado de saldos
* Registro de documentos
* Registro diario, mensual y anual de ventas
* Registro diario, mensual y anual de productos vendidos
* Exportaci贸n de registro de ventas seg煤n resoluci贸n AFIP RG3685

### Otras
* Copias de seguridad
* Incremento masivo de precios
* Exportaci贸n de listas de precios


## Tecnolog铆as
* **Borland C++ Builder 6 (C++)**
* **PyAfipWs**


# thread4msx

Librer铆a para programar threads en C para MSX.

脡ste proyecto es bastante personal, se trata de una implementaci贸n de multitarea apropiativa (preemptive multitasking) para una computadora MSX del a帽o 1983! que utiliza un procesador Z80 corriendo a una velocidad de 3.58MHz 馃榿. El motivo del desarrollo fue poder probar algunos problemas t铆picos de sistemas operativos.

<img src="https://user-images.githubusercontent.com/75378876/175836223-fd2382e8-baa6-4956-8315-03707f2345bc.gif" alt="animacion-counters" width="600">

Puedes encontrar informaci贸n m谩s detallada en el [repositorio del proyecto](https://github.com/fcamussi/thread4msx)

## Tecnolog铆as

* **Ensamblador para Z80**
* **Compilador SDCC**
