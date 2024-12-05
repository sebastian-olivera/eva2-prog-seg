
Code: cvss
Title: Vulnerabilidades y exposiciones comunes CVE - CVSS y otros
Content: |
  **Programación Segura para Desarrollo - OWASP**

  **Aprendizaje Esperado de la Semana:**

  Implementan adaptación de *hardening* de sistemas, considerando listas de vulnerabilidades y exposiciones comunes, plan de parchado de *framework*, comunicaciones seguras y autentificación robusta:

  * 1.11 Adaptan vulnerabilidades y exposiciones comunes CVE y sistema de puntaje de vulnerabilidades comunes CVSS para la creación de un modelo de *hardening* de sistemas.
  * 1.12 Configuran un plan de parchado de *framework* de desarrollo y entornos seguros de sistemas operativos *hardenizados*, considerando requerimientos técnicos.
  * 1.13 Comprueban las comunicaciones seguras y la encriptación WS, SOAP y XML, de acuerdo con los requerimientos técnicos.
  * 1.14 Comprueban el uso de CAPTCHAs y la autenticación robusta centralizada en un entorno *hardenizado*.
  * 1.15 Demuestran autonomía en actividades y funciones especializadas en diversos contextos.

  **1. Vulnerabilidades y Exposiciones Comunes CVE**

  Al usar cualquier aplicación con acceso a internet, tanto usuarios como desarrolladores deben estar pendientes de la protección de la información.  Para protegernos, es importante conocer los peligros y amenazas.

  En seguridad informática existe la tríada de la seguridad: Integridad, Confidencialidad y Disponibilidad de los datos.  Para mantener estos aspectos estables, debemos conocer que las aplicaciones pueden ser vulnerables y, por lo tanto, tener amenazas que pueden eventualmente convertirse en riesgos.

  **1.1 ¿Qué es una vulnerabilidad?**

  Una vulnerabilidad es una debilidad o fallo en un sistema de información que pone en riesgo la seguridad de los datos y la información. Puede permitir que un atacante comprometa la integridad, disponibilidad o confidencialidad de la información. Es crucial corregir cualquier vulnerabilidad porque constituye un peligro potencial para la estabilidad y seguridad del sistema.

  **1.2 ¿Qué es una amenaza?**

  Una amenaza es una acción que aprovecha una vulnerabilidad para atentar contra la seguridad de un sistema de información.  Puede tener un efecto negativo en la organización, dependiendo del tipo de ataque (pasivo o activo). Las amenazas pueden clasificarse según su ámbito de acción: físicas, lógicas, de comunicaciones o a usuarios.

  **1.3 ¿Qué es un riesgo?**

  El riesgo es la probabilidad de que se materialice una amenaza o incidente de seguridad debido a una vulnerabilidad en la aplicación, causando pérdida de información y afectando la tríada de la seguridad.  El riesgo surge cuando existen vulnerabilidades en un sistema y además existe la amenaza (ej. un hacker).

  **1.4 Lista de vulnerabilidades y exposiciones comunes (CVE)**

  CVE (Common Vulnerabilities and Exposures) es una lista de nombres estandarizados para vulnerabilidades de seguridad conocidas públicamente. Cada vulnerabilidad tiene un código de identificación único. CVE define una vulnerabilidad como una debilidad en la lógica computacional que, al ser explotada, tiene un impacto negativo en la confidencialidad, integridad o disponibilidad. El CVE facilita el intercambio de datos en bases de datos de vulnerabilidades y herramientas de seguridad.

  **1.4.1 Ventajas del uso de CVE:**

  * Plataforma para reconocer vulnerabilidades conocidas.
  * Ayuda a diferenciar vulnerabilidades.
  * Base de datos en constante actualización.

  **2. Sistema de Puntaje de Vulnerabilidades Comunes (CVSS)**

  El CVSS (Common Vulnerability Scoring System) es un sistema de puntaje que estima el impacto de las vulnerabilidades.  Se usa para cuantificar la severidad que una vulnerabilidad representa para la organización. El CVSS utiliza una escala de 0 a 10 (0 = nula, 10 = crítica).

  Existen tres grupos métricos:

  * **2.1 Grupo Métrico Base:** Características intrínsecas a la vulnerabilidad (constantes en el tiempo).  Incluye vector de acceso, complejidad de acceso y autenticación.
  * **2.2 Grupo Métrico Temporal:** Características que cambian en el tiempo.  Incluye explotabilidad, nivel de remediación y reporte de confianza.  Es opcional.
  * **2.3 Grupo de Métrica de ambiente o entorno:** Características únicas y relevantes para el entorno del usuario.


  **3. Uso de Componentes con Vulnerabilidades Conocidas - OWASP A9:2017**

  El OWASP A9:2017 trata sobre el uso de componentes (bibliotecas, *frameworks*) con vulnerabilidades conocidas.  Si se explota un componente vulnerable, se puede perder información o el control del servidor.

  **4. Importancia de las Comunicaciones Seguras y la Encriptación:**

  **4.1 ¿Qué es encriptar o el proceso de encriptación?**

  La encriptación convierte información en ilegible mediante algoritmos, protegiéndola de accesos no autorizados. Se usa para proteger mensajes de texto, voz, imágenes y código.  SOAP, WS y XML son relevantes en este contexto:

  * **SOAP (Simple Object Access Protocol):** Protocolo para intercambiar información en servicios web.
  * **WS (Web Services):** Tecnología para intercambiar datos entre aplicaciones.
  * **XML (Extensible Markup Language):** Lenguaje de marcas para documentos con información estructurada.


  **5. Hardening en Sistemas**

  El *hardening* es una medida de seguridad para reducir la superficie de vulnerabilidad en un sistema, minimizando los puntos de acceso para posibles ataques.  Se busca un equilibrio entre un sistema inaccesible y uno completamente libre.  Implica mantener los servicios actualizados, eliminar software innecesario, cerrar puertos, usar *firewalls*, establecer políticas de contraseñas, encriptar datos, etc.

  **6. Test de Turing Público y Automático para Distinguir a los Ordenadores de Humanos (CAPTCHA)**

  Un CAPTCHA es una prueba para diferenciar humanos de ordenadores, protegiendo contra *spam* y el descifrado de contraseñas.

  **7. Autenticación Robusta Centralizada**

  La autenticación robusta requiere al menos dos factores de autenticación (algo que tiene, algo que sabe, algo que es) para verificar la identidad del usuario.
