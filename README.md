# churn_prediction
Modelo predictivo para detectar a clientes con alta probabilidad de abandono de una compañía

Una compañía telefónica que ha detectado muchas bajas de clientes entre diciembre de 2019 y enero de 2020 nos pide que desarrollemos un modelo analítico capaz de predecir los clientes con alta probabilidad de abandono para lanzar una campaña e intentar fidelizarles antes de su portabilidad. Además los directivos quieren conocer las causas de fuga de los clientes.

Para realizar este modelo de Machine Learning disponemos de dos cosechas con datos de diciembre y de enero. Cada cosecha cuenta con las siguientes tablas y variables:


**Tabla clientes**
* ```id```: identificador de cliente
* ```edad```: de los clientes.
* ```facturacion```: dinero que pagan los clientes al mes.
* ```antiguedad```: fecha de alta del cliente.
* ```provincia```: lugar de procedencia del cliente.
* ```num_lineas```: número de líneas móviles contratadas.
* ```num_dt```: número de líneas en impago.
* ```incidencia```: es SI, si el cliente ha tenido alguna incidencia/reclamación


**Tabla productos**
* ```conexión```: tipo de conexión de internet del cliente.
* ```vel_conexion```: velocidad de conexión de internet.
* ```TV```: tipo de paquete de tv contratado por el cliente.


**Tabla consumos**
* ```num_llamad_ent```: número de llamadas entrantes de todas sus líneas.
* ```num_llamad_sal```: número de llamadas salientes de todas sus líneas.
* ```mb_datos```: mb de los datos consumidos en todas sus líneas.
* ```seg_llamad_ent```: segundos consumidos en llamadas entrantes.
* ```seg_llamad_sal```: segundos consumidos en llamadas salientes.


**Tabla financiación**
* ```financiación```: es SI, si el cliente tiene financiado algún terminal.
* ```imp_financ```: el dinero mensual que paga por los terminales financiados.
* ```descuentos```: es SI, si el cliente tiene activo algún descuento (campaña).
* ```target```: esta variable no la tenemos. Una vez que tenemos los dos tablones analíticos construidos (diciembre y enero) hay que pensar como podemos construir esta variable.


