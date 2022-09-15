### Hola! Gracias por visitarme 😃
### A continuación encontrarás los proyectos 🚀 más interesantes que he desarrollado.


# Conteo de plantas de girasol

Aplicación para el conteo de plantas de girasol en cultivos en hileras a partir de imágenes UAV.

El conteo de plantas de girasol se realiza mediante modelos de regresión a partir de descriptores de forma y tamaño sobre los objetos que son segmentados como plantas. Los modelos se generan a partir del entrenamiento de conjuntos de puntos marcados sobre los centros de las plantas.

Ésta aplicación implementa parte de mi trabajo de investigación durante el desarrollo de mi tesina de grado *"Conteo de plantas de girasol en cultivos en hileras a partir de imágenes UAV"* la cuál combina técnicas de Procesamiento Digital de Imágenes con Machine Learning y en la cual se proponen cuatro algoritmos esenciales para el conteo:

* Segmentación de la imagen, para separar las plantas de girasol del fondo.
* Detección de la orientación de las hileras, para rotar la imagen de manera que las hileras queden de forma horizontal.
* Detección de hileras y etiquetado de objetos de plantas de girasol a las mismas.
* Estimación de la cantidad de plantas de girasol mediante métodos de regresión.

Si bien durante el trabajo se probaron diferentes métodos de regresión: Modelo lineal multivariado con mínimos cuadrados, regresión Ridge, Lasso, y SVR (Regresión de Vectores Soporte) lineal. En ésta aplicación sólo se implementó el Modelo lineal multivariado con mínimos cuadrados, el cual obtuvo un R^2 de 0.96 en la etapa de testeo.

## Capturas

![screenshot1](https://user-images.githubusercontent.com/75378876/187995752-0a5a7c6e-0e21-47ce-814e-cafa629a444d.png)

![screenshot2](https://user-images.githubusercontent.com/75378876/187995764-ed08b946-d371-41e9-8180-5f5a03db4f79.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/187995770-99027a5e-ee71-4993-861f-3751acb4cc66.png)

## Características

* Detección y corrección de la orientación de la imagen
* Detección de cada hilera
* Estimación de la cantidad de plantas
* Zoom y ROI (región de interés)
* Creación de conjuntos de puntos marcados
* Entrenamiento de nuevos modelos

## Tecnologías

* Lenguaje **Python**
* Librería de Procesamiento de Imagenes Digitales **OpenCV**
* Librería de Machine Learning **scikit-learn**
* Librería de interfaz gráfica **PyQt5 (QT)**

## Fecha
Octubre 2020 - Actualidad


# ML Alertas

Aplicación de alertas para Mercado Libre para Android.

Permite agregar búsquedas para que las mismas se realicen de forma automáticas en segundo plano cada cierto intervalo de tiempo configurable y avise, mediante una notificación push, cuando se publica un árticulo nuevo que coincida con los criterios de la búsqueda.

Para las búsquedas se utiliza la API de Mercado Libre, mediante la librería [ML Searcher](https://github.com/fcamussi/ml_searcher) que desarrollé especialmente para éste proyecto, y permite hacer búsquedas en los diferentes sitios (países) de Mercado Libre.

Es una aplicación ideal para coleccionistas que buscan artículos dificil de encontrar y que se venden muy rápido.

## Capturas

![screenshot1](https://user-images.githubusercontent.com/75378876/189788294-cc9e93dd-8d57-4db5-b755-e168f13190f6.png)
![screenshot2](https://user-images.githubusercontent.com/75378876/189788301-acef15e3-491f-409c-b49d-d7835eb4c8ce.png)

![screenshot3](https://user-images.githubusercontent.com/75378876/189788310-1d74c010-7b43-4c54-909e-983426bcd75f.png)
![screenshot4](https://user-images.githubusercontent.com/75378876/189788336-f6c0b1f7-3112-4ab2-bc3c-1d4d1b57ff89.png)

![screenshot5](https://user-images.githubusercontent.com/75378876/189788357-82196b2b-e523-4307-a8ac-b48a81c52810.png)

## Características

- Opción de país para cada búsqueda
- Intervalos de tiempo configurable para cada búsqueda
- Notficación push cuando se encuentra un nuevo artículo
- Opción de no buscar en segundo plano si no se está conectado a una red Wi-Fi
- Opción de no buscar si la batería está baja
- Multilenguaje: Inglés, Español, Portugués

## Tecnologías
- Lenguaje **Java**
- **Android Studio**

## Fecha
Julio 2022 - Actualidad


# Ventas2012

Sistema de facturación, contabilidad, y control de stock desarrollado para la empresa N.S.A. Cereales Integrales.

## Capturas

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
* Lenguaje **C++**
* Entonrno **Borland C++ Builder 6**
* Librería para acceso a los webservices de la AFIP **PyAfipWs**

## Fecha
2009 - 2011

Mantenimiento hasta 2015


# thread4msx

Librería para programar threads en C para MSX.

Éste proyecto es bastante personal, se trata de una implementación de multitarea apropiativa (preemptive multitasking) para una computadora MSX del año 1983! que utiliza un procesador Z80 corriendo a una velocidad de 3.58MHz 😁. El motivo del desarrollo fue poder probar algunos problemas típicos de sistemas operativos en ésta belleza 💙.

<img src="https://user-images.githubusercontent.com/75378876/175836223-fd2382e8-baa6-4956-8315-03707f2345bc.gif" alt="animacion-counters" width="70%">

Puedes encontrar información más detallada en el [repositorio del proyecto](https://github.com/fcamussi/thread4msx)

## Tecnologías

* Lenguajes **C** y **ensamblador** para **Z80**
* Compilador **SDCC**

## Fecha
2014


# Más proyectos
Puedes ver más proyectos en mi [lista de repositorios](https://github.com/fcamussi?tab=repositories)
