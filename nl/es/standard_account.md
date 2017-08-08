---



copyright:

  years: 2016, 2017
lastupdated: "2017-06-01"


---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:new_window: target="_blank"}

# Versión limitada de cuenta estándar de IBM {{site.data.keyword.Bluemix_notm}}
{: #betaintro}

La cuenta Estándar de versión limitada de {{site.data.keyword.Bluemix}} presenta una nueva cuenta gratuita, que ofrece una nueva forma de trabajo en la nube pública de {{site.data.keyword.Bluemix_notm}}. La cuenta Estándar no caduca nunca, lo que la diferencia de la cuenta de prueba de {{site.data.keyword.Bluemix_notm}} de 30 días. Puede seguir trabajando en sus aplicaciones de {{site.data.keyword.Bluemix_notm}} sin ninguna preocupación sobre las restricciones de tiempo. 
{:shortdesc}

Los usuarios en las regiones del Reino Unido y EE.UU. Sur serán aptos para la cuenta Estándar. Si no está en una de estas regiones, puede seguir creando una cuenta Estándar y pedir una invitación a un amigo o ponerse en contacto con nuestro equipo de ventas en sales@bluemix.net. Una vez tenga una cuenta Estándar, puede invitar a sus amigos y colegas para que participen.    

## Presentación de la cuenta Estándar de {{site.data.keyword.Bluemix_notm}}
{: #standardaccount}

Puede que se pregunte sobre qué diferencia hay entre la cuenta Estándar y la cuenta de prueba. Las tablas siguientes resumen los detalles clave sobre la cuenta Estándar de {{site.data.keyword.Bluemix_notm}}. 

|¿Qué novedades hay en una cuenta Estándar? |    
|-----------------|
| La cuenta no caduca nunca. |
| Las aplicaciones de Cloud Foundry pueden acceder hasta un máximo 256 MB de memoria de tiempo de ejecución gratuita e instantánea. |
| Puede acceder a los planes Lite gratuitos para servicios in-demand Watson como Conversación, Plataforma de Internet de las Cosas, Cloudant NoSQLDB. Para obtener más información, consulte [Qué hay disponible](/docs/pricing/standard_account.html#whatsavailable). |
| Sus aplicaciones entrarán en suspensión si no hay actividad de desarrollo durante 10 días. |
| Las instancias de servicio se suprimirán tras 30 días de inactividad. |
{:caption="Tabla 1. Novedades en una cuenta estándar" caption-side="top"}

|¿Qué es lo que no cambia cuando se convierte una cuenta de prueba? | 
|-----------------|
|La cuenta es gratuita. No necesita una tarjeta de crédito. |
|Puede seguir utilizando sus instancias de planes Lite. |
|Los valores de acceso de su organización, espacios y miembros de equipo asociados siguen siendo los mismos. Se puede transferir una organización a su cuenta nueva. |
|El nivel de soporte de {{site.data.keyword.Bluemix_notm}} sigue siendo el mismo. |
{:caption="Tabla 2. Qué es lo que no cambia" caption-side="top"}

**Nota**: Si la cuenta de prueba no se convierte, verá un mensaje que le dirá el motivo. Puede que tenga más de una organización en la cuenta de prueba existente o apps que no se puedan transferir. Puede realizar la acción apropiada y volver a intentar convertir la cuenta.

Cuando se haya registrado para una cuenta Estándar, puede invitar a los miembros del equipo a colaborar en su organización y espacios, a ver su uso, a crear espacios, a actualizar el perfil de la cuenta y a gestionar su organización.

## Planes de Lite
{: #liteplans}
   
Los planes de Lite, que también están disponibles en una cuenta de pago según uso, están estructurados como una cuota gratuita. Puede trabajar en sus proyectos sin preocuparse, sin el riesgo de generar una factura accidentalmente. La cuota puede funcionar durante un periodo de tiempo específico, por ejemplo, un mes, o sobre una base de uso único. A continuación se mencionan algunos ejemplos de las cuotas del plan de Lite:

<ul>
<li>Número máximo de dispositivos registrados.</li>
<li>Número máximo de enlaces de aplicaciones.</li>
<li>Límite de almacenamiento de datos cifrados, como por ejemplo, 1 GB.</li>
<li>Capacidad de rendimiento suministrada.</li>
</ul> 

En una cuenta Estándar, puede utilizar cualquier cosa del Catálogo de {{site.data.keyword.Bluemix_notm}} que tiene un plan de Lite. Los planes de Lite son fáciles de encontrar. De forma predeterminada, cuando abra el Catálogo, todos los servicios de que tengan un plan de Lite se muestran y se identifican con una etiqueta de Lite ![etiqueta de Lite](../icons/Lite.svg). Seleccione un servicio para ver los detalles de la cuota para el plan de Lite asociado.

## ¿Qué hay disponible en la cuenta Estándar?
{: #whatsavailable}

En una cuenta Estándar, las aplicaciones de Cloud Foundry pueden acceder hasta un máximo de 256 MB de memoria de tiempo de ejecución instantánea. Si supera la cuota asignada, puede detener algunas de las apps para liberar memoria de tiempo de ejecución. También puede trabajar con un clúster de Kubernetes con 2 CPU y 4 GB de RAM. 

Durante la cuenta Estándar versión limitada, los siguientes servicios de {{site.data.keyword.Bluemix_notm}} ofrecen un plan Lite:

<ul>
<li>{{site.data.keyword.prf_hublong}}</li>
<li>{{site.data.keyword.mobilepushfull}}</li>
<li>{{site.data.keyword.cloudantfull}}</li>
<li>{{site.data.keyword.conversationfull}}</li>
<li>{{site.data.keyword.iot_full}}</li>
<li>{{site.data.keyword.languagetranslatorfull}}</li>
<li>{{site.data.keyword.personalityinsightsfull}}</li>
<li>{{site.data.keyword.toneanalyzerfull}}</li>
</ul>

Algunos servicios no están disponibles en todas las regiones de {{site.data.keyword.Bluemix_notm}}. Para obtener más información, consulte [Servicios por región](/docs/services/services_region.html#services_region).

Permanezca atento a las novedades que iremos añadiendo a esta lista de servicios.

### Límites de cuota

Cuando se alcancen los límites de la cuota, se detendrá la aplicación o se inhabilitará el servicio. Si el plan de Lite especifica que la cuota se proporciona de forma mensual, el uso de los recursos se restablecerá el día 1 de cada mes cuando vuelva a trabajar con el servicio. Cuando esté llegando al límite de una cuota, o cuando esté en el límite de la misma, recibirá un correo electrónico de notificación. 

Puede suministrar 1 instancia por plan de Lite. 

**Nota**: Estas limitaciones se aplican únicamente a la cuenta Estándar. Puede actualizar a una cuenta de pago según uso o de suscripción en cualquier momento. Pague sólo lo que utilice más allá de las concesiones gratuitas. Para obtener más información sobre las cuentas de Pago según uso y Suscripción, consulte [Registro de una cuenta facturable](/docs/pricing/billable.html#billable).

## Características de eficiencia
{: #devactivity}

Para ayudarle a gestionar los recursos, hemos incluido características de eficiencia que se basan en la actividad y el uso del desarrollo.

### Inactividad automática de la app

Las apps entrarán en suspensión tras 10 días de inactividad de desarrollo. Esto ayuda a la hora de trabajar en una nueva app, porque así no llegará al límite de cuota de memoria de 256 MB. 

Para reactivar las apps, empiece trabajando en ellas de nuevo en la línea de mandatos de Cloud Foundry o en la consola de {{site.data.keyword.Bluemix_notm}}. 
 
 A continuación hay una lista de todos los mandatos que reactivarán la app:
  * cf push
  * cf restate
  * cf restart
  * cf ssh
  * cf scale
  * cf stop
  * cf start
  * cf create-route
  * cf map-route
  * cf unmap-route
  * cf delete-route
  * cf enable-ssh
  * cf disable-ssh

Para ver los detalles de uso, consulte los [mandatos de Cloud Foundry](/docs/cli/reference/cfcommands/index.html).

 **Nota**: Si la app ya tiene habilitado ssh, no puede utilizar los mandatos `cf enable-ssh` y `cf disable-sh` para reactivar la app. 

### Recogida de basura

Los servicios del plan de Lite se suprimen si no hay ninguna actividad en ellos durante 30 días. Esto significa que no tendrá que suprimir las instancias inactivas cuando desee crear una nueva instancia. 
 
## Participación en la cuenta Estándar de disponibilidad limitada
{: #lgainvitation}
Puede solicitar a un amigo con una cuenta Estándar a que le invite o póngase en contacto con nuestro equipo de ventas en sales@bluemix.net. ¡Nos gustaría que lo probara!
