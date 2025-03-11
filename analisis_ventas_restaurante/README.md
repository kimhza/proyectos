# README: Análisis de Datos de Pedidos de Restaurantes

## Descripción del Dataset

Para este proyecto utilicé el dataset de Restaurant Orders que se encuentra en [Kaggle](https://www.kaggle.com/datasets/mohamedharris/restaurant-order-details), éste contiene detalles sobre los pedidos realizados por clientes a restaurantes a través de una aplicación de entrega de comida. El dataset esta compuesto por 2 archivos: Orders y Restaurants. A continuación detallo los campos de cada hoja:

1. **Orders**: Detalles de los pedidos realizados por los clientes.

   - **Columnas**:
     - **Order ID**: Identificador único del pedido.
     - **Customer Name**: Nombre del cliente que realizó el pedido.
     - **Restaurant ID**: Identificador único del restaurante.
     - **Order Date**: Fecha y hora en que se realizó el pedido.
     - **Quantity of Items**: Cantidad de artículos solicitados en el pedido.
     - **Order Amount**: Monto total del pedido.
     - **Payment Mode**: Método de pago utilizado (e.g., tarjeta, efectivo, etc.).
     - **Delivery Time Taken (mins)**: Tiempo que tomó la entrega del pedido en minutos.
     - **Customer Rating-Food**: Calificación del cliente sobre la comida.
     - **Customer Rating-Delivery**: Calificación del cliente sobre la entrega.

2. **Restaurants**: Detalles de los restaurantes.
   - **Columnas**:
     - **Restaurant ID**: Identificador único del restaurante.
     - **Restaurant Name**: Nombre del restaurante.
     - **Cuisine**: Tipo de cocina ofrecida por el restaurante.
     - **Zone**: Zona geográfica del restaurante.
     - **Category**: Categoría del restaurante (e.g., Casual, Fast food, Fine Dining).
