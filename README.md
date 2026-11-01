# BP Digital Banking — Arquitectura de Soluciones

## Descripción del ejercicio

Este repositorio presenta la propuesta de arquitectura de soluciones para un ejercicio técnico de **DEVSU**, basado en el diseño de una plataforma de banca digital para la entidad ficticia **BP**.

El objetivo es diseñar una solución omnicanal que permita a los clientes consultar su información y el histórico de movimientos, efectuar transferencias entre cuentas propias e interbancarias y realizar pagos, integrándose con el Core Bancario y otros sistemas de la institución.

La propuesta contempla dos canales de atención —una aplicación web SPA y una aplicación móvil multiplataforma—, autenticación mediante un proveedor de identidad existente basado en OAuth 2.0, onboarding con reconocimiento facial, auditoría de las acciones del cliente y mecanismos de notificación de movimientos.

También aborda atributos de calidad y restricciones de una plataforma financiera: **seguridad, protección de datos, alta disponibilidad, tolerancia a fallos, recuperación ante desastres, baja latencia, monitoreo, auto-healing, desacoplamiento y control de costos**.

## Documento de solución

**[Consultar y descargar el documento PDF — BP Digital Banking: Arquitectura de Soluciones (v2.0)](./BP_Digital_Banking_Arquitectura_DEVSU_v2.pdf)**

El documento contiene la propuesta completa y autocontenida, incluyendo:

- Modelo C4: diagramas de **contexto, contenedores y componentes**.
- Diagramas de secuencia de flujos críticos e infraestructura propuesta en AWS.
- Decisiones arquitectónicas (ADR), alternativas evaluadas y sus fundamentos teóricos.
- Metodologías y patrones aplicados: DDD, arquitectura hexagonal, API Gateway/BFF, Cache-Aside, Transactional Outbox, idempotencia, ACL y resiliencia.
- Arquitectura de identidad, onboarding biométrico, integración, auditoría y notificaciones.
- Consideraciones de seguridad, normativa, continuidad, observabilidad, capacidad y costos.
- Trazabilidad de requisitos, riesgos y supuestos de diseño.

## Alcance de la entrega

Este repositorio está destinado exclusivamente a la **publicación del documento de arquitectura** para su evaluación. La solución presentada corresponde a un **diseño de referencia**: los objetivos cuantitativos y elementos sujetos a validación se identifican como propuestas o supuestos, no como resultados de implementación o pruebas productivas.

---

**Ejercicio técnico:** Arquitecto de Soluciones — DEVSU  
**Caso de estudio:** BP Digital Banking  
**Entregable:** Documento PDF de arquitectura de soluciones (versión 2.0)
