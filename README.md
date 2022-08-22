### Hola! Gracias por visitarme 😃
### A continuación encontrarás los proyectos 🚀 más interesantes que he desarrollado y en los que altualmente estoy trabajando.


# ML Alertas (en desarrollo)

Aplicación de alertas para Mercado Libre para Android.

Permite agregar búsquedas para que las mismas se realicen de forma automáticas en segundo plano cada cierto intervalo de tiempo configurable y avise, mediante una notificación push, cuando se publica un árticulo nuevo que coincida con los criterios de la búsqueda.

Para la búsqueda se utiliza la API de mercadolibre y permite hacer búsquedas en los diferentes sitios (países).

Es una aplicación ideal para coleccionistas que buscan artículos dificil de encontrar y que se venden muy rápido.

## Capturas

![screenshot1](https://user-images.githubusercontent.com/75378876/185560633-e2228a0f-88b3-4056-9b94-0f2d034ffa6c.png) 
![screenshot2](https://user-images.githubusercontent.com/75378876/185560636-e231139b-a39f-412f-88c1-c376c25bb82d.png) 
![screenshot3](https://user-images.githubusercontent.com/75378876/185560640-3287850e-2adb-43b9-9013-685f26f9a9f4.png)

## Requisitos para la compilación
- Android Studio
- JDK

# Girasol

Aplicación para el conteo de plantas de girasol en cultivos en hileras a partir de imágenes UAV.

El conteo de plantas de girasol se realiza mediante modelos de regresión a partir de descriptores de forma y tamaño sobre los objetos que son segmentados como plantas. Los modelos se generan a partir del entrenamiento de conjuntos de puntos marcados sobre los centros de las plantas y son realizados desde la misma aplicación.

![screenshot1](https://user-images.githubusercontent.com/75378876/176992989-09f57342-1a8d-42a3-9367-551aa8e23258.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/176992992-e0fbc3d9-0dec-40bb-a94d-3574d7844a22.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/176992993-514854b1-94a8-4b17-bf1c-8b2aac9d39cc.png)

## Características

* Detección y corrección de la orientación de la imagen
* Detección de cada hilera
* Estimación de la cantidad de plantas
* Zoom y ROI (región de interés)
* Creación de conjuntos de puntos marcados
* Entrenamiento de nuevos modelos

## Tecnologías

* **Python**
* **PyQt5 (QT)**
* **OpenCV**
* **pandas**
* **scikit-learn**
* **PIL**
* **SciPy**

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
* **Borland C++ Builder 6 (C++)**
* **PyAfipWs**


# thread4msx

Librería para programar threads en C para MSX.

Éste proyecto es bastante personal, se trata de una implementación de multitarea apropiativa (preemptive multitasking) para una computadora MSX del año 1983! que utiliza un procesador Z80 corriendo a una velocidad de 3.58MHz 😁. El motivo del desarrollo fue poder probar algunos problemas típicos de sistemas operativos en ésta belleza 💙.

<img src="https://user-images.githubusercontent.com/75378876/175836223-fd2382e8-baa6-4956-8315-03707f2345bc.gif" alt="animacion-counters" width="70%">

Puedes encontrar información más detallada en el [repositorio del proyecto](https://github.com/fcamussi/thread4msx)

## Tecnologías

* **Ensamblador para Z80**
* **Compilador SDCC**
