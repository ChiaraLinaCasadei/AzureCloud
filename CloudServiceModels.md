
# IaaS
## Infrastructure as a Service
Es el mas cercano a gestionar servidores físicos.
Un proveedor cloud mantendrá el hardware actualizado, pero el mantenimiento del sistema operativo, y la configuración de red están a tu cargo como propietario del cloud.

Por ejemplo, las máquinas virtuales son dispositivos virtuales de cómputo completamente operativos, que correr en los datacenters de Microsoft.  

Una ventaja del IaaS es el rapido lanzamiento de nuevos servicios de cómputo.
Poner en marcha una máquina virtual es mucho mas rápido de configurar e instalar un servidor físico.

# PaaS
## Platform as a Service
Este modelo de servicio es un ambiente de hosting administrado. El proveedor cloud gestiona las máquinas virtuales y recursos de networking.
El propietario del cloud deployea sus aplicaciones dentro de este ambiente de hosting.

Por ejemplo, Azure App Services provee un ambiente gestionado de hosting donde los desarrolladores pueden subir sus web apps, sin tener que preocuparse sobre requerimiento de hardware y software.

# SaaS
## Software as a Service
El proveedor cloud controla todos los aspectos del entorno de la aplicación, como máquinas virtuales, recursos de networking, almacenamiento de datos, y aplicaciones.
El propietario del cloud solo necesita proveer los datos a la aplicación que administra el proveedor.

Por ejemplo, Microsoft Office 365 provee una version completamente operativa de Microsoft Office que corre en la nube. Todo lo que necesitas hacer como propietario es crear tu contenido, y Office 365 se encarga de todo lo demás.

![alt text](https://docs.microsoft.com/en-us/learn/azure-fundamentals/fundamental-azure-concepts/media/iaas-paas-saas-575a09e9.png)

# Niveles de responsabilidad entre el proveedor y el propietario

![alt text](https://docs.microsoft.com/en-us/learn/azure-fundamentals/fundamental-azure-concepts/media/shared-responsibility-76efbc1e.png)

# Serverless Computing

Le permite a los desarrolladores buildear aplicaciones mas rápido, ya que se elimina la necesidad de administrar la infraestructura.
Con aplicaciones *serverless* , el proveedor cloud automáticamente provee, escala y gestiona la infraestructura requerida para correr el código.
Las arquitecturas de este tipo son altamente escalables y orientadas a eventos, solo utilixando recursos cuando una función específica o un trigger sucede.

Ojo, que los servidores siguen corriendo el código.
El nombre viene de que las tareas asociadas con infraestructura, provisión y administración son invisibles para el desarrollador.
Este enfoque permite que los desarrolladores se concentren má en la lógica de negocio y agreguen mas valor al cuerpo del negocio.
*Serverless computing* ayuda a los equipos a elevar su productividad, y lanzar mas rápido los productos al mercado. Les permite a las organizaciones optimizar recursos y enfocarse en la innovación.
