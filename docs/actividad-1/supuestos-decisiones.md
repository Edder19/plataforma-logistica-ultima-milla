# Supuestos y decisiones iniciales

## 1. Supuestos

Para realizar el diagnóstico inicial se establecen los siguientes supuestos:

1. La empresa ya cuenta con diferentes canales mediante los cuales recibe pedidos.
2. Existen uno o varios almacenes donde se administra el inventario.
3. Los pedidos deben pasar por diferentes estados durante su ciclo de vida.
4. La empresa trabaja con diferentes repartidores y rutas.
5. Los clientes necesitan consultar información relacionada con sus pedidos.
6. El área de soporte necesita acceder al estado actualizado de los pedidos.
7. Existen sistemas externos para pagos, geolocalización y notificaciones.
8. La empresa dispone de un ERP o CRM interno que debe continuar funcionando.
9. La plataforma deberá integrarse con sistemas existentes en lugar de reemplazarlos inmediatamente.
10. La cantidad de pedidos puede aumentar con el crecimiento del negocio.

## 2. Decisiones iniciales

### Plataforma centralizada

Se propone una plataforma centralizada como punto de integración de la información logística.

### Integración con sistemas existentes

El sistema deberá comunicarse con el ERP o CRM, el sistema de pagos, el servicio de geolocalización y el sistema de notificaciones.

### Trazabilidad

Cada pedido deberá mantener información sobre sus diferentes estados y eventos relevantes para poder reconstruir su recorrido.

### Gestión de incidencias

Las incidencias deberán registrarse y asociarse al pedido correspondiente para facilitar su seguimiento.

### Escalabilidad

Aunque todavía no se selecciona una tecnología específica, la solución deberá considerar el crecimiento futuro del volumen de pedidos, usuarios y entregas.

## 3. Aspectos pendientes de confirmar

Todavía es necesario determinar:

* Cantidad promedio y máxima de pedidos.
* Número de almacenes.
* Número de repartidores.
* Volumen de usuarios simultáneos.
* Sistemas ERP y CRM utilizados.
* Proveedores de geolocalización.
* Proveedores de notificaciones.
* Proveedor del sistema de pagos.
* Requisitos de disponibilidad.
* Requisitos de seguridad.
* Tiempo máximo permitido para actualizar el estado de una entrega.
* Políticas de conservación de información.
* Requisitos legales aplicables.

Estas cuestiones deberán validarse con los responsables del negocio antes de tomar decisiones arquitectónicas definitivas.
