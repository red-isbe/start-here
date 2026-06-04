# ISBE — Release 1: Documentación del Proyecto

**Infraestructura de Servicios Blockchain de España (ISBE)**  
Financiada por NextGenerationEU · PRTR C13 · Convenio CAM–Alastria  
Operada por [Alastria](https://alastria.io) · Documentación técnica: [docs.redisbe.com](https://docs.redisbe.com/documentation/)

---

## Sobre el proyecto

ISBE es la infraestructura blockchain nacional de España, construida sobre Hyperledger Besu. Es la primera red DLT cualificada (qDLT) bajo el Reglamento Europeo eIDAS2 (EU Reg. 2025/2531) operativa en Europa.

La arquitectura de ISBE sigue un modelo de **red de redes** federada: una capa pública abierta combinada con control permisionado. Su stack incluye un Smart Contract Framework basado en el patrón Diamond (EIP-2535) con RBAC, un marco de identidad digital soberana (`did:isbe`, compatible con EBSI), un Filtering Proxy que garantiza el cumplimiento RGPD, y el token TKN (utility token exento MiCA, denominado en euros).

ISBE opera 9 Core Capabilities sobre las que los Service Providers construyen sus servicios sin competir con la infraestructura. Los pilares estratégicos actuales cubren desde certificación de evidencias y lógica de negocio verificable hasta identidad descentralizada, dinero digital y tokenización de activos reales.

Esta Release 1 representa la entrega formal de la **Fase 1 (Platform Consolidation)**: arquitectura de referencia, gobernanza, marco regulatorio, modelo de sostenibilidad, puesta en producción e implantación.

---

## Código fuente y repositorios

El código fuente de ISBE está alojado en la organización [**github.com/alastria**](https://github.com/alastria).
Aquí está el índice de artefactos que corresponde a el entregable T4 [**github.com/alastria/isbe-artefactos**](https://github.com/alastria/isbe-artefactos/blob/main/README.md)

> **Nota:** El acceso a los repositorios es restringido. Para solicitar permisos, contacta con el equipo de ISBE en [redisbe.com](https://redisbe.com) o abre una solicitud a través del canal habilitado para desarrolladores.

---

## Documentos entregados — Release 1

Los documentos están organizados en los siguientes bloques temáticos. Todos los archivos están disponibles en la [carpeta de Google Drive de Release 1](https://drive.google.com/drive/folders/1oj8H0V10UySCgmqniiNFaRgSzMweLtjT?usp=sharing).

### T1x — Análisis y Arquitectura

| Ref | Documento |
|-----|-----------|
| T11 | [Evaluación de necesidades](https://drive.google.com/file/d/1cDK-JxsxuX9lfjG-J5N9KgSJ3ArXTvNu/view?usp=drivesdk) |
| T12 | [Análisis de requerimientos](https://drive.google.com/file/d/1FZulP-igttpLaIDBPgU4XxDvIGbZjwIO/view?usp=drivesdk) |
| T13 | [Arquitectura de Referencia de ISBE v1](https://drive.google.com/file/d/10L7guGd-485adh3C8JshUIhQn7NhaLzU/view?usp=drivesdk) |
| T14 | [Código fuente y documentación técnica v2.0](https://drive.google.com/file/d/1fVMdFaLiDavbdQlTr1Q0ynlLFea2te8I/view?usp=drivesdk) ⚠️ Ver nota sobre repositorios |
| T15 | [Prueba de concepto y validación v2](https://drive.google.com/file/d/13AztkHZFIlCbe3LZe4xGm357R2DjJiyS/view?usp=drivesdk) |

### T21 — Gobernanza y Marco Jurídico

| Ref | Documento |
|-----|-----------|
| T21-1 | [Memoria de Gobernanza — Diseño v2.0](https://drive.google.com/file/d/1U-_DhXsqJvA7r6aQyYI39rKe8uoEDkn7/view?usp=drivesdk) |
| T21-1B | [ISBE Report Jan 2026](https://drive.google.com/file/d/1jKJlXQHLSaqS2_pKW6CaULNZ3Bw8n9L0/view?usp=drivesdk) |
| T21-2 | [Catálogo de Políticas ISBE](https://drive.google.com/file/d/18Ww7Fen7BSsauzNk44op80jFA9WVf6Nl/view?usp=drivesdk) |
| T21-3 | [Modelo de Referencia de Procesos v1.0](https://drive.google.com/file/d/1B9GTAGJtqs6GpPhBN1oM6FgBboVsm4Sq/view?usp=drivesdk) |
| T21-4 | [Contrato Marco de Adhesión (CMA)](https://drive.google.com/file/d/1wsS-TeR6MEHHqacPRuWgjFaEAgY788IH/view?usp=drivesdk) |
| T21-5-A | [Forma jurídica Red ISBE (enero 2026)](https://drive.google.com/file/d/1EJdwhkFcyV2AjHpoM90HjD5ln_zES4Pg/view?usp=drivesdk) |
| T21-5-B | [Vehículo jurídico ISBE — Derecho Administrativo](https://drive.google.com/file/d/1MxD-h8iVrcCBjwVY19OtYmiiuxlyDvfH/view?usp=drivesdk) |

### T22 — Cumplimiento Regulatorio

| Ref | Documento |
|-----|-----------|
| T22 | [Informe de adecuación al marco legal y cumplimiento regulatorio v2.0](https://drive.google.com/file/d/19PLK2ejHirGrKKGYVOKvAsjpa7kXdbk3/view?usp=drivesdk) |
| T22-1 | [Memoria Técnica 1 — Análisis de Interoperabilidad de Redes](https://drive.google.com/file/d/1-BcqPitVnW2tfJAR1Nb4KNGfdtA9PkE_/view?usp=drivesdk) |
| T22-2 | [Memoria Técnica 2 — Análisis de Privacidad en Transacciones](https://drive.google.com/file/d/1A8VwBB-BiNob7aOsa6CvMLFrxh2eSArc/view?usp=drivesdk) |
| T22-A1a | [Anexo 1a — Política de servicio y requisitos de seguridad (QEL)](https://drive.google.com/file/d/1c9rXzytY5dHKftFzkZbf3bD9rckSx2ff/view?usp=drivesdk) |
| T22-A1b | [Anexo 1b — Lista de conformidad servicio libro mayor](https://drive.google.com/file/d/1WWWPZCKnY816k18dnUMo3_5vEaoyRYdV/view?usp=drivesdk) |
| T22-A1c | [Anexo 1c — Declaración de Prácticas de Certificación](https://drive.google.com/file/d/1euRZG5iSLA9-O2el_sw2wD96yM4vJ10R/view?usp=drivesdk) |
| T22-A2a | [Anexo 2a — Directrices generales de cumplimiento](https://drive.google.com/file/d/1bNjXk7mnyf8yC5wv7hnIxM1OpxqFX9CS/view?usp=drivesdk) |
| T22-A2b | [Anexo 2b — Gestión de Incidentes de Seguridad con datos personales](https://drive.google.com/file/d/1RjRAw_S9BmWOXkwJyVhOmElM03Kax5Kq/view?usp=drivesdk) |
| T22-A2c | [Anexo 2c — Cláusulas contrato de encargado](https://drive.google.com/file/d/13QPrU68ekJPSikDrbE7WP3bIqS_KEgo2/view?usp=drivesdk) |
| T22-A2d | [Anexo 2d — Evaluación de Impacto en Protección de Datos (EIPD/PIA)](https://drive.google.com/file/d/1U0mf9asK9aLoTdKc73GMOmfTKlLofxzY/view?usp=drivesdk) |
| T22-A2e | [Anexo 2e — Directrices Vinculantes RGPD](https://drive.google.com/file/d/1DESv7CeysVWm74XniZYkVzfn4wkyeO_4/view?usp=drivesdk) |
| T22-A3 | [Anexo 3 — Análisis ENS (Esquema Nacional de Seguridad)](https://drive.google.com/file/d/1tuzIeNYBE2aENx8vhdFim8FiyL0rFlSg/view?usp=drivesdk) |
| T22-A4 | [Anexo 4 — Análisis NIS2](https://drive.google.com/file/d/1sTYgHFJ_ERIm-GR42nMiMZ-GPnDdGapT/view?usp=drivesdk) |
| T22-A5a | [Anexo 5a — Variables red ISBE](https://drive.google.com/file/d/11seLvV8gc5G23SsQgvJVLKL2RFLw28Ol/view?usp=drivesdk) |
| T22-A5b | [Anexo 5b — Article 9 (eIDAS2)](https://drive.google.com/file/d/1LnryvCuHVhI6ABbPdAb5ILeS_nKIhcox/view?usp=drivesdk) |
| T22-A5c | [Anexo 5c — Article 56 DORA](https://drive.google.com/file/d/1EF2MndgZ4P1yGt_n2kbpxhkB8aL32OjI/view?usp=drivesdk) |
| T22-A5d | [Anexo 5d — Yellowpaper ISBE TKN](https://drive.google.com/file/d/18SgJvLi4B17cl9ZguerA0mTMlznw7Vdm/view?usp=drivesdk) |
| T22-A6 | [Anexo 6 — Análisis Criptoactivos y Tokenización](https://drive.google.com/file/d/16RB5to21TqX_1S-6mCUM5z6j-wjY6X-U/view?usp=drivesdk) |
| T22-A7 | [Anexo 7 — Términos y condiciones](https://drive.google.com/file/d/1e2ajSE_rKnT_3xrP2hZA-4mhp6JpHbYU/view?usp=drivesdk) |
| T22-A8 | [Anexo 8 — RGPD: Evaluación de Impacto en Protección de Datos (EIPD/PIA) v2](https://drive.google.com/file/d/14apsNiQ3T0u557lOWpqa3_AwW2mhXJRp/view?usp=drivesdk) |
| T22-A9 | [Anexo 9 — QEL: Declaración de Prácticas de Certificación](https://drive.google.com/file/d/1jgC3WDpcCvaQzhPWsn3tcsjrxwPTqplc/view?usp=drivesdk) |

### T23–T25 — Operaciones y Sostenibilidad

| Ref | Documento |
|-----|-----------|
| T23 | [Modelo de Sostenibilidad v2.0](https://drive.google.com/file/d/13XnqgZLTc5ovurfy6tt7zGw4Pi4sbEMg/view?usp=drivesdk) |
| T24 | [Memoria de puesta en producción v1.0](https://drive.google.com/file/d/1OOMea4QTa3bwjWympzjjkcTWbr5EByKD/view?usp=drivesdk) |
| T25 | [Memoria de implantación y estabilización v1.0](https://drive.google.com/file/d/1TfBzKAAxWKvGzg06kEzTV8l3neliznru/view?usp=drivesdk) |

---

## Documentación técnica

La documentación técnica de ISBE está disponible en:

**[docs.redisbe.com](https://docs.redisbe.com/documentation/)**

Incluye guías de integración, referencia del Smart Contract Framework, especificación del protocolo `did:isbe`, y documentación del Filtering Proxy.

---

## Próximos pasos — Release 2 (H2 2026)

La Release 2 está prevista para el segundo semestre de 2026.

---

## Contacto

**Alastria / ISBE**  
[redisbe.com](https://redisbe.com) · [alastria.io](https://alastria.io)  
