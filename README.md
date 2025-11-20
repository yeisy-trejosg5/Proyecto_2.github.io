**Pasos seguidos para completar el proyecto:**
Dicho proyecto se realiza para generar un modelo de constelación de hechos. 
Primeramente, para entender la teoría del modelo de constelación de hechos, este se produce cuando
hay múltiples tablas de hechos que comparten las mismas dimensiones. Se le denomina "constelación"
porque, a diferencia de la estructura estrella que solo tiene un cubo de análisis, se crean múltiples cubos
que se vinculan entre sí, dando lugar a una estructura más extensa y complicada. Esto es parecido a
cómo varias estrellas forman una constelación en el cielo.
Por otro lado, diferencias del modelo estrella y del modelo copo de nieve: El modelo estrella se define
por tener una única tabla de hechos en el centro, que está conectada directamente a sus dimensiones, lo
que lo convierte en fácil de comprender, aunque presenta algo de redundancia en los datos. El modelo
copo de nieve, en contraste, también inicia con una única tabla de hechos, pero sus dimensiones se
organizan en múltiples tablas interrelacionadas, lo que disminuye la redundancia, pero eleva la
complejidad.
Ahora, se identificaron al menos 4 dimensiones comunes entre las tablas de hechos como  DimProduct, DimDate, DimStore, DimCustomer). 
Esto se puede visualizar  en la imagen llamado *Modelado de Datos-tablas de hechos*.
Las tablas que se tomaron en cuenta fueron las siguientes:
<img width="410" height="495" alt="image" src="https://github.com/user-attachments/assets/5b658a72-c3f6-4968-b340-9321374197df" />

En este tabla de hechos se debe revisar las relaciones porque en ocasiones Power BI no las enlaza con otras tablas que
coninciden.

Seguidamente, se procedió a realizar un dashboard para presentar los datos pertinentes a analizar. La visualiazión de datos
se puede evidenciar en la imagen llamada *Dashboard Power BI*.


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


