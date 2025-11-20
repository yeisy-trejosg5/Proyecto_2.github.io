**Pasos seguidos para completar el proyecto:**
Dicho proyecto se desarrolla con el objetivo de diseñar un modelo de constelación de hechos.
Para comprender este modelo, es importante señalar que se utiliza cuando existen múltiples tablas de hechos que comparten las mismas dimensiones. Se denomina constelación porque, a diferencia del modelo estrella —que contiene un único “cubo” de análisis—, en este caso se generan varios cubos vinculados entre sí, formando una estructura de mayor alcance y complejidad. Esta relación es comparable con la forma en que varias estrellas se conectan para formar una constelación en el cielo.

Respecto a las diferencias entre el modelo estrella y el modelo copo de nieve, se destaca lo siguiente:

Modelo estrella: posee una única tabla de hechos conectada directamente con sus dimensiones. Su principal ventaja es la facilidad de interpretación, aunque puede presentar redundancia de datos.

Modelo copo de nieve: también parte de una única tabla de hechos, pero sus dimensiones se descomponen en múltiples tablas interrelacionadas, lo que reduce la redundancia, pero incrementa la complejidad del modelo.

En el proyecto realizado, se identificaron al menos cuatro dimensiones compartidas entre las diferentes tablas de hechos: DimProduct, DimDate, DimStore y DimCustomer, como se observa en el modelo expuesto en la siguiente imagen: 
<img width="1892" height="991" alt="Modelo de datos-tabla de hechos" src="https://github.com/user-attachments/assets/fafffd78-8b4f-49d0-8f52-6bdd4053db1a" />

Asimismo, se consideraron las siguientes tablas para el análisis:
<img width="410" height="495" alt="image" src="https://github.com/user-attachments/assets/5b658a72-c3f6-4968-b340-9321374197df" />

Es importante recalcar que, en este tipo de estructuras, se deben verificar manualmente las relaciones, puesto que Power BI no siempre reconoce o enlaza correctamente las dimensiones compartidas.

Finalmente, se diseñó un dashboard en Power BI con el propósito de visualizar la información relevante generada a partir del modelo. Esta visualización puede apreciarse en la imagen titulada Dashboard Power BI.

**Storytelling**
Dicho dashboard, peresenta el rendimiento comercial de dos años seguidos (2008 y 2009), mostrando 
tendencias significativas en cuanto a la actuación de productos,ncanales de venta y participación por nación.
Primero, la comparación de los resultados anuales muestra que las ventas totales en 2008 fueron 
de 4.11 millones, pero cayeron a 3.74 millones en 2009, lo que señala una leve contracción del 
mercado. No obstante, esta reducción no ha impactado de la misma manera a todas las categorías 
de productos.
Cuando examinamos la venta por clases, observamos que los productos Regular constituyen el 
volumen más grande en ambos años, rebasando de manera constante los 0.5 millones cada trimestre; 
en cambio, las líneas Economy y Deluxe sostienen ventas más bajas, pero estables. Esto señala que la opción 
estándar es la más preferida en el mercado, lo cual podría estar relacionado con costos más accesibles y una rotación continua.
El catálogo, con un 52.98% del total de ventas (4.2 millones), se impone notablemente en términos 
de canales de venta, después vienen las ventas en línea y las de tienda. Esto indica que los consumidores 
todavía confían en las plataformas de compra tradicionales, lo cual implica una oportunidad para reforzar 
las tácticas de comercio electrónico y ventas digitales.
El análisis indica que los celulares, con 10 millones de ventas, encabezan el mercado, seguidos por las computadoras, 
los electrodomésticos y las cámaras. El gráfico de barras también confirma esta tendencia, en el que las categorías de tecnología 
y de uso diario lideran las preferencias al comprar. Otras categorías, como juguetes, audio o entretenimiento, tienen una 
participación más baja; sin embargo, podrían incrementarla a través de promociones o campañas específicas.
Al final, el país que tiene un mayor impacto en términos comerciales es Estados Unidos, muy por encima de los demás mercados; 
China y Alemania lo siguen. Esto demuestra que las ventas están muy concentradas en zonas desarrolladas, mientras que los países 
emergentes constituyen áreas de oportunidad para la expansión global.
**Dashboard:**
<img width="1902" height="1015" alt="Dashboard Power BI" src="https://github.com/user-attachments/assets/3acd4509-36ae-4a47-a6ef-6ad3c350b928" />



