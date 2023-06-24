# AWS-Certified-Cloud-Practitioner-CLF-C01
Notas del Curso

## Vista general de la IT (Tecnología de la información) tradicional

### Cómo funcionan los sitios web
- Los clientes tienen direcciones IP
- Red (viajan por la red)
- Los servidores tienen direcciones IP

Correo postal: Receptor (emitimos la dirección de carta), la red es la red de transporte, se verá nuestra dirección.

Analogía para entender la arquitectura (cleinte / servidor) tradicional en los sitios web

### ¿De qué se compone un servidor?
- Computación: CPU
- Memoria: RAM
= Cerebro

- Almacenamiento: Información

- Base de Datos: Almacenar los datos de forma estructurada
- Red: Routers, switch, servidor DNS

### Terminología informática
- Red: cables, routers y servidores conectados entre sí.
- Router: Dispositivo de red que reenvía paquetes de datos entre redes de ordenadores. Saben dónde enviar los paquetes en Internet. (pueden ser varios puntos de control)

Cada vez que se le envía cierta información, el router define cuál será la ruta de salida para así comunicar emisor y receptor.

- Switch: Toma un paquete y lo envía al servidor / cliente correcto en la red.

- Imagen estructura de red

### Tradicionalmente, la forma de construir infraestructuras

De casas o garajes a oficinas (o centro de datos).

### Problemas con el enfoque tradicional de las IT
- Pagar el alquiler del centro de datos
- Pagar el suministro eléctrico, la refrigeración y el mantenimiento.
- Añadir y sustituir el hardware lleva tiempo.
- El escalado es limitado.
- Contratar un equipo 24/7 para supervisar la infraestructura
- ¿Cómo hacer frente a las catástrofes? (terremoto, apagón, incendio...)

- ¿Podemos externalizar todo esto?

## ¿Qué es el Cloud Computing?
- El Cloud Computing (Computación en la nube) es el **suministro bajo demanda** de potencia de cálculo, almacenamiento en bases de datos, aplicaciones y otros recursos informáticos.
- A través de una plataforma de servicios en el cloud con **precios de pago por uso**.
- Puedes **aprovisionar exactamente el tipo y el tamaño** de recursos informáticos que necesitas.
- Puedes acceder a tantos recursos como necesites, **casi al instante**.
- Forma sencilla de acceder a **servidores, almacenamiento, bases de datos** y un conjunto de **servicios de aplicaciones**.
- Amazon Web Services (AWS) posee y mantiene el hardware conectado a la red necesario para estos servicios de aplicaciones, mientras que aprovisionas y utilizas lo que necesitas a través de una aplicación web.

### Los modelos de despliegue del Cloud
## Cloud privado
- Servicios en el cloud utilizados por una sola organización, no expuestos al público.
- Control total
- Seguridad para aplicaciones sensibles
- Satisfacer necesidades empresariales específicas

## Cloud público
- Recursos en el cloud que son propuedad de un proveedor de servicios en el cloud t son operados por él, y que se suministran a través de Internet (por ejemplo AWS desde su consola).
- Seis ventajas de computación el el cloud.

## Cloud híbrido
- Mantener algunos servidores en las instalaciones y extiende algunas capacidades al cloud
- Control de los activos sesibles en tu infraestructura privada.
- Flexibilidad y rentabilidad de cloud público.

### Las cinco características del Cloud computing

- **Autoservicio bajo demanda(on-demand)**:
    - Los usuarios pueden aprovisionar recursos y utilizarlos sin interacción humana del proveedor de servicios
- **Amplio acceso a la red**:
    - Los recursos están disponibles a través de la red, y pueden ser accedidor por diversas plataformas de clientes.
- **Alquiler múltple y agrupación de recursos**:
    - Varios clientes pueden compartir la misma infraestructura y aplicaciones con seguridad y privacidad
    - Múltiples clientes reciben servicio desde los mismos recursos físicos.
- **Rápida elasticidad y escalabilidad**:
    - Adquirir y disponer de recursos de forma automática y rápida cuando sea necesario.
    - Escala rápida y fácilmente en función de la demanda.
- **Servicio medido**    
    - El uso se mide, los usuarios pagan correctamente por lo que han utilizado.

### Seis ventajas del Cloud computing
- Cambia el gasto de capital (CAPEX) por el gasto operativo (OPEX).
    - Pagar bajo demanda: no poseer el hardware
    - Reducción del coste total de propiedad (TCO) y de los gastos operativos (OPEX).
- Te beneficias de economías de escala masivas
    - Los precios se reducen ya que AWS es más eficiente debido a la gran escala
- Deja de adivinar la capacidad
    - Escala basada en el uso real medido        
- Aumentar la velocidad y la agilidad.
- Deja de gastar dinero en el funcionamiento y el mantenimiento de los centros de datos.    
- Se global en minutos: Aprovecha la infraestructura global de AWS.

Problemas resueltos por el Cloud
- Flexibilidad: Cambia los tipos de recursos cuando sea necesario.
- Rentabilidad: Paga por lo que utilizas
- Escalabilidad: Permite acomodar mayores cargas reforzando el hardware o añadiendo nodos adicionales
- Elasticidad: Capacidad de reducir y aumentar la escala cuando sea necesario.
- Alta disponibilidad y tolerancia a fallos: Construye a través de los centros de datos (data centers).
- Agilidad: Desarrollar, testear y lanzar rápidamente aplicaciones de software. 
