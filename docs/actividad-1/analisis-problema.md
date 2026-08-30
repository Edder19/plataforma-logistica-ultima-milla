# Análisis del problema

## 1. Situación actual

La empresa de retail digital recibe pedidos provenientes de diferentes canales de venta. Estos pedidos deben ser procesados, asociados con el inventario disponible, preparados en los almacenes y posteriormente asignados a rutas y repartidores para realizar la entrega al cliente.

Actualmente, la operación logística involucra diferentes actores y sistemas, pero no existe una vista centralizada que permita consultar de manera confiable el estado real de cada pedido durante todo su ciclo de vida.

La información puede encontrarse distribuida entre diferentes procesos, áreas y sistemas, lo que dificulta que todos los actores trabajen con la misma información.

Por ejemplo, el área de almacén puede disponer de una información diferente sobre el inventario frente a la información utilizada para procesar un pedido. De igual manera, el área de soporte puede no contar con información actualizada sobre la ubicación o estado de una entrega.

---

## 2. Problema identificado

El problema principal es la falta de centralización y trazabilidad de la información relacionada con los pedidos y su proceso de entrega.

La empresa necesita coordinar diferentes procesos relacionados con:

* Recepción de pedidos.
* Validación de inventario.
* Preparación de pedidos.
* Asignación de rutas.
* Asignación de repartidores.
* Seguimiento de entregas.
* Gestión de incidencias.
* Atención de solicitudes de los clientes.

Cuando estos procesos no comparten información actualizada y consistente, aumenta la posibilidad de errores operativos y se dificulta conocer cuál es el estado real de un pedido.

Por lo tanto, el problema no consiste únicamente en la ausencia de una aplicación, sino en la necesidad empresarial de **centralizar la información logística y mejorar la coordinación y trazabilidad de los pedidos**.

---

## 3. Causas principales

Se identifican inicialmente las siguientes causas:

### 3.1. Información distribuida

La información relacionada con pedidos, inventarios, rutas y entregas puede estar almacenada o gestionada mediante diferentes sistemas y procesos.

### 3.2. Falta de una vista centralizada

Los diferentes actores no necesariamente disponen de una única fuente de información sobre el estado actual de cada pedido.

### 3.3. Falta de sincronización

Los cambios realizados en un proceso pueden no reflejarse inmediatamente en otros procesos relacionados.

### 3.4. Coordinación entre múltiples actores

El proceso logístico requiere la participación de comercio, almacén, repartidores, soporte y sistemas externos.

### 3.5. Dependencia de sistemas externos

La operación depende de servicios como pagos, geolocalización, notificaciones y sistemas empresariales internos.

---

## 4. Consecuencias

La situación actual puede producir diferentes consecuencias operativas y empresariales.

### Operativas

* Duplicación de pedidos.
* Errores en la preparación de pedidos.
* Inconsistencias en el inventario.
* Asignación incorrecta de rutas.
* Retrasos en las entregas.
* Entregas fallidas.
* Dificultades para gestionar incidencias.

### Para el cliente

* Información desactualizada sobre su pedido.
* Incertidumbre sobre el tiempo de entrega.
* Mayor cantidad de reclamaciones.
* Mala experiencia durante el proceso de compra y entrega.

### Para la empresa

* Incremento de costos operativos.
* Pérdida de productividad.
* Mayor carga de trabajo para el área de soporte.
* Dificultad para medir el desempeño logístico.
* Pérdida de trazabilidad.
* Dificultad para escalar la operación.

---

## 5. Variables relevantes

Para comprender adecuadamente el problema se deben considerar las siguientes variables.

### 5.1. Pedido

* Identificador del pedido.
* Cliente.
* Productos.
* Cantidades.
* Fecha y hora de creación.
* Estado actual.
* Dirección de entrega.
* Forma de pago.

### 5.2. Inventario

* Producto.
* Cantidad disponible.
* Almacén.
* Cantidad reservada.
* Disponibilidad para despacho.

### 5.3. Ruta

* Identificador de ruta.
* Pedidos asociados.
* Repartidor asignado.
* Secuencia de entregas.
* Estado de la ruta.
* Ubicación.

### 5.4. Repartidor

* Identificador.
* Disponibilidad.
* Ruta asignada.
* Estado de la entrega.

### 5.5. Entrega

* Pedido asociado.
* Repartidor.
* Estado.
* Ubicación.
* Fecha estimada.
* Fecha de entrega.
* Resultado de la entrega.

### 5.6. Incidencia

* Tipo de incidencia.
* Pedido afectado.
* Fecha y hora.
* Descripción.
* Estado.
* Responsable.
* Acción realizada.

---

## 6. Necesidad del negocio

La empresa necesita disponer de una solución que permita centralizar la información relacionada con los pedidos y facilitar la coordinación de las diferentes etapas del proceso logístico.

La necesidad principal es contar con una fuente de información confiable que permita conocer el estado de cada pedido, desde su recepción hasta su entrega, y que facilite la comunicación entre los diferentes actores involucrados.

Esta necesidad justifica analizar una plataforma centralizada de gestión logística como posible solución inicial.

Sin embargo, en esta etapa no se define todavía la arquitectura interna ni las tecnologías que se utilizarán. Primero se debe comprender completamente el contexto, validar los requisitos y establecer los límites del sistema.
