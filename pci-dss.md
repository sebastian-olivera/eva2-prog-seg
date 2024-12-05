Code: pci-dss
Title: PCI DSS
Content: |
    ## Qué es PCI DSS: Una guía simplificada

    PCI DSS (Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago) es un conjunto de estándares de seguridad diseñados para prevenir el fraude relacionado con tarjetas de débito y crédito. Protege tanto los datos del titular de la tarjeta como la información sensible de autenticación.  El objetivo principal de PCI DSS es garantizar la gestión segura de estos datos, previniendo robos y fraudes.
    Obtener la certificación PCI DSS significa que una empresa ha cumplido con los requisitos del estándar,  demostrando su compromiso con la seguridad. Para lograrlo, las empresas son auditadas por una entidad autorizada o deben completar evaluaciones específicas. Esta certificación genera confianza en los clientes.
    PCI DSS surgió ante la necesidad de unificar los estándares de seguridad. Anteriormente, compañías como Mastercard, Visa, Discover y American Express, tenían sus propios estándares, lo que generaba confusión y complejidad para las empresas que procesaban transacciones de diferentes tarjetas.  Para simplificar este panorama, se creó un estándar único: PCI DSS. Esto mejoró sustancialmente el ecosistema de cumplimiento de seguridad en torno a los datos de las tarjetas.

    **¿A quién va dirigido PCI DSS?**
    Esta certificación es obligatoria para *cualquier* empresa que procesa, almacena o transmite datos de tarjetas de pago. Esto incluye entidades bancarias, comercios online como Amazon, AliExpress y eBay, y cualquier otra empresa involucrada en estos procesos, independientemente de si sus sistemas están en sus propias instalaciones o en la nube.
    El cumplimiento debe demostrarse periódicamente a auditores externos autorizados.  Sin embargo, las empresas que procesan menos de 80,000 transacciones al año pueden realizar una autoevaluación mediante un cuestionario.
    Existen cuatro niveles de cumplimiento basados en el volumen de transacciones anuales. Las exigencias de cumplimiento y auditoría varían según el nivel del comerciante. En algunos casos, la auditoría la realiza una empresa externa, mientras que en otros se utiliza la autoevaluación.
    El incumplimiento del estándar puede resultar en la pérdida de permisos, sanciones y auditorías forzosas.

    **¿Quién define PCI DSS?**
    El Consejo de Estándares de Seguridad de la Industria de Tarjetas de Pago (PCI SSC, por sus siglas en inglés) es el organismo responsable de establecer y mantener el estándar PCI DSS, incluyendo sus requisitos y contenido.

    **Los 12 requisitos de PCI DSS:**

    PCI DSS comprende doce requisitos clave:

    1. **Firewall:** Instalar, configurar y mantener un firewall para proteger el entorno donde se almacenan los datos de las tarjetas.

    2. **Contraseñas:** No usar contraseñas predeterminadas de fábrica en los sistemas.

    3. **Protección de datos almacenados:** Proteger los sistemas que almacenan datos de tarjetas.

    4. **Cifrado de transmisiones:** Cifrar la transmisión de datos de tarjetas a través de redes públicas.

    5. **Antivirus y Anti-malware:** Utilizar y mantener actualizados software antivirus y anti-malware.

    6. **Desarrollo seguro de sistemas:** Desarrollar y mantener sistemas seguros.

    7. **Control de acceso:** Restringir el acceso a los datos a las personas autorizadas y registrar todos los accesos.

    8. **Autenticación única:** Implementar credenciales de acceso únicas para cada usuario.

    9. **Acceso físico:** Restringir el acceso físico a los datos de las tarjetas.

    10. **Monitorización y rastreo:** Monitorizar y rastrear el acceso a la red y a los datos de las tarjetas.

    11. **Pruebas de seguridad:** Realizar pruebas de seguridad regulares.

    12. **Política de seguridad:** Mantener una política de seguridad de la información para toda la empresa.

    Los requisitos 1 y 2 se centran en la seguridad de la red. Los requisitos 3 y 4 protegen los datos de los titulares de tarjetas. Los requisitos 5 y 6 se refieren a la gestión de vulnerabilidades. Los requisitos 7, 8 y 9 se enfocan en el control de acceso.  Los requisitos 10 y 11 abordan la monitorización y las pruebas de seguridad. Finalmente, el requisito 12 establece la necesidad de una política de seguridad integral.
Questions:
  - Number: 1
    Description: "Qué significa PCI DSS y cuál es su propósito principal"
    Expected: "PCI DSS significa Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago. Su propósito principal es proteger los datos de las tarjetas de pago y prevenir el fraude, estableciendo un conjunto de estándares de seguridad para las empresas que manejan esta información."
    Score: 3

  - Number: 2
    Description: "A qué tipo de empresas afecta PCI DSS"
    Expected: "Afecta a cualquier empresa que procesa, almacena o transmite datos de tarjetas de pago. Esto incluye bancos, comercios online, y cualquier otra empresa involucrada en el manejo de estos datos, sin importar el tamaño o el método de almacenamiento (local o en la nube)."
    Score: 2

  - Number: 3
    Description: "Menciona tres ejemplos de datos que PCI DSS busca proteger."
    Expected: "Número de tarjeta, fecha de vencimiento, código de seguridad (CVV), nombre del titular, y cualquier información sensible de autenticación."
    Score: 2

  - Number: 4
    Description: "Por qué es importante la certificación PCI DSS para las empresas"
    Expected: "Demuestra el compromiso de la empresa con la seguridad de los datos de los clientes, genera confianza y evita posibles sanciones, multas y la pérdida de permisos para procesar pagos con tarjeta."
    Score: 1
    
  - Number: 5
    Description: "Describe brevemente tres de los doce requisitos de PCI DSS."
    Expected: "1. Firewall: Instalar, configurar y mantener un firewall para proteger el entorno donde se almacenan los datos de las tarjetas. 2. Contraseñas: No usar contraseñas predeterminadas de fábrica en los sistemas. 3. Protección de datos almacenados: Proteger los sistemas que almacenan datos de tarjetas."
    Score: 2
