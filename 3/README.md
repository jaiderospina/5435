---
title: "Organización de la asignatura   Propuesta jaider V3"
source_file: "Organización de la asignatura - Propuesta_jaider_V3.docx"
format: "docx"
converted_date: "2026-11-02T00:13:09.824Z"
extracted_images_count: 1
---

# Organización de la asignatura   Propuesta jaider V3

Fundamentos de programación segura y criptografía Básica


| Unidad 1. Programación segura y taxonomía de vulnerabilidades | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 1 | 1. La programación segura como problema de ingeniería | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • De la gestión del riesgo al código: de los controles a los requisitos de software Material de autoría propia — Presentación narrada • Ciclo de vida de desarrollo seguro ( Secure SDLC) y principios de diseño seguro OWASP (2019). ASVS 4.0, cap. V1 «Architecture, Design and Threat Modeling». https://owaspsamm.org/model/ https://top10.owasp.org/2025/es/0x00_2025-Introduction/ • Caso de software propio y protocolo de anonimización, confidencialidad e integridad académica Material de autoría propia — Cartilla (guía del caso y formato del protocolo de anonimización) | • Firma del protocolo de anonimización y confidencialidad (requisito, sin calificación) |
| - | 2. Taxonomía de vulnerabilidades del software | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • Vulnerabilidades de gestión de memoria: desbordamiento de búfer, use-after-free y errores de puntero Seacord (2013). Secure Coding in C and C++, caps. 2–4 (cadenas, subterfugio de punteros y memoria dinámica). [Enlace CRAI] • Inyección (SQL, NoSQL, comando, plantilla), validación de entrada, autenticación y gestión de sesiones OWASP (2021). OWASP Top 10: A01, A03 y A07. [Enlace CRAI] • CWE/SANS Top 25, MITRE: de la debilidad al CVE y al CVSS Material de autoría propia — Interactivo (ruta debilidad → CVE → CVSS) ( Fundamentación práctica ) • Explotación en entorno controlado y lecciones para el diseño defensivo Material de autoría propia — Cartilla (guía del laboratorio aislado) . | • Foro de crítica metodológica 2: clasificación de hallazgos del caso con OWASP/CWE |
| - | 3. Codificación segura y diseño defensivo | RAE 2. Analizar código fuente identificando vulnerabilidades de las taxonomías reconocidas (OWASP Top 10, CWE) y proponiendo correcciones conforme a prácticas de codificación segura. | • Prácticas de codificación segura, manejo de excepciones y registros ( logging ) seguros Howard y LeBlanc (2003). Writing  Secure Code (2.ª ed.), capítulos de principios de codificación defensiva. [Enlace CRAI] • Manejo  seguro de secretos OWASP. Cheat Sheet Series: Secrets Management. [Enlace CRAI] • Seguridad en dependencias y cadena de suministro: SBOM, versionado y selección de bibliotecas Center for Internet Security. CIS Software Supply Chain Security Guide. [Enlace CRAI] • Modelado de amenazas con STRIDE y superficie de ataque Material de autoría propia — Presentación narrada • Codificación asistida por IA generativa: oportunidades, riesgos y obligación de verificación Material de autoría propia — Podcast | • Entrega 1: análisis de vulnerabilidades del caso con taxonomía OWASP/CWE y correcciones propuestas  30 % |



