# Proyecto Alura Store – Análisis de Tiendas

## Propósito del Análisis
El objetivo de este proyecto es ayudar al Sr. Juan a decidir **qué tienda de su cadena Alura Store debería vender** para iniciar un nuevo emprendimiento.  
Se analizaron ventas, ingresos, productos, categorías, calificaciones de clientes y costos de envío para tomar una decisión informada.

---

## Estructura del Proyecto
- `AluraStoreLatam.ipynb` → Notebook con todo el análisis, cálculos y visualizaciones.
- `base-de-datos-challenge1-latam/` → Carpeta que contiene los archivos CSV de cada tienda:
  - `tienda_1.csv`
  - `tienda_2.csv`
  - `tienda_3.csv`
  - `tienda_4.csv`
- `README.md` → Este archivo que describe el proyecto y guía al usuario.
- `graficos/` (opcional) → Carpeta donde se pueden guardar las imágenes generadas de los gráficos.

---

## Gráficos e Insights Obtenidos

1. **Ingresos Totales por Tienda (Bar Chart)**  
   Permite identificar la tienda con menor rendimiento económico.

   | Tienda   | Ingreso Total |
   |----------|---------------|
   | Tienda 1 | 1,150,880,000 |
   | Tienda 2 | 1,116,344,000 |
   | Tienda 3 | 1,098,020,000 |
   | Tienda 4 | 1,038,376,000 |

2. **Distribución de Categorías de Productos (Pie Chart)**  
   Muestra las categorías más y menos populares en cada tienda, ayudando a ajustar inventario.

3. **Calificación Promedio de Clientes vs. Costo de Envío (Scatter Plot)**  
   Relaciona la satisfacción del cliente con el costo promedio de envío por tienda.

   | Tienda   | Calificación Promedio | Costo de Envío Promedio |
   |----------|---------------------|------------------------|
   | Tienda 1 | 3.98                | 26,018.61              |
   | Tienda 2 | 4.04                | 25,216.24              |
   | Tienda 3 | 4.05                | 24,805.68              |
   | Tienda 4 | 4.00                | 23,459.46              |

4. **Productos Más y Menos Vendidos (Bar Chart)**  
   Ejemplo Tienda 1 – Top 5 productos más vendidos:

   | Producto           | Cantidad |
   |-------------------|----------|
   | Microondas         | 60       |
   | TV LED UHD 4K      | 60       |
   | Armario            | 60       |
   | Secadora de ropa   | 58       |
   | Mesa de noche      | 56       |

   Productos menos vendidos:

   | Producto                     | Cantidad |
   |-------------------------------|----------|
   | Ciencia de datos con Python   | 39       |
   | Pandereta                     | 36       |
   | Olla de presión               | 35       |
   | Auriculares con micrófono     | 33       |
   | Celular ABXY                  | 33       |

> Todos los gráficos se encuentran dentro del notebook `AluraStoreLatam.ipynb`.

---

## Conclusión y Recomendación
Tras analizar todos los factores (ingresos, productos, categorías, calificaciones y costos de envío):

- La **Tienda 4** presenta ingresos más bajos, menor número de productos destacados y calificación promedio similar a otras tiendas.  
- Por lo tanto, se **recomienda vender la Tienda 4**, optimizando la inversión y enfocándose en las tiendas más rentables y con mejor aceptación del cliente.

---

## Instrucciones para Ejecutar el Notebook

1. Clonar el repositorio:
```bash
git clone https://github.com/Tilyberto/Portafolio.git

2. Abrir el archivo `AluraStoreLatam.ipynb` en **Google Colab** o **Jupyter Notebook**.
3. Ejecutar todas las celdas para generar los análisis, cálculos y gráficos.
4. Visualizar los resultados y la recomendación final dentro del notebook.

---

## Notas Finales

- Todos los cálculos y visualizaciones se basan en los datos originales de las tiendas proporcionados en los archivos CSV.
- El análisis fue desarrollado íntegramente en **Google Colab**, utilizando las bibliotecas `pandas`, `matplotlib` y `numpy`.
- Este proyecto forma parte del **Challenge de Data Science – Alura LATAM**, enfocado en aplicar análisis exploratorio de datos (EDA) para la toma de decisiones.

---

📊 **Autor:** Ricardo Vásquez  
📅 **Última actualización:** Octubre 2025  
🔗 **Repositorio:** [Portafolio GitHub](https://github.com/Tilyberto/Portafolio)
