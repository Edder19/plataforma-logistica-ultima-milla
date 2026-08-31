# Registro de riesgos

| ID   | Riesgo                                 | Probabilidad | Impacto | Prioridad | Mitigación inicial                                     |
| ---- | -------------------------------------- | ------------ | ------- | --------- | ------------------------------------------------------ |
| R-01 | Duplicación de pedidos                 | Alta         | Alto    | Crítica   | Identificador único y validación de pedidos            |
| R-02 | Inventario desactualizado              | Alta         | Alto    | Crítica   | Centralizar y sincronizar información                  |
| R-03 | Retrasos en entregas                   | Media        | Alto    | Alta      | Seguimiento de estados y rutas                         |
| R-04 | Entrega fallida                        | Media        | Alto    | Alta      | Registro de incidencias y seguimiento                  |
| R-05 | Pérdida de trazabilidad                | Media        | Alto    | Alta      | Registrar eventos relevantes del pedido                |
| R-06 | Fallos de integración                  | Media        | Alto    | Alta      | Definir mecanismos de comunicación y manejo de errores |
| R-07 | Información desactualizada             | Media        | Alto    | Alta      | Definir frecuencia y mecanismos de actualización       |
| R-08 | Crecimiento del volumen de pedidos     | Media        | Alto    | Alta      | Considerar escalabilidad desde el diseño               |
| R-09 | Fallos en notificaciones               | Media        | Medio   | Media     | Registrar estado de envío y reintentos                 |
| R-10 | Fallos del servicio de geolocalización | Media        | Alto    | Alta      | Manejo de errores y alternativas operativas            |

## Riesgos prioritarios

Los riesgos que deben recibir mayor atención inicialmente son:

1. Duplicación de pedidos.
2. Inconsistencias de inventario.
3. Pérdida de trazabilidad.
4. Retrasos y entregas fallidas.
5. Fallos en las integraciones con sistemas externos.

Estos riesgos pueden afectar directamente la operación, los costos y la satisfacción del cliente.