Questions:
  - Number: 1
    Description: Define vulnerabilidad, amenaza y riesgo en el contexto de la seguridad informática.
    Expected: "Vulnerabilidad: Debilidad o fallo en un sistema que pone en riesgo la seguridad. Amenaza: Acción que aprovecha una vulnerabilidad para atentar contra la seguridad. Riesgo: Probabilidad de que se materialice una amenaza."
    Score: 2

  - Number: 2
    Description: Qué es CVE y cuál es su propósito
    Expected: CVE (Common Vulnerabilidades and Exposures) es una lista estandarizada de nombres para vulnerabilidades de seguridad conocidas. Su propósito es facilitar la identificación y el intercambio de información sobre vulnerabilidades.
    Score: 1

  - Number: 3
    Description: Menciona tres ventajas del uso de CVE
    Expected: Facilita la identificación de vulnerabilidades conocidas, permite diferenciar vulnerabilidades, y es una base de datos en constante actualización.
    Score: 1

  - Number: 4
    Description: Que es CVSS y para qué se utiliza
    Expected: CVSS (Common Vulnerability Scoring System) es un sistema para cuantificar la severidad de una vulnerabilidad en una escala de 0 a 10.
    Score: 1

  - Number: 5
    Description: Describe los tres grupos métricos del CVSS
    Expected: "Base: Características intrínsecas de la vulnerabilidad. Temporal: Características que cambian en el tiempo (opcional). Ambiental: Características específicas del entorno del usuario."
    Score: 1

  - Number: 6
    Description: Explica el concepto de "componentes con vulnerabilidades conocidas" (OWASP A9:2017)
    Expected: Se refiere al uso de componentes de software (bibliotecas, frameworks) que tienen vulnerabilidades conocidas. Explotar estas vulnerabilidades puede comprometer la aplicación.
    Score: 1

  - Number: 7
    Description: Qué es la encriptación y cuál es su objetivo
    Expected: La encriptación convierte la información en ilegible para protegerla de accesos no autorizados. Su objetivo es asegurar que solo usuarios autorizados puedan acceder a la información.
    Score: 1
  - Number: 8
    Description: Qué significan las siglas SOAP, WS y XML
    Expected: "SOAP: Simple Object Access Protocol. WS: Web Services. XML: Extensible Markup Language."
    Score: 1
  - Number: 9
    Description: Qué es hardening y cómo se relaciona con la seguridad de sistemas
    Expected: Hardening es el proceso de asegurar un sistema reduciendo su superficie de vulnerabilidad. Se relaciona con la seguridad al minimizar los puntos de acceso para posibles ataques.
    Score: 2
  - Number: 10
    Description: Describe tres acciones comunes de hardening
    Expected: Mantener el software actualizado, eliminar software innecesario, cerrar puertos no utilizados, configurar firewalls, establecer políticas de contraseñas robustas, encriptar datos, establecer roles de usuario.
    Score: 2
  - Number: 11
    Description: Qué es un CAPTCHA y cuál es su función
    Expected: Un CAPTCHA es un test para distinguir humanos de ordenadores. Sirve para prevenir el abuso de servicios por parte de bots.
    Score: 1
  - Number: 12
    Description: Qué se entiende por "autenticación robusta centralizada"
    Expected: Es un sistema de autenticación que requiere al menos dos factores para verificar la identidad del usuario, aumentando la seguridad.
    Score: 1
