---
title: "Organización de la asignatura   Propuesta"
source_file: "Organización de la asignatura - Propuesta.docx"
format: "docx"
converted_date: "2026-10-31T18:32:40.207Z"
extracted_images_count: 1
---

# Organización de la asignatura   Propuesta

Organización de la asignatura

A partir de la información que encuentra en el sílabo y de su criterio disciplinar y pedagógico distribuya la asignatura que va a virtualizar en la siguiente tabla:


| Créditos | Unidades |
| :--- | :--- |
| 1 | 2 |
| 2 | 3 |
| 3 | 3 o 4 |
| 4 | 3 o 4 |
| 5 | 3 o 4 |
| 6 | 3 o 4 |


Nota: 1 crédito académico corresponde a 48 horas de trabajo.

Distribución propuesta para «Fundamentos de Programación Segura y Criptografía Básica»

Con 2 créditos (96 horas: 40 con acompañamiento —12 sincrónicas y 28 asincrónicas— y 56 de trabajo independiente) corresponden 3 unidades, distribuidas en las 7 semanas del período. Los 7 módulos del sílabo se conservan como una semana cada uno y se agrupan así: Unidad 1 (módulos 1 a 3, semanas 1 a 3), Unidad 2 (módulos 4 y 5, semanas 4 y 5) y Unidad 3 (módulos 6 y 7, semanas 6 y 7).

Peso de la evaluación por unidad: Unidad 1 = 30 %, Unidad 2 = 30 %, Unidad 3 = 40 %. Total = 100 %, como lo establece el sílabo.


| Unidad 1. Programación segura y taxonomía de vulnerabilidades | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 1 | 1. La programación segura como problema de ingeniería | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • De la gestión del riesgo al código: de los controles a los requisitos de software Material de autoría propia — Presentación narrada • Ciclo de vida de desarrollo seguro ( Secure SDLC) y principios de diseño seguro OWASP (2019). ASVS 4.0, cap. V1 «Architecture, Design and Threat Modeling». [Enlace CRAI] • Caso de software propio y protocolo de anonimización, confidencialidad e integridad académica Material de autoría propia — Cartilla (guía del caso y formato del protocolo de anonimización) | • Foro de crítica metodológica 1: presentación del caso de software y principios de diseño aplicables • Firma del protocolo de anonimización y confidencialidad (requisito, sin calificación) • Foro de presentación y foro de consultas (Generalidades) |
| - | 2. Taxonomía de vulnerabilidades del software | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • Vulnerabilidades de gestión de memoria: desbordamiento de búfer, use-after-free y errores de puntero Seacord (2013). Secure Coding in C and C++, caps. 2–4 (cadenas, subterfugio de punteros y memoria dinámica). [Enlace CRAI] • Inyección (SQL, NoSQL, comando, plantilla), validación de entrada, autenticación y gestión de sesiones OWASP (2021). OWASP Top 10: A01, A03 y A07. [Enlace CRAI] • CWE/SANS Top 25, MITRE: de la debilidad al CVE y al CVSS Material de autoría propia — Interactivo (ruta debilidad → CVE → CVSS) • Explotación en entorno controlado y lecciones para el diseño defensivo Material de autoría propia — Cartilla (guía del laboratorio aislado) y Cuestionario formativo | • Foro de crítica metodológica 2: clasificación de hallazgos del caso con OWASP/CWE • Cuestionario formativo: taxonomías y explotación controlada (sin calificación) |
| - | 3. Codificación segura y diseño defensivo | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • Prácticas de codificación segura, manejo de excepciones y registros ( logging ) seguros Howard y LeBlanc (2003). Writing  Secure Code (2.ª ed.), capítulos de principios de codificación defensiva. [Enlace CRAI] • Manejo  seguro de secretos OWASP. Cheat Sheet Series: Secrets Management. [Enlace CRAI] • Seguridad en dependencias y cadena de suministro: SBOM, versionado y selección de bibliotecas Center for Internet Security. CIS Software Supply Chain Security Guide. [Enlace CRAI] • Modelado de amenazas con STRIDE y superficie de ataque Material de autoría propia — Presentación narrada • Codificación asistida por IA generativa: oportunidades, riesgos y obligación de verificación Material de autoría propia — Podcast | • Foro de crítica metodológica 3: modelado de amenazas y uso crítico de IA en el caso (Foros 1 a 3 = 15 %) • Entrega 1: análisis de vulnerabilidades del caso con taxonomía OWASP/CWE y correcciones propuestas (15 %) |



