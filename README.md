# Dashboard-Excel-Chocolate-Sales 🍫
Es un Mínimo Producto Viable (MVP), 

se espera proximamente crear semáforos y hojas complementarias.
📊 Vistazo Dashboard

---

<img width="1853" height="862" alt="image" src="https://github.com/user-attachments/assets/2ad05774-6f91-4eef-ba39-1f00732465ee" />


## 📂 Origen de los Datos
Los datos utilizados en este dashboard fueron obtenidos de **Kaggle**. 

*   **Dataset:** Chocolate Sales
*   **Fuente original:** https://www.kaggle.com/datasets/saidaminsaidaxmadov/chocolate-sales
*   **Autor:** [Saidamin Saidakhmadov]

*Este proyecto es una adaptación en Excel basada en el reporte de Power BI disponible en la misma fuente.*


🚀 Valor Agregado (Mejoras Propias)
---
A diferencia del informe base de Power BI, mi versión en Excel incluye: gráficas y tarjetas que permitan comparar el rendimiento comercial y temporal de las ventas de chocolates.
----

🛠️ ## Metodología y Herramientas

Para este proyecto no solo repliqué el informe original, sino que analicé la información para generar una nueva propuesta que amplie las herramientas para la toma de decisiones. 

* Power Query (ETL):
  Una vez conectados los datos con el csv de mi Github, transformé los datos en Power Query

  <img width="953" height="385" alt="image" src="https://github.com/user-attachments/assets/4004bf28-305a-4167-8b94-5d0675231edf" />


* Power Pivot (Modelado de Datos):
  Una vez cargados y transformados los datos, generé una tabla calendario para establecer la relación de 1 a muchos (*) con la tabla de **Chocolate sales** para así facilitar la creación de medidas Dax y segmentadores con fecha.

  <img width="1426" height="718" alt="image" src="https://github.com/user-attachments/assets/50dfcaf5-4b44-498a-9db2-94e91b0d4e42" />

Tal y como se puede observar en la imagen anterior, creé cuatro medidas DAX (Data Analysis Expressions) para la creación de tarjetas en el tablero, a continuación nombro las medidas y su propósito:

* m_ventas_totales
* m_ventas_por_caja
* m_ventas_año_anterior
* m_%crecimiento_anual 

---
# Fuente iconos utilizados:

* Barra de Chocolate:
  https://www.flaticon.es/icono-gratis/chocolate_2234851?term=chocolate&page=1&position=12&origin=search&related_id=2234851
* Vendedor:
https://www.flaticon.es/icono-gratis/hombres_10206112?term=vendedor&page=1&position=31&origin=search&related_id=10206112

  


