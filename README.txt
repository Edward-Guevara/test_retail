## Descripcion de los datosC:\Users\Edward\OneDrive - Universidad Tecnológica de Panamá\projects\retail_test\parte01 - basic_insight.ipynb
Este conjunto de datos contiene información transaccional de compradores frecuentes en una tienda retail. La historia de los datos es de 2 años.

## Objetivo del análisis
1. Describir los clientes de la tienda en base a su información transaccional
2. Crear un modelo que nos permita detectar a los clientes que son buenos compradores para ofrecerles descuentos personalizados.

## Tareas por hacer
1.  Análisis exploratorio de los datos
2. Entrenar modelo de ML.
3. Evaluación y explicación de los resultados del modelo.
4. Sugerencia de posibles desarrollos que se puedan realizar a partir de los datos analizados y de los resultados obtenidos.

## Indicaciones
1. Entregar un notebook(ipynb) con los resultados obtenidos (gráficas, tablas, etc.). También incluir todo el código desarrollado.
2. Sustentar los resultados lo más detallado posible.
3. Explicación detallada de los diferentes descubrimientos que se han encontrado.

**Nota**: 
1. Es preferible que el notebook final esté organizado como si estuvieras contando una historia, es decir, que siga un hilo que se pueda entender a medida que se avance en la lectura.

## Descripción de las variables
1. transaction_data.csv
    * household_key: Identificación única del cliente.
    * BASKET_ID: Identificación única de la  transacción.
    * PRODUCT_ID: Identificación única del producto.
    * QUANTITY: Cantidad de productos comprados.
    * SALES_VALUE: Monto en dolares de la compra.
    * STORE_ID: Identificación única de cada tienda.
    * WEEK_NO: Semana en que se realizó la transacción (1 - 102)
2. product.csv
    * PRODUCT_ID: Identificación única del producto.
    * MANUFACTURER: Código del proveedor.
    * DEPARTMENT: Departamento al cual pertenece un producto .
    * BRAND: Indica si la marca del producto es internacional o nacional.
    * COMMODITY_DESC:Categoría al que pertenece el producto.
3. hh_demographic.csv
    * AGE_DESC: Rango de edad estimado.
    * MARITAL_STATUS_CODE: Estado marital del cliente.
    * INCOME_DESC: Ingresos del cliente.
    * household_key: ID por cada cliente
    * label: Indica si el cliente es buen comprador o no (0= mal comprador, 1=buen comprador)