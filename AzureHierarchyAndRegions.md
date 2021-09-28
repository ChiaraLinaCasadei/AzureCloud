# Jerarquía en Azure

![alt text] (https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-architecture-fundamentals/media/hierarchy-372fef74.png)

## Managment Groups
Te ayudan a gestionar acceso, política y cumplimiento para múltiples suscripciones. Si yo establezco condiciones en un *managment group*, todas las suscripciones que este contiene las heredan.
## Subscriptions
Agrupan cuentas de usuario y los recursos que esas cuentas crearon. Para cada suscripción, hay límites o cuotas respecto a la cantidad de recursos que pueden crearse y utilizarse. 
Las organizaciones pueden usar suscripciones para gestionar costos y recursos creados por usuarios, equipos o proyectos.
## Resource groups
Los recursos se agrupan, estas agrupaciones actúan como contenedor lógico dentro del cual recursos de Azure, como web apps, databases, y storage accounts son deployeadas y administradas.
## Resources
Son instancias de servicios que uno crea, como virtual machines, almacenamiento, o bases de datos SQL.

# Regiones, zonas de disponibilidad y pares de regiones

## Regions
Es un área que contiene al menos un datacenter, generalmente varios, vinculados con una red de baja latencia.
Al deployear un recurso en Azure, hay que elegir la región.
## Avaiability Zones
Son datacenters separados (físicamente hablando), en cada Region.
Cada una de estas zonas tiene uno o más datacenters, cada uno equipado con energía, refrigeración y conexion a red.
Están hechas para que, si una zona se cae, otras continuen trabajando.
Están conectadas mediante fibra óptica de alta velocidad.

![alt text] (https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-architecture-fundamentals/media/availability-zones-5c3c490c.png)
## Region Pair
Cada region está vinculada con otra en la misma geografía. Esto es para respaldar en caso de cualquier desastre o sueceso geográfico que afecte a alguna de las dos regiones.

![alt text] (https://docs.microsoft.com/en-us/learn/azure-fundamentals/azure-architecture-fundamentals/media/region-pairs-d9eb9728.png)
