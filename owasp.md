Code: owasp
Title: OWASP y programación segura
Content: |
    Open Web Application Security Project (OWASP)
    El Open Web Application Security Project (OWASP) es una organización mundial sin fines de lucro, centrada en mejorar la seguridad del software. Su misión es hacer que la seguridad del software sea visible, para que las personas y las organizaciones puedan tomar decisiones informadas. Es una comunidad abierta dedicada a permitir que las organizaciones desarrollen, adquieran y mantengan aplicaciones confiables.
    Uno de sus proyectos más conocidos es el OWASP Top 10, un importante documento de concientización sobre la seguridad de aplicaciones web. Representa un amplio consenso sobre los riesgos de seguridad más críticos para las aplicaciones web.

    **1.1 OWASP Top 10**

    OWASP ofrece, de forma abierta y gratuita:

    * Herramientas y estándares de seguridad en aplicaciones
    * Libros sobre revisiones de seguridad en aplicaciones
    * Desarrollo de código fuente seguro y revisiones de seguridad en código fuente
    * Controles de seguridad estándar y bibliotecas
    * Información relevante para la programación segura.

    El Top 10 describe los diez riesgos de seguridad más relevantes en aplicaciones web según OWASP.  Esta lista se actualiza cada tres años; la versión actual es la de 2017.  [Se omite la tabla comparativa por ser extensa y ya estar explicada en detalle en las siguientes secciones]

    **1.2 OWASP Top 10 - 2017**

    Esta versión se basa en datos de más de 40 empresas especializadas en seguridad de aplicaciones y una encuesta a más de 500 personas. La información recopila vulnerabilidades de cientos de organizaciones y más de 100,000 aplicaciones y APIs.  Las 10 categorías principales se seleccionaron y priorizaron según su prevalencia, explotabilidad, detectabilidad e impacto.

    El OWASP Top 10 busca educar a desarrolladores, diseñadores, arquitectos, gerentes y organizaciones sobre las consecuencias de las debilidades de seguridad más comunes en aplicaciones web. También proporciona técnicas básicas de protección y orientación.

    [Se omiten las descripciones detalladas de cada vulnerabilidad del Top 10 (A1-A10) ya que están presentes en la transcripción original y se incluyeron en la corrección anterior].

    **1.3 OWASP ASVS**

    ASVS (Application Security Verification Standard) es un estándar de verificación de seguridad de aplicaciones web de OWASP.  Proporciona una base para probar los controles técnicos de seguridad y una lista de requisitos para un desarrollo seguro.

    Tiene dos objetivos principales:

    * Ayudar a las organizaciones a desarrollar y mantener aplicaciones seguras.
    * Permitir la alineación entre las necesidades y ofertas de servicios de seguridad, proveedores de herramientas y consumidores.

    El ASVS define tres niveles de verificación de seguridad:

    * **Nivel 1 (Oportunista):** Para cualquier software.  Cubre vulnerabilidades fáciles de descubrir, como las del OWASP Top 10.
    * **Nivel 2 (Estándar):** Para aplicaciones con datos sensibles.  Asegura que los controles de seguridad sean efectivos.
    * **Nivel 3 (Avanzado):** Para aplicaciones críticas (ej. militares, salud). Requiere un análisis de seguridad profundo.

    **1.4 Norma PCI-DSS: Checklist Self-Assessment**

    PCI-DSS (Payment Card Industry Data Security Standard) es la normativa internacional de seguridad para entidades que manejan datos de tarjetas de pago.  Establece un nivel básico de protección para minimizar fraudes y filtraciones de datos.

    El cumplimiento implica tres aspectos:

    1. **Manejo seguro de los datos:** Procesar y transmitir datos de tarjetas de forma segura.
    2. **Almacenamiento seguro:** Cifrado, vigilancia y control de acceso a los datos.
    3. **Validación anual:**  Cumplir con cuestionarios, escaneos de vulnerabilidades y auditorías.

    [Se omite la tabla de niveles PCI-DSS por estar explicada en la corrección anterior].

    **1.5 Modelamiento de Amenazas**

    Es una técnica para identificar amenazas, ataques, vulnerabilidades y contramedidas que podrían afectar una aplicación. Ayuda a dar forma al diseño, cumplir objetivos de seguridad y reducir riesgos.  Permite identificar:

    * Posibles amenazas y vulnerabilidades.
    * Gravedad de cada amenaza.
    * Técnicas de mitigación.
    * Protección de recursos TI.

    **7 metodologías principales de modelado de amenazas:**

    1. STRIDE (Microsoft):  Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege.
    2. DREAD: Damage potential, Reproducibility, Exploitability, Affected users, Discoverability.
    3. PASTA:  Proceso de siete pasos para alinear objetivos comerciales con requisitos técnicos.
    4. VAST:  Visual, Agile, and Simple Threat modeling.  Enfoque escalable para DevOps.
    5. TRIKE: Enfoque basado en el riesgo con un modelo de requisitos.
    6. OCTAVA (Carnegie Mellon):  Para el modelado de amenazas de ciberseguridad.
    7. NIST:  Centrado en datos, con un enfoque de cuatro pasos.

    **1.6 Modelo de Amenazas STRIDE**

    Descompone el sistema en componentes y analiza cada uno para determinar su susceptibilidad a las seis categorías de amenazas STRIDE.  Se proponen mitigaciones y el proceso se repite hasta alcanzar un nivel de riesgo aceptable.

    **1.7 Modelo de Seguridad SDL (Microsoft)**

    Es un proceso de control de seguridad orientado al desarrollo de software. Se centra en:

    * Anticipar fallas en el código.
    * Proteger todo el código, no solo componentes específicos.
    * Eliminar código y funciones obsoletas.
    * Reemplazar protocolos viejos.
    * Reconocer que el código fallará y reducir la superficie de ataque.
