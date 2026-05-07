## 2. Modelo C4 - Nivel 1: Diagrama de Contexto

**Responsable:** Dayana

En este nivel, se describe el ecosistema de **DataCo** de forma macro, enfocándose en las interacciones entre los usuarios, los sistemas externos y la nueva solución de datos, sin hacer énfasis en tecnologías específicas.

### 2.1. Visualización del Diagrama
![Diagrama de Contexto C1](./assets/Diagrama_C1_contexto.jpg)

### 2.2. Diccionario de Elementos
A continuación, se describen las responsabilidades de cada componente y actor representado en el diagrama:

| Elemento | Tipo | Descripción |
| :--- | :--- | :--- |
| **Sistema ERP** | Sistema Externo | Fuente principal de datos transaccionales, facturas y pedidos de la compañía. |
| **Sistema de Inventarios** | Sistema Externo | Provee información sobre movimientos de stock y fechas de vencimiento de productos. |
| **Sistema CRM** | Sistema Externo | Repositorio de datos sobre acuerdos comerciales, clientes y gestión de cartera. |
| **Sistema de Logística** | Sistema Externo | Suministra datos geográficos (GPS), rutas y tiempos de entrega. |
| **Plataforma de Datos** | **Sistema Central** | Solución encargada de centralizar, transformar y modelar la información para el negocio. |
| **Sistema de Visualización** | Sistema Externo | Herramienta donde los usuarios finales consumen los dashboards e indicadores (KPIs). |
| **Gerencia Comercial** | Persona (Actor) | Usuario estratégico que toma decisiones basadas en el análisis de los KPIs. |
| **Analista de BI** | Persona (Actor) | Usuario técnico que diseña reportes y analiza tendencias de ventas. |
| **Auditor de Datos** | Persona (Actor) | Responsable de supervisar la calidad, integridad y gobierno de la información. |

---
