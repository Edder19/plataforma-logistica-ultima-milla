                         ┌─────────────────────┐
                         │  Sistema de pagos   │
                         └──────────┬──────────┘
                                    │
                                    │ pagos
                                    ▼
┌──────────────┐            ┌──────────────────────────┐
│   Cliente    │───────────►│                          │
└──────────────┘  pedidos,  │ Plataforma de Gestión    │
                  consultas │ Logística de Última Milla│
                            │                          │
┌──────────────┐            │                          │
│   Tienda /   │───────────►│                          │
│   Comercio   │            └────────────┬─────────────┘
└──────────────┘                         │
                                         │
┌──────────────┐                         │
│ Administrador│─────────────────────────┤
│  de almacén  │                         │
└──────────────┘                         │
                                         │
┌──────────────┐                         │
│  Repartidor  │◄────────────────────────┤
└──────────────┘                         │
                                         │
┌──────────────┐                         │
│   Soporte    │◄────────────────────────┤
│ al cliente   │                         │
└──────────────┘                         │
                                         │
                 ┌───────────────────────┼────────────────────┐
                 │                       │                    │
                 ▼                       ▼                    ▼
        ┌────────────────┐      ┌────────────────┐   ┌────────────────┐
        │ Geolocalización│      │ Notificaciones │   │   ERP / CRM    │
        └────────────────┘      └────────────────┘   └────────────────┘| Actor/Sistema            | Interacción                                           |
| ------------------------ | ----------------------------------------------------- |
| Cliente                  | Crea pedidos y consulta estado de entrega             |
| Tienda/Comercio          | Gestiona pedidos y operaciones comerciales            |
| Administrador de almacén | Consulta inventario y prepara pedidos                 |
| Repartidor               | Consulta rutas y actualiza estado de entrega          |
| Soporte                  | Consulta pedidos y gestiona incidencias               |
| Sistema de pagos         | Procesa y confirma pagos                              |
| Geolocalización          | Proporciona ubicación y datos necesarios para rutas   |
| Notificaciones           | Envía actualizaciones al cliente y personal           |
| ERP/CRM                  | Intercambia información empresarial con la plataforma |