| Unidad 2. Criptografía: fundamentos y aplicación correcta | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 2 | 4. Fundamentos de criptografía | RAE 1. Explicar los fundamentos de la criptografía aplicada —cifrado simétrico y asimétrico, hash, firmas digitales y PKI— seleccionando el mecanismo adecuado para cada requisito de seguridad y argumentando sus propiedades y límites. | • Objetivos de seguridad; cifrado simétrico (AES, ChaCha20) y modos de operación Aumasson (2018). Serious Cryptography, caps. 1, 4 y 5. [Enlace CRAI] • Criptografía asimétrica: RSA, Diffie-Hellman y curvas elípticas Aumasson (2018), caps. 10, 11 y 12. [Enlace CRAI] • Funciones hash y MAC: SHA-2, SHA-3, HMAC Aumasson (2018), caps. 6 y 7. [Enlace CRAI] • Firmas digitales, certificados, PKI y cadena de confianza Stallings (2022). Cryptography and Network Security (8.ª ed.), capítulos de firmas digitales y PKI. [Enlace CRAI] • Post-cuántica y rotación de algoritmos Aumasson (2018), cap. 14. [Enlace CRAI] Material de autoría propia — Cartilla interactiva (mapa de mecanismos según requisito de seguridad) | • Cuestionario formativo: selección del mecanismo según el requisito, con sus propiedades y límites (sin calificación) |
| - | 5. Criptografía aplicada: errores comunes y buenas prácticas | RAE 1. Explicar los fundamentos de la criptografía aplicada —cifrado simétrico y asimétrico, hash, firmas digitales y PKI— seleccionando el mecanismo adecuado para cada requisito de seguridad y argumentando sus propiedades y límites. RAE 3. Proponer e implementar controles criptográficos correctos en una aplicación (almacenamiento seguro de contraseñas, cifrado en tránsito y en reposo, firma y verificación), gestionando claves de manera apropiada y evitando los errores de implementación más comunes. | • Regla de oro: no diseñar protocolos propios; uso de bibliotecas estándar Aumasson (2018), cap. 2 (aleatoriedad) y cap. 8 (cifrado autenticado). [Enlace CRAI] • Almacenamiento seguro de contraseñas: salado, bcrypt , scrypt , Argon2 NIST (2018). SP 800-63B; OWASP Cheat Sheet Series: Password Storage. [Enlace CRAI] • Cifrado en tránsito: TLS 1.3, certificados y HSTS Aumasson (2018), cap. 13. [Enlace CRAI] • Cifrado en reposo: envelope  encryption , HSM/KMS Material de autoría propia — Presentación narrada • Ciclo de vida de claves y errores clásicos ( nonce reutilizado, RNG débil, comparaciones no constantes) NIST (2020). SP 800-57 Part 1 Rev. 5. [Enlace CRAI] Material de autoría propia — Interactivo (errores clásicos: detectar el fallo en fragmentos de código) | • Entrega 2: implementación de controles criptográficos en el caso —contraseñas, cifrado en tránsito y en reposo, gestión de claves— 35% |



| Unidad 3. Verificación, integración en el ciclo de vida y marco normativo | - | - | - | - |
| :--- | :--- | :--- | :--- | :--- |
| Unidad | Semana | RAE asociados | Temas y referencias (CRAI o material de autoría propia) | Actividad evaluativa |
| 3 | 6. Marco normativo, ética y comunicación técnica | RAE 4. Integrar prácticas de programación segura y pruebas de seguridad en el ciclo de vida del desarrollo de software, documentando decisiones técnicas y comunicándolas a equipos de desarrollo y a la alta dirección. | • Marco normativo colombiano: Ley 1273 de 2009, Ley 1581 de 2012 y Decreto 1377 de 2013 República de Colombia. Ley 1273/2009; Ley 1581/2012; Decreto 1377/2013. [Enlaces oficiales] • Ética del desarrollo seguro: divulgación responsable y límites de la experimentación Material de autoría propia — Podcast • Requisitos de seguridad en la contratación de software Material de autoría propia — Cartilla • Comunicación de hallazgos a equipos de desarrollo y a la alta dirección Material de autoría propia — Presentación narrada con ejemplo de informe y de resumen ejecutivo | • Entrega 3: informe final con integración de controles en el ciclo de vida —pipeline, pruebas y documentación técnica— ( 35 %) |
| - | 7. Verificación y pruebas de seguridad del software | RAE 3. Proponer e implementar controles criptográficos correctos en una aplicación (almacenamiento seguro de contraseñas, cifrado en tránsito y en reposo, firma y verificación), gestionando claves de manera apropiada y evitando los errores de implementación más comunes. RAE 4. Integrar prácticas de programación segura y pruebas de seguridad en el ciclo de vida del desarrollo de software, documentando decisiones técnicas y comunicándolas a la comunidad interesada (clientes, usuarios, equipos técnicos, auditores, entre otros). | • SAST, DAST y SCA: alcances y límites OWASP . ASVS 4.0, niveles de verificación. [Enlace CRAI] • Pruebas de penetración básicas y pruebas de seguridad en la API; fuzzing Material de autoría propia — Cartilla (guía de laboratorio) y Presentación narrada • Revisión de código y trabajo con hallazgos OWASP. Cheat  Sheet Series (lista de verificación de revisión de código). [Enlace CRAI] • Controles de seguridad en pipelines CI/CD ( DevSecOps ): puertas de calidad, umbrales y excepciones Center for Internet Security. CIS Software Supply Chain Security Guide. [Enlace CRAI] Material de autoría propia — Interactivo (anatomía de un pipeline DevSecOps ) | • Sustentación técnica tipo comité de arquitectura, en sesión sincrónica (15 %; requisito de aprobación) Laboratorio formativo: incorporar SAST y SCA al pipeline del caso (sin calificación) |