| Unidad 2. Criptografía: fundamentos y aplicación correcta | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 2 | 4. Fundamentos de criptografía | RAE 1. Explicar los fundamentos de la criptografía aplicada —cifrado simétrico y asimétrico, hash, firmas digitales y PKI— seleccionando el mecanismo adecuado para cada requisito de seguridad y argumentando sus propiedades y límites. | • Objetivos de seguridad; cifrado simétrico (AES, ChaCha20) y modos de operación Aumasson (2018). Serious Cryptography, caps. 1, 4 y 5. [Enlace CRAI] • Criptografía asimétrica: RSA, Diffie-Hellman y curvas elípticas Aumasson (2018), caps. 10, 11 y 12. [Enlace CRAI] • Funciones hash y MAC: SHA-2, SHA-3, HMAC Aumasson (2018), caps. 6 y 7. [Enlace CRAI] • Firmas digitales, certificados, PKI y cadena de confianza Stallings (2022). Cryptography and Network Security (8.ª ed.), capítulos de firmas digitales y PKI. [Enlace CRAI] • Post-cuántica y rotación de algoritmos Aumasson (2018), cap. 14. [Enlace CRAI] Material de autoría propia — Cartilla interactiva (mapa de mecanismos según requisito de seguridad) | • Cuestionario formativo: selección del mecanismo según el requisito, con sus propiedades y límites (sin calificación) |
| - | 5. Criptografía aplicada: errores comunes y buenas prácticas | RAE 1. Explicar los fundamentos de la criptografía aplicada —cifrado simétrico y asimétrico, hash, firmas digitales y PKI— seleccionando el mecanismo adecuado para cada requisito de seguridad y argumentando sus propiedades y límites. RAE 3. Proponer e implementar controles criptográficos correctos en una aplicación (almacenamiento seguro de contraseñas, cifrado en tránsito y en reposo, firma y verificación), gestionando claves de manera apropiada y evitando los errores de implementación más comunes. | • Regla de oro: no diseñar protocolos propios; uso de bibliotecas estándar Aumasson (2018), cap. 2 (aleatoriedad) y cap. 8 (cifrado autenticado). [Enlace CRAI] • Almacenamiento seguro de contraseñas: salado, bcrypt , scrypt , Argon2 NIST (2018). SP 800-63B; OWASP Cheat Sheet Series: Password Storage. [Enlace CRAI] • Cifrado en tránsito: TLS 1.3, certificados y HSTS Aumasson (2018), cap. 13. [Enlace CRAI] • Cifrado en reposo: envelope  encryption , HSM/KMS Material de autoría propia — Presentación narrada • Ciclo de vida de claves y errores clásicos ( nonce reutilizado, RNG débil, comparaciones no constantes) NIST (2020). SP 800-57 Part 1 Rev. 5. [Enlace CRAI] Material de autoría propia — Interactivo (errores clásicos: detectar el fallo en fragmentos de código) | • Revisión por pares del diseño de controles de un compañero (5 %) • Entrega 2: implementación de controles criptográficos en el caso —contraseñas, cifrado en tránsito y en reposo, gestión de claves— (25 %) |