Questions:
  - Number: 1
    Description: Qué es OWASP y cuál es su principal objetivo
    Expected: OWASP (Open Web Application Security Project) es una organización sin fines de lucro dedicada a mejorar la seguridad del software. Su objetivo es hacer la seguridad del software visible para que individuos y organizaciones tomen decisiones informadas.
    Score: 3

  - Number: 2
    Description: Qué es el OWASP Top 10 y por qué es importante para los desarrolladores
    Expected: El OWASP Top 10 es un documento que lista los diez riesgos de seguridad más críticos en aplicaciones web. Es importante porque ayuda a los desarrolladores a comprender y mitigar las vulnerabilidades más comunes.
    Score: 4

  - Number: 3
    Description: Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017.
    Expected: | 
      Inyección: Ocurre cuando se envían datos no confiables a un intérprete como parte de un comando o consulta. 
      Pérdida de Autenticación: Cuando las funciones de autenticación y gestión de sesiones son implementadas incorrectamente, permitiendo a los atacantes comprometer cuentas de usuario.
    Score: 4

  - Number: 4
    Description: Qué es OWASP ASVS y cuáles son sus niveles de verificación
    Expected: |
      OWASP ASVS (Application Security Verification Standard) es un estándar para verificar la seguridad de las aplicaciones web. 
      Define tres niveles: 
      1. Oportunista
      2. Estándar
      3. Avanzado:
      cada uno con mayor profundidad en la verificación.
    Score: 4

  - Number: 5
    Description: Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS
    Expected: El Nivel 1 es un nivel básico para cualquier software, mientras que el Nivel 3 es el más alto y se reserva para aplicaciones críticas que requieren la máxima seguridad. El Nivel 3 implica un análisis mucho más exhaustivo.
    Score: 4

  - Number: 6
    Description: Qué es el modelado de amenazas y cuáles son sus beneficios
    Expected: Es un proceso para identificar amenazas, ataques, vulnerabilidades y contramedidas que podrían afectar una aplicación. Ayuda a mejorar el diseño, cumplir objetivos de seguridad y reducir riesgos.
    Score: 4

  - Number: 7
    Description: Nombra dos metodologías de modelado de amenazas.
    Expected: STRIDE, DREAD, PASTA, VAST, TRIKE, OCTAVA, NIST.
    Score: 3

  - Number: 8
    Description: Qué es el SDL y cómo ayuda a la seguridad del software
    Expected: SDL (Security Development Lifecycle) es un proceso de Microsoft para integrar la seguridad en el ciclo de vida del desarrollo de software. Ayuda a reducir el número y la gravedad de las vulnerabilidades.
    Score: 4