Bibliografía:

David Arboledas Brihuega. (2017). Criptografía sin secretos con Python. RA-MA Editorial.

https://research.ebsco.com/plink/16f0d9bf-1dea-31f3-9d30-d87ad97a8922

Solar, M., Villacura, J.-P., Cisternas Alvarez, F., & Dombrovskaia, L. (2024). Detectando un Espía con Criptografía Cuántica. Memoria Investigaciones En Ingeniería, 27, 200–219. https://doi.org/10.36561/ING.27.13

https://research.ebsco.com/plink/66390c5e-9fe9-34be-9b24-8e7abca134c5

Chopra, R., & Raheja, S. (2020). Design and analysis of algorithms. NEW AGE International Publishers.

https://research.ebsco.com/plink/3f802907-295a-3fc0-8acc-684cd170763d

Timi Omoyeni. (2023). Generative AI tools for developers: A practical guide. SitePoint.

https://research.ebsco.com/plink/73563086-5cff-32c9-bd24-df6e7f6194fb

Oppliger, R. (2021). Cryptography 101: From theory to practice. Artech House.

https://research.ebsco.com/plink/75828576-cd34-30b8-9b15-98f8f1b79b07

María Isabel González Vasco, & Ángel Luis Pérez Del Pozo. (2021). Criptografia esencial. RA-MA Editorial.

https://research.ebsco.com/plink/4999ed86-e8fb-32de-a0ce-7ba492faef20

Omar Ivan Trejos Buriticá, & Luis Eduardo Muñoz Guerrero. (2021). Introducción a la programación con Python. RA-MA, S.A. Editorial y Publicaciones.

https://research.ebsco.com/plink/3c3af267-e3dc-3e19-81cb-3d79b87d3af5

Dr. Gabriele Lanaro, Quan Nguyen, & Sakis Kasampalis. (2019). Advanced Python programming : Build high performance, concurrent, and multi-threaded apps with Python using proven design patterns. Packt Publishing.

https://research.ebsco.com/plink/9ac14f0b-4a08-384f-b8fd-8cdaa9e7cbba

Jit Sinha. (2025). Kickstart Python programming fundamentals. Orange Education Pvt Ltd.

https://research.ebsco.com/plink/65705cb8-5133-3a77-b8c8-af76d5dd7c69

Donald R. Franceschetti, P. (2018). Principles of programming & coding. Salem Press.

https://research.ebsco.com/plink/9a0c2d0f-7da4-3551-bdec-5dc4919c7a20

Bernie Fishpool, & Mark Fishpool. (2020). Software development in practice. BCS, The Chartered Institute for IT.

https://research.ebsco.com/plink/a232ffaf-f151-351b-9af3-6ddef991ff4a

Amany Fawzy Elgamal. (2024). Object-oriented programming. Cambridge Scholars Publishing.

https://research.ebsco.com/plink/56985ed4-9fa0-35b5-aa63-b2eb9c87fdf8


## Figuras y Diagramas Extraídos


![Figura 01 referente a image1](./images/fig-01-image1.png)

*Figura 01: Gráfico descriptivo extraído del documento*
