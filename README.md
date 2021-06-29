# Diagrama para red en AWS

![alt text](https://github.com/lbrines/diagrama/blob/main/AWS.png?raw=true)

1. Para el registro de dominio y administración de las zonas DNS.
2. Configuración CDN para distribución global del contenido.
3. Balanceo entre zonas.
4. Creación de dos zonas de disponibilidad para HA.
5. Nginx en la zona publica configurado como proxy inverso a la solicion.
6. Se eligio Elastic Beanstalk por la fácil utilización y escalabilidad.
7. Base de datos en subnet especial, con replicación de la db relacional.
8. Conexión seguro por SSL con API externa.