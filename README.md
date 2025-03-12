# Análisis de Cancelación de reservas de hotel :hotel:

## :memo:**Descripción**

Este proyecto lleva a cabo un exploración y análisis de las reservas canceladas de un establecimiento hotelero, en un período de tiempo determinado. El objetivo es identificar factores facilitadores, así como tendencias y posibles causas de las cancelaciones, para poder tomar decisiones futuras y de esta manera evitarlas.

Fuente: https://www.kaggle.com/datasets/youssefaboelwafa/hotel-booking-cancellation-prediction?resource=download



## :file_folder:**Estructura del proyecto**

Booking.csv :  *Datos crudos utilizados*

ProyectoDashboard.xlsx :  *Tablas, tablas dinámicas y Dashboard*

README.md:   *Descripción del proyecto*


## :mag: **Columnas dataset**

**Booking_ID:** Identificador único para cada reserva

**Adults:** Número de adultos incluidos en la reserva

**Children:** Número de niños incluidos en la reserva

**Total PAX:** Total de personas inluidas en la reserva	

**Weekend nights:** Número de noches de fin de semana incluidas en la reserva

**Week nights:** Número de noches entre semana incluidas en la reserva

**Total nights:** Total de noches incluidas en la reserva

**Type of meal:** Tipo de comida incluido en la reserva

**Car parking space:** Indica si ha incluido plaza de aparcamiento en la reserva

**Room type:** Tipo de habitación reservada

**RoomType Agrupado:** Columna creada para analizar tipos de habitación reservados con más frecuencia

**Lead time (days):** Número de días entre la fecha de reserva y la fecha de llegada

**Market segment type:** Tipo de segmento de mercado asociado a la reserva

**Repeated:** Indica si es una reserva repetida

**P-C:** Número de reservas anteriores canceladas por el cliente antes de la reserva actual

**P-not-C:** Número de reservas anteriores no canceladas por el cliente antes de la reserva actual

**Average price:** Precio medio asociado a la reserva

**ADR ok:** Columna de precio medio asociado a la reserva con valores extremos agrupados

**Special requests:** Número de peticiones especiales realizadas por el huésped

**Date of reservation:** Fecha de la reserva

**M-Y reservation:** Extracción del mes y año de la reserva	

**Booking status:** Estado de la reserva


## :wrench:**Herramientas**

Este proyecto utiliza Microsoft Excel.


## :bar_chart:**Resultados y conclusiones**

-	De las 36.285 reservas analizadas se han identificado 11.889 Canceladas, representando el 33% del total explorado.
-	Se ha observado que las reservas realizadas con un tiempo de antelación de 150 días o más (>5 meses) tienen una mayor predisposición a ser canceladas con una tasa por encima del 60%. Siendo de ellas, las mayores de 390 días (>1 año) que evidencian el 100% de reservas canceladas.
-	Respecto al período de tiempo examinado (Sep 2016 - Dic 2018) se detectó un pico de cancelaciones en el mes de Junio 2018, y uno mayor aún en Octubre 2018. 
-	Se encontró que las reservas de habitación tipo 1 constituyen el 76% de las cancelaciones totales.
-	El 72% de las reservas con antecedentes de cancelaciones previas, fueron nuevamente canceladas, por lo que constituye un factor facilitador evidente.


## :feet:**Próximos pasos**

Sería ideal, para poder refinar el análisis, obtener datos como: porcentaje de ocupación del hotel al momento de la reserva, motivo de cancelación expresado por el cliente, política de cancelación de cada una (totalmente reembolsable, parcialmente reembolsable, con costo de cancelación, etc.), y si alguna de ellas fue reubicada o reprogramada para una fecha diferente. Así como también si existió alguna campaña de marketing o descuentos en el período de tiempo explorado.
Con esta información, podríamos lograr sacar conclusiones más acertadas y precisas para poder evitar futuras cancelaciones, y con ellas pérdidas económicas para la empresa.


## :bust_in_silhouette:**Autor**

Julieta Bauza Silveyra

https://github.com/Julibauza
