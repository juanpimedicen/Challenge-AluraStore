# 📊 Análisis de Ventas y Rendimiento de Tiendas - Challenge Alura LATAM

Este proyecto consiste en un análisis de los datos de ventas de **cuatro tiendas**, con el propósito de identificar cuál de ellas debería ser vendida por el **Sr. João**. Para ello, se evaluaron diversos indicadores clave, como los ingresos totales, las categorías y productos más y menos vendidos, las calificaciones promedio de los clientes, y los costos de envío. El análisis permite tomar una decisión informada basada en el desempeño integral de cada tienda.


---

## 🗂️ Contenido del Proyecto

### 1. Carga de Datos
- Se cargan los archivos `.csv` correspondientes a las 4 tiendas.
- Los archivos están organizados y procesados en Google Colab.

### 2. Análisis de Ingresos Totales
- Se calcula el ingreso total por tienda, sumando cada venta, ya que cada fila es una venta.

### 3. Análisis por Categoría de Productos
- Se identifica cuál es la categoría de producto más vendida en cada tienda.
- Se detectan tendencias comunes entre tiendas (por ejemplo, la venta de muebles).

### 4. Calificaciones Promedio de Clientes
- Se calcula el promedio de calificaciones otorgadas por los clientes.
- Se comparan las tiendas en términos de satisfacción del cliente.

### 5. Productos Más y Menos Vendidos
- Se listan los 5 productos más vendidos por tienda.
- También se identifican los 5 productos con menor volumen de ventas.
- Se generan visualizaciones con `Matplotlib` que muestran los 10 productos con más ventas.

### 6. Costo de Envío Promedio
- Se calcula el promedio de costos de envío por tienda.
- Se analiza el impacto del envío sobre la experiencia de compra.

### 7. Distribución Geográfica de Ventas
- Se visualizan coordenadas de ventas utilizando mapas con `Folium`.
- Se identifican zonas de mayor densidad de clientes o pedidos.

---

## 🔧 Tecnologías Utilizadas

- Google Colab (entorno de desarrollo)
- Python  
- Pandas  
- Matplotlib  
- Folium  

---

## 📍 Recomendación Final

Después de analizar los ingresos, productos vendidos, calificaciones, costos de envío y la distribución geográfica, se concluye lo siguiente:

### ✅ Mantener Tienda 3:
- Mayor calificación promedio (**4.05**).
- Buen volumen de ingresos y variedad en productos vendidos.
- Costo de envío competitivo.
- Distribución geográfica amplia y estable.

### ❌ Vender Tienda 1:
- Aunque tiene los ingresos más altos, presenta la **calificación más baja** por parte de los clientes (**3.98**).
- Tiene el **mayor costo de envío promedio**, lo que puede desincentivar compras.
- Las debilidades a largo plazo podrían afectar la sostenibilidad del negocio.

---

## 📝 Autor

Desarrollado por **Juan Pablo Guilarte**  
Proyecto realizado como parte del **Challenge de Ciencia de Datos - Alura LATAM**