| Unidad 3. Verificación, integración en el ciclo de vida y marco normativo | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 3 | 6. Verificación y pruebas de seguridad del software | RAE 3. Proponer e implementar controles criptográficos correctos en una aplicación (almacenamiento seguro de contraseñas, cifrado en tránsito y en reposo, firma y verificación), gestionando claves de manera apropiada y evitando los errores de implementación más comunes. RAE 4. Integrar prácticas de programación segura y pruebas de seguridad en el ciclo de vida del desarrollo de software, documentando decisiones técnicas y comunicándolas a equipos de desarrollo y a la alta dirección. | • SAST, DAST y SCA: alcances y límites OWASP (2019). ASVS 4.0, niveles de verificación. [Enlace CRAI] • Pruebas de penetración básicas y pruebas de seguridad en la API; fuzzing Material de autoría propia — Cartilla (guía de laboratorio) y Presentación narrada • Revisión de código y trabajo con hallazgos OWASP. Cheat  Sheet Series (lista de verificación de revisión de código). [Enlace CRAI] • Controles de seguridad en pipelines CI/CD ( DevSecOps ): puertas de calidad, umbrales y excepciones Center for Internet Security. CIS Software Supply Chain Security Guide. [Enlace CRAI] Material de autoría propia — Interactivo (anatomía de un pipeline DevSecOps ) | • Laboratorio formativo: incorporar SAST y SCA al pipeline del caso (sin calificación) |
| - | 7. Marco normativo, ética y comunicación técnica | RAE 4. Integrar prácticas de programación segura y pruebas de seguridad en el ciclo de vida del desarrollo de software, documentando decisiones técnicas y comunicándolas a equipos de desarrollo y a la alta dirección. | • Marco normativo colombiano: Ley 1273 de 2009, Ley 1581 de 2012 y Decreto 1377 de 2013 República de Colombia. Ley 1273/2009; Ley 1581/2012; Decreto 1377/2013. [Enlaces oficiales] • Ética del desarrollo seguro: divulgación responsable y límites de la experimentación Material de autoría propia — Podcast • Requisitos de seguridad en la contratación de software Material de autoría propia — Cartilla • Comunicación de hallazgos a equipos de desarrollo y a la alta dirección Material de autoría propia — Presentación narrada con ejemplo de informe y de resumen ejecutivo | • Entrega 3: informe final con integración de controles en el ciclo de vida —pipeline, pruebas y documentación técnica— (25 %) • Sustentación técnica tipo comité de arquitectura, en sesión sincrónica (15 %; requisito de aprobación) |


Resumen de la evaluación (según el sílabo)


| Unidad | Actividad evaluativa | RAE | Peso |
| :--- | :--- | :--- | :--- |
| 1 | Participación calificada en foros de crítica metodológica (módulos 1 a 3) | 2 | 15 % |
| 1 | Entrega 1: análisis de vulnerabilidades del caso (OWASP/CWE) y correcciones | 2 | 15 % |
| 2 | Revisión por pares del diseño de un compañero | 1, 3 | 5 % |
| 2 | Entrega 2: implementación de controles criptográficos | 1, 3 | 25 % |
| 3 | Entrega 3: informe final de integración en el ciclo de vida | 3, 4 | 25 % |
| 3 | Sustentación técnica tipo comité de arquitectura (sincrónica) | 3, 4 | 15 % |
| - | Total | - | 100 % |


Supuestos y pendientes por confirmar

• Referencias: cada tema indica la fuente de la bibliografía del sílabo y el capítulo o sección sugerido. Los marcadores [Enlace CRAI] deben reemplazarse por el enlace del CRAI, y los capítulos sugeridos deben precisarse con las páginas exactas de la edición disponible; no se incluyeron enlaces ni páginas que no pudieran comprobarse.

• Material de autoría propia: se asignó el tipo de recurso según el Catálogo de recursos didácticos 2026 (Cartilla interactiva, Presentación narrada, Cuestionario formativo, Podcast, Interactivo y Cartilla). La selección es una propuesta y puede ajustarse según la producción disponible.

• Foros de crítica metodológica: se programó uno por semana en las semanas 1 a 3 (módulos 1 a 3, como indica el sílabo) y se calificarán en conjunto (15 %).

• Revisión por pares: el sílabo la describe como «del diseño metodológico de un compañero». Se interpretó como revisión del diseño de controles criptográficos del caso, previa a la Entrega 2. Si se mantiene la redacción original, conviene confirmar su alcance.

• Sustentación: se programó en la semana 7 dentro de las 12 horas sincrónicas; el sílabo no fija la distribución de esas horas por semana.

• Decreto 1377 de 2013: figura en el sílabo; se recomienda verificar su vigencia, pues fue compilado en el Decreto 1074 de 2015.

• Actividades sin calificación (cuestionarios y laboratorio formativo): se agregaron para cumplir con que cada secuencia semanal incluya una actividad formativa o evaluativa, según la matriz de diseño instruccional.


## Figuras y Diagramas Extraídos


![Logotipos de la Universidad del Rosario y de la Dirección de Educación Digital DED](./images/fig-01-logo-rosario-educacion-digital.png)

*Figura 01: Logotipos institucionales de la Universidad del Rosario y la Dirección de Educación Digital (DED).*
