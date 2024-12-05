Code: 3bsi
Title: Las Tres Bases de la Seguridad Informática
Content: |
  ## Las Tres Bases de la Seguridad Informática: Confidencialidad, Integridad y Disponibilidad

  Los datos son valores en bruto: números, medidas, textos, documentos. La información, en cambio, es lo que obtenemos al procesar y estructurar esos datos, dándoles significado y utilidad.  Manuales de procedimiento, datos de empleados, proveedores, clientes, facturación; todos son datos que, al organizarse, se convierten en información valiosa para una empresa.

  La seguridad de la información se basa en tres pilares fundamentales: **confidencialidad, integridad y disponibilidad**.  Estos pilares garantizan que la información se utilice de forma eficiente y segura, minimizando los riesgos.

  **1. Confidencialidad:**
  La confidencialidad asegura que solo el personal autorizado acceda a la información que le corresponde.  Protege nuestra privacidad, capacidad de maniobra y reputación, evitando que la información caiga en manos de cibercriminales, competidores u otras amenazas.

  Para garantizar la confidencialidad, se utilizan:
  * **Autenticación de usuarios:** Verificar la identidad de quien accede a la información.
  * **Asignación de privilegios:** Permitir a los usuarios operar solo con la información y las funciones que necesitan (ej. permisos de lectura/escritura).
  * **Cifrado de información (encriptación):**  Proteger la información, tanto en tránsito como almacenada, para que solo sea accesible con la clave correcta.

  La confidencialidad no solo protege nuestra información, sino también aquella de la que somos responsables, incluyendo datos protegidos por leyes de privacidad como la GDPR. Un ejemplo de violación de confidencialidad son las filtraciones de datos de empresas, bancos o gobiernos.

  **2. Integridad:**
  La integridad garantiza que la información no se pierda ni se vea comprometida, ya sea de forma accidental o intencionada. Trabajar con información errónea puede ser tan perjudicial como perderla. Incluso pequeñas alteraciones pueden llevar a errores acumulativos y malas decisiones.

  Para asegurar la integridad:

  * **Control del tráfico de red:** Detectar intrusiones.
  * **Políticas de auditoría:** Registrar quién accede a la información, cuándo y qué hace con ella.
  * **Sistemas de control de cambios:**  Verificar la integridad de los archivos (ej. mediante hashes).
  * **Copias de seguridad:** Recuperar la información a un estado anterior en caso de pérdida o manipulación.

  **3. Disponibilidad:**

  La disponibilidad asegura que la información esté accesible para quienes la necesitan, cuando la necesitan. De nada sirve la confidencialidad y la integridad si la información no está disponible.
  Para garantizar la disponibilidad:

  * **Acuerdos de Nivel de Servicio (SLA):**  Establecer compromisos de disponibilidad.
  * **Balanceadores de carga:** Distribuir el tráfico para evitar sobrecargas y mantener los servicios en línea.
  * **Copias de seguridad:** Restaurar la información en caso de pérdida.
  * **Medidas contra ataques DDoS:**  Mitigar el impacto de ataques de denegación de servicio que buscan interrumpir la disponibilidad.

  En resumen, la seguridad de la información se logra cuando:

  * Solo el personal autorizado accede a la información.
  * Se puede detectar y recuperar la información de manipulaciones.
  * Se garantiza un nivel de servicio y acceso a la información adecuado.
Questions:
  - Number: 1
    Description: Cuáles son los tres pilares de la seguridad informática y qué significan
    Expected: |
      Confidencialidad: Solo personal autorizado accede a la información. 
      Integridad: La información es precisa y no ha sido alterada. 
      Disponibilidad: La información está accesible cuando se necesita.
    Score: 3

  - Number: 2
    Description: Qué diferencia hay entre datos e información
    Expected: "Datos: Valores en bruto sin procesar (números, texto, etc.). Información: Datos procesados y organizados que tienen significado y utilidad."
    Score: 1

  - Number: 3
    Description: Describe una medida para garantizar la confidencialidad
    Expected: Cifrado de la información, autenticación de usuarios, asignación de privilegios.
    Score: 2

  - Number: 4
    Description: Por qué es importante la integridad de la información
    Expected: Porque trabajar con información errónea puede llevar a malas decisiones y ser tan perjudicial como perderla.
    Score: 2

  - Number: 5
    Description: Menciona un ejemplo de cómo se puede ver afectada la disponibilidad de la información
    Expected: Un ataque DDoS, un fallo de hardware, un error de software, correo electrónico bloqueado en listas negras.
    Score: 2
