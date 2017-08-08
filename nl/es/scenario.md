---

copyright:

  years: 2015, 2017
lastupdated: "2017-05-30"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Ejemplo: Estimación de costes de una app Node.js de ejemplo
{: #sample}

Suponga que tiene una app web de Node.js con prestaciones de escalabilidad y que la app utiliza varios servicios que suministra {{site.data.keyword.Bluemix_notm}}. En este ejemplo, podrá aprender a calcular el coste real de la app. La app web utiliza los servicios y elementos de {{site.data.keyword.Bluemix_notm}} siguientes:

* Cuatro instancias de tiempo de ejecución de 256 MB de Node.js.
* Dos políticas, un procesador y una memoria de {{site.data.keyword.autoscaling}}.
* 2 GB al mes de {{site.data.keyword.datacshort}}
* 150 GB al mes de base de datos NoSQL, 100.000 llamadas de API pesadas y 500.000 llamadas de API ligeras.
* 20 GB de tráfico de red de entrada o de salida

## Precios para los recursos de Bluemix
{: #sample_resources}

Para dar un ejemplo sencillo, suponga que los precios en la tabla siguiente no fluctúan en un intervalo de tiempo, por ejemplo, en un mes. En este ejemplo, todos los precios se indican en moneda de EE. UU.

|Servicio |	Características |	Precio |
|--------|-----------|--------|
|SDK for Node.js |	375 GB por hora gratuito al mes (compartido entre todos los tiempos de ejecución) |	0,07 USD/GB por hora|
|Auto-Scaling |	Plan de servicio gratuito para el servicio Auto-Scaling |	Gratuito|
|Memoria caché de datos - Iniciador |	1 GB de memoria caché y una réplica |	55,00 USD/instancia |
|Memoria caché de datos - Estándar |	5 GB de memoria caché y una réplica |	155,00 USD/instancia |
|Memoria caché de datos - Premium |	25 GB de memoria caché y una réplica |	505,00 USD/instancia|
|IBM Cloudant® NoSQL DB para {{site.data.keyword.Bluemix_notm}} |	2 GB de almacenamiento gratuito de datos<br/>50.000 llamadas de API ligeras gratuitas al mes<br/>10.000 llamadas de API pesadas gratuitas al mes | 1,00 USD/GB<br/>0,03 USD/1000 llamadas de API ligeras<br/>0,15 USD/1000 llamadas de API pesadas |
{:caption="Tabla 1. Precios para los recursos" caption-side="top"}

## Cálculo del precio de una app

El precio de la app se puede calcular de la forma siguiente:

<dl>
<dt>Cuatro instancias de tiempo de ejecución de 256 MB de Node.js.</dt>
<dd>Cargos de Bluemix para un tiempo de ejecución por GB por hora. El número de GB utilizados al mes es de <code>4 x 256 = 1024 MB o 1 GB al mes</code>. Suponga que hay <code>24 x 30 = 720 horas en un mes</code>, por consiguiente la app ha facturado <code>1 x 720 = 720 GB por hora</code>.
<p>
375 GB por hora están incluidos en la concesión gratuita al mes, compartidos en todos los tiempos de ejecución de {{site.data.keyword.Bluemix_notm}}. Por consiguiente, el coste total para el tiempo de ejecución es de <code>0,07 dólares x (720-375) = 24,15 dólares</code>.</p></dd>

<dt>Dos políticas de Auto-Scaling (procesador y memoria)</dt>
<dd>Las políticas de Auto-Scaling no tienen ningún coste.</dd>

<dt>2 GB al mes de Data Cache</dt>
<dd>El plan de 50 MB proporcionado por el servicio de Data Cache es gratuito. Sin embargo, el plan gratuito no cubriría su uso proyectado de 2 GB al mes. Los tres planes de pago para Data Cache cuestan una cantidad fija por una cantidad de espacio específica, independientemente de cuánto espacio utilice realmente. Por lo tanto, le interesa elegir el plan mínimo que satisfaga su uso proyectado, que es el plan estándar de 5 GB. El coste total es de 155 dólares al mes.</dd>

<dt>Una base de datos NoSQL de 150 GB al mes</dt>
<dd>Los cargos de servicio de IBM Cloudant NoSQL DB for {{site.data.keyword.Bluemix_notm}} se basan en el almacenamiento de datos y en la posibilidad de acceder a dichos datos mediante diferentes métodos de API. Los mandatos <strong>PUT</strong> y <strong>POST</strong> se consideran llamadas de API pesadas, pero
los mandatos <strong>GET</strong> se consideran llamadas de API ligeras.
<p>
Añada el número de GB y deduzca 2 GB de concesión gratuita. Se cargan 148 GB al mes. Sustraiga la concesión gratuita de 50.000 para llamadas de api ligeras y 10.000 para llamadas de api pesadas. El precio de almacenamiento total incluye las partes siguientes:</p>
<pre class="codeblock">
<codeblock>
    148 x 1 = 148
    (450,000 / 1000) x 0.03 = 13,5 dólares
    (90,000 / 1000) x 0.15 = 13,5 dólares
</codeblock>
</pre>
<p>
El precio total es 148 + 13.5 + 13.5 = 175 dólares.</p></dd>

<dt>20 GB de tráfico de red de entrada o de salida</dt>
<dd>El tráfico de red de entrada y salida está libre de cargo adicional.</dd>

</dl>

Cuando se añaden todos los elementos, el precio total de la app es de 354,15 dólares.
