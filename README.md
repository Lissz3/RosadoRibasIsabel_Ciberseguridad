# Carrera Ciberseguridad en la Empresa
Realizada por Isabel Rosado.

----------

## Índice  
1. [Onboarding Becas Openwebinars](README.md#onboarding-becas-openwebinars)
2. [Onboarding en Ciberseguridad](README.md#onboarding-en-ciberseguridad)
3. [Curso de análisis y gestión del riesgo](README.md#análisis-y-gestión-del-riesgo)
4. [OSINT para fuga de datos empresariales](README.md#osint-para-fuga-de-datos-empresariales)
5. [Criptografía Simétrica y Asimétrica en la práctica](README.md#criptografía-simétrica-y-asimétrica)
6. [Seguridad de red en el ámbito corporativo: Capa 2 del modelo OSI](README.md#seguridad-de-red-en-el-ámbito-corporativo-capa-2-del-modelo-osi)
7. [Seguridad de red en el ámbito corporativo: Capas 3 y 7 del modelo OSI](README.md#seguridad-de-red-en-el-ámbito-corporativo-capas-3-y-7-del-modelo-osi)
8. [Curso de Triage informático](README.md#curso-de-triage-informático)
9. [Desarrollo seguro](README.md#curso-de-desarrollo-seguro)
10. [Introducción al Esquema Nacional de Seguridad](README.md#introducción-al-esquema-nacional-de-seguridad)

----------

## Onboarding Becas Openwebinars
Curso de introducción a la plataforma y a términos básicos dentro del mundo IT.

- **Examen** realizado: [Certificado curso de onboarding becas](Certificados/certificado_curso_de_onboarding_becas_openwebinars.pdf)

## Onboarding en Ciberseguridad
### Introducción y terminología
1. **Vulnerabilidad**

	Debilidad ante la posibilidad de sufrir un daño.
	Es lo que buscan los atacantes.
	Todo dispositivo tiene sus vulnerabilidades. Un dispositivo puede ser 100% seguro un día y que se descubran nuevas vulnerabilidades al día siguiente, es decir, *no existen los dispositivos 100% seguros*.
	
2. **Amenaza**

	Posibilidad de que se produzca una vulnerabilidad.
	Que una vulnerabilidad pueda llegar a explotarse.
	1. Amenazas **internas** o *insiders*:
	Proceden desde dentro de la organización

	2. Amenazas **externas** o *ciberdelicuencia*:
	Proceden desde fuera de la organización

3. **Ingeniería social**

	Manipulación para la obtención de información confidencial.
	Se basa en el "*eslabón débil*" de la cadena, es decir: el ser humano.
	- **Funcionamiento**:
		1. Llamada telefónica o conexión a internet.
		2. Falsas identidades, por ejemplo hacerse pasar por una compañía.
		3. Manipulación de la persona.
		4. Obtención de la información.

### Dispositivos - *qué conocer sobre ellos*
Un dispositivo es **cualquier** aparato que tenga una conexión a internet y que nos permite interactuar con personas.
Dentro de estos paratos electrónicos los más conocidos son orenadores, tablets o smartphones, pero otros como cámaras de fotos (*reflex*), cajeros automáticos(*ATMS*) o GPS's independientes también son vulnerables ante ataques dado que están conectados a internet, a pesar de que su seguridad no dependa de nuestras acciones.
	
1. **Sistemas operativos**  
	Existen diferencias entre los software y las app's pero son similares:
	
	- **Software**  
	 Aplicación o herramienta desarrollada para realizar una función o funciones en un dispositivo como ordenadores
	
	- **App**  
	 Se pueden definir de manera similar a software, pero para realizar su función o funciones suelen estar en dispositivos móviles o tablets.
	 Ambos pueden sufrir problemas de seguridad, por tanto ambos se deben utilizar de manera segura.
	
2. **Contraseñas**  
	Las contraseñas no se pueden definir como fuertes a simple vista.  
	Cosas a tener en cuenta para definir contraseñas fuertes:  
		- Longitud de caracteres largas (12 a 14 caracteres).
		- Mezcla entre mayúsculas y minúsculas.
		- Incluir números.
		- Incluir caracteres especiales.  
	Las contraseñas de cuentas y usuarios tienen que cambiarse habitualmente (cada 1-2 meses).
	
	3. **Dispositivos corporativos**  
	Cualquier dispositivo electrónico que nos facilite la empresa.
	La empresa marcará normas de uso correcto y unos límites de uso.
	Existen medidas de protección, dado que no son 100% seguros.  
	- ¿Por qué no son 100% seguros?  
	Apesar de que puedan llevar instalados sistemas de protección y sistemas antivirus, *la seguridad depende en gran medida del uso que le demos*.  
	Para evitar brechas de seguridad debemos mantener un aprendizaje continuo, no utilizarlo de manera personal, no usarlos para ocio o en RRSS.  
	Por defecto no acceder ni pulsar enlaces desconocidos.  
### Dispositivos BYOD

**B**ring **Y**our **O**wn **D**evice.
Permiso para usar dispositivos personales como ordenadores o smartphones para el trabajo.

Tipo de impactos:  
1. **Corporativos**  
	- Pérdida de seguridad en los dispositivos, dado que no nos pueden obligar a instalar herramientas de monitorización.
	- Menor control sobre los dispositivos.
	- En caso de brecha, es más difícil de identificar ya que es complicado saber de qué dispositivo procede la brecha sin herramientas de monitorización.
	- Se utiliza también de manera personal.  
2. **Personales**  
	- Es el dispositivo personal, y entregamos información privada nuestra cuando accedemos al sistema de la empresa.
	- En caso de avería puede necesitar una inversión por parte de la persona.
	- Puede existir algún tipo de obligación de normas de uso por parte de la empresa a pesar de ser un dispositivo personal.
	- Cada persona es responsable de su propio dispositivo y las medidas de seguridad aplicadas.

### Usuarios y contraseñas

Un usuario es un **alias o seudónimo** utilizado para identificarse en un sistema. Debe ir siempre acompañado de una contraseña.
La unión usuario+contraseña corresponde a las credenciales de acceso, es decir, aporta seguridad.

1. **Qué función realiza**  
	Acreditación virtual de acceso, identificación de usuarios y autenticación de usuarios, es decir, una identificación de una persona física en un sistema virtual.

2. **Gestores de contraseñas**  
	Nos permite guardar usuarios y contraseñas de forma segura.

3. **Cambios de contraseña**  
	Se deben cambiar las contraseñas cada 30-90 días tiempo sin repetir contraseñas que hemos utilizado anteriormente.


### Backups o copias de seguridad
Se utilizan para recuperar documentos, en caso de borrado por error y en caso de ataque informático, recuperar información.  
Realizar habitualmente copias.  
Hacer copias en dispositivos distintos.  
Se realizan con nuestras credenciales, es decir, la información solo es accesible para el usuario que ha realizado la copia.


### Carpetas compartidas
Carpeta a la que se puede acceder desde distintos perfiles de acceso.  
Sirven para compartir y trabajar sobre una misma carpeta y realizar actualizaciones de ficheros en tiempo real para todas las personas

- Peligros:  
	1. Acceso por varias personas.
	2. La información puede extraerse sin ser consciente.
	3. Robo de información.
	4. Entrada de información maliciosa.
	5. Corrupción de información importante.  

- Recomendaciones:
	1. Compartir carpetas únicamente cuando sea estrictamente necesario
	2. Proteger las carpetas mediante permisos de acceso
	3. Crear copias de seguridad de la información

### Navegación segura
Un navegador es una aplicación que nos permite movernos por Internet
Su objetivo es permitir la visualizacón correcta de páginas web, pudiendo también mostrar recursos locales y remotos

Un navegador seguro es un navegador web con medidas de seguridad extra, ayudando así a prevenir actividad no autorizada
Utilizan métodos proactivos, actuando de manera preventiva y no reactiva
Ayuda con las cookies "maliciosas" y protegen la identidad.

- Precacuciones a tomar:
	1. No confiar por tener un navegador seguro instalado.
	2. Concienciarnos y aprender a navegar de forma segura.
	3. Inlcuir protección con herramientas de seguridad.  

- Actualizaciones en navegadores:
	1. Necesitan ser actualziados.
	2. Es una aplicación más que va sufriendo cambios.  

- Extensiones en navegadores:
	1. Son pequeños programas instalados en el navegador
	2. Hay que tener precaución con lo que se instala, dado que algunas pueden buscar un funcionamiento que no se indica
	3. No es recomendable tener un gran número de ellas, ya que puede perjudicarel funcionamiento del navegador
	4. Se pueden instalar verificando que no es maliciosa

- URLS o direcciones de internet:
	1. Una URL es el nombre a través del que nos conectamos a una página.
	2. Se compone de 3 partes principales:  
		- **Protocolo** (https) hay que verificar que el protocolo es seguro
		- **Dominio** o nombre web (google.com)
		- **Subdominio** (se encuentra entre el protocolo y el dominio)

- Cómo reconocer urls seguras e inseguras:
	1. Nunca estar 100% seguros de una dirección.
	2. Verificar que la dirección está escrita correctamente.
	3. Antes de pulsar un enlace, verificar donde redirige.
	4. Verificar que el protocolo es https.

- Una URL **insegura** suelen ser direcciones no reconocibles, que no corresponden a un nombre de empresa, contienen caracteres alfanumericos y el protocolo no es https, si no http.  

Que la web esté aplicando https no implica 100% seguridad dentro de ella.  
Una dirección https puede ser segura en la comunicación (es decir, que nuestra información no pueda ser interceptada por terceros) pero que la página web realice guardados de nuestra información sensible para usarla en su beneficio.  

Hay páginas web como [**_VirusTotal_**](https://www.virustotal.com/gui/home/upload) que hacen un checkeo sobre URLS para comprobar que no son maliciosas.  

- Codigos QR  
	1. Evolución de código de barras que almacena información
	2. Pueden contener enlaces maliciosos.
	3. Conexiones que no conocemos.
	4. Hay que verificar los enlaces detrás de los códigos QR con herramientas como **QR Scanner**.

- Certificados
Permite la identificación del remitente y ayuda a verificar al propietario de la web.  
_Se puede comprobar en los candados de los navegadores web (a la izquierda de la url)_
 
### Correo electrónico seguro
Es el equivalente al correo ordinario de manera digital, es decir, se utiliza para enviar y recibir información entre un emisor y un receptor.
Se puede enviar información en el mensaje como texto, archivos adjuntos, entre los cuales entran imágenes, documentos, presentaciones, informes, etc. 

- Precauciones
 1. Remitentes desconocidos.  
Es mejor no abrir los emails de remitentes desconocidos dado que podemos darle información sobre que nuestra cuenta está activa.
 2. En el envío de información confidencial
 3. Spam.
 4. Protección de la cuenta.  

- Pishing:  
Ténicas que persiguen engañar a la victima mediante la ingeniería social para que accedamos a enlaces o robar información confidencial.  

  - Tipos de pishing:
	1. Correo electrónico
	2. Vishing (Pishing a través de voz)
	3. Smishing (Pishing a través de sms)
	4. Carta nigeriana (Recibir premios, defunción de familiares lejanos, etc.)  

- Documentos adjuntos en el correo:
	1. Ficheros que vienen enlzados a un mensaje
	2. Pueden ser de distintos formatos (documentos de texto, hojas de cálculo, imágenes...)
	3. No hay una respuesta 100% acertada acerca de su seguridad.  

- Peligros:
	1. Pueden contener información maliciosa.
	2. Robo de información.
	3. Provocar la descarga de software adicional.

- Recomendaciones:
	1. Por defecto no descargar ni abrir documentos adjuntos.
	2. Verificar que el remitente es correcto y el documento es seguro.
	3. Si sospechamos, aún pareciendo un remitente correcto, puede existir suplantación de identidad.

### Descargas de internet
Obtención de cualquier dato desde la web y hacernos con ello (imágenes, streaming, descarga de software y app's, ficheros adjuntos del email)
Durante la navegación por Internet pueden existir descargas de las que no seamos conscientes.

### Seguridad en las descargas de internet
Por defecto, debemos desconfiar de la información compartida en internet
Fuentes conocidas:
- Emails internos de la empresa
- Carpetas compartidas corporativas
- Webs conocidas y verificadas

Fuentes desconocidas:
- Emails de emisores desconocidos
- Repositorios de internet
- Webs de dudosa seguridad y fiabilidad

### Precacuciones a tener en cuenta para las descargas de internet
- Verificar la procedencia del fichero
- Analizar con sistema de Antiviruos los ficheros antes de abrirlos o ejecutarlos
- Ante cualquier duda, no descargar

### Bloqueo de sesiones
Una sesión está relacionada con nuestra usuario+contraseña.
Cuando se accede a un sistema, se crea la sesión de usuario.
Permanece activa durante todo el uso del sistema.

Por tanto no debemos acceder con nuestras credenciales en otros dispositivos y si lo hacemos cerrarlas antes de irnos.
Bloquear la sesión siempre que no estemos delante del ordenador.

### Datos sensibles
Un dato sensible es aquel que afecta a la privacidad de la persona:
- Opiniones políticas
- Origen racial
- Religión
- Información médica
- ...

Deben ser protegidos con medidas de seguridad fuertes.
El visionado de la información solo puede hacerlo personal autorizado.
La filtración de datos puede conllevar multas


###	Notificación de incidencias de Ciberseguridad

Un incidente de ciberseguridad es cuando sucede un problema que afecta a la seguridad virtual de la empresa.
Ejemplos: Ataques con virus informático, borrado de información, etc.

Un trabajador de manera voluntaria puede crear incidentes de ciberseguridad:
- Subiendo información confidencial a Internet
- Ceder credenciales de acceso a otra persona
- Instalación de programas descargados de Internet
- Instalación de software ilegal

De manera involuntaria:
- Suplantación de identidad
- Robo de credenciales de acceso
- Caer en una estafa y facilitar datos
- Fraude del CEO (Pishing + ingeniería social para hacerse pasar por el CEO).

Como notificar estos incidentes:
- En cada empresa se debe notificar a los trabajadores como realizar estas notificaciones.

No indicarlo puede traer peores consecuencias, y a la hora de exponerlo hay que ser lo mas transparente posible.

###	Desconexión de la red
La red se refiere a:
- Red cableada
- Red wifi

Si un dispositivo no es desconectado de la red:
- Siguen enviando información a la red aunque no se este activamente utilizando
- Abre una posible brecha de seguridad
- No ser consciente de lo que está sucediendo

Recomendaciones
- Desconexión directa cuando no se está activamente utilizando

### Cierre de sesión
Consiste en dejar nuestra sesión de usuario libre, pero el dispositivo queda liberado

- Así nadie pueda utilizar con nuestra sesión
- El diopositivo queda diposible para que otra persona pueda iniciar sesión con sus credenciales
- En aplicaciones, seguramos que nuestro usuario no ha quedado iniciado
  
Recomendaciones
- Cerrar sesiones cuando vayamos a dejar de utilizar el dispositivo fisico.
- En aplicaciones en internet, cerrarla siempre que vayamos a dejar de necesitar su uso

### Apagado del dispositivo
Si no lo hacemos puede ser posible objetivo de ciberdelincuentes, de un uso indebido sin consentimiento o ejecución de arhivos sin ser consciente

### Conclusiones
Qué se ha visto:
- Conceptos esenciales en Ciberseguridad
- Peligros del uso y la navegación sin seguridad

Que se ha aprendido:
- Uso seguro de dispositivos electrónicos
- Navegación segura por internet
- Uso correcto del correo electrónico
- Actualización continua de los sistemas y aplicacion

- **Examen** realizado: [Certificado curso de Onboarding en Ciberseguridad : Bienvenid@ a bordo](Certificados/certificado_curso_de_onboarding_en_ciberseguridad__bienvenid@_a_bordo.pdf)  

----------

## Análisis y gestión del riesgo
### Terminología
1. **Análisis de riesgos informáticos**

	Proceso por el cual se identifican todos los activos de la organización, qué cosas tienen valor comenzando por la información y siguiendo por todo aquello que da soporte a la información (instalaciones, sistemas de información, personas, etc) y sus vulnerabilidades y qué amenazas podrían impactarle, con el objetivo de establecer los controles y estrategias para gestionarlo.  
	Estas amenazas se relacionan con el riesgo, que es el impacto que podría tendría dicha amenaza sobre el activo junto con la probabilidad de que eso ocurra.
	
2. **Riesgos de seguridad de información**
	
	Éstos deben ser considerados en el contexto de negocio, y las interrelaciones con otras funciones de negocios. Todos los sistemas de información, todas las sedes de la organización y las personas están para darle valor al negocio. La función de análisis de riesgo no es una función a parte del negocio si no para facilitar el negocio.
	
3. **Activo**

	Cualquier cosa que tenga valor para nuestra organización, puede ser desde información, una aplicación de negocio o la más importante: las personas.
	
3. **Impacto**

	Degradación sobre un activo. Cuánto valor perderíamos, qué daño causaria (reputacional, perdida de clientes, etc).

3. **Probabilidad**

	Cuán a menudo puede ocurrir una amenaza.

3. **Riesgo**

	La fórmula clásica de calcular el riesgo es el **impacto** multiplicado por la **probabilidad**.

### Una **amenaza** explota una **vulnerabilidad**, la cual afecta a un **activo** y provoca un **impacto**.  

4. **Análisis del riesgo**
	
	Proceso por el cual identificamos las amenazas, vulnerabilidades y activos, y le damos esa valoración de impacto y probabilidad y logramos un mapa del riesgo de nuestra organización.
	
5. **Gestión o tratamiento del riesgo**
	
	Continuación del análisis del riesgo, es decir, una vez tenemos nuestro mapa trazado, qué debemos hacer para tratarlo.

5. **Informe de estado de riesgo**
	
	Informe que recoge cómo está la organización en un momento dado con los controles establecidos.
	
5. **Informe de evaluación de salvaguardas**
	
	Informe que recoge cómo están funcionando los controles establecidos.
	
6. **Impacto residual**
	
	Impacto que queda después de implementar los controles que tenemos actualmente.

6. **Riesgo acumulado**
	
	Cuanto riesgo se ha acumulado respecto a nuestra situación actual.

7. **Riesgo potencial o inherente**
	
	Riesgo si no tenemos en cuenta las salvaguardas.
	
8. **Riesgo residual**
	
	Riesgos que quedan después de implementar las salvaguardas.
	
9. **Apetito, Tolerancia y Capacida del riesgo**
	
	Cuánto riesgo está dispuesto a asumir una organización de cara a hacer su negocio.
	
10. **Salvaguarda (Control, medida de seguriad o contramedida)**
	
	Qué estamos poniendo para prevenir que un riesgo suceda, para detectar que un riesgo ha sucedido y para recuperarnos de esa amenaza.
	
11. **Valor de un activo**
	
	Un activo puede tener valor persé o valor agregado por otra serie de cosas. También se tiene en cuenta qué daño causaria (reputacional, perdida de clientes, costes de recuperarse de la amenaza, etc).

12. **Gestión de riesgos TI**
	
	Proceso contínuo o cíclico que busca proteger todos los activos de la organización, especialmente la información, en su proceso o tratamiento en los sistemas de información.
	
13. **Gestión en proyectos TI**
	
	En la introducción de nuevos paradigmas o nuevas tecnologías podemos tener nuevas amenazas y vulnerabilidade y es necesario poder lidiar con ellas. En este caso como los proyectos son a corto plazo, se tiene que aplicar una gestión de riesgo cada pocos meses.

### Gobierno, Riesgo y Cumplimiento.  
Es una estrategia para administrar el gobierno general de una organización, la administración de riesgos empresariales y el cumplimiento de las regulaciones. Una estrategia bien planitifacada mejora la toma de decisiones, se optimizan las inversiones en TI, se eliminal los silos y se reduce la fragmentación entre las divisiones y departamentos.  

1. **Gobierno**
	
	Garantiza que las actividades de la organización como la gestión de operaciones de TI, estén alineadas de manera que apoyen los objetivos empresariales de la organización.
	
2. **Riesgo**

	Asegurar que cualquier riesgo u *oportunidad* asociados con las actividades de la organización se identifican y abordan de manera que apoyen los objetivos de negocio de la organización.

3. **Cumplimiento**
	
	Cumplimiento generalmente regulatorio, legal y normativo pero también puede ser de normas o cumplimiento de condiciones contractuales con nuestros clientes.  

Las organizaciones desarrollan este marco para el liderazgo, organización y operación de las áreas de TI de la organización para asegurar que apoyan y permiten los objetivos estratégicos de la organización.  

4. **Gobierno de riesgo**

	Framweork que introduce los artefactos de gobiernos requeridos para la gestión (políticas, procedimientos, procesos, etc), así como otros elementos requeridos (p. ej, apetito del riesgo). Da soporte a la **gestión del riesgo**. Esta parte define qué hacer y como hacerlo y la gestión del riesgo es la que lo hace.

5. **Gestión del riesgo**

	Mecanismo que identifica, cualifica y evalúa el riesgo para determinar dónde se requiere mayor o menor gobierno. Retroalimenta a la organización con el mapa de riesgos actual de forma que se pueda decidir sobre la mejor estrategia de tratamiento del riesgo en base a las reglas establecidas.  
	
El gobierno y la gestión del riesgo deben estar alineadas con los objetivos corporativos como los financieros, estratégicos, de reputación, etc con la finalida de convertirse en un facilitador del negocio en lugar de un centro de coste.

- **Test repaso** realizado: Análisis y gestión del riesgo - Introducción.  
![image](https://user-images.githubusercontent.com/93931447/229547404-9c357b18-2ebc-4dbd-83d1-b9c18f843181.png)

### Introducción a la gestión del riesgo

Para poder gestionar el riego primero se necesita contar con un "framework" o marco para el mismo dentro de la organización, que define los roles y responsabilidades, qué politicas y procedimientos vamos a tener, que recuersos, el apetito o tolerancia al riesgo, etc.  La principal salida es la estrategia de gestión del riesgo que permite dirigir cómo las organizaciones pretenden valorar el riesgo, responder a este y monitorizar el mismo.  La estrategia también incluye cualquier decisión a nivel estratégico y las consideraciones sobre cómo los riesgos a las operaciones y activos serán gestionadas por el comité de dirección y la gerencia senior.

1. **Marco de gestión ISO 27005**

	Estándar internacional que se ocupa de la gestión de riesgos de la seguridad de información. Suministra directrices para la gestión de la seguridad de la información en una empresa, apoyando particularmente los requisitos de sistema de gestión de seguridad de la ISO 27001. La ISO 27001 un marco de sistemas de gestion de la seguridad de la información, es decir, nos permite definir la seguridad de la información como un proceso homogéneo estable y continuo en el tiempo, un proceso de mejora contínua. Para ello se requiere establecer un marco de gestión del riesgo para definir de forma estándar y repetible como vamos a gestionar el riesgo.  Busca un enfoque centrado en el "Risk Management" para Tecnologías de la Información, adecuándose a la ISO 31000 que hace referencia a la gestión del riesgo empresarial general, en subconjunto con la ISO 27005.  

	La gestión del riesgo de la información de una organización está incluído dentro de la gestión de todo el riesgo (financiero, social, de cumplimiento, etc).  

	Este marco tiene diferentes aspectos:

	1. **Identificación del riesgo:**  
		- Identificación de activos  
		- Identificación de amenazas  
		- Identificación de controles existentes  
		- Identificación de vulnerabilidades  

	2. **Análisis del riesgo:**  
		- Metodologías  
		- Evaluación de las consecuencias  
		- Evaluación de la probabilidad de los incidentes  
		- Determinación del riesgo  
		- Evaluación de riesgos  
	
	La norma 27005 no solo se centra en la valoración y determinación del riesgo, si no que también comprende de tratamiento de riesgo o aceptación, comunicación y consulta y monitorización y revisión. Hace todo el ciclo de gestión del riesgo.  

2. **Estándares NIST 800-39 y 800-30**
	
	Su propósito es proporcionar una guía para la organización de riesgos de seguridad de la información. Otro factor importante es proporcionar orientación para desplegar un sistema integrado para toda la organización del programa para la gestión de riesgos de seguridad de información.

	![image](https://user-images.githubusercontent.com/93931447/230739851-cea6d180-e9aa-423b-9455-60bb10580212.png)

	1. **Estándar NIST 800-39**

		Establece un marco y proceso para la gestión del riesgo de sistemas de información en la organización.

	2. **Estándar NIST 800-30**

		Es, específicamente, una guía para realizar la evaluación del riesgo en TI.

3. **Definicion del marco de gestión del riesgo**

	Este marco se va basar en el marco de gestión **NIST 800-39**.  
	Hay diferentes niveles de responsabilidad:
	
	1. **Nivel 1 de responsabilidad**
		
		Los líderes de la organización junto con la colaboración del responsable del riesgo deben defeinir el marco de riesgo organizacional, inlcuyendo el tipo de decisiones soportadas, por ejemplo: qué respuestas al riesgo vamos a tomar, cómo y bajo qué condiciones se valorará el riesgo para dar soporte a las decisiones sobre el mismo de forma regular: cada cuánto, ante cambios de impacto, cuales serían estas condiciones... También cómo se va a monitorizar el riesgo, hasta qué nivel de detalle, de qué forma, con qué frecuencia, etc.  
		En resumen, establece el modelo **general**, las restricciones generales, el apetito del riesgo general y la metodología entre otros.
		
	2. **Nivel 2 de responsabilidad**
	
		Esta es la capa intermedia de gestión, es decir, los responsables de áreas y procesos. En este nivel los propietarios de los servicios o procesos aplicarán la **comprensión** del marco organizacional del riesgo para dirigir sus preocupaciones específicas a sus funciones de negocio.  
		Éstos deben enfocar el modelo general dentro de su área o proceso.
		
	3. **Capa 3**
	
		Esta capa pertenece a los responsables de los programas, propietarios de sistemas informáticos y los proveedores comunes de controles (por ejemplo, el área de ciberseguridad) aplican su entendimiento del marco de riesgo de la organización en base a cómo los decisores en las capas 1 y 2 decidieron gestionar el riesgo.
		
	
	Sin embargo, para realizar una definición del marco de gestión del riesgo hay que tener un trabajo previo hecho:
	
	- Identificar las asunciones que afectan a cómo el riesgo se evalúa, se responde y se monitoriza en la organización.
	- Identificar las restricciones para la realización de las actividades de evaluación, respuesta y monitorización del riesgo dentro de la organización, como pueden ser:
		- Limitaciones financieras.
		- Requisitos legales, regulatorios y/o contractuales.
		- La cultura organizacional.
	- Identificar el nivel de tolerancia al riesgo de la organización.
	- Identificar las prioridades y compensaciones consideradas por la organización para la gestión del riesgo. 

	**Estos marcos tan complejos se tienen que aplicar, sobretodo, en grandes empresas.**
	
	4. **Aplicación en organizaciones pequeñas y medianas _(PYMES)_**
		
		En éste tipo de organizaciones o en aquellas con poco nivel de madurez respecto a la gestión del riesgo, el marco puede establecerse con una línea básica y seguir madurando desde ahí, éstas mismas líneas pueden ser, por ejemplo:
		- Metodologías de análisis del riesgo, incluyendo valores posibles para la probabilidad e impacto.
		- Catálogo de activos y amenazas.
		- Catálogo de potenciales salvaguardas.
		- Tolerancia del riesgo simplificada.
		
4. **Alineación con el negocio**
	
	En el proceso de identificación del riesgo es necesario que se consulte a los principales líderes de la organización con objeto de saber qué activos son especialmente importantes para ellos, qué procesos de transformación sufrirá en el corto y medioplazo la organización, cuáles son los escenarios de amenaza/riesgo que les preocupan de verdad, etc. Con este conocimiento será másfácil adaptar la identificación de activos y amenazas y alinearse con el negocio.
	
5. **Cultura del riesgo**
	
	- Es necesario tener una cultura del riesgo que permita reportar, escalar e intervenir los posibles daños o aprovechar las oportunidades.
	- La definición de cultura del riesgo abarca los valores, las creencias, las actitudes y el conocimiento sobre el riesgo que se tiene en el interior de una organización.
	- Es importante que esta cultura del riesgo de ciberseguridad sea instruida dentro de la cultura del riesgo general de la organización, dado que es parte del riesgo laboral.
	- Una cultura de riesgos también involucra a los cibernéticos, siendo necesario aquí definir líneas de accion específica en tres áreas:
		- El uso de una metodología alineada con la estrategia de operación.
		- Planes flexibles.
		- Líneas de comunicación con los grupos.
		
	Cada una de las líneas de gestión de riesgos debe estar alineada con los valores, metas y objetivos de la compañía, de esta forma será más fácil que los colaboradores estén preparados ante cualquier posible problema al que se enfrente la organización y hará más fácil que acepten esta cultura del riesgo.
	
5. **Registro del riesgo**

	El registro del riesgo es un documento o herramienta donde se registran todos los nuevos riesgos que afecten a la organización de forma que en todo momento se pueda saber el estado de riesgo de la mismo. Es un repositorio centralizado de todos los riegos.  
	Debería ser actualizado de forma regular, tras cada evaluación del riesgos, con cada reunión del comité del comité deriesgos, con los resultados del monitoreo del riesgo y su tratamiento, etc.  

	Por cada riesgo se debería recopilar la siguiente información:  
	- Identificador único
	- Fecha de detección
	- Probabilidad
	- Impacto
	- Nivel de riesgo
	- Propietario
	- Acciones/Salvaguardas de tratamiento
	- Acción de contigencia (reacciones ante la amenaza si se hace real)
	- Progreso de las acciones
	- Estado

## Evaluación del riesgo
### Introducción
El análisis del riesgo ayuda a las personas encargadas a la toma de decisiones y a entender la gestión de riesgos y cómo éstos pueden afectar a la consecución de sus objetivos y a la capacidad de eficiencia de controles ya implantados.

Es la parte del proceso de gestión de riesgos donde conocemos e inspeccionamos los riesgos, las amenazas, las probabilidades y su impacto.

Los procedimientos de identificación del riesgo pueden contener:  
- Procedimientos en base a evidencias  
*Por ejemplo, revisión de datos anteriores.*  

- Enfoques metodológicos del equipo  
*Los expertos identifican los riesgos a través de una serie de preguntas.*  
	
- Métodos de razonamiento inductivo  
*Un razonamiento inductivo es una forma de razonamiento en que la verdad de las premisas apoyan la conclusión, pero no la garantizan (Todos los cuervos observados hasta ahora son negros - Por ello todos los cuervos son negros).*
		
En esta primera fase de la metodología se identifican de forma sistemática las posibles causas concretas de los riesgos empresariales de seguridad, así como los diversos y posibles efectos que debe afrontar la organización 

### Métodos y herramientas para el análisis de riesgo (I)
Se deben utilizar una serie de herramientas y métodos que facilitarán el análisis de la organización entre los cuales, los más comunes son:    
1. **Checklists**  
	Catálogo de preguntas de posibles amenazas o lista previamente desarrollada de las mismas. Un ejemplo es el catálogo de amenazas de **MAGERIT**.
	
2. **Entrevistas**  
	Se realizan entrevistas con expertos de la organización y/o externos para la identificación de los riesgos.
	
3. **Análisis Delphi**  
	Se crean entrevistas y cuestionarios anónimos, individuales y de conjunto, que se distribuirán todas las personas de los diferentes grupos de expertos dotados de un conocimiento amplio en temas de gestión de riesgos. Luego se recopila esa información y se distribuye a todo el mundo sin decir de donde procede la misma para evitar influencias de unos sobre otros. La idea final es llegar a un consenso entre los grupos.
	
4. **Informes de inteligencia externos**  
	Fuera de las organizaciones existen varios organismos públicos y privados, tanto sin ánimo de lucro como comerciales que se dedican a recopilar información  sobre nuevas amenazas o de indicadores para detectar estas amenazas.
	Por un lado se dispone de feeds de ciberinteligencia que alertan de nuevo malware, vulnerabilidades y ataques, junto con posibles indicadores de
compromiso **(IoCs)** para su detección automática mediante herramientas (como SIEM o un EDR). 
	Por otro lado, existen organizaciones llamadas **ISACs** (Information
Sharing and Analysis Centers) que proveen de recursos centralizados para la recopilación de información sobre amenazas y que permiten una comunicación
bidireccional con sus miembros (de forma que se retroalimenten entre ellos), ofreciendo información sobre experiencias en diferentes causas raíz, incidentes y
amenazas, así como la compartición de experiencias, conocimiento y análisis realizados. Estos ISACs suelen ser sectoriales: por ejemplo, en el ámbito bancario llamado **FSISAC**.
	
5. **Análisis what-if**  
	Este análisis e usa en la etapa preliminar de la gestión cuando se comienzan a identificar los riesgos.
	Consiste en programar reuniones con expertos que conozcan en detalle un área / servicio / proceso concreto. En la reunión inicial se plantean interrogantes para evidenciar riesgos futuros. Las reuniones siguientes son para encontrar causas, consecuencias y acciones. Se basa en imaginas casos que impactarían en la organización y validar su probabilidad e impacto final.
	
### Métodos y herramientas para el análisis de riesgo (II)
Existen otros métodos más avanzados para empresas muy maduras e incluso en algunos casos especificas para sectores.  
1. **Análisis preliminar de riesgo (APR)**  
	Identifica posibles riesgos al inicio de un proyecto.
	
2. **Cinco porqués**  
	Mediante trabajo grupal, se presenta un problema y se plantean preguntas repetitivas que lleven a descifrar la causa raíz.
	
3. **FMEA (Failure mode and effecive analysis)**  
	Identifica, clasifica y elimina anticipadamente los problemas de los proyectos y de los procesos de una empresa. Comienza mediantee la identificación de errores, los cuales después se clasifican según una puntuación obtenida dependiendo de su frecuencia, gravedad y detección. Después de haberlos clasificado y priorizado, se establecen los problemas más graves para atenderlos de manera inmediata.
	
4. **Matrix SWOT (Strenghts, Weaknesses, Oportunities and Threats)**  
	Consiste en el análisis de fortalezas, debilidades, oportunidades y amenazas. Comienza con un análisis internos por el cual se identifican las fortalezas y los puntos débiles del negocio. En el contexto externo se identifican las oportunidades y amenazas.	
	
5. **Análisis del árbo de fallas**  
	Se inicia con un evento no deseado y se determinan todas las maneras en las que podría ocurrir. Una vez mostrados gráficamente en un diagráma de arbol lógico, se pasa a considerarse las posibilidades de formas de reduciar o eliminar las posibles causas/fuentes, etc.
	
6. **Diagramas causa-efecto (o Ishikawa)**  
	Dado que un efecto puede tener un número de factores que se pueden agrupar en distintas categorias, los cuales se identifican a menudo a trvaés del intercambio de ideas y se muestran en una estructura de "espina de pescado", dando a conocer la raíz del problema y los posibles cuellos de botella en los procesos.
	
7. **Cuestionario de análisis de riesgos**  
	Se elaboran una serie de preguntas para definir la probabiliadad de que sucedan eventos de impacto. Cada uno de los inerrogantes tocan cuestiones que pueden implicar algún riesgo. Una vez la lista está creada, deve revisarse y complementarse de acuerdo con cada proyecto o proceso.
	
8. **Gráfico de flujo de procesos**  
	Herramienta que muestra gráficamente la secuencia de funcionamiento de un proceso, determinando asi el flijo de actividades de una empresa. Se utiliza nomenclatura estandarizada por organizaciones como la ISO y la ANSI, facilitando su compresión independientemente del proceso descrito. De esta manera se podrán detectar potenciales problemas y amenazas en dichos pasa que afectarían al proceso.
	
9. **Análisis Modal de Fallos y Efectos (AMFE)**  
	Identifica y analiza fallos potenciales, mecanismos y los efectos de los mismos. Se utuliza, entre otras cosas, para el diseño de componentes y productos, sistemas, procesos de fabricación y montaje, servicio y software.
	
10. **Análisis funcional de operatividad (HAZOP)**  
	Proceso general de identificación de riesgos para definir posibles desviaciones del rendimiento esperado o deseado. Se utiliza para detectar situaciones de inseguridad en plantas industriales, debido a la operación o a los procesos productivos.
	
11. **Análisis de capas de protección (LOPA)**    
	Permite la evaluación de controles así como su eficacia.
	
12. **Análisis de Montecarlo**  
	Mediante una simulación matemática compleja, aproxima el resultado de cálculos de los que no se pueden obtener una solución exacta. Es un método que se utiliza par realizar estimaciones en caso de que existan parámetros que muestran variablidad. De esta manera, se generan multitud de simulaiones con diferentes variaciones en las variables de forma aleatoria de forma que se pueda obtener una representación de los valores más probables.

### Análisis de impacto de negocio **(BIA)**
Tiene como principal objetivo identificar las necesidades del negocio en términos de recuperación.
Un aspecto importante a tener en cuenta en la elaboración de un BIA son los tiempos.

![image](https://user-images.githubusercontent.com/93931447/232259329-43f8cd54-3ac2-42b0-9a30-f74b509f6a5b.png)

1. **RTO (Recovery Time Objective)**  
Tiempo de recuperación de las actividades que hemos identificado bajo unas condiciones mínimas aceptables. Por ejemplo, supongamos que el Responsable del Departamento de Administración nos indica que, en caso de que fallara la plataforma que soporta las aplicaciones para la generación y emisión de la nómina, se deberían recuperar el servicio en un plazo máximo de 24h. En este caso, estableceríamos que el RTO asociado a dicho proceso es de 24h.

2. **MTD (Maximum Tolerable Downtime)**  
Tiempo máximo tolerable de caída el cual nos determina el tiempo que puede estar caído un proceso antes de que se produzcan efectos desastrosos en la compañía y repercuta en el negocio. Volviendo al caso anterior, supongamos que el proceso de gestión de nóminas no debe estar interrumpido por un periodo superior a 48h. En este caso, estableceríamos que el MTD asociado a dicho proceso es de 48h.

3. **RPO (Recovery Point Objective)**  
El grado de dependencia de la actualidad de los datos determina la cantidad máxima de información que se podría perder sin llegar a tener consecuencias inaceptables, formando parte de las políticas de respaldo definidas por la organización. En este sentido, imaginemos que el Responsable del Departamento de Administración nos indica que podrían tolerar una pérdida de información siempre y cuando no se perdieran los datos generados en más de un día completo. Por lo tanto, estableceríamos que el RPO es de 24h.

Por cada servicio o proceso analizado se debería obtener la siguiente información:  

- Identificación y nombre del servicio / proceso  
- Descripción del mismo  
- Datos de contacto del resposable de negocio y del técnico  
- Procesos o servicios que dependen de este  
- Procesos o servicios de los que depende este  
- Árbol de interrelaciones entre los servicios / procesos de la organización  
- Proveedores críticos  
- RTO, RPO y MTD
- Matriz de impacto indisponibilidad servicio / procesos  
  
La información obtenida en la elaboración del BIA se validará con los distintos departamentos involucrados. Adicionalmente, contrastaremos los requisitos de
recuperación con la capacidad de recuperación de los sistemas que intervienen en la prestación de servicios / procesos. 
En última instancia, se deberán presentar las conclusiones al comité de dirección para hacerlos partícipes y así obtener su respaldo de cara a afrontar nuevos proyectos para mejorar la capacidad de recuperación actual.  
  
El BIA es un requisito básico de cara a la evaluación de riesgo, dado que nos permitirá entender mejor el impacto en la disponibilidad de las diferentes amenazas así como poder establecer salvaguardas acordes al impacto y a la criticidad de los diferentes servicios / procesos afectados.

### Identificación de activos
Como mínimo, la evaluación del riesgo deberá determinar los siguientes elementos:  
  
   ![image](https://user-images.githubusercontent.com/93931447/232259886-c7e37a8f-ebfa-4b46-83dc-32d4476d2de5.png)

El primer paso será identificar los activos, así como las amenazas que podrían impactar en los mismos y las vulnerabilidades que pueden ser explotadas para hacer
realidad estas amenazas. A continuación veremos como se puede realizar el modelado de esto basada en la metodología MAGERIT v3 (metodología de acceso público
creada para su uso en las administraciones públicas españolas y en las organizaciones privadas que les prestan servicios, y que se ha convertido en un estándar de facto en España). 
En un sistema de información hay 2 cosas esenciales:
- La información que maneja
- Los servicios que presta  

Estos activos esenciales marcan los requisitos de seguridad para todos los demás componentes del sistema.  
Subordinados a dicha esencia se pueden identificar otros activos relevantes:    
- Datos que materializan la información.  
- Servicios auxiliares que se necesitan para poder organizar el sistema.  
- Las aplicaciones informáticas (software) que permiten manejar los datos.  
- Los equipos informáticos (hardware) y que permiten hospedar datos, aplicaciones y servicios.  
- Los soportes de información que son dispositivos de almacenamiento de datos.  
- El equipamiento auxiliar que complementa el material informático.  
- Las redes de comunicaciones que permiten intercambiar datos.  
- Las instalaciones que acogen equipos informáticos y de comunicaciones.  
- Las personas que explotan u operan todos los elementos anteriormente citados.  
    
Los activos esenciales son la información y los servicios prestados; pero estos activos dependen de otros activos más prosaicos como pueden ser los equipos, las mcomunicaciones, las instalaciones y las frecuentemente olvidadas personas que trabajan con aquellos.  

Por ello aparece como importante el concepto de “dependencias entre activos”. Se dice que un “activo superior” depende de otro “activo inferior” cuando la materialización de una amenaza en el activo inferior tiene como consecuencia un perjuicio sobre el activo superior.  

Aunque en cada caso hay que adaptarse a la Organización objeto del análisis, con frecuencia se puede estructurar el conjunto de activos en capas, donde las capas
superiores dependen de las inferiores:  
1. **Activos esenciales:**
	- Información que se maneja  
	- Servicios prestados  
	  
2. **Servicios internos:**
	- Estructuran ordenadamente el sistema de información
	  
3. **El equipamiento informático:**
	- Aplicaciones (software)  
	- Equipos informáticos (hardware)  
	- Comunicaciones  
	- Soportes de información: discos, cintas, etc.  
	  
4. **El entorno: activos que se precisan para garantizar las siguientes capas:**
	- Equipamiento y suministros: energía, climatización, etc.  
	- Mobiliario  
	- Servicios subcontratados a terceros  
	- Instalaciones físicas (edificios, CPDs, etc).  

5. **El personal:**
	- Usuarios
	- Operadores y administradores  
	- Desarrolladores.

### Identificación de amenazas

El siguiente paso consiste en determinar las amenazas que pueden afectar a cada activo. Las amenazas son “cosas que ocurren”. Y, de todo lo que puede ocurrir, interesa lo que puede pasarle a nuestros activos y causar un daño.
El capítulo 5 del Catálogo de Elementos (MAGERIT V3) presenta una relación de amenazas típicas.  
  
1. **De origen natural: Hay accidentes naturales (terremotos, inundaciones, ...). Ante esos avatares el sistema de información es víctima pasiva, pero de todas formas tendremos en cuenta lo que puede suceder.**  
	- Fuego.  
	- Daños por agua.  
	- Desastres naturales.  
  
2. **Del entorno (de origen industrial): Hay desastres industriales (contaminación, fallos eléctricos, ...) ante los cuales el sistema de información es víctima pasiva; pero no por ser pasivos hay que permanecer indefensos.**
	- Fuego.  
	- Daños por agua.  
	- Desastres industriales (explosiones, sobrecarga eléctrica, contaminación química, etc).  
	- Contaminación mecánica como polvo, suciedad, vibraciones, etc.  
	- Contaminación electromecánica: interferencias de radio, eléctricas, etc.  
	- Avería de origen físico o lógico como fallos en equipos o programas.  
	- Corte del suministro eléctrico.  
	- Condiciones inadecuadas de temperatura y/o humedad.  
	- Fallo de servicios de comunicaciones (intencionados o accidentales).  
	- Interrupción de otros servicios y suministros esenciales como papel, toner, refrigerante, etc.  
	- Degradación de los soportes de almacenamiento de la información.  
	- Emanación electromagnética (se puedan interceptar datos de forma remota, como leer emanaciones de una pantalla o un procesador o vibraciones de una conversación telefónica en un crsital). Ésta, aún pudiendo ser muy compleja de realizar, existen equipamientos y atacantes que son capaces de hacerlo.  
  
3. **Causadas por las personas de forma accidental: Las personas con acceso al sistema de información pueden ser causa de problemas no intencionados, típicamente por error o por omisión.**  
	- Errores de los usuarios.  
	- Errores de los administradores.  
	- Errores de monitorización como falta de registros, registros incompletos, registros incorrectamente fechados, registros incorrectamente atribuidos, etc.  
	- Errores de configuración.  
	- Deficiencias de la organización (cuando no está claro quién tiene que hacer exactamente qué y cuándo, incluyendo tomar medidas sobre los activos o informar a la jerarquía de gestión).  
	- Difusión de software dañino (como malware, ransomware, etc).  
	- Errores de (re-)encaminamiento en dispositivos de red.  
	- Errores de secuencia (alteración accidental del orden de los mensajes transmitidos).  
	- Escapes o fugas de información (llega a personas que no debería sin que se haya modificado, por ejemplo por envío de correo a destinatario incorrecto, incontinencia verbal).  
	- Alteración accidental de la información.  
	- Destrucción de información.  
	- Vulnerabilidades de los programas (software).  
	- Errores de mantenimiento / actualización de programas (software).  
	- Errores de mantenimiento / actualización de equipos (hardware).  
	- Caída del sistema por agotamiento de recursos (DoS/DDoS).  
	- Pérdida de equipos.  
	- Indisponibilidad del personal.  
  
4. **Causadas por las personas de forma deliberada: Las personas con acceso al sistema de información pueden ser causa de problemas o ataques intencionados, bien con ánimo de beneficiarse indebidamente, bien con ánimo de causar daños y perjuicios a los legítimos propietarios.**  
	- Manipulación de los registros de actividad (log).  
	- Manipulación de la configuración.  
	- Suplantación de la identidad del usuario.  
	- Abuso de privilegios de acceso.  
	- Uso no previsto (juegos, consultas personales en internet, etc).  
	- Difusión de sw dañino.  
	- [Re-]encaminamiento de mensajes.  
	- Alteración de secuencia.  
	- Acceso no autorizado.  
	- Análisis de tráfico (sin necesidad de entrar a analizar el contenido de las comunicaciones, es capaz de extraer conclusiones a partir del análisis del origen, destino, volumen y frecuencia de los intercambios).  
	- Repudio (origen, recepción y/o entrega).  
	- Interceptación de información (escucha).  
	- Modificación deliberada de la información.  
	- Destrucción de información.  
	- Divulgación de información.  
	- Manipulación de programas.  
	- Manipulación de los equipos.  
	- Denegación de servicio.  
	- Robo.  
	- Ataque destructivo (vandalismo, terrorismo, acción militar, etc).  
	- Ocupación enemiga.  
	- Indisponibilidad del personal.  
	- Extorsión.  
	- Ingeniería social.  

### Identificación de vulnerabilidades
MAGERIT no incluye un catálogo de vulnerabilidades, dado que estas pueden ser muy variadas y una lista completa sería muy exhaustiva. Por ello, se recomienda trabajar con las amenazas y validar si por cada una de ellas que pueda afectar a la organización existen vulnerabilidades que las harían posibles.  
Desde el estándar ISO 27001 se dispone de un catálogo de vulnerabilidades generalista que podría servir como base para el trabajo (sirva más como ejemplo que como un "catálogo completo"):
- Interfaz de usuario complejas.  
- Contraseñas predeterminadas no modificadas.  
- Eliminación de medios de almacenamiento sin eliminar datos.  
- Sensibilidad del equipo a los cambios de voltaje.  
- Sensibilidad del equipo a la humedad, temperatura o contaminantes.  
- Inadecuada seguridad del cableado.  
- Inadecuada gestión de capacidad del sistema.  
- Gestión inadecuada del cambio.  
- Clasificación inadecuada de la información.  
- Control inadecuado del acceso físico.  
- Mantenimiento inadecuado.  
- Inadecuada gestión de red.  
- Respaldo inapropiado o irregular.  
- Inadecuada gestión y protección de contraseñas.  
- Protección física no apropiada.  
- Reemplazo inadecuado de equipos viejos.  
- Falta de formación y conciencia sobre seguridad.  
- Inadecuada segregación de funciones.  
- Mala segregación de las instalaciones operativas y de prueba.  
- Insuficiente supervisión de los empleados y vendedores.  
- Especificación incompleta para el desarrollo de software.  
- Pruebas de software insuficientes.  
- Falta de política de acceso o política de acceso remoto.  
- Ausencia de política de escritorio limpio y pantalla clara.  
- Falta de control sobre los datos de entrada y salida.  
- Falta de documentación interna.  
- Carencia o mala implementación de la auditoría interna.  
- Falta de políticas para el uso de la criptografía.  
- Falta de procedimientos para eliminar los derechos de acceso a la terminación del empleo.  
- Desprotección en equipos móviles.  
- Falta de redundancia, copia única.  
- Ausencia de sistemas de identificación y autenticación.  
- No validación de los datos procesados.  
- Ubicación vulnerable a inundaciones.  
- Mala selección de datos de prueba.  
- Copia no controlada de datos.  
- Descarga no controlada de Internet.  
- Uso incontrolado de sistemas de información.  
- Software no documentado.  
- Empleados desmotivados.  
- Conexiones a red pública desprotegidas.  
- Los derechos del usuario no se revisan regularmente.  

## Evaluación del riesgo
1. **Valoración de activos (I)**  
	- La valoracón se puede ver desde la perspectiva de la **necesidad de proteger**.  
	- El valor puede ser propio o acumulado. Se dice que los activos inferiories en un esquema de dependencias, acumulan el valor de los activos que se apoyan en ellos.  
	- El valor nuclear suele estar en la información que el sistema maneja y los servicios que se prestan (activos denominados esenciales), quedando los demás activos subordinados a las necesidades de explotación y protección de lo esencial.  
	- De un activo cabe valorar:
		1. Su **confidencialidad** (*¿Qué daño causaría que lo conociera quien no debe?*)  
		2. Su **integridad** (*¿Qué perjuicio causaría que estuviera dañado o corrupto?*)  
		3. Su **disponibilidad** (*¿Qué perjuicio causaría no tenerlo o no poder utilizarlo?*)  

	En sistemas dedicados a servicios de la sociedad de la información como puedan ser los de administración electrónica o comercio electrónico, el conocimiento de los actores es fundamental para poder prestar el servicio correctamente y poder perseguir los fallos (accidentales o deliberados) que pudieran darse.  
	- De los activos esenciales cabe valorar:  
		1. Su **autenticidad** (*¿Qué perjuicio causaría no saber exactamente quien hace o ha hecho cada acción?), tanto de los de servicios (autenticidad del usuario) como de los datos (autenticidad de quien accede a los datos para escribir o, simplemente, consultar*)  
		2. La **trazabilidad** del uso del servicio (*¿Qué daño causaría no saber a quién se le presta tal servicio? O sea, ¿quién hace qué y cuándo?*)  

2. **Valoración de activos (II)**
	La valoración es la determinación del coste que supondría recuperarse de una incidencia que destrozara el activo.
	Hay muchos factores a considerar, entre ellos:
	- Coste de reposición
	- Coste de mano de obra
	- Lucro cesante (*cuánto dinero estamos dejando de ingresar porque un servicio no esté disponible o haya sido comprometido*)
	- Capacidad de operar
	- Sanciones por incumplimiento de la ley u obligaciones contractuales
	- Daños a otros activos, propios o ajenos
	- Daño a personas
	- Daños mediambientales  

	La valoración puede ser cuantitativa (*cantidad numérica*) o cualitativa (*en algún tipo de escala de niveles, por ejemplo bajo, medio o alto*). Los criterios más importantes a respetar son:  
	1. La **homogeneidad**: es importante poder comparar valores aunque sean de diferentes dimensiones a fin de poder combinar valores propios y valores acumulados, así como poder determinar si es más grave el daño en una dimensión o en otra.
	2. La **relatividad**: es importante poder relativizar el valor de un activo en comparación con otros activos.
	
	Casi todas las dimensiones mencionadas anteriormente permiten una valoración simple, cualitativa o cuantitativa, salvo la disponibilidad.

3. **Valoración de las amenazas**  
	Cuando un activo es víctima de una amenaza, no se ve afectado en todas sus dimensiones, ni en la misma cuantía.
Una vez determinado que una amenaza puede perjudicar a un activo, hay que valorar su influencia en el valor del activo, en dos sentidos:  
	![image](https://user-images.githubusercontent.com/93931447/232327495-9bb22cbd-fc79-44b3-b173-9e63dfb1e9d9.png)
	1. La degradación mide el daño causado por un incidente en el supuesto de que ocurriera. 
	La degradación se suele caracterizar como una fracción del valor del activo y así aparecen expresiones como que un activo se ha visto “totalmente degradado”, o “degradado en una pequeña fracción”. Cuando las amenazas no son intencionales,
probablemente baste conocer la fracción físicamente perjudicada de un activo para calcular la pérdida proporcional de valor que se pierde. Pero cuando la amenaza es intencional, no se puede pensar en proporcionalidad alguna pues el atacante puede causar muchísimo daño de forma selectiva.  
	2. La probabilidad de ocurrencia es más compleja de determinar y de expresar. A veces se modela de forma cualitativa por medio de alguna escala nominal (*alto, medio y bajo*) o a veces (en organizaciones con una mayor madurez), de forma numérica (*asumiendo que 1 es 1 a vez al año de ocurrencia, 100 sería a diario o 1/100 cada siglo*).
	- Determinación del impacto potencial:  
	Se denomina impacto a la medida del daño sobre el activo derivado dde la materialización de una amenaza.  
	Conociendo el valor de los activos (en varias dimensiones) y la desgradación que causan las amenazas, es direto derivar el impacto que estas tendrían sobre el sistema. La única consideración que queda hacer es relativa a las dependencias entre activos.  
		1. **Impacto acumulado**  
		Se tiene en cuenta:  
			- Su valor acumulado
			- Las amenazas a las que está expuesto  
		Se calcula para cada activo, por cada amenaza y en cada dimensión de valoración, siendo una función del valor acumulado y de la degradación causada:  
			- El impacto es tanto mayor cuando mayor es el valor propio o acumulado sobre un activo  
			- El impacto es tanto mayor cuanto mayor sea la degradación del activo atacado  
		2. **Impacto repercutido**  
		Se tiene en cuenta:  
			- Su valor propio  
			- Las amenazas a que están expuestos los activos de los que depende  
		Se calcula para cada activo, de igual manera que en el impacto acumulado. Según los impactos:
			- El impacto es tanto mayor cuanto mayor es el valor propio de un activo  
			- El impacto es tanto mayor cuanto mayor sea la degradación del activo atacado  
			- El impacto es tanto mayor cuanto mayor sea la dependencia del activo atacado  
		El impacto repercutido al calcularse sobre los activos que tienen valor propio, permite determinar las consecuencias de las incidencias técnicas sobre la misión delsistema de información. Es pues una presentación gerencial que ayuda a tomar una de las decisiones críticas de un análisis de riesgos: **aceptar un cierto nivel de riesgo**.  
4. **Determinación del riesgo potencial (I)**
	Se denomina riesgo a la medida del daño probable sobre un sistema. Conociendo el impacto de las amenazas sobre los activos, es directo derivar el riesgo sin más que tener en cuenta la probabilidad de ocurrencia. Por lo general se calcula multiplicando el impacto por la probabilidad, si bien para cada organización se puede adaptar esta
formula:  
	![image](https://user-images.githubusercontent.com/93931447/232328991-58b7fe51-6605-4b54-b054-afe4d4f4581e.png)
	- Zona 1: Riesgos muy probables y de muy alto impacto.  
	- Zona 2: franja amarilla: cubre un amplio rango desde situaciones improbables y de impacto medio, hasta situaciones muy probables pero de impacto bajo o muy bajo.  
	- Zona 3: riesgos improbables y de bajo impacto.  
	- Zona 4: riesgos improbables pero de muy alto impacto.  
4. **Determinación del riesgo potencial (II)**
Así mismo, y en base a las dependencias se pueden calcular dististintos tipos de riesgos:  
	1. **Riesgo acumulado**  
	Impacto acumulado por probabilidad de ocurrencia.
	El riesgo acumulado, al calcularse sobre los activos que soportan el peso del sistema de información, permite determinar las salvaguardas de que hay que dotar a los medios de trabajo: protección de los equipos, copias de respaldo, etc.  
	2. **Riesgo repercutido**  
	Impacto repercutido por probabilidad de ocurrencia.
	El riesgo repercutido, al calcularse sobre los activos que tienen valor propio, permite determinar las consecuencias de las incidencias técnicas sobre la misión del sistema de información. Es pues una presentación gerencial que ayuda a tomar una de las decisiones críticas de un análisis de riesgos: aceptar un cierto nivel de riesgo.
	3. **Agregación de riesgos**  
	Las organizaciones pueden utilizar la agregación de riesgos para juntar diferentes riesgos discretos o de bajo nivel dentro de un riesgo más general o de alto nivel.
	También se puede utilizar la agregación para gestionar eficientemente el alcance y escala de las evaluaciones del riesgo que involucran múltiples SI y áreas/servicios/procesos con relaciones específicas y dependencias entre dichos elementos.
	La agregación debe realizarse bajo ciertas condiciones:
		- Puede agregarse el riesgo repercutido sobre diferentes activos.
		- Puede agregarse el impacto acumulado sobre activos que no sean dependientes entre sí, y no hereden valor de un activo superior común.
		- No debe agregarse el riesgo acumulado sobre activos que no sean independientes, pues ello supondría sobre ponderar el riesgo al incluir varias veces el valor acumulado de activos superiores.
		- Puede agregarse el riesgo de diferentes amenazas sobre un mismo activo, aunque conviene considerar en qué medida las diferentes amenazas son independientes y pueden ser concurrentes.
		- Puede agregarse el riesgo de una amenaza en diferentes dimensiones.

5. **Modelos cuantitivos y cualitativos**
	 ![image](https://user-images.githubusercontent.com/93931447/232580763-95e96250-cd65-4100-bbe0-a8521bc3332b.png)

7. **Escenarios de riesgo, modelado de amenazas y metodologías de análisis del riesgo**  
	1. **Escenarios de riesgo**  
		La estimación, prevención y reducción de riesgos es la clave para evitar pérdidas y desastres en cualquier organización. Uno de los pasos para lograr estos osbjetivos es la construcción de una serie de escenarios de riesgos, amenazas y vulnerabilidades. Su objetivo principal es tener una visión global de los riesgos, roles e interacciones para identificar prioridades en el tratamiento de riesgo. Ayudan a los profesionales a realizar las preguntas correctas y prepararse para lo inesperado.  
		Para ello se pueden tomar 2 aproximaciones:  
		- De arriba a abajo:  
			En esta aproximación se comienza con los objetivos de negocio globales y se realiza un análisis de los escenarios de riesgos más probables y
relevantes que podrían afectar a dichos objetivos.  
		- De abajo a arriba:  
			En esta aproximación se comienza con un conjunto genérico de escenarios para definir escenarios más específicos y concretos para la organización.  
		Una aproximación de cómo desarrollar estos escenarios sería:  
		![image](https://user-images.githubusercontent.com/93931447/232583759-37ab93d1-4e39-4fe3-b51e-6d283f42538b.png)
	2. **Modelado de amenazas**  
		Conjunto de técnicas que permiten analizar las potenciales amenazas que un desarrollo de software podría tener con el fin de asegurar que las mismas son tratadas mediante controles.  
		Los pasos para crear un modelo de amenazas son:
		1. Crear una descripción de la arquitectura: utilizar diagramas y tablas para documentar la arquitectura, incluyendo subsistemas, fronteras de confianza (*donde la información abandona zonas que se consideran seguras*) y flujo de datos.  
		2. Descomponer la aplicación: Descomponer la arquitectura de la aplicación, incluyendo la capa de red y el diseño de infraestructura, para crear un perfil de seguridad para la aplicación.  
		3. Identificar las amenazas: Utilizar la información de los pasos 1 y 2 y la mentalidad de un atacante para identificar las amenazas más importantes para el contexto y el escenario del sistema.  
		4. Documentar las amenazas: Utilizar plantillas predefinidas para asegurarnos de que no nos olvidamos ningún tipo de infomración importante.
		5. Asignar prioridades a las amenazas: Utilizar una calificación de amenazas para centrarse en las áreas donde existe mayor vulnerabilidad y riesgo.
		Para la identificación y documentación de las amenazas existen diferentes modelos. Uno de los más conocidos y utilizados es el modelo STRIDE creado por Microsoft.
			- **S**poofing - *suplantación de identidad de usuario*
			- **T**ampering - *modificación indebida*
			- **R**epudiation
			- **I**nformation Disclosure - *brecha de privacidad o filtración/divulgación de información*
			- **D**enegation of Service o *DoS*
			- **E**levation of Privileges
	3. **Metodologías de análisis del riesgo**
		Además de la metodología MAGERIT, la cual ha sido desarrollada por el Consejo Superiro de Administración Electrónica  y publicado por el Ministerio de Administraciones Públicas español, existen otras metodologías que pueden ser utilizadas:  
		- OCTAVE  
		- Estándar Intenacional ISO/IEX 27005  
		- MEHARI  
		- CRAMM  
		- NIST 800-30
		
## Informe de evaluación del riesgo
Este informe es el resultado del trabajo ralizado durante la evaluación del riesgo.  
Recoge todas las evidencias recopiladas y las conclusiones obtenidas sobre el entorno de riesgo, las amenazas encontradas, su valoración en impacto y probabilidad y el mapa de riesgo de la organización.  
1. **Plantilla simple**  
	- Descripción de los activos:  
	Descripción de procesos de negocio o área, y por cada uno su árbol de activos y dependencias.  
	- Por cada área de la organización:  
	Mostrar la misma con sus servicios y la información asociada a éstos.  
	- Por cada elemento de soporte de los servicios:  
	Mostrar su detalle.
	- Incluir la relación entre los activos  
	- Crear un resumen del valor de los activos con detalles de los siguientes elementos:  
		- Descripción de los servicios/procesos críticos y la explicación de su criticidad.  
		- Descripción de las aplicaciones y elementos de soporte críticos y la trazabilidad. Se incluye también la documentación en papel crítica respecto a la confidencialidad.  
		- Descripción de las redes críticas respecto a las diferentes dimensiones (*por ejemplo, autenticidad*).  
	- Crear una descripción del riesgo, lo cual incluye una descripción de las principales amenazas y su valoración a nivel de servicios/procesos, información, elementos de soporte, elementos de seguridad y almacenamientos, elementos de seguridad física y las personas.  
	- Crear una descripción de los valores seleccionados para la probabilidad y degradación en las amenazas (*metodología cuantitativa o cualitativa*). 
	- Crear un mapa de riesgo según:  
		- Riesgo potencial: riesgo al que está expuesta la organización en caso de que no hubiera ningún tipo de salvaguarda implantada, siendo ésto un escenario de riesgo simulado, no real.  
		- Riesgo presente: riesgo al que está expuesta la organización con las salvaguardas existentes. Se trata de su situación actual.  
	- Debilidades (o vulnerabilidades): Descripción resumen de las principales debilidades encontradas por dominios (*de la norma ISO 27001, como criptografía, seguridad de las comunicaciones, control de accesos, organización de la seguridad de la información, seguridad física y ambiental, gestión de activos, etc*).  
	- Se debe crear un anexo resumen de áreas, servicios, valoraciones, red(es) donde se encuentra la información, apliucaciones, herramientas y repositorios, información gestionada en general, dónde se encuentra localizada la información en papel, dónde se encuentra localizada la información digital y el responsable de área.

- **Test repaso** realizado: Análisis y gestión del riesgo.  
![image](https://user-images.githubusercontent.com/93931447/232601594-c75e85e6-da3f-47b9-9a10-5fae147648da.png)  

### Mitigación del riesgo
1. **Introducción a la gestión del riesgo (I)**  
A la vista de los impactos y riesgos a que están expuestos los activos de las organizaciones, hay que tomar una serie de decisiones condicionadas por diversos factores:  
	- La gravedad del impacto y/o del riesgo.  
	- Las obligaciones a las que por ley esté sometida la organización.  
	- Las obligaciones a las que por reglamentos sectoriales esté sometida la organización (banca, seguros, industrias críticas, etc).  
	- Las obligaciones a las que por contrato esté sometida la organización.  
	
Dentro del margen de maniobra que permita este marco, pueden aparecer consideraciones adicionales sobre la capacidad de la organización para aceptar ciertos impactos de naturaleza intangible como pueden ser:  
	- Imagen pública de cara a la sociedad (aspectos reputacionales).
	- Política interna: relaciones con los propios empleados, tales como la capacidad de contratar al personal idóneo, capacidad de retener a los mejores, capacidad de soportar rotaciones del personal, capacidad de ofrecer una carrera profesional atractiva, etc.  
	- Relaciones con los proveedores 
	- Relaciones con los clientes o usuarios.  
	- Relaciones con otras organizaciones.  
	- Nuevas oportunidades de negocio.  
	- Acceso a sellos o calificaciones reconocidas de seguridad (*ISO 27001, ISO 22301, CSA STAR, etc*).  

2. **Introducción a la gestión del riesgo (II)**  
Todas las consideraciones anteriores desembocan en una calificación de cada riesgo significativo, determinándose si:  
	1. Es crítico en el sentido de que requiere atención urgente.  
	2. Es grave en el sentido de que requiere atención.  
	3. Es apreciable en el sentido de que pueda ser objeto de estudio para su tratamiento.  
	4. Es asumible en el sentido de que no se van a tomar acciones para atajarlo. Ésta siempre es arriesgada y hay que tomarla con prudencia y justificación. Las razones que pueden llevar a esta aceptación son:
		- Cuando el impacto residual es asumible.  
		- Cuando el riesgo residual es asumible.  
		- Cuando el coste de las salvaguardas oportunas es desproporcionado en comparación al impacto y riesgo residuales.
	
El resultado del análisis es sólo un análisis. A partir de el disponemos de información para tomar decisiones conociendo lo que queremos proteger (activos valorados), de qué lo queremos proteger (amenazas valoradas) y qué hemos hecho por protegerlo (salvaguardas valoradas). Todo ello sintetizado en los valores de impacto y riesgo.  
A partir de aquí, las decisiones son de los órganos de gobierno de la organización que actuarán realizando una evaluación y a posterior un tratamiento.  

3. **Decisiones para el tratamiento del riesgo**  
![image](https://user-images.githubusercontent.com/93931447/233572478-a55733df-4c28-4cfc-a92c-fc0f51f3f928.png)

4. **Evaluación y tratamiento del riesgo**  
	1. Interpretación de los valores de impacto y riesgos residuales  
		- Son una medida del estado presente, entre la inseguridad potencial y las medidas adecuadas que reducen impacto y riesgo a valores aceptables  
		- Si el valor residual es igual al valor potencial, las salvaguardas existententes no valen para nada.  
		- Un valor resiual es sólo un número. Para su correcta interpretación debe venir acompañado de lo que se debería hacer y no se ha hecho  

	2. Aceptación del riesgo  
		- El comité de dirección debe determinal el nivel de impacto y riesgo aceptable y aceptar la responsabilidad de las insuficiencias
		- Estos niveles de aceptación se pueden establecer por activo o por agrupación de activos
		- Cualquier nivel de impacto y/o riesgo es aceptable si lo conoce y acepta formalmente la dirección
		- Estos riesgos aceptados deberían ser monitorizados de forma continua y especial para asegurar que no cambien su valor  

	Cabe destacar que esta no es una opción de tratamiento del riesgo, per se, sino que el riesgo existente (o parte de el) es aceptado sin más por el motivo que sea.  
	Estos riesgos aceptados deberán ser monitorizados de forma continua y especial para asegurar que no cambien su valor (impacto y/o probabilidad, y puedan llegar a causar un impacto severo en la organización).  
	
	3. Tratamiento del riesgo  
		1. Opciones  
			- Reducir el riesgo residual  
			- Ampliar el riesgo residual *(aceptar un mayor riesgo)*  
		2. Decisiones:  
			- Zona 1; riesgos muy probables y de muy alto impacto. Posiblemente nos planteemos sacarlos de esta zona, es decir, tratarlos inmediatamente. 
			- Zona 2; riesgos de probabilidad relativa e impacto medio; se pueden tomar varias opciones.  
			- Zona 3; riesgos improbables y de bajo impacto. O los dejamos como están, o permitimos que suban a mayores si ello nos ofrece alguna ventaja o beneficio en otro terreno.  
			- Zona 4; riesgos improbables pero de muy alto impacto; suponene un reto de decisión dado a su improbabilidad, ya que esta justifica que se tomen medidas preventivas, pero su elevado impacto exige que tengamos algo previsto para reaccionar: medidas para limitar el daño y de recuperación si esta ocurriera.
		  
	También conviene considerar la incertidumbre del análisis. En ocasiones, la incertidumbre afecta a la probabilidad. Estos escenarios suelen afectar a la zona 3 y 4, ya que cuando la probabilidad es alta normalmente adiquirimos experiencia con rapidez y salimos de la incerticumbre. En cualquier caso, toda incertidumbre debe considerarse como mala y debemos hacer algo:  
	- Buscar formas de mejorar la previsión (*Indagando en foros, centros de respuesta a incidentes o expertos en la materia*)  
	- Evitar el riesgo cambiando algún aspecto, componente o ariquitectura del sistema  
	- Tener preparados sistemas de alerta y procedicimentos flexibles de contención, limitación y recuperación del posible incidente (*mediante la monitorización continua del riesgo*)  
	4. Estudio del coste beneficio  
	No se puede invertir en salvaguardas más allá del valor que queremos proteger.
	Es intencionado el hecho de que el riesgo caiga fuertemente con pequeñas inversiones y que el coste de las inversiones se dispare para alcanzar niveles de seguridad cercanos al 100%.  
		- Análisis cuantitivo  
		En la práctica, cuando hay que protegerse de un riesgo, aparecen varios escenarios hipotéticos:  
			1. **E0:** Si no se hace nada  
			2. **E1:** Si se aplican cierto conjunto de salvaguardas  
			3. **E2 a N:** Si se aplican otros conjuntos de salvaguardas  
		El análisis económico tiene como misión decidir entre estas opciones, siendo E0 (*seguir como estamos*) una opción posible, pudiendo estar justificada económicamente.  
		En cada escenario hay que estimar el coste que va a suponer a lo largo del tiempo, teniendo en cuenta los siguientes elementos:  
				- Sumar el coste del riesgo residual (*recurrente*)  
				- Sumar el coste de las salvaguardas  
				- Sumar el coste anual de mantenimiento de salvaguardas (*recurrente*)  
				- Restar el coste del análisis en la porductividad  
				- Restar al coste las mejoras en la capacidad de la organización (*para prestar nuevos servicios, conseguir mejores condiciones de los proveedores, entrar en asociacion con otras organizaciones, etc*) (*recurrente*)  
		- Análisis cualitativo  
		En estos tipos de análisis, en la balanza de costes beneficios aparecen aspectos intangibles que impiden el cálculo de un punto numérico de equilibrio.  
		Entre los aspectos intangibles se suelen contemplar:  
			- Aspectos reputacionales o de imagen  
			- Aspectos de competencia: comparación con otras organizaciones de mismo ámbito de actividad  
			- Cumplimiento normativo, que puede ser obligatorio o voluntario  
			- Capacidad de operar  
			- Productividad  
		Estas consideraciones nos llevan a contemplar diversos escenarios para determinar el balance neto.  
		- Análisis mixto
		En análisis de riesgos meramente cualitativos, la decisión la marca el balance de costes y beneficios intangibles, si bien siempre hay que hacer un cálculo de lo que cuesta la solución y cerciorarse de que el gasto es asumible. De lo contrario, la supuesta solución no es una opción. Es decir, primero hay que pasar el filtro económico y luego elegir la mejor de las soluciones factibles.  
		
	4. Opciones de tratamiento del riesgo  
	Si los riesgos no se aceptan será necesario tener una estrategia para tratarlos (*respuesta al riesgo*).
		1. Eliminación  
			La eliminación de la fuente de riesgo es una opción frente a un riesgo que no es aceptable. En un sistema podemos eliminar varias cosas, siempre que no afecten a la esencia de la organización.
Es extremadamente raro que podamos prescindir de la información o los servicios esenciale. Cambiar estos activos supone reorientar la misión de la organización. Sin embargo, en determinados casos puede darse el caso de que el coste de otras opciones sea muy elevado frente al beneficio aportado por el activo amenazado, por lo que se decide prescindir del mismo (*por ejemplo de un servicio o proceso, de una actividad de negocio, etc*).
Por otro lado, es más viable prescindir otros componentes no esenciales, que están presentes simple y llanamente para implementar la misión, y no siendo parte constituyente de la misma de diferentes formas:
			- Eliminar cierto tipo de activos, empleando otros en su lugar (*cambiar de sistema operativo, de fabricante de equipos, etc*)
			- Reordenar la arquitectura del sistema (esquema de dependencias) de forma que se altere el valor acumulado en ciertos activos expuestos a grandes amenazas (*segregar redes, desdoblar equipos para atender a necesidades concretas, alejando lo más valioso de lo más expuesto, etc*)
		3. Mitigación  
		La mitigación del riesgo se refiere a una de dos opciones:  
			- Reducir la degradación causada por una amenaza (*acotar el impacto*)  
			- Reducir la probabilidad de que una amenaza de materializa  
		En ambos casos lo que hay que hacer es ampliar o mejorar el conjunto de salvaguardas, es decir, subir de nivel.  
		Entre los tipos de salvaguardas, encontramos las siguientes tipologías desde el punto de vista de mitigación del riesgo:
			- Salvaguardas preventivas: Buscan prevenir que una amenaza se haga real, por lo que disminuyen la probabilidad.  
			- Salvaguardas correctivas: Buscan minimizar el daño realizado en caso de materializarse la amenaza (*disponer de un plan de recuperación ante desastres, copias de seguridad ante ransomware, sistemas de automatización de la respuesta ante incidentes de seguridad, etc*), por lo que disminuyen el impacto. 
			- Salvaguardas detectivas: Buscan detectar la ocurrencia de una amenaza. No modifican el impacto de forma directa, pero son necesarios para el funcionamiento de las salvaguardas correctivas.  
		Tras su depliegue hay repetir el análisis de riesgos, ampliándolo con los nuevos controles y cerciorarse de que las salvaguardas efectivamente disminuyen el estado de riesgo de la organización respecto a la original.
		4. Compartición o transferencia  
		Tradicionalmente se ha hablado de ‘transferir el riesgo’. Como la transferencia puede ser parcial o total, es más general hablar de ‘compartir el riesgo’.  
		Hay dos formas básicas de compartir riesgo:  
			- Riesgo cualitativo: se comparte por medio de la externalización de componentes del sistema, de forma que se reparten responsabilidades  
			- Riesgo cuantitativo: se comparte por medio de la contratación de seguros, de forma que a cambio de una prima, el tomador reduce el impacto de las posibles amenazas y el asegurador corre con las consecuencias  
		5. Financiación (*Aprovisionamiento*)  
		Cuando se acepta un riesgo, la organización hará bien en reservar fondos para el caso de que el riesgo se concrete y haya que responder de sus consecuencias.
			- Cálculo de disminución del riesgo  
			Una vez finalizado la evaluación del tratamiento y los controles a implementar, se deben generar los nuevos mapas de riesgo que muestren la situación de la organización tras su implementación.  
			El cálculo de la disminución en impacto y/o probabilidad no es sencillo. Generalmente se recomienda utilizar el sentido común, si bien existen herramientas para el análisis de riesgos que incluyen catálogos de controles con valores predeterminados, si bien estos se deberían editar cuando así se requiera para al organización (*una herramienta podría ser la metodología PILAR, asociada a MAGERIT*).
5. **Requisitos de un programa de ciberseguridad**  
Un programa de ciberseguridad busca la implementación de los proyectos de seguridadd, entendiendo pr tales proyectos los que permitirán materializar las decisiones adoptadas para el tratamiento de los riesgos. Para ello, se deben realizar los siguientes pasos para su implementación:
	1. **Identificación de los proyectos de seguridad**  
	Se busca la agrupación por conveniencia de tareas que en singular carecerían de eficacia, que persigan un objetivo en común o que competen a una única acción. Cada programa debe detallar:
		- Su objetivo genérico.  
		- Las salvaguardas concretas a implantar o mejorar, detallando sus objetivos de calidad, eficacia y eficiencia  
		- La relación de escenarios de impacto y/o riesgo que afronta: activos afectados, tipos de activos, amenazas afrontadas, valoración de activos y amenazas y niveles de impacto y riesgo  
		- La unidad responsable de su ejecución  
		- Una estimación de costes, tanto económicos como de esfuerzo de realización, teniendo en cuenta:  
			- Costes de adquisición (de productos), o de contratación (de servicios), o de desarrollo (de soluciones llave en mano)  
			- Costes de implantación inicial y mantenimiento en el tiempo. 
			- Costes de formación, tanto de los operadores como de los usuarios  
			- Costes de explotación  
			- Impacto en la productividad de la organización  
		- Una relación de subtareas a afrontar, teniendo en cuenta:  
			- Cambios en la normativa y desarrollo de procedimientos  
			- Solución técnica: programas, equipos, comunicaciones e instalaciones  
			- Plan de despliegue  
			- Plan de formación  
			- Una estimación del tiempo de ejecución desde su arranque hasta su puesta en marcha  
		- Una estimación del estado de riesgo (impacto, probabilidad y riesgo residual) a su finalización  
		- Un sistema de indicadores (métricas) de eficacia y eficiencia que permitan conocer en cada momento la calidad del desempeño de la función de seguridad que se desea y su evolución temporal.
		Las estimaciones anteriores pueden ser muy precisas en los programas sencillos; pero pueden ser simplemente orientativas en los programas complejos que conlleven la realización de un proyecto específico de seguridad. En este último caso, cada proyecto desarrollará los detalles últimos por medio de una serie de tareas propias de cada proyecto que, en líneas generales responderán a los siguientes puntos:  
		- Estudio de la oferta del mercado: productos y servicios  
		- Coste de un desarrollo específico, propio o subcontratado  
		- Si se estima adecuado un desarrollo específico hay que determinar: 
			- La especificación funcional y no-funcional del desarrollo  
			- El método de desarrollo que garantice la seguridad del nuevo componente  
			- Los mecanismos de medida (controles) que debe llevar  
			- Los criterios de aceptación  
			- El plan de mantenimiento: incidencias y evolución
	2. **Plan de ejecución**  
	Hay que ordenar en el tiempo los proyectos de seguridad teniendo en cuenta los siguientes factores:
		- La criticidad, gravedad o conveniencia de los impactos y/o riesgos que se afrontan, teniendo máxima prioridad los programas que afronten situaciones críticas  
		- El coste del programa  
		- La disponibilidad del personal propio para responsabilizarse de la dirección (y, en su caso, ejecución) de las tareas programadas  
		- Las posibles dependencias entre proyectos. En muchos casos puede ocurrir que el comienzo de un proyecto dependa de la salida de otro/s. Por ejemplo, en el caso del despliegue de una salvaguarda técnica, puede ser necesario que se dispongan primero de los procedimientos y guías antes de poder acometer dicho proyecto (con el objetivo de asegurar el alineamiento del control técnico con los objetivos y requisitos organizacionales)  
		- Otros factores (*elaboración del presupuesto anual de la organización, las relaciones con otras organizaciones, la evolución del marco legal,
reglamentario o contractual, etc.*)  
		Típicamente, un plan de seguridad se planifica en tres niveles de detalle:  
		- **Plan director:** A menudo denominado “plan de actuación”, trabaja sobre un periodo largo (_típicamente entre 3 y 5 años_), estableciendo las directrices de actuación.  
		- **Plan anual** (una serie de planes anuales): Trabaja sobre un periodo corto (_típicamente entre 1 y 2 años_), estableciendo la planificación de los programas de seguridad.  
		- Plan de proyecto (un conjunto de proyectos con su planificación): Trabaja en el corto plazo (_típicamente menos de 1 año_), estableciendo el plan detallado de ejecución de cada programa de seguridad.  
		Se debe desarrollar un plan director único, que es el que da perspectiva y unidad de objetivos a las actuaciones puntuales. Este plan director permite ir desarrollando planes anuales que, dentro del marco estratégico, van estructurando la asignación de recursos para la ejecución de las tareas, en particular partidas presupuestarias. Por último habrá una serie de proyectos que materializan los programas de seguridad.
	3. **Plan de adecuación**  
	El objetivo de esta fase es el de alcanzar los objetivos previstos en el plan de seguridad para cada proyecto planificado.  
	Como salida del mismo tendremos lo siguiente:  
		- Salvaguardas implantadas
		- Normas de uso y procedimientos de operación  
		- Sistema de indicadores de eficacia y eficiencia del desempeño de los objetivos de seguridad perseguidos  
		- Modelo de valor actualizado  
		- Mapa de riesgos actualizado  
		- Estado de riesgo actualizado (impacto, probabilidad y riesgo residuales)
		
6. **Informe de tratamiento del riesgo**  
El informe de tratamiento del riesgo incorpora las diferentes opciones de tratamiento del riesgo (riesgos aceptados, transferidos, eliminados y las salvaguardas a
desplegar) junto con el mapa del riesgo tras su implementación. Este informe puede ser independiente o bien incluirse como continuación del informe de evaluación de
riesgos.  
Como mínimo debería contener la siguiente información:  
	1. Introducción:  
		- Fecha de ejecución
		- Resumen del objetivo   
		- Descripción del alcance (relacionado con el informe de evaluación de riesgos y si el tratamiento afectará a todos los riesgos de la evaluación o una parte, definiendo en este segundo caso cuáles)  
		- Objetivos estratégicos de seguridad. Descripción de los objetivos de seguridad a nivel estratégicos buscados con este plan de tratamiento  
	2. Enfoque metodológico: Descripción del enfoque utilizado, incluyendo criterios de valoración, formulas, etc  
	3. Situación actual:  
		- Debilidades: Detalle de las diferentes debilidades (_vulnerabilidades_) halladas por cada dominio de seguridad (_de la ISO 27001_)  
		- Mapas de riesgos: Incluir los mapas de riesgo presente así como el del riesgo final tras aplicar todas las salvaguardas. En caso de que se trate de un proyecto a medio-largo plazo (2-3 años), se pueden incluir los mapas de riesgos de cómo quedaría la situación tras cada año (con las medidas implementadas de forma estimada en cada momento)  
		- Resumen de los planes de acción: Descripción del periodo de implantación de las medidas (_definir qué se entiende por corto, medio y lago plazo_) e incluir una tabla con el resumen de medidas y su plazo de implantación (_corto, medio o largo plazo_)  
	4. Descripción en detalle de los planes de acción. Se pueden crear sub-capítulos por el tipo de planes que sean (seguridad lógica, física y administración y gestión de la seguridad). Por cada uno de los planes se detallará:  
		- Descripción de la medida  
		- Objetivos concretos buscados  
		- Actividades a realizar
		- Nivel de madurez buscado (_por ejemplo en base al CMMi_)  
		- Entorno tecnológico involucrado (si lo hubiera)  
		- Recursos necesarios (a nivel de personal y de inversión monetaria, explicitando cada elemento)  
		- Métricas propuestas para la medición del plan.
	5. Acciones de monitorización necesarias: De acuerdo a lo establecido en el marco de gestión del riesgo de la organización y/o de forma ad-hoc. qué acciones son requeridas para monitorizar la implantación de los controles así como para valorar la disminución del riesgo en el tiempo.  
	6. Apéndices:
		- Resumen de los planes de acción  
		- Plan de proyecto con todos los proyectos necesarios, con fecha de inicio y fin  
7. **Frameworks de seguridad**  
Existen diferentes frameworks de seguridad de la información y ciberseguridad que nos permitirán contar con un conjunto de salvaguardas base entre las que poder escoger para los planes de mitigación del riesgo, así como establecer un marco general de gestión de la seguridad.  
Los que vamos a ver los dos más famosos a nivel mundial:  
	1. **ISO 27001**  
	La norma ISO/IEC 27001 es un estándar para la seguridad de la información. Especifica los requisitos necesarios para establecer, implantar, mantener y mejorar un sistema de gestión de la seguridad de la información (SGSI) según el conocido como “Ciclo de Deming”: PDCA, acrónimo de Plan, Do, Check, Act (Planificar, Hacer, Verificar, Actuar).
Dado que el riesgo no es algo estático sino dinámico, un SGSI establecido bajo esta norma debe contemplar un proceso cíclico desarrollado en el ciclo PDCA:  
	![image](https://user-images.githubusercontent.com/93931447/234074751-4d41cdf6-4020-4ec6-ac99-7a9934cfb586.png)  
	La norma se encuentra dividida en dos partes. La primera se compone de 10 puntos que son:
		- Objeto y campo de aplicación  
		Especifica la finalidad de la norma, su uso dentro de una organización y el modo de aplicación estándar  
		- Referencia normativas  
		Recomendación de la consulta de los documentos necesarios para la aplicación del estándar  
		- Términos y definiciones  
		- Contexto de la organización  
		Busca determinar necesidades y expectativas dentro y fuera de la organización que afecten directa o indirectamente al SGSI 
		- Liderazgo  
		Importancia de la alta dirección y su compromiso con el SGSI
		- Planificación  
		Valorar, analizar y evaluar los riesgos de seguridad de acuerdo a los criterios de aceptación de riesgos  
		- Soporte  
		Recursos destinados por la organización  
		- Operación  
		Cómo se debe planificar, implementar y controlar los procesos de la operación  
		- Evaluación de desmpeño  
		Realizar un seguimiento mediante el PDCA para asegurar su correcto funcionamiento  
		- Mejora  
		Tratamiento de las no conformidades, acciones correctivas y mejoras contínuas  
La segunda parte establece los objetivos de control y los controles de referencia.  
	2. **NIST CSF (_Cyber Security Framework_)**  
	Este marco no provee de nuevas funciones o categorías de ciberseguridad, si no que recopila las mejores prácticas (_ISO, ITU, CIS y NIST entre otros_) y los agrupa según afinidad.  
	Se centra en el uso de impulsores de negocio para guiar las actividades de ciberseguridad y considerar los riesgos de ciberseguridad como parte de los procesos de gestión de riesgos de la organización.  
	El framework consta de tres partes:
		- Marco básico  
		- Perfil del marco  
		- Niveles de implementación
	Los niveles de implementación del marco o “tiers” proporcionan un contexto sobre cómo una organización ve el riesgo en ciberseguridad y los procesos implementados para manjearlo.  
	Las escalas descirben el grado en que las prácticas de gestión de riesgos de ciberseguridad de una empresa exhiben las características definidas en el marco. Actúan como niveles de madurez en estos procesos.  
	Los niveles de implementación caracterizan las prácticas de una compañía en un rango. Hay 4 niveles: parcial, riesgo informado, repetible y adaptativo.  
	Estos niveles reflejan una progresión desde respuestas informales y reactivas hasta enfoques que son ágiles y están informados sobre el riesgo.  
	El núcleo de este marco proporciona cinco funciones contínuas (_Identificar, Detectar, Proteger, Responder y Recuperar_). También brinddad un conjunto de actividades para lograr resultados específicos de ciberseguridad.
	![image](https://user-images.githubusercontent.com/93931447/234081552-1d17bb03-c502-4b31-bf2d-b7462b2c09ef.png)
### Controles de mitigación: Seguridad administrativa y física
Este apartado habla sobre los controles necesarios para garantizar la seguridad en la **gestión de la seguridad de la información** en la organización. Basicamente se explica como establecer controles necesarios para la gestión de la seguridad de la información en la organización, como políticas de seguridad, gestión de usuarios, control de acceso, control de cambios, monitoreo de la actividad del usuario y gestión de incidentes de seguridad.  
A continuación, se presenta un resumen de los temas tratados en este apartado:  
1. **Políticas de seguridad**  
Se establecen políticas y procedimientos que describen las medidas necesarias para proteger la información, incluyendo la identificación y autenticación de usuarios, el control de acceso y la gestión de contraseñas.  
2. **Gestión de usuarios**  
Se establecen procedimientos para la gestión de los usuarios, incluyendo la creación, modificación y eliminación de cuentas, así como la revisión periódica de los permisos de acceso.  
3. **Control de acceso**  
Se establecen controles para limitar el acceso a la información y los sistemas de información a los usuarios autorizados. Esto incluye la autenticación de usuarios, la autorización de acceso y el control de acceso físico a los sistemas.  
4. **Control de cambios**  
Se establecen procedimientos para la gestión de cambios en los sistemas y la información, con el fin de evitar cambios no autorizados y garantizar la integridad de los datos.  
5. **Monitoreo de la actividad del usuario**  
Se establecen controles para registrar y monitorear la actividad de los usuarios, con el fin de detectar comportamientos anormales o sospechosos.  
6. **Gestión de incidentes de seguridad**  
Se establecen procedimientos para la gestión de incidentes de seguridad, con el fin de minimizar el impacto de los incidentes de seguridad y garantizar la continuidad del negocio.   

### Controles de mitigación: Seguridad lógica
Al contrario que en el apartado anterior, éste se enfoca en los controles necesarios para garantizar la **seguridad física** de los activos de información de la organización. El apartado explica como establecer controles necesarios para garantizar la seguridad física de los activos de información de la organización, como el acceso físico restringido, la protección de activos de información, la gestión de los medios de almacenamiento, la seguridad en el manejo de los activos, el monitoreo de la seguridad física y la disponibilidad de los servicios.    
Este apartado lo podemos resumir en los siguientes temas:  
1. **Acceso físico restringido**  
Se establecen controles para limitar el acceso físico a los activos de información y las áreas que los contienen, incluyendo el uso de cerraduras, tarjetas de acceso y sistemas de vigilancia.  
2. **Protección de activos de información**  
Se establecen controles para proteger los activos de información de la organización de daños físicos o robo, incluyendo la protección contra incendios, la protección contra inundaciones y el uso de sistemas de alarma.  
3. **Gestión de los medios de almacenamiento**  
Se establecen procedimientos para la gestión y protección de los medios de almacenamiento de la información, como discos duros, cintas de respaldo y dispositivos USB.
4. **Seguridad en el manejo de los activos**  
Se establecen controles para garantizar la seguridad en el manejo de los activos de información, incluyendo el transporte seguro de los dispositivos y la eliminación segura de la información.  
5. **Monitoreo de la seguridad física**  
Se establecen controles para el monitoreo y registro de la actividad en las áreas que contienen activos de información, con el fin de detectar comportamientos sospechosos o no autorizados.  
6. **Disponibilidad de los servicios**  
Se establecen controles para garantizar la disponibilidad de los servicios de información, incluso en caso de interrupciones físicas.  

- **Test autoevaluación** realizado: Mitigación del riesgo. 
![image](https://user-images.githubusercontent.com/93931447/234583565-c2a39176-9f4a-4215-a2fc-6bc2e32ff8c4.png)

### Monitorización del riesgo
Este apartado habla de los controles necesarios a establecer para monitorear y gestionar adecuadamente los riesgos de seguridad de la información en la organización, incluyendo la identificación de los riesgos, la evaluación y análisis del riesgo, la selección y aplicación de controles, el monitoreo continuo de los riesgos y los informes de riesgos.  
A continuación se explican los temas tratados en este apartado:  
1. **Identificación de los riesgos**  
Se establecen procesos para identificar los riesgos de seguridad de la información en la organización, incluyendo la evaluación de amenazas, vulnerabilidades y posibles impactos.
2. **Evaluación y análisis del riesgo**  
Se establecen procesos para evaluar y analizar los riesgos identificados, incluyendo la evaluación de la probabilidad y el impacto de cada riesgo.  
3. **Selección y aplicación de controles**  
Se establecen procesos para seleccionar y aplicar controles para mitigar los riesgos de seguridad de la información, incluyendo la implementación de políticas y procedimientos, la capacitación del personal y el uso de tecnologías de seguridad.  
4. **Monitoreo continuo de los riesgos**  
Se establecen procesos para monitorear continuamente los riesgos de seguridad de la información y los controles aplicados, con el fin de detectar cualquier cambio en el nivel de riesgo y tomar medidas para mitigarlo.  
5. **Informes de riesgos**  
Se establecen procesos para generar informes regulares sobre los riesgos de seguridad de la información y los controles aplicados, con el fin de informar a la dirección y otros interesados sobre el estado de la seguridad de la información en la organización.  

#### KRIs (_Indicadores Clave del Riesgo_)  
Este apartado se centra en los indicadores clave que se utilizan para medir y monitorear el riesgo en la organización.  
En cuanto a los KRI:  
1. **Definición**  
Se definen los KRIs como medidas cuantitativas o cualitativas que se utilizan para evaluar y monitorear el riesgo en la organización.  
2. **Importancia**  
Se explica la importancia de los KRIs para la gestión del riesgo, ya que permiten identificar y monitorear los riesgos críticos para la organización y tomar medidas para mitigarlos.  
3. **Selección de KRI**  
Se establecen procesos para seleccionar los KRIs adecuados para la organización, basados en los riesgos identificados, los objetivos de la organización y otros factores relevantes.  
4. **Desarrollo** 
Se establecen procesos para desarrollar los KRIs adecuados para la organización, incluyendo la definición de las fórmulas para calcular los indicadores, el establecimiento de los umbrales de alerta y los límites críticos, y la integración de los KRIs en los sistemas de monitoreo.
5. **Monitoreo y reporte**  
Se establecen procesos para monitorear continuamente los KRIs y generar informes regulares sobre el estado del riesgo en la organización, con el fin de informar a la dirección y otros interesados sobre el desempeño de la gestión del riesgo.  

#### Herramientas para monitorización del riesgo  
En cuanto a las herramientas que se utilizan para monitorear y evaluar el riesgo en la organización, incluimos herramientas de análisis de riesgos, monitoreo de KRIs, gestión de incidentes, seguimiento de controles y análisis de datos.  
El uso de estas herramientas ayuda a la organización a evaluar y monitorear el riesgo de manera efectiva y tomar medidas para mitigarlo.  
Hay diferentes tipos de herramientas:  
1. **Herramientas de análisis de riesgos**  
Matriz de riesgos, el análisis de causa-raíz, el análisis de escenarios y el análisis de impacto y probabilidad. Estas herramientas se utilizan para identificar, evaluar y priorizar los riesgos en la organización.  
2. **Herramientas de monitoreo de KRIs**  
Dashboards e informes automatizados. Estas herramientas se utilizan para monitorear los indicadores clave del riesgo y generar informes regulares sobre el estado del riesgo en la organización.  
3. **Herramientas de gestión de incidentes**  
Sistemas de gestión de incidentes y los protocolos de respuesta a incidentes. Estas herramientas se utilizan para identificar, registrar, investigar y reportar los incidentes relacionados con el riesgo en la organización.  
4. **Herramientas de seguimiento de controles**  
Planes de acción, los registros de controles y los sistemas de seguimiento de controles. Estas herramientas se utilizan para monitorear la implementación y eficacia de los controles de mitigación del riesgo en la organización.  
5. **Herramientas de análisis de datos**  
Herramientas de minería de datos y los sistemas de inteligencia artificial. Estas herramientas se utilizan para analizar grandes cantidades de datos y identificar patrones y tendencias que puedan indicar riesgos potenciales en la organización.  

#### Herramientas GRC (_Gobierno, Riesgo y Cumplimiento_)  
Las herramientas GRC son sistemas que permiten integrar y coordinar las actividades de gobierno, riesgo y cumplimiento de una organización. Estas herramientas son una forma efectiva de gestionar y monitorear el riesgo en tiempo real, y pueden ayudar a las organizaciones a identificar y prevenir riesgos, así como a cumplir con las normativas y regulaciones aplicables.  
Las herramientas GRC incluyen diversas funcionalidades, como la gestión de políticas y procedimientos, la evaluación de riesgos, la monitorización del cumplimiento, la gestión de incidentes y la generación de informes y análisis. Además, estas herramientas pueden ser personalizadas para adaptarse a las necesidades específicas de la organización y pueden ser utilizadas en diferentes áreas, como finanzas, recursos humanos, seguridad de la información, entre otros.  
Al utilizar las herramientas GRC, las organizaciones pueden optimizar sus procesos de gestión del riesgo, mejorar la eficiencia y eficacia de sus operaciones, reducir los costos y, sobre todo, reducir los riesgos asociados a su actividad.  
En resumen, las herramientas GRC son una solución integral para la gestión del riesgo, que permite a las organizaciones mantener el control y la visibilidad sobre sus actividades críticas.  

![image](https://user-images.githubusercontent.com/93931447/234872099-6c329430-47fc-4a60-ad4e-41263d93af08.png)

- **Test autoevaluación** realizado: Monitorización del riesgo
![image](https://user-images.githubusercontent.com/93931447/234886061-b51edc4f-d393-44f3-a3a1-85e27cfe1c55.png)

- **Examen** realizado: [Certificado curso de análisis y gestión del riesgo](Certificados/certificado_curso_de_análisis_y_gestión_del_riesgo.pdf)

----------

## OSINT para fuga de datos empresariales

La herramienta OSINT (Open-Source Intelligence) de Kali es una colección de herramientas de inteligencia de fuentes abiertas que pueden ser utilizadas para recopilar información de fuentes públicas en línea.  
Estas herramientas pueden ayudar en la recopilación de información sobre personas, organizaciones, direcciones IP, nombres de dominio, redes sociales y otros datos relevantes para la investigación de seguridad, la evaluación de amenazas y la inteligencia de negocios.  
La herramienta OSINT de Kali también puede ser útil para los profesionales de seguridad en la identificación de vulnerabilidades y en la preparación de pruebas de penetración. Algunas de las herramientas incluidas en la herramienta OSINT de Kali son Maltego, theHarvester, Recon-ng y Metagoofil.  
Estos datos pueden ser sacados, remarcando que siempre es de forma legal, de plataformas como LinkedIn, QDQ, librebor, infobel, twago, indeed, Páginas Amarillas, invenes, hunter.io, boletines del BOE, páginas del Gobierno, y redes sociales en general.  
Como herramientas de búsqueda se pueden utilizar Google, Yahoo, Bing o Yandex.

----------

## Criptografía Simétrica y Asimétrica

La criptografía es el estudio de técnicas de codificación para proteger la privacidad y la seguridad de la información.  
En la criptografía, existen dos tipos principales de algoritmos: criptografía simétrica y criptografía asimétrica.  

La **criptografía simétrica** utiliza una clave compartida entre el remitente y el destinatario para cifrar y descifrar la información. La misma clave se utiliza tanto para cifrar como para descifrar el mensaje. Esto significa que ambas partes deben conocer la clave compartida para asegurar la privacidad de la información. Algunos ejemplos de algoritmos de criptografía simétrica son DES, AES y Blowfish.  
La criptografía simétrica tiene varias ventajas y desventajas que deben tenerse en cuenta al elegir un algoritmo de cifrado:  
- Ventajas  
	1. **Eficiente**  
	Rápida y eficiente en términos de procesamiento de datos, ya que utiliza una única clave para cifrar y descifrar los mensajes. Esto la hace ideal para aplicaciones que requieren un alto rendimiento y velocidad.
	2. **Fácil implementación**  
	Fácil de implementar, ya que solo se necesita una clave compartida entre el remitente y el destinatario.  
	3. **Ampliamente disponible**  
	Existen muchos algoritmos de cifrado simétricos disponibles que son ampliamente utilizados y soportados por sistemas y dispositivos.  
	
- Desventajas:  
	1. **Clave compartida**  
	La misma clave debe ser compartida entre el remitente y el destinatario. Esto significa que si la clave cae en manos equivocadas, toda la información cifrada con esa clave puede ser descifrada.  
	2. **Distribución de claves**  
	La distribución segura de las claves entre el remitente y el destinatario puede ser difícil y puede requerir la implementación de mecanismos adicionales de seguridad.  
	3. **Escalabilidad**  
	Puede no ser escalable para grandes redes o sistemas distribuidos debido a la necesidad de compartir la misma clave entre múltiples entidades.  
Es decir, la criptografía simétrica es rápida, eficiente y fácil de implementar, pero su principal desventaja es la necesidad de compartir la misma clave y la distribución segura de la misma.

La **criptografía asimétrica**, por otro lado, utiliza un par de claves diferentes: una clave pública y una clave privada. La clave pública se comparte ampliamente y se utiliza para cifrar los mensajes, mientras que la clave privada se mantiene en secreto y se utiliza para descifrar los mensajes cifrados. Esto significa que el remitente no necesita conocer la clave privada del destinatario para enviar un mensaje cifrado. Algunos ejemplos de algoritmos de criptografía asimétrica son RSA, DSA y ECC.  
Al igual que la criptografía simétrica, la simétrica también tiene sus ventajas y desventajas:  
- Ventajas:  
	1. **Mayor seguridad**  
	La criptografía asimétrica proporciona un mayor nivel de seguridad al utilizar dos claves diferentes, una pública y otra privada. Esto significa que la clave pública puede ser compartida ampliamente sin comprometer la seguridad de la información.  
	2. **No es necesario compartir claves**  
	No es necesario compartir una clave secreta entre el remitente y el destinatario, lo que simplifica la distribución y gestión de claves en entornos de red.
	3. **Escalabilidad**  
	Escalable para grandes redes y sistemas distribuidos debido a la capacidad de generar múltiples claves públicas y privadas.  

- Desventajas:  
	1. **Procesamiento más lento**  
	Más lenta que la criptografía simétrica debido al uso de dos claves diferentes para cifrar y descifrar los mensajes.
	2. **Mayor complejidad**  
	Más compleja de implementar y administrar que la criptografía simétrica, lo que puede dificultar su implementación.
	3. **Vulnerable a ataques de intermediario**  
	Vulnerable a ataques de intermediario en los que un atacante intercepta y manipula la comunicación entre el remitente y el destinatario.  
	
Las principales diferencias entre ambas es que la criptografía simétrica utiliza una clave compartida para cifrar y descifrar la información, mientras que la criptografía asimétrica utiliza un par de claves diferentes para asegurar la privacidad de la información. Ambas técnicas son ampliamente utilizadas en la seguridad de la información.

## Seguridad de red en el ámbito corporativo: Capa 2 del modelo OSI
### Introducción a la capa de enlace de datos 
La capa de enlace de datos es la segunda capa del modelo OSI y se encarga de la transferencia de datos entre nodos que están directamente conectados en una red local. Esta capa se encarga de dividir los datos en paquetes más pequeños y de transmitirlos de forma segura y eficiente a través de un medio de transmisión, como un cable o una conexión inalámbrica.  
Encapsula los datos de la capa 3 de red (_Tx_) e interpreta los bits de la capa 1 física (_Rx_).  
También se encarga de la detección y corrección de errores que puedan ocurrir durante la transmisión de datos, así como de controlar el flujo de datos para evitar la congestión en la red. Además, esta capa puede asignar direcciones físicas a los dispositivos conectados a la red, lo que permite su identificación en la misma.

#### Subcapas
Según el IEEE 802, la capa de enlace de datos se divide en dos subcapas:  
1. Control de enlace lógico (LLC)  
	- Implementado en software  
	- Identifica el protocolo de Capa 3  
2. Control de acceso al medio (MAC)  
	- Implementado en hardware  
	- Encapsulación de datos  
		- Delimitación de tramas  
		- Direccionamiento  
		- Detección de errores  
	- Control de acceso a medios  

#### Tipos de comunicación
1. **Simplex**  
Transmiten información en una sola dirección  
2. **Semi-dúplex**  
Transmiten información en ambas direcciones pero no de manera simultánea  
3. **Dúplex**  
Transmiten información en ambas direcciones de manera simultánea  

### Métodos de control de acceso
1. **Acceso por contienda**
	- **Acceso múltiple con detección de colisiones (CSMA/CD)**  
		Protocolo de acceso al medio **utilizado en redes de área local (LAN)**.  
		En un sistema CSMA/CD, cada dispositivo que desea transmitir datos escucha el canal de comunicación para detectar si otros dispositivos están transmitiendo datos. Si el canal está libre, el dispositivo comienza a transmitir sus datos. Si otro dispositivo comienza a transmitir al mismo tiempo, se produce una colisión de datos y ambas transmisiones se interrumpen. Los dispositivos implicados en la colisión esperan un tiempo aleatorio antes de intentar transmitir de nuevo, para evitar una nueva colisión. Por otro lado, si un dispositivo que desea transmitir datos detecta que está recibiendo una trama, no enviará su trama hasta que termine dicha transmisión.  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/ada83cca-37f3-4731-a81e-38f119f7ad97)  

	- **Acceso múltiple con prevención de colisiones (CSMA/CA) ** 
		Protocolo de acceso al medio **utilizado en redes inalámbricas**.  
		En un sistema CSMA/CA, cada dispositivo que desea transmitir datos envía primero una señal de solicitud de transmisión al punto de acceso de la red inalámbrica (AP). El AP luego concede permiso para la transmisión de datos a través de una señal de confirmación de transmisión. Si varios dispositivos envían señales de solicitud de transmisión al mismo tiempo, el AP utiliza un mecanismo de programación para otorgar permiso de transmisión a un dispositivo a la vez, lo que evita las colisiones.  
		Antes de transmitir datos, un dispositivo escucha el canal de comunicación para detectar si otros dispositivos están transmitiendo. Si el canal está libre, el dispositivo espera un tiempo aleatorio antes de comenzar a transmitir sus datos, para evitar que otros dispositivos comiencen a transmitir al mismo tiempo.  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/c1e75d2a-1a43-4e31-a38f-9d4685989d8e)

2. **Acceso controlado**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/9a2ba092-3d38-40f1-84e6-5f27ae9b49e0)

### Campos de la trama Ethernet
- **Tecnología Ethernet**  
	- Funciona en las Capas 1 y 2  
	- Se define en los estándares **IEEE 802.2 y 802.3**  
- **Trama Ethernet**  
	- Tamaño mín.: 64 bytes  
	- Tamaño máx.: 1518 bytes  

![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/dbb33f16-c509-40c6-bd31-e28024e4d0cb)  

### Tipos de direcciones
**Dirección MAC**  
La dirección MAC (Media Access Control) es una dirección **única y permanente** asignada a cada interfaz de red de un dispositivo (_como una tarjeta de red_) por el fabricante del dispositivo.  

![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/75525b67-e45c-40ad-b8c2-f34305a9d5ff)  

1. **Dirección MAC unicast**  
	- Un único dispositivo de destino  
	- MAC Dest.: MAC Dispositivo  
2. **Dirección MAC broadcast**  
	- Todos los dispositivos de la red local reciben y procesan la trama  
	- MAC Dest.: FF-FF-FF-FF-FF-FF  
3. **Dirección MAC multicast**  
	- Grupo de dispositivos como destino  
	- MAC Dest.: 01-00-5E-XX-XX-XX  

 ### ARP  
 1. **Explicación general**
 	- Protocolo de la capa de enlace de datos responsable de encontrar la dirección MAC asociada a una determinada dirección IP  
 	- Mantiene una tabla de asignaciones de direcciones IPv4 a MAC  
 	- Esencial en la transmisión de datos en redes Ethernet  
 2. Dos tipos de paquetes: **ARP Request y ARP Reply**  
	- ARP Request  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/23895822-af97-4270-9804-bdd070e3790c)  
	- ARP Reply  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/073b3456-adc1-4d45-bff5-362f60fbd9ab)

3. Dos modos de almacenar las relaciones: **estática o dinámica**
	- **ARP estático**  
		- Añadidas por el administrador (manual)  
		- Únicamente _read-only_  
		- Más seguro pero menos escalable  
	- **ARP dinámico**  
		- Se aprenden a través del protocolo ARP  
		- Tienen fecha de vencimiento  
		- Menos seguro pero más escalable  
4. **Variaciones ARP**  
	- **Reverse ARP (RARP)**  
		- Encuentra la dirección IP asociada a una determinada dirección MAC  
		- Necesidad de un servidor RARP especializado  
		- A día de hoy casi no se utiliza, reemplazandose por BOOTP y DHCP  

	- **Proxy ARP**
		- Un host responde a peticiones ARP destinadas a un host que se encuentra fuera de la red local. No es necesario enrutamiento o puerta de enlace.  

		`R1(config-if)# ip proxy-arp`  
			
5. **Fallos de seguridad y posibles mitigaciones**
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/86577adc-38d3-49c2-9da9-cea347a1e2a4)

### STP
1. **Explicación general**  
	- Protocolo de la capa de enlace de datos que gestiona la presencia de buclesen topologías de red debido a enlaces redundantes  
	- Permite a los switches activar o desactivar automáticamente los enlaces según las necesidades de la topología  
	- Para conseguir eliminar bucles se determina un root en función de la prioridad y 3 tipos de puerto: root, designado y alternativo  
	- Para el intercambio de información entre los switches de la topología se utilizan tramas BPDU  

2. **Algoritmo STP**  
![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/5035b52e-95f6-42a5-8b16-7b92a22ee90e)  

3. **Unidad de datos STP: BPDU**  
	- Prioridad del puente  
	Valor personalizable que influye en la elección del root (de 0 a 61440)  
	- ID del sistema extendido  
	Valor agregado al valor de la prioridad que identifica la VLAN para esta BPDU  
	- Dirección MAC  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/954f6831-e9f8-40b0-b1f6-7ad32add6f59)  
	
4. **Pasos para topologías sin bucles**  
	1. Elegir el root  
	La elección se basa en la elección de la MAC más pequeña en caso de que la prioridad sea la misma para todos los switchs.
	De manera administra se puede modificar la prioridad para que esta sea más baja y así poder elegir de manera manual el root.
	3. Seleccionar los puertos root
	Aquellos que conectan los switches con el root mediante la ruta más rápida (_corta_)  
	4. Seleccionar los puertos designados  
	Aquellos switches que tengan un puerto root, al otro lado siempre vamos a tener un puerto designado.  
	Por defecto todos los puertos son designados si no existe un puerto root al otro lado.  
	6. Seleccionar los puertos alternativos (bloqueados)  
	Aquel que por descarte queda bloqueado, evitando los bucles.  

5. **Temporizadores**  
	1. Hello Timer  
		- Intervalo entre BPDU  
		- Valor predeterminado: 2 segundos  
	2. Forward Delay Timer  
		- Tiempo que se pasa en el estado de escucha y aprendizaje  
		- Valor predeterminado: 15 segundos  
	3. Max Age Timer  
		- Duración máxima de espera antes de cambiar la topología STP  
		- Valor predeterminado: 20 segundos  

6. **Estados del puerto**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/706346d8-70e1-46a4-82ef-efd369151961)  
	
7. **Versiones STP**  
	1. **PVST+**  
	Proporciona una instancia de árbol diferente por cada VLAN  
	2. **RSTP**  
	Proporciona una convergencia más veloz que STP  
	3. **PVST+ rapid**  
	Mejora de RSTP con una instancia de árbol diferente por cada VLAN  
	4. **MSTP**  
	Asigna varias VLAN en la misma instancia de árbol

8. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/0971e4a2-58ff-4fb1-b07f-690750b958ac)

### CDP  
1. **Explicación general**  
	- Protocolo de capa 2 patentado por Cisco que se utiliza para obtener información de los dispositivos Cisco que comparten enlace de datos  
	- Envía mensajes CDP (multicast) periódicos a los dispositivos conectados  
	- Información que contienen los paquetes: nombre del dispositivo, imagen del OS, tipo y modelo, dirección IP, VLAN nativa, etc  
	- Ayuda a tomar decisiones de diseño y solucionar problemas en la red  

2. **Configuración**
	- Para observar que CDP está activo por defecto  
		`Router# show cdp`  

	- Para desactivar CDP globalmente  
		`Router(config)# no cdp run`  

	- Para activar CDP globalmente  
		`Router(config)# cdp run`  

	- Para activar CDP por interfaz  
		`Switch(config-if)# cdp enable`  

	- Para verificar la configuración  
		`Router# show cdp interface`  

	- Detección de vecinos  
		`R1# show cdp neighbors`  
	
		`R1# show cdp neighbors detail`  

3. **LLDP**  
	1. **Descripción**  
	Idéntico a CDP pero no es específico únicamente de dispositivos Cisco.  
	LLDP no depende del proveedor, por lo que es compatible con dispositivos Cisco.  

	2. **Configuración**  
		`Switch(config)# lldp run`  

		`Switch(config-if)# lldp transmit`  

		`Switch(config-if)# lldp receive`  

		`Switch# show lldp`  

	3. **Detección de vecinos**  
		`S1# show lldp neighbors`  

		`S1# show lldp neighbors detail`  

4. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/75087095-e531-4801-90c2-0617480d5679)  


### [VLAN](CiscoPacketTracer/ConfigVLAN.pkt)
1. **Descripción general**  
Las VLAN son divisiones lógicas de la red  que nos permiten distribuirla de manera que los dispositivos no se puedan comunicar todos entre todos, si no que estará restringida entre aquellos
que pertenezcan a una misma VLAN.  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/8ad25fd4-f90d-4eb9-99a8-aa80a3850e27)  

2. **Tipos de enlace**  
	- **Enlace de acceso**  
		- Tráfico de una única VLAN  
		- Conexión con los dispositivos finales  
	- **Enlace troncal**  
		- Tráfico de múltiples VLAN  
		- Conexión entre switches o de un switch con la capa superior  

![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/1c5adef9-9ab0-4c07-a3d2-f21c52880595)

3. **Ventajas de un diseño con VLAN**  
	- Dominios de difusión más pequeños  
	- Seguridad mejorada  
	- Mejora la eficiencia del departamento de TI  
	- Reducción de costes  
	- Mejor rendimiento  
	- Administración más simple de proyectos y aplicaciones

4. **Tipos de VLAN**  
	1. **VLAN predeterminada**  
		- Por defecto, VLAN 1  
	2. **VLAN de datos**  
	3. **VLAN nativa**  
		- Por defecto, VLAN 1  
		- Mismo en ambos extremos  
	4. **VLAN de administración**  
		- Por defecto, VLAN 1
	5. **VLAN de voz**  

5. **Etiquetado 802.1Q VLAN nativa**  
	1. Marcos etiquetados en la VLAN nativa  
		- Tráfico de la VLAN nativa no se debe etiquetar  
	2. Marcos sin etiquetas en la VLAN nativa  
		- Enlace troncal: Se asigna ID de la nativa al ID de la VLAN de puerto (PVID)  
		- Todo el tráfico sin etiquetar del puerto 802.1Q se envía según el valor de PVID

6. **Etiquetado VLAN de voz** 
	- **Puerto 1**  
		Conecta teléfono IP con el switch  
	- **Puerto 2**  
		Puerto interno  
	- **Puerto 3**  
		Conecta con el PC  

	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/c8848afc-8fc8-4158-b305-3ff85fa3b62b)

7. **Rango de VLAN en Switches**
	- **Rango normal VLAN**  
		- Redes pequeñas y medianas  
		- VLAN ID: 1-1005  
		- 1002-1005 reservadas  
		- Se guardan en vlan.dat (memoria flash)
	- **Rango extendido de VLAN**  
		- Proveedores de servicio y empresas globales  
		- VLAN ID: 1006-4094  
		- Se guardan en el archivo de configuración  

8. **Creación y borrado de VLAN**
	1. **Creación VLAN en un rango normal**  
	
		```
		Switch# configure terminal  
		Switch(config)# vlan vlan-id  
		Switch(config-vlan)# name vlan-name
		```  
	
	2. **Borrado de una VLAN de la memoria flash (permanente)**
	
		`Switch(config)# no vlan vlan-id`  

	3. **Borrado de toda la configuración de VLAN de la memoria flash (permanente)**
	
		`witch# delete flash:vlan.dat`  

9. **Puertos de acceso**
	```
	Switch# configure terminal  
	Switch(config)# interface interface-id  
	Switch(config-if)# switchport mode access  
	Switch(config-if)# switchport access vlan vlan-id
	```  

	```
	Switch# configure terminal  
	Switch(config)# interface interface-id  
	Switch(config-if)# no switchport access vlan
	```  
	
	- **VLAN de voz y datos**
		```
		Switch# configure terminal  
		Switch(config)# interface interface-id  
		Switch(config-if)# switchport mode access  
		Switch(config-if)# switchport access vlan vlan-id  
		Switch(config-if)# mls qos trust cos  
		Switch(config-if)# switchport voice vlan vlan-id
		```  
		
		
	- **Puertos troncales**
		```
		Switch# configure terminal  
		Switch(config)# interface interface-id  
		Switch(config-if)# switchport mode trunk  
		Switch(config-if)# switchport trunk native vlan vlan-id  
		Switch(config-if)# switchport trunk allowed vlan vlan-list
		```
		
		
10. **Verificación de la configuración**  
	`Switch(config)# show vlan brief`  

	`Switch(config)# show vlan id vlan-id`  

	`Switch(config)# show vlan name vlan-name`  

	`Switch(config)# show vlan summary`  

	- **VLAN de voz y datos**  
		`Switch(config)# show interface interface-id switchport`  

11. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/cd98cc69-e1f6-4ea9-beeb-865b5f509fbb)  

### DTP  
1. **Descripción general**  
	- Protocolo de capa 2 exclusivo de Cisco que se habilita de manera automática en los switches  
	- Maneja la negociación de enlaces troncales  
	- Una interfaz se puede establecer como troncal, de acceso o para negociar troncal con la interfaz vecina  
	- Ayuda al administrador a acelerar el proceso de configuración de la red  

2. **Modos de interfaz y configuración**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/b0de07f8-73fd-462b-98df-742b331e9dc1)  

3. **Resultados de una configuración**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/b015e64c-1879-42cd-becd-7e67978b2c84)  

4. **Verificación de la configuración**  
	`S1# show dtp interface fa0/1`

5. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/da06a93e-9651-4195-aad7-9d0b1974036b)  

### [VTP](CiscoPacketTracer/ConfigVTP.pkt)  
1. **Descripción general**  
	- Protocolo de capa 2 usado para administrar y configurar VLANs en los dispositivos Cisco  
	- Simplifica y centraliza la administración de las VLANs de una red, reduciendo así el número de fallos de configuración  
	- Se distinguen 3 modos de operación VTP: servidor, cliente y transparente  
	- VTP sólo aprende VLAN de rango normal (1-1005) almacenadas en el fichero vlan.dat  

2. **Modos de operacion de VTP**  
	1. **Servidor** (modo por defecto)  
		- Puede crear, borrar y modificar VLANs del dominio  
		- Todas las VLANs configuradas en el servidor se anuncian  

	2. **Cliente**  
		- No puede crear, borrar ni modificar VLANs del dominio  
		- Sincroniza su información con la que recibe de los anuncios del servidor  

	3. **Transparente**  
		- No procesa anuncios VTP, simplemente los reenvía  

3. **Anuncios VTP**
	1. **Anuncios de resumen** 
	Sincronización de la información de las VLAN dentro del dominio  

	2. **Anuncios de subconjunto**  
	Informa de cambios en alguna VLAN  

	3. **Publicación de solicitud**  
	Se envía cuando un cliente necesita actualizar la configuración  

4. **Configuración**  
	- Definir en el switch con rol de servidor las VLANs que se desea anunciar  
	- Definir como troncales los puertos que conectan los switches VTP  
		1. Versión VTP deseada  
			`Sw(config)# vtp version {1 | 2 | 3}`  	
		2. Modo VTP del switch  
			`Sw(config)# vtp mode {server | client | transparent}`  
		3. Dominio VTP  
			`Sw(config)# vtp domain domain_name`  
		4. Contraseña VTP  
			`Sw(config)# vtp password password`  

5. **Verificacióin de la configuración**  
	`Sw1(config)# do sh vtp status`  

6. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/188aa5d2-630b-4df8-981a-e6193110a060)  

	
- **Examen** realizado: [Certificado curso de seguridad de red en el ámbito corporativo - Capa 2 del modelo OSI](Certificados/certificado_curso_de_seguridad_de_red_en_el_ámbito_corporativo__capa_2_del_modelo_osi.pdf)

----------

## Seguridad de red en el ámbito corporativo: Capas 3 y 7 del modelo OSI
### Capa 3 - Capa de red
La capa de red es la tercera capa del modelo OSI y se encarga de proporcionar servicios de comunicación de extremo a extremo, permitiendo que los paquetes de datos viajen entre redes diferentes.   
La capa de red también se encarga de fragmentar y ensamblar los paquetes de datos para permitir una transmisión eficiente y segura a través de diferentes redes, y proporciona servicios de calidad de servicio (QoS) para garantizar que los paquetes se entreguen según prioridades establecidas.  
En resumen, las operaciones básicas de la capa 3 son:  
- Direccionamiento de dispositivos finales  
- Encapsulación  
- Enrutamiento  
- Desencapsulación  

1. **Características de IP**  
	- Puede haber una comunicación sin conexión (_A pesar de que no se sepa si el paquete llega, cuándo llegará o si se puede leer_)  
	- Máximo esfuerzo (_Enrutamiento rápido de paquetes, aunque algunos se puedan perder por el camino_)  
	- Independencia de los medios (_Inalámbrico, cobre, fibra_)  

2. **Paquete IPV4**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/5934e74e-ccca-43cf-9b17-3214e6d47eee)  

3. **Limitaciones IPV4**  
	- Agotamiento de las direcciones IPv4  
		- Solución temporal: **NAT**  
	- Falta de conectividad de extremo a extremo  
	- Mayor complejidad de la red
		- Solución óptima: **Transición a IPv6**  

4. **NAT: Traducción de direcciones**  
	La traducción de direcciones de red (NAT, por sus siglas en inglés de Network Address Translation) es un proceso utilizado en redes de computadoras para permitir que los dispositivos en una **red privada** tengan **acceso a Internet** o a otra **red pública** utilizando **una única dirección IP pública**.  
	En una red NAT, un router o dispositivo similar se utiliza como intermediario entre la red privada y la red pública, y asigna direcciones IP privadas a los dispositivos dentro de la red privada. Cuando un dispositivo en la red privada solicita acceso a Internet o a otra red pública, el router utiliza su dirección IP pública para enviar y recibir datos hacia y desde ese dispositivo.  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/b82a2340-7eb8-4397-a5c6-da82733622ce)  

	Rango de direcciones privadas  
	- 10.0.0.0 - 10.255.255.255  
	- 172.16.0.0 - 172.31.255.255  
	- 192.168.0.0 - 192.168.255.255  

5. **Paquete IPV6**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/fc67f894-372a-4ea5-b721-fa422217cdaf)  

6. **Modos de coexistencia de IPV4 e IPV6**  
	1. **Dual-stack**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/bd95ce27-a9e1-4489-bb23-bae86dfa1281)  

	2. **Tunnelling**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/87d36144-2f6c-45c9-b6ae-ce5a336917fe)  
	
	3. **Traducción**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/fa00882e-d8ae-4cab-817f-f6decdfdc09d)  

### Enrutamiento  
El elemento principal de la capa 3 es el Router. Éste determinará qué interfaz debe usar para el reenvío eligiendo la mejor ruta.

1. **Enrutamiento estático VS dinámico**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/1d972c6d-18cf-4318-8e9b-40f2ef536587)

2. **Clasificación del routing dinámico**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/be6d5ee0-092d-4d8f-9658-6dd52c2ec13b)  

3. **Conceptos del routing dinámico**  
	1. **Estructura de datos**  
		Tablas o bases de datos
	2. **Mensajes del protocolo de routing**  
		Intercambia información con vecinos
	3. **Algoritmo**  
		Determina el mejor camino

4. **Tabla de enrutamiento y elección de la mejor ruta**  
	Comando:  
	`show ip route`  
	1. **Elección de la mejor ruta según protocolo**  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/7f483104-8daf-4dfa-9bdd-f40eb4522df0)  

	2. **Principios de la tabla de routing**  
		- Cada router toma su **decisión por si solo**  
		- Las tablas de enrutamiento **no coinciden necesariamente**
		- La información de enrutamiento **no proporciona enrutamiento de retorno** al secundario  

	3. **Entradas de la tabla de routing**  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/ad984996-656f-4e46-ae70-a892945f1e13)  

	4. **Tipos de ruta**  
		1. **Redes conectadas directamente**  
			- La red se indica con una C seguido de la dirección IP y la máscara
			- La interfaz se indica con una L y un prefijo /32 (IPv4) o /128 (IPv6)  
		2. **[Rutas estáticas](CiscoPacketTracer/ConfigStaticRoutes.pkt)**
			- ip route 10.0.4.0 255.255.255.0 10.0.3.2
			- ipv6 route 2001:db8:acad:4::/64 2001:db8:acad:3::2
		3. **Rutas dinámicas**  
			- Las redes no se configuran manualmente, se descubren a través de otros routers  
		4. **Ruta predeterminada**
			- Se usa en ausencia de otra posible ruta que se ajuste mejor
			- Reduce el número de rutas de tabla
			- Tienen una entrada de ruta 0.0.0.0/0 (IPV4) o ::/0 (IPV6)
		5. **Mejor ruta**  
			- La mejor ruta se conoce también como la de coincidencia más larga  
			![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/c7c6865f-f751-436c-a6b0-dce8e66ddb5b)  
	
	5. **Tipos de rutas estáticas**  
		1. **Definición de la ruta estática**  
		- Ruta del siguiente salto (_Opción recomendada en interfaces que requieren de capa 2 - Ethernet_)  
		- Ruta conectada directamente  
		- Ruta completamente especificada  
			`Router(config)# ip route network-address subnet-mask { ip-address | exit-intf [ip-address] } [distance]`  
			```
			Router(config)# ipv6 unicast-routing
			Router(config)# ipv6 route ipv6-prefix/prefix-length { ipv6-address | exit-intf[ip-address] } [distance]
			```  
		2. **Ruta estática estándar**  
			```
			R1(config)# ip route 192.168.1.0 255.255.255.0 172.16.2.2
			R1(config)# ip route 192.168.1.0 255.255.255.0 s0/1/0
			R1(config)# ip route 192.168.1.0 255.255.255.0 s0/1/0 172.16.2.2
			```   
			```
			R1(config)# ipv6 route 2001:db8:cafe:1::/64 2001:db8:acad:2::2
			R1(config)# ipv6 route 2001:db8:cafe:1::/64 s0/1/0
			R1(config)# ipv6 route 2001:db8:cafe:1::/64 s0/1/0 fe80::2
			```   
		4. **Ruta estática predeterminada**  
			```
			R1(config)# ip route 0.0.0.0 0.0.0.0 172.16.2.2
			R1(config)# ip route 0.0.0.0 0.0.0.0 s0/0/0
			R1(config)# ip route 0.0.0.0 0.0.0.0 s0/0/0 172.16.2.2
			```   
			```
			R1(config)# ipv6 route ::/0 2001:db8:acad:2::2
			R1(config)# ipv6 route ::/0 s0/0/0
			R1(config)# ipv6 route ::/0 s0/0/0 fe80::2
			```   
		5. **Ruta estática flotante**  
			Distancia administrativa por defecto:  
			- Conectado directamente: 0  
			- Estática: 1  
			- BGP (externo): 20  
			- EIGRP: 90  
			- OSPF: 110  
			- RIP: 120  
			```
			R1(config)# ip route 0.0.0.0 0.0.0.0 172.16.2.2
			R1(config)# ip route 0.0.0.0 0.0.0.0 172.16.3.2 5
			```   
			```
			R1(config)# ipv6 route ::/0 2001:db8:acad:2::2
			R1(config)# ipv6 route ::/0 2001:db8:cafe:2::2 5
			```   
		6. **Ruta estática resumida**  
			```
			R1(config)# ip route 172.20.0.0 255.255.0.0 s0/0/0
			R1(config)# ip route 172.21.0.0 255.255.0.0 s0/0/0
			R1(config)# ip route 172.22.0.0 255.255.0.0 s0/0/0
			R1(config)# ip route 172.23.0.0 255.255.0.0 s0/0/0
			```   
			↓  
			`R1(config)# ip route 172.20.0.0 255.252.0.0 s0/0/0`  
		7. **Verificación de las rutas estáticas**  
			`Router# show ip route static`  
			`Router# show ip route 192.168.2.0`  
			`Router# show running-config | section ip route`  

	6. **Ventajas y desventajas**  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/fc87aa3b-d593-4d42-9952-c1818b5cdfd9)  

### RIP  
1. **Descripción general**
	- Protocolo de encaminamiento dinámico interior  
	- Puerto 520 de UDP  
	- Usa el número de saltos como métrica  
	- Para determinar el camino más corto utiliza el algoritmo de Bellman Ford  
	- Número máximo de saltos: 15  
	- Emplea la regla de horizonte dividido y el envenenamiento de rutas  
	- Actualmente existen 3 versiones: RIPv1, RIPv2 y RIPng (RIP para IPv6)  

2. **Comparativa RIPv1 y RIPv2**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/aed9fca2-2fb3-4358-a747-827903bcf747)  

3. **Modos de funcionamiento y mensajes**  
	1. **Modos de funcionamiento de las interfaces**  
		- **Activo**: Normalmente solo los router operan en este modo  
		- **Pasivo**: Normalmente conecta con usuarios finales  
	2. **Tipos de mensaje (sólo en interfaces activas)**
		- **Request**: Solicita parte o toda la tabla de rutas  
		- **Reply**:  
			- Respuesta a un request  
			- Actualización periódica  
			- Actualización por cambio en topología  
	3. **Tipos de temporizadores**  
		- **Temporizador periodíco** (_update timer_): 30 segundos  
		- **Temporizador de caducida**d (_invalid timer_): 180 segundos  
		- **Temporizador de purga** (_flush timer_): 240 segundos  
		- **Temporizador de retención** (_holddown timer_): 180 segundos  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/da564896-683f-4407-87d5-5f77374423d4)  
4. **Configuración**  
	- Configuración RIPv2
		```
		R1(config)# router rip
		R1(config-router)# version 2
		R1(config-router)# no auto-summary
		R1(config-router)# network network-address
		```  
	- Redistribución de rutas predeterminadas  
		```
		R1(config)# ip route 0.0.0.0 0.0.0.0 [next-hop-address | exit-intf]
		R1(config-router)# redistribute static
		```  
	- Interfaz pasiva (_usuario final_)  
		`R1(config-router)# passive-interface interface-id`  
	- Verificación de la configuración  
		`R1# show ip route`  
5. **Ventajas y desventajas**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/07783d95-99db-4552-ab0c-2b9defa48cf0)  

6. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/5acebe50-f5f7-4faf-a801-f17ff0f58829)  

### OSPF
1. **Descripción general**  
	- Protocolo de **encaminamiento dinámico interior**  
	- Se encapsula sobre el **protocolo IP (campo protocolo: 89)**  
	- Se tiene en **cuenta el ancho de banda para calcular la métrica**  
	- **Protocolo de estado de enlace y el concepto de áreas**  
	- **Existen 2 versiones**: OSPFv2 (OSPF para IPv4) y OSPFv3 (OSPF para IPv6)  
	- **Componentes de OSPF**:
		- Mensajes de protocolo de enrutamiento  
		- Estructura de datos  
		- Algoritmo: Dijkstra  

2. **Tipos de paquetes**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/4c9fb4cf-2edb-4b28-9b56-a6a31c727ff0)

3. **Estructuras de datos**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/35ca4c7f-c285-46be-8a26-b37b726d4ebd)

4. **Algoritmo de Dijkstra**  
	El algoritmo de Dijkstra es un algoritmo de búsqueda de caminos mínimos utilizado para encontrar la ruta más corta entre un nodo fuente y todos los demás nodos en un grafo ponderado. Es ampliamente utilizado en redes de comunicaciones y en la optimización de rutas de transporte.  
	Comienza desde el nodo fuente y explora de manera iterativa los nodos adyacentes, seleccionando el camino de menor peso en cada iteración, hasta que se hayan visitado todos los nodos. Durante el proceso, el algoritmo mantiene una lista de nodos visitados y sus distancias mínimas desde el nodo fuente, actualizando estas distancias a medida que se descubren rutas más cortas.  

5. **Área única y multiárea**  
	- **Area única**  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/2e946539-9f45-4d40-98fc-5325eb138f5c)  

	- **Multiárea**  
		![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/bb041fb1-2824-461a-a825-ed5ff8eb49db)  

6. **Tipos de Routers**
	- Designated Router (DR)  
	- Backup Designated Router (BDR)
	- Internal Router (IR)  
	- Area Border Router (ABR)  
	- Backbone Router (BR)  
	- Autonomous System Boundary Router (ASBR)  

7. **Funcionamiento del estado de enlace**  
	1. Establecimiento de adyacencias de vecinos 
	2. Intercambio de anuncios de estado de enlace  
	3. Crear la base de datos de estados de vínculo  
	4. Ejecutar el algoritmo SPF (Dijkstra)  
	5. Elección de la mejor ruta

8. **Tipos de estados**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/ad28b122-b453-4bbc-9d51-e81b7b6e23a2)

9. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/43ceb1ff-ff4e-4672-a1e2-baf0d80e6ec1)

### [HSRP](CiscoPacketTracer/ConfigHSRP.pkt)
1. **Descripción general**  
	- **Protocolo de capa 3 propiedad de Cisco**  
	- **Uso de puertas de enlace redundantes** (conmutación por fallo transparente)  
	- **Definición de MAC y dirección IP virtuales**  
	- Se forma un grupo HSRP compuesto por un **router activo** y un **router de respaldo** (elimina SPOF)  
	- Comunicación mediante la dirección **multicast 224.0.0.2 (versión 1) o 224.0.0.102 (versión 2) y el puerto UDP 1985**  

2. **Prioridad y preferncia**  
	- **Prioridad**  
		- Valor entre 0 y 255. Por defecto: 100  
		- Se elige como router activo el que tenga mayor prioridad  
		- Si las prioridades iguales, se elige aquel con la dirección IPv4 más alta  
	- Preferencia  
		- Fuerza un nuevo proceso de elección de HSRP  
		- Si se habilita, el router con la prioridad más alta asume el rol de activo  
		- Si la prioridad es igual en los routers, no se modifica el rol de activo  

3. **Estados**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/bf3d5401-eff6-46ff-97b7-82474a962093)  

4. **Configuración**  
	- **Configuración de router activo**  
		```
		R1(config)# interface interface-id
		R1(config-if)# standby version 2
		R1(config-if)# standby 1 ip virtual-ip-address
		R1(config-if)# standby 1 priority priority-value
		R1(config-if)# standby 1 preempt
		```  
	- **Configuración de router de respaldo**  
		```
		R2(config)# interface interface-id
		R2(config-if)# standby version 2
		R2(config-if)# standby 1 ip virtual-ip-address
		```  
	**Prioridad activo siempre mayor que prioridad de respaldo**  
	- **Verificación de la configuración**  
		`R1# show standby`  

5. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/b2b7d460-f4ad-4207-94d5-8a11585d860e)  

### Capa 7 - Capa de aplicación
La capa de aplicación es la última capa del modelo OSI y es la que está más cerca del usuario final. Esta capa proporciona una interfaz entre las aplicaciones del usuario y la red subyacente, y se encarga de proporcionar servicios de red específicos de aplicación.  
La capa de aplicación incluye una variedad de protocolos y servicios, como HTTP, SMTP, FTP y DNS.  
Ejemplos de aplicaciones podrían ser una terminal virtual, gestión de ficheros, servicio de correo o servicio de directorio.

1. **La capa de aplicación en TCP/IP**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/9b5ca070-9246-417e-88dd-e5c8dc5f2474)

2. **Modelo cliente/servidor**  
	- **Cliente**: Solicita información  
	- **Servidor**: Provee información  
	- Puede **requerir autenticación**  
	- **Red centralizada** (Servidor en el centro)  
	- **Problema SPOF** (Single Point Of Failure)  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/15d31d66-5bd6-4c6c-bef8-2930bc2f1046)  

3. **Modelo P2P (_Peer to peer_)**  
Consta de dos partes: **Red P2P** y **Aplicaciones P2P**  
	1. **Red P2P**  
		- Cada PC es **servidor** y **cliente**
		- **Compartir** recursos (conexión a Internet, juegos…)  
	2. **Aplicación P2P**
		- Permite que cada dispositivo actúe como cliente y servidor  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/1bdb4533-5c3b-4495-aff1-b441c690ee30)  
	
4. **Protocolos de la capa de aplicación**  
	1. **Nombre de dominio**  
		- DNS  
	2. **Configuración de dispositivos**  
		- DHCP  
	3. **Email**  
		- SMTP  
		- POP3  
		- IMAP  
	4. **Transferencia de ficheros**  
		- FTP  
		- TFTP  
	5. **Web**  
		- HTTP  
		- HTTPS  

### DNS
1. **Descripción general**  
	- Sistema de nombres de dominio (DNS)  
	- Traduce nombres de dominios web a la dirección IP del servidor en el que se aloja la página web  
	- Se encapsula sobre el puerto 53 tanto de UDP como TCP  
	- Sigue una arquitectura de cliente/servidor  
	- Utiliza una base de datos distribuida y jerárquica

2. **Jerarquía DNS**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/62873abb-5b71-49e5-9709-aa36ff3616c8)  

3. **Funcionamiento DNS**  
La primera consulta se hace al **servidor DNS local del sistema operativo**. Se comprueba la **memoria caché**.  
En caso de no encontrarse, la consulta se envía al servidor **DNS del ISP**.  

### [DCHP](CiscoPacketTracer/ConfigDHCP.pkt)
1. **Descripción general**  
	- Protocolo de red de tipo **cliente/servidor**  
	- Se encarga de la a**signación dinámica de direcciones IP y otros parámetros de configuración de red**  
	- Se encapsula sobre el **puerto 67 (servidor) y 68 (cliente) de UDP**  
	- Un servidor DHCP es **escalable** y relativamente **fácil de administrar**  
	- Las direcciones IP se asignan un tiempo configurable (**período de concesión**)  
	- **DHCPv6** proporciona **servicios similares** pero **sin compartir el gateway**  

2. **Funcionamiento**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/4047aedb-95ae-4f9f-a332-584653355c8f)  

3. **Renovar una dirección temporal**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/871071b8-c1a3-44b5-b240-1842b74df7a0)  

4. **Configuración** 
- **Exclusión de direcciones IP**  
	`R1(config)# ip dhcp excluded-address ip-address`  

- **Configuración pool DHCP**  
	`R1(config)# ip dhcp pool pool-name`  

	- **Red**  
		`R1(dhcp-config)# network network-address mask`  

	- **Puerta de enlace**  
		`R1(dhcp-config)# default-router gateway-address`  

	- **Servidor DNS**  
		`R1(dhcp-config)# dns-server dns-server-address`  

	- **Nombre de dominio**  
		`R1(dhcp-config)# domain-name domain`  

	- **Duración de la concesión**	 
		`R1(dhcp-config)# lease { days [hours [ minutes]] | infinite }`  

- **Desactivar DHCP**  
	`R1(config)# no service dhcp`  

- **Activar DHCP**  
	`R1(config)# service dhcp`  

5. **Verificación de la configuración**  
	`R1# show running-config | section dhcp`  
	`R1# show ip dhcp binding`  

	- **Verificación del cliente DHCP**  
		`> ipconfig /all`  

6. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/13488b45-5a87-4a79-93c5-a77c6be44c60)  
	
### [SNMP](CiscoPacketTracer/ConfigSNMP.pkt)
1. **Descripción general**  
	- Protocolo de la capa de aplicación que **facilita el intercambio de información de administración de los dispositivos de red**  
	- Se encapsula sobre el **puerto 161 y el 162 (traps) de UDP**  
	- Se distinguen **4 componentes principales**: **administrador** SNMP (NMS), **agente** SNMP, **dispositivos** y **recursos** administrados por SNMP y MIB  
	- Arquitectura simple basada en el **modelo cliente/servidor**  
	- Existen **3 versiones** del protocolo: **SNMPv1, SNMPv2c y SNMPv3**  

2. **Tipos de mensajes SNMP**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/0b947f02-ccf7-416f-9527-8604b086b95a)  

3. **Versiones**  
	1. **SNMPv1 y v2c**  
		Usan coincidencia de cadena de comunidad para autenticación  
	2. **SNMPv3**  
		- **noAuthNoPriv**: Sin autenticación (solo nombre de usuario sin contraseña) ni privacidad  
		- **authNoPriv**: Con autenticación (contraseña con MD5 o SHA) pero sin privacidad  
		- **authPriv**: Con autenticación (contraseña con MD5 o SHA) y privacidad (cifrado DES o AES)  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/a36888d0-af38-41ab-9b61-d15d80b37fb5)  

4. **Configuración SNMPv2c**  
	- **Cadena de comunidad de sólo lectura**  
		No permite cambiar la configuración del dispositivo  
		`R1(config)# snmp-server community password ro`  

	- **Cadena de comunidad de lectura y escritura**  
		Permite modificar la configuración del dispositivo  
		`R1(config)# snmp-server community password rw`  

5. **Fallos de seguridad y posibles mitigaciones**  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/937b6ef9-94c7-4585-90a9-2d5456990d25)  


- **Examen** realizado: [Certificado curso de seguridad de red en el ámbito corporativo: Capas 3 y 7 del modelo OSI](Certificados/certificado_curso_de_seguridad_de_red_en_el_ámbito_corporativo__capas_3_y_7_del_modelo_osi.pdf)

----------

## Curso de triage informático
### Introducción

1. **Definición de malware**  
Acrónimo del inglés “Malicious Software”, traducido como código malicioso.  
Se puede definir como el código o programa informático que esta específicamente diseñado para provocar un daño, una mal función, un bloqueo, una extracción de información o un acceso no autorizado a una plataforma tecnológica.  

2. **Características del malware**  
	- **Persistencia**  
		Capacidad para permanecer en el sistema  
	- **Ofuscación**  
		Condición de ser confuso y dificultar la identificación del mismo  
	- **Backdoor**  
		Posibilidad de establecer conexiones remotas con un operador humano o con C&C (_Command and control_)  
	- **FUD**  
		Full Undetectable

2. **Tipos de malware**  
	- **Adware** (_genera publicidad_)  
	- **Clickers** (**Redirige y hace click en sitios especificos**)  
	- **Ramsonware** / **Lockers** (_Bloquea o encripta datos_)  
	- **Spyware** (_Extrae información_)  
	- **Worm** (_Aquel capaz de extenderse a otros dispositivos por la red_)  
	- **Phishing** (_Señuelo para solicitar datos, claves, y cualquier otra información_)  
	- **Troyano** (_Malware encapsulado en un software_)  
	- **Keylogger** (_Registrador de pulsaciones en teclado_)  
	- **RAT** (_Administración remota_)  
	- **RootKit** (_Kit de herramientas de explotación_)  

3. **Procesos**  
Toda actividad realizada en un ordenador genera uno o más procesos para ofrecer al usuario el resultado deseado.  
Un programa, por ejemplo, es un cúmulo de instrucciones ordenadas en un paquete para la obtención de resultados determinados, siendo los procesos las ejecuciones individuales de cada una de las instrucciones.  

4. **Conexiones, puertos y protocolos**  
Un puerto es una interfaz a través de la cual se pueden enviar y recibir diferentes tipos de datos. Existen los puertos lógicos (_software_) y los puertos físicos (_hardware_).
Los puertos se dividen según su utilidad y función:  
	- **Puertos de red**  
		Ofrecen capacidad de interconexión con otros dispositivos a nivel de red (Internet / Ethernet)  
	- **Puertos inalámbricos**  
		Conectividad Bluetooth, Wireless, infrarrojo, Wi-Fi
	- **Puertos para unidades de almacenamiento**  
		IDE, SATA, SCSI, SAS, USB
	- **Pueros de alimentación de eneergía**  
		Conector IEC, Enchufe, USB  
Los puertos lógicos llevan una numeración aprobada internacionalmente por la IANA (_Internet Assigned Numbers Authority_) para determinar qué tipo de datos o portocolo de comunicación aplica a los puertos preesstablecidos.
Según la tabla de asignación de puertos determinados, son los más importantes:  
	- 20 y 21 FTP  
	- 22 SSH  
	- 23, 95 y 107 Telnet  
	- 25 SMTP (email)  
	-66 Oracle SQLnet  
	- 67 y 68 DHCP  
	- 80 HTTP  
	- 110 POP3 (email)  
	- 143, 220, 993 IMAP (email)  
	- 443 HTTPS  
	- 465 SMTPS (email seguridad)  
	- 1433 SQL Server  
	- 1521 Oracle Listener  
	- 3306 MySQL  
	- 6881 y 6969 BitTorrent  
	
5. **Diferenciación entre Hacker y Cracker**  
Hoy en día, la RAE ha modificado la definición de **hacker**, aceptando además de: “pirata informático” a incluir en segunda opción: “la persona experta en el manejo de computadoras, que se ocupa de la seguridad de los sistemas y de desarrollar técnicas de mejora”.  
Sin embargo, la RAE mantiene en esta definición, la que correspondería a la de un **cracker**, quien realmente es la persona que usa el conocimiento informático para actividades ilegales.

- **Test repaso** realizado: Curso de triage informático - Introducción.
![image](https://user-images.githubusercontent.com/93931447/236833696-13b3f21e-3ada-45a1-aafe-367fb3473aab.png)

### Búsqueda de malware
1. **Metadatos**  
Conjunto estructurado ed datos que describen a otros ddaots, a su estructura interna y a sus servicios, cuyo propósito es incrementar la identificación y la individualidad de cada archivo o paquete de datos.  
Es decir, aunque una persona cree un documento en Word y lo copie varias veces, aunque en su forma y contenido sea idéntico, sus metadatos proporcionarán información que harán de que cada uno de ellos sea un elemento único y diferente.
2. **Firma y descripción**
En el momento de verificar un software o proceso en el ordenaor, observaremos que existen nombres de fabricantes en cada de uno de ellos, así como una descripción del producto o el software asociado a cada proceso.  
A esta traza o secuencia que se obtiene al ejecutar un código se le denomina firma, siendo este casi siempre identificado por un **hash**.
El hash es el algoritmo matemático que transforma cualquier bloque arbitrario de datos en una nueva serie de caracteres con una longitud fija.  
4. **Análisis heurístico**  
La heurística es un conjunto de **técnicas y procedimientos** para determinar según la cantidad de puntos a favot o en contra, la condición o característica de un software o proceso.  
Utilizar el análisis heruístico sería, en este caso, analizar qué es lo que pretende realizar el ejecutable y al detectar de qué se trata, bloquearlo instantaneamente si se trata de una acción maliciosa.
5. **Herramientas**  
Hay dos tipos de herramientas que podemos tener:  
	- **Local**  
	Software instalado en nuestro ordenador para su protección (_por ej, anitivirus_)
	- **Online**  
	Aplicación web que nos permite revisar arhivos sin ejecutarlos en nuestro ordeador o que se remiten a una web para su escaneo (_por ej, [VirusTotal](https://www.virustotal.com/gui/home/upload)_)

- **Test repaso** realizado: Curso de triage informático - Búsqueda de malware.
![image](https://user-images.githubusercontent.com/93931447/236868772-6ccbce95-63e7-473d-9536-6bc48bf42893.png)

### Análisis de archivos ejecutables
1. **Paquete**  
Serie de programas que se distribuyen conjuntamente de forma que cada uno de ellos complemente o necesita de los otros.  
También se puede definir como una colección de arhivos de código fuente o binarios con un de archivos de instrucciones que especifican qué hacer con cada uno de ellos. Todos los archivos van comprimidos según un formato especial que depende de la distribución.  
Se debe tener en cuenta que descomprimir y desempaquetar no significa lo mismo.
Estos paquetes contienen:  
	- **Datos**  
		Conjunto de archivos que serán instalados y/o manipulados. Son los archivos del programa, bibliotecas, etc.  
	- **Cabecera**  
		Instrucciones para el proceso de instalación y configuración, además de información como: datos técnicos del mismo paquete, dependencias, incompatibilidades, descripción, datos del responsable del paquete y archivos con instrucciones para comprobar dependencias, preparación del sistema, etc.  

2. **Ruta de instalación**  
Ubicación designada por el sistema para realizar la instalación de un software. La ruta puede ser modificada por el usuario mediante instalaciones personalizadas.  

3. **Ruta de ejecución**  
Toda aplicación tiene un fichero .exe que es el ejecutable de la misma, por lo tanto, basta con ahcer click sobre este  archivo para que la aplicación se lance automáticamente.  
Por defecto, en Windows 10 las aplicaciones instaladas las podemos encontrar bajo la ruta `C:\Arhivos de programa` o `C:\Archivos de programa (x86)`, siendo `C:` la unidad principal donde tendremos instalado el sistema operativo de Windows. Esto está definido por las instrucciones predefinidas en el código y no es modificable por el usuario.  

4. **Uso de recursos**  
Un recurso del sistema es cualquier componente físico o virtual de disponibilidad limitada dentro de un sistema informático. Cada dispositivo conectado en un sistema informatico es un recurso, asi como cada componente interno del sistema también es un recurso. Los recursos del sistema virtual incluyen archivos, conexiones de red y áreas de memoria.  
La gestión de reecursos incluye tanto la prevención de fugas de recursos (_no liberar un recurso cuando u nproceso ha terminado de utilizarlo_) como el tratamiento de la contención de recursos (_cuando varios procesos desean acceder a un recurso limitado_).  
Por ejemplo, recursos informáticos (_de capacidad_) pueden ser: **memoria**, capacidad de **almacenamiento** o la **CPU**.  
Un recurso libre es la capacidad de un recurso con la que cuenta un ordenador en un determinado momento. Por ejemplo, el recurso de memoria RAM libre en un determinado momento puede ser 450 MB de un total de memoria de 1 GB.  
Un recurso también puede ser un dispositivo; por ejemplo, un ordenador que cuenta con una impresora, cuenta con dicho recurso.

5. **Establecimiento de conexiones**  
En informática, una **conexión** puede refererirse a:  
	1. El punto exacto donde se realiza un enlace entre dispositivos o sistemas.  
	También puede hacer referencia al enlace completo establecido, no sóilo el punto específico. En algunos contextos, conexión puede ser sinónimo de acceso. Puede ser una conexión digital o analógica.
	2. **Conexión cableada**  
	3. **Conexión inalámbrica**  
	4. **Conexión a una red**, con el objetivo de transferir datos usualmente en ambos sentidos  
		- Conexión a internet 
		- Conexión punto a punto
		- Conexión dial-up
	5. **Conexión a una base de datos**  
	6. **Conexión virtual o VPN**  
	7. **Conexión de un dispositivo a un ordenador**  
	8. **Conexión a un servicio online**, siendo sinónimo de _iniciar sesión_  
	9. **Conexión por acceso remoto**  
	
- **Test repaso** realizado: Curso de triage informático - Análisis de archivos ejecutables.
![image](https://user-images.githubusercontent.com/93931447/236928529-f4a53b20-dfa0-4442-95bd-22bdfc6e22ef.png)

### Emails y pishing  
1. **Emails sospechosos y archivos infectados**  
Existen varias maneras de detectar un correo electrónico falso y evitar caer en cualquier estafa de pishing.  
Algunas de las maneras de identificarlos son:  
- El **dominio** de la dirección email **no coincide** con el de la empresa  
- **Faltas de ortografía** o de **concordancia**  
- El correo **solicita información personal**  
- El **asunto** del correo es de **"máxima alerta"**  
- Generalmente incluyen **archivos adjuntos** 
 
2. **Como comprobar el auténtico remitente de un correo**  
Aprender a identficar el auténtico remitente de un correo electrónico puede ser útil cuando se sospecha que un mensaje que ha llegado a nuestro buzón puede ser pishing, es decir, parecido a un correo de spam.  
Además de hablar directamente con esa persona para avisarle de un posible virus en su equipo, podemos asegurarnos identificando la dirección IP del servidor o del equipo desde el que se ha enviado el mensaje.  

A continuación, como ejemplo, veremos como se hace desde **Gmail**:  
	- Clickar en la flecha situada a la derecha del asunto y entrar en _"Mostrar original"_  
Al revisar el contenido, podemos observar la IP desde donde se ha mandado el correo.  
Además, en la ID del mensaje (_Message-ID_) veremos de qué servidor viene el correo.  
El código de Received viene a decir que se ha enviado desde una IP concreta, a través de qué web, y la hora concreta del servidor.
		
3. **Archivos infectados**  
La mayoria de los incidentes de seguridad se inician al hacer **click** en algún enlace de una p**ágina web comprometida** o en un **archivo recibido y no verificado** por un antivirus o pos nosotros mismos.  
La forma de revisar los paquetes de datos o ficheros sospechosos es hacerles un **scan** con el **antivirus** instalado en local o subiéndolo a páginas especializadas como [_VirusTotal_](https://www.virustotal.com/gui/home/upload), entre otras.
- **Test repaso** realizado: Curso de triage informático - Emails y pishing.
![image](https://user-images.githubusercontent.com/93931447/236934611-7db27513-741e-4d17-be59-994b7de35bae.png)

- **Examen** realizado: [Certificado curso de triage informático](Certificados/certificado_curso_de_triage_informático.pdf)

----------

## Curso de desarrollo seguro

1. **Introducción**  
	> “ La protección de la información frente  
	> a las distintas amenazas al objeto de  
	> garantizar el buen funcionamiento. ”  

La seguridad se basa en cuatro principios:  
- **Autenticidad** - _qué usuario está haciendo que actividadd_  
- **Confidencialidad** - _nadie que no deba ver una información no pueda verla_  
- **Integridad** - _que la información sea veraz y no pueda modificarla nadie que no pueda hacerlo, y saber que no se han modificado_  
- **Disponibilidad** - _necesitamos que los servicios y procesos estén activos_  

La **información**, como el software, tiene un ciclo de vida, siendo importante la seguridad en cualquiera de sus pasos o ciclos:  
- Creación  
- Distribución  
- Uso  
- Mantenimiento  
- Destrucción  

La seguridad, como hemos comentado anteriormente, requiere de un **mantenimiento continuado**, siendo las **personas** el **factor fundamental** (_ya que son estás, según la seguridad, la parte más peligrosa dado que no impera el sentido común_).  
Ésta debe estar **integrada** en **todos** los **procesos** y **procedimientos**, requiriendo de la **implicación** de **todos**.  

2. **Ciclo de desarrollo de software**  
La pregunta que nos hacemos en este apartado es: _**¿Por qué desarrollar de manera segura?**_, siendo la respuesta que “_el coste de arreglar un fallo de seguridad aumenta exponencialmente con el tiempo_”.  
Fases del **Secure SDLC**:  
- **Requisitos**  
	En la fase de análisis y requisitos se deben tener en cuenta:  
	- Los requisitos y objetivos de la aplicación  
	- Posibles problemas  
	- Tecnología  
	- Frameworks  
	- Lenguajes  
	- Funcionales y no funcionales (_definen el funcionamiento de la aplicación_)  
	**Tener en cuenta la seguiridad desde esta primera fase es vital para ahorrar en el futuro.**  
	Algunos de los consejos que podemos tomar para llevar esto adelante son:  
		- Solventar vulnerabilidades conocidas  
		- Realizar un análisis de riesgos 
		- Usar tecnologías con mantenimiento y actualizaciones y mantenerlas actualizadas  
		- Usar frameworks extendidos y respaldados por la comunidad o alguna empresa  
- **Arquitectura y diseño**  
	En la fase de arquitectura y diseño se deben tener en cuenta: 
	- Definición de servicios  
	- Interfaces  
	- Protocolos  
	- Sistemas  
	- Redes  
	- Flujo de datos  
	Para tener en cuenta la seguridad en la arquitecturea y el diseño hay que tener en cuenta, al menos, los siguientes puntos:  
		- Identificar las vulnerabilidades en las tecnologías escogidas y protegerlas  
		- Asegurar los recursos de datos  
		- Emplear protocolos de comunicación seguros  
		- Estudiar estándares y arquitecturas típicas  
	Todas las preguntas que debemos hacernos para una arquitectura segura la podemos encontrar en las _cheat sheets_ de [Owasp](https://cheatsheetseries.owasp.org/index.html).  
- **Implementación**  
	En la fase de implementación, que será la fase de **desarrollo de la aplicación** debemos tener en cuenta:  
	- Seguir buenas prácticas  
	- Evitar el uso de funciones _deprecated_  
	- Controlar errores  
	- Controlar flujos de datos  
	- Mantener los procesos lo más simples posibles  
	Una de las frases más usadas para esta fase es: **_“Piensa mal y acertarás”_**
- **Testeo**  
	La fase de testeo se compone de:  
	- Plan de pruebas  
	- Tests unitarios  
	- Tests de integración  
	- Tests de los sistemas  
	- Automatización de tests  
	- Revisión de tests  
	Para añadir seguridad en la fase de testeo, se tendrá en cuenta:  
		- Testear las vulnerabilidades conocidas para asegurarnos de que están protegidas  
		- Fuzz testing  
		_Técnica de prueba de software que se utiliza para encontrar errores y vulnerabilidades en un programa mediante la entrada de datos aleatorios o inesperados en el programa. El objetivo del fuzz testing es descubrir errores y fallas que puedan ser explotados por atacantes malintencionados o que puedan afectar la estabilidad y funcionalidad del programa en situaciones inesperadas._  
		- Pentesting básico  
		_El objetivo del pentesting es simular un ataque informático para descubrir y explotar vulnerabilidades y brechas de seguridad que puedan ser utilizadas por un atacante malintencionado._  
- **Despliegue**  
	En esta fase los pasos a tener en cuenta quedarían de la siguiente manera:  
	- Preparación del entorno de producción  
	- Configuración de servicios  
	- Configuración de sistemas  
	- Gestión de usuarios  
	- Gestion de operaciones  
	**Es importante recordar que el enotrno de testing es distinto del mundo del mundo real.**  
	Para aplicar seguridad en esta fase, tendremos en cuenta:  
		- Configuración segura de cada servicio
		- Configuración segura de cada sistema  
		- Gestión segura de los peermisos y operaciones  
- **Mantenimiento**  
	A tener en cuenta:  
	- Revisión de bugs  
	- Nuevas funcionalidades  
	- Optimización de código  
	Para mantener la seguridad en el apartado de mantenimiento:  
		- Versión actualizadas de cada framework o librería  
		- Actualizar tecnologías  
		- Actualizar procedimientos  
		- Revisión de logs  
		
3. **Validación de entradas y codificación de salidas**  
	1. **Validación de entradas**
	Cualquier dato introducido por un usuario **es susceptible de ocasionar errores**, por tanto, es **imprescindible** controlar la inserción de datos a nuestro software.  
	Para entender la importancia de la validación de entradas se explicará el ejemplo de SQLi - inyección de código SQL:  
		- Es un ataque de inyección de código  
		- Permite a un atacante ejecutar código SQL sobre nuestra base de datos  
	Con una simple sentencia como: 
	`SELECT * FROM users WHERE username=’blabla’ or ‘1’=‘1’;`  
	sin un correcto control le daría al atacante todas las entradas de nuestra base de datos dado que la condición `‘1’=‘1’` siempre se cumpliría en la sentencia.  
		1. **Validación de ficheros subidos**  
			- Si nuestro software o aplicación permite subir ficheros a un determinado servidor, debemos cuidar la seguridad de esta funcionalidad.  
			- Un atacante podría tomar el control de nuestra máquina mediante este tipo de ataques.  
		2. **Valicadión de entradas**  
			- Realizar todas las validaciones en un sistema de confianza  
			- Especificar la codificación de caracteres para todas las entradas (UTF-8...)  
			- Identifica todas las entradas de datos y clasifícalas en confiables y no confiables. Valida las no confiables.  
			- Crea una rutina centralizada de validación de entradas para tu aplicación  
			- Canonicaliza los datos antes de validarlos (codifica todos igual)  
			- Cualquier fallo de validación debe incurrir en el rechazo de la entrada  
			- Valida todos los datos que provenga del cliente  
			- Valida rangos de datos, tamaño de datos y tipos de datos  
			- Si es posible, valida los datos empleando una lista blanca  
			- Si es necesario para tu aplicación utilizar caracteres raros, asegurate de implementar controles de entrada y salida específicos para estos  

	2. **Codificación de salidas**  
	¿Por qué es necesaria la validación de entradas?  
		- Las entradas de datos pueden ser imprescindibles, haciendo imposible la validación de la entrada perfecta
		- Debido al funcionamiento de la aplicación, puede ser necesario admitir caracteres _raros_  
		- Los datos recibidos pueden ser empleados en muchos contextos (_JS, CSS, HTML..._)  
	Estas tres razones hacen necesario emplear la codificación de salidas.  
	Uno de los ejemplos que podemos tener en cuenta  es el XSS (_Cross site scripting_).  
		- Es un ataque de inyección de código
		- Permite a un atacante ejecutar código javascript malicioso  
	La codificación de salidas es, en resumen:  
		- El mejor método para prevenir XSS y SQLi  
		- El objetivo principal es convertir entradas de datos no confiables en datos seguros que mostrar  
	Como cliente se puede enviar `<script>alert(1)</script>`, pero como servidor devolveriamos algo parecido a `&ltscript&gtalert(1)&lt&#x2Fscript&gt`, haciendo el posible código ejecutable inofensivo.  
	La codificación de salidas se deberían hacer siguiendo los siguientes consejos:  
		- La codificación debe ser hecha en un sistema de confianza  
		- Utilizar una rutina testeada y estándar para la codificación de cada tipo de datos  
		- Codificar todos los caracteres a menos que sean seguros para el intérprete previsto  
		- Sanitizar todas las salidas de datos no confiables destinadas a comandos o consultas: OS, SQL, XML o LDAP  

	3. **Criptografía**  
	¿Por qué cifrar la información?
		- Una de las máximas de la seguridad informática es la **confidencialidad**  
		- En el siglo XXI el valor está en los datos  
		- No queremos revelar información relevante de nuestro negocio ni de nuestros usuarios  
		- Para seguir la LOPD (Ley de protección de datos)  
	En cuanto a la criptografía:  
		- Todas las funciones criptográficas empleadas deben implementarse en un sistema de confianza  
		- Proteger los “secretos maestros” de accesos no autorizados  
		- Manejar el sistema ante errores de los módulos criptográficos  
		- Todos los números, nombres de archivo, GUIDs y cadenas que deban ser aleatorios/as y no adivinables, serán generados con un módulo testeado y aprobado que cumpla con ese requisito  
		- Los módulos criptográficos utilizados deben ser compatibles con FIPS 140-2 o algún estándar similar  
		- Debe establecerse una política y un proceso para la gestión de claves criptográficas  

	4. **Buffer overflow**  
	El buffer overflow es el excesivo relleno de una variable o recurso que resulta en un problema con el manejo de memoria, pudiendo incurrir en modificaciones de memoria, manipulación y acceso a direcciones de memoria y crasheos de programas.  
	Para evitar este tipo de problemas las opciones que tenemos son:  
		- Auditar el código  
		- Conocer la documentación del lenguaje y sus vulnerabilidades conocidas: Estándares de desarrollo, funciones inseguras, etc.  
		- Usar herramientas de compilación específicas: StackShield, StackGuard, etc.  

	7. **Autenticación y manejo de contraseñas**  
	Como hemos visto anteriormente, uno de los principios de las seguridad es la propia **autenticación**.  
	La funcionalidad básica para asignar permisos de acceso a determinados recursos, según roles, grupos, dueños, etc.  
	Un fallo de autenticación podría ocasionar graves daños, alguien podría hacerse pasar por un usuario que no es.  
	- **Cómo asegurar la autenticación**:  
		1. **Existen multiples ataques posibles**  
		2. Deben usarse soluciones **testadas** y **extendidas** para cada lenguaje que **simplifiquen** este proceso y que cuenten con **actualizaciones periódicas**  
		3. Debemos **realizar** todas **comprobaciones** en un sistema de **confianza**  
		4. **Centraliza** todos los servicios de autenticación del software  
		5. Todos los controles de autenticación deben **fallar de manera segura**  
		6. **Almacena las contraseñas hasheadas** (no MD5) **con sal** y asegurate de que **solo** la **aplicación** puede **escribir** en esa tabla/colección  
		7. **No mostrar** qué parte de la autenticación ha fallado: usuario o contraseña  
		8. **Utiliza** el método **HTTP POST** para autenticar en caso de aplicación web  
		9. **Obliga** a los usuarios a emplear **contraseñas complejas** que incluyan números, letras minúsculas, mayúsculas y símbolos y tengan cuantos más caracteres mejor  
		10. **No muestres la contraseña en la pantalla** del usuario cuando la introduzca  
		11. **Limita** el número de **intentos** de **login fallidos** y **bloquea** la cuenta si se sobrepasa  
		12. **Notifica** a los usuarios cuando ocurra un reseteo de sus contraseñas y **asegura** este proceso tanto o más como la propia creación de usuarios  
		13. **No usar** ningún **mail** de usuario para notificar que no estuviera **previamente registrado**  
		14. Si es necesario, **obliga a los usuarios a cambiar la contraseña cada cierto tiempo**  
		15. **Cambia** todas las contraseñas **por defecto**  
		16. **Usa doble factor de autenticación** para recursos e información muy sensible  

	- **Manejo de sesiones**  
	El resumen de la importancia de las sesiones sería:  
		- Permiten guardar información relativa de cada usuario que opera usando nuestro software  
		- Debemos intentar registrar todas las operaciones que se realicen, así como el actor que la ejecuta  
		- Puede servir para trazar errores, mejorar la interfaz de usuario o comprobar un funnel de ventas  
		- Contienen demasiada información relevante para no cuidarla  
	De esta manera, deberíamos tener claro que es algo a proteger, lo cual podemos hacer de la siguiente manera:  
		- Usar los **controles de manejo de sesión** que implemente el servidor o framework e **identificar** estas sesiones como las **únicas válidas**  
		- Los **identificadores de sesión** deben **generarse** en un **sistema de confianza** y de **manera aleatoria**  
		- Las **funciones de logout** deben **eliminar** la conexión de una sesión **por completo** y estar disponibles en todas las pantallas de la aplicación  
		- **Terminar las sesiones periódicamente**, incluso aunque la sesión esté activa  
		- Tras cada re-autenticación debe **crearse una nueva sesión**, no mantener la antigua  
		- Los id de sesión **solo deben estar presentes en la cookie**  
		- **Reciclar** los id de sesión periódicamente  
		- Configurar el **atributo** `secure` para las cookies  
			
	- **Manejo de errors y logs**  
	1. La importancia del manejo de errores y logs se debe a:  
		- Un error puede **desvelar información sensible**  
		- Un log **guarda** la **traza** de **cualquier operación** que se realice en nuestra aplicación  
		- **La integridad del log es vital para la detección de ataques, malas prácticas o acciones no permitidas**  
		- Un correcto manejo de errores **mejora** la experiencia de usuario en una aplicación  

	2. **¿Cómo podemos asegurar esto?**  
		- **No desvelar información relevante** en los errores (detalles del sistema, información de cuentas o ids de sesión)  
		- **No mostrar mensajes de debug**  
		- Implementar mensajes de error **genéricos**  
		- **Liberar la memoria** en uso cuando ocurra un error  
		- Todos los sistemas de log deben **implementarse** en un **sistema de confianza**  
		- Asgurarse de que los mensajes de error que **incluyan código no se ejecuten** como tal en ninguna UI  
		- **Restringir el acceso** a los logs  
		- **No almacenar información relevante en los logs** (detalles del sistema, ids de sesión o contraseñas)  
		- **Validar** la **integridad** de los logs usando **hashes**  

	3. **¿Qué guardar en los logs?**  
		- **Fallos** de **validación** de **entrada**  
		- **Intentos** de **autenticación**  
		- **Fallos** de acceso de **control**  
		- Eventos de **manipulación** de datos  
		- **Intentos** de **login** con tokens **expirados** o **inválidos**  
		- **Excepciones** del sistema  
		- Funciones de **administración**, incluyendo **cambios** en la **configuración de seguridad**  
		- **Fallos** en** conexiones TLS**  
		- **Fallos criptográficos**  

4. **Seguridad en la configuración del entorno**  
	- **Control de accesos**  
	El control de acceso es importante para evitar que cualquier usuario no vea nada que no deba ver en el software.  
	De esta manera:  
		1. Se persevera la confidencialidad de los datos  
		2. Se protege la información de los usuarios  
		3. Se protegen los recursos de nuestro software que solo deben ser accionados o usados por algunos roles o usuarios específicos  

	- **Cómo controlar los accesos**  
		1. Emplear únicamente objetos de sistemas de confianza para tomar decisiones de autorización de accesos  
		2. Emplear un único componente en tu software que revise la autorización de accesos  
		3. Los controles de accesos deben **fallar de manera segura**  
		4. **Rechazar** cualquier acceso **ante cualquier caída o error** en la información de configuración de la seguridad  
		5. **Forzar la autenticación** para cualquier petición (aunque proceda del propio servidor)  
		6. Si deben almacenarse datos sobre el estado en el cliente, **usar encriptación** y **chequear la integridad en el servidor**  
		7. **Limitar el número de transacciones** en el tiempo por usuario  
		8. **Desactivar** las cuentas **sin uso**  
		9. **Minimizar los privilegios** que se otorgan a cualquier usuario al mínimo posible  
		10. Crear una **política** de control de accesos  

	- **Es importante restringir los accesos a:**  
		1. Ficheros o otros recursos  
		2. URLs protegidas  
		3. Funciones protegidas  
		4. Referencias directas a objetos  
		5. Servicios protegidos  
		6. Datos de aplicación  
		7. Atributos de usuarios y datos y políticas empleadas por los controles de acceso  
		8. Información de configuración de seguridad

	- **Protección de datos**  
		- **Acerca de la información**  
			1. Son el **oro del siglo XXI**  
			2. En ellos reside el **verdadero valor** de nuestro software  
			3. Las **leyes** exigen una **alta protección** para según qué tipo de datos  
			4. Los usuarios **demandan seguridad** en sus datos y **les preocupa** de cara a usar una aplicación o no  
		- **Cómo proteger los datos:**  
			1.  Usar el principio de **mínimos privilegios**  
			2.  **Proteger** cualquier **copia en caché** o de seguridad de datos sensibles y **eliminar** las copias temporales  
			3.  **Encriptar** la información secreta almacenada por el software  
			4.  **Proteger el código fuente**  
			5.  **Eliminar comentarios del código** visible para el usuario para evitar mostrar información del backend  
			6.  **Eliminar y restringir** el **acceso** a **documentación** innecesaria de la aplicación  
			7.  **No incluir** información sensible en los parámetros de las peticiones **GET**  
			8.  **No autocompletar** formularios sensibles _como las contraseñas_  
			9.  **No guardar** en memoria **caché** la información de páginas con **datos sensibles** (_Cache-Control:no-store_)  
			10.  La aplicación debe **soportar** la **eliminación** de datos sensibles cuando estos no sean necesarios  
			11.  **Implementar un control de accesos seguro**, con una **política robusta** y una buena configuracion de ésta  

	- **Seguridad de las comunicaciones**  
	La comunicación se define como una **conexión funcional** entre dos sistemas, programas, dispositivos o componentes de cualquier tipo que permite el **intercambio de información**  
		- **Cómo proteger las comunicaciones**  
			1. Implementa el cifrado para la transmisión de cualquier información sensible  
			2. Emplea TLS siempre o algún cifrado discreto cuando no sea posible  
			3. El certificado TLS debe ser válido, no estar expirado y tener el nombre de dominio bien  
			4. Una conexión TLS fallida no debe abrir una conexión insegura  
			5. Emplea TLS para todas las conexiones que requieran autenticación  
			6. Emplea TLS para conexiones a sistemas externos que impliquen el uso de información sensible  
			7. Emplea una única implementación estándar TLS que esté bien configurada  

	- **Configuración del sistema**  
	Entendemos por sistema a la **máquina física** o **virtual** que contiene el software, así como todas las dependencias necesarias para que funcione correctamente.  
	Puede ser una red de sistemas conectados (_microservicios_) o un solo sistema con varios contenedores.  
	La manera de asegurar la configuración del sistema sería:  
		1. Asegurarse de que todos los **servidores**, **frameworks** y **componentes** están **actualizados**, **parcheados** y en su **última versión estable**  
		2. **Desactivar el directory listing**  
		3. **Restringir los privilegios** al mínimo para el servidor, los procesos y las cuentas de usuario  
		4. Cuando ocurra una excepción del sistema, debe **fallar de manera segura**  
		5. **Eliminar** cualquier fichero o funcionalidad **innecesaria**  
		6. **Eliminar** cualquier **código** o **comentario** no pensado para un entorno de **producción**  
		7. **No mostrar la estructura de fichero en robots.txt**, anida todos los ficheros a ocultar bajo un directorio  
		8. **Controlar** y **definir** los **métodos HTTP** que permites en cada página, **desactivar los innecesarios**  
		9. **Eliminar cabeceras innecesarias** relacionadas con el sistema operativo  
		10. Implementar un **sistema de gestión de activos** y **registra el software** y los **componentes** del sistema en él  
		11. Implementar un **software de control de cambios** para **gestionar** y **guardar** los cambios del código en **producción** y **desarrollo**  
		12. **Separar** y **delimitar** los entornos de **desarrollo** y **producción** y **limitae** y **controlar** el **acceso** al primero  

	- **Seguridad en bases de datos**  
	Las bases de datos son parte fundamental de casi cualquier software actual. Existen muchas y de diversos tipos, pero todas basan su funcionamiento en los métodos CRUD.  
	La información es parte fundamental de cualquier software, así que hay que **salvaguardar su identidad**.  
	Las mejores maneras de asegurar las bases de datos serían:  
		1. Usar **queries fuertemente parametrizadas**  
		2. **Validar** las entradas y **codificar** las salidas  
		3. Darle a la aplicación los **mínimos privilegios** posibles cuando acceda a la BBDD  
		4. Usar **contraseñas seguras**  
		5. La configuración de la conexión con las BBDD no debe estar _hardcodeada_, debe estar en un **fichero de configuración** o en un **sistema de confianza** y **cifrada**
		6. **Cerrar la conexión** lo antes posible  
		7. **Eliminar** y **modificar** cualquier contraseña o configuraicón **por defecto** de la base de datos que pudiera exponerla  
		8. **Desactivar** cualquier **funcionalidad innecesaria** de la BBDD
		9. **Eliminar** cualquier **contenido** que viniera **por defecto**  
		10. **Eliminar** cualquier **cuenta** que viniera **por defecto**  
	
	- **Seguridad al manerjar y tratar ficheros**  
	Hay que tener en cuentra que el software no es más que un montón de código guardado en ficheros. Por esta razón, las aplicaciones pueden requerir que los usuarios puedan subir ficheros de diversa índole.  
	Aunque así sea, un fichero puede ser inofesivo o altamente peligroso, así que no se debe confiar en la buena fe del usuario o en el origen de su fichero, así que hay que tener en cuenta ciertos motivos a la hora de que esto ocurra:  
		1. **No** se debe **entregar información** dada por el usuario **directamente a una función**  
		2. **Requerir autenticación** antes de subir cualquier fichero  
		3. **Limitar** y **validar** los tipos de los fichero subidos (_extensión y cabecera_)  
		4. **No guardar** ficheros en el **mismo contexto** de la aplicación, deben ir a la **BBDD** o a **otro servidor**  
		5. **No permitir subir** ningún **fichero** que pueda **interpretar un servidor web**  
		6. **Desactivar la ejecución de ficheros en cualquier directorio que no lo requiera**  
		7. **Crear una lista blanca** de tipos de ficheros subidos y nombres que tienen permiso para ser leídos o ejecutados  
		8. **No enviar** o **mostrar** nunca **rutas absolutas** al usuario  
		9. Asegurarse de que los **recursos** y **ficheros** de la aplicación son de **sólo lectura**  
		10. **Escanear** los fichero subidos en **busca** de **malware**  
	
	- **Manejo de memoria**  
	La memoria de un ordenador nos permite ejecutar los procesos de nuestro software, almacenar informacion en caché de rápido acceso y almacenar información a largo plazo, por lo que es **fundamental** cuidar la memoria de nuestros sistemas para un buen funcionamiento.  
	El cloud computing ha incrementado la preocupación por el buen uso de la memoria, ya que ésta cuesta dinero.  
	Para cuidar la memoria de nuestros equipos, los factores a tener en cuenta serían:  
		1. Emplear **controles** de **entrada** y **salida** para datos no confiables  
		2. Revisar que los **buffer** son tan **grandes** como deben ser  
		3. Cuidar que el **buffer** de **destino** tenga la **misma longitud** que el **origen** en los casos específicos (_funciones como strncpy()_)  
		4. **Truncar** las cadenas de entrada antes de pasarlas a funciones de copia o concatenación  
		5. **Liberar la memoria** cuando se complete una función o proceso  
		6. **Evitar el uso de funciones vulnerable**s (_printf, strcpy..._)

5. **Resumen y comentarios**  
De todo lo aprendido anteriormente, podemos resumirlo en:  
	- **KISS** _Keep it simple and stupid_
	- **Mínimos privilegios**  
	- Ninguna configuración **por defecto**  
	- Todo **actualizado**  
	- **Revisar** siempre la **seguridad** en **sistemas de confianza** 
	- **Desconfianza total en el usuario**  
	- Conocer la **tecnología**, **lenguaje** o **framework** que se vaya a utilizar  

También, de este curso es relevante comentar que todas las prácticas se han realizado en una máquina virtual, siendo en este caso [VirtualBox](https://www.virtualbox.org/), en la cual vamos a tener una máquina vulnerable que obtendremos gracias a OWASP llamada [Broken Web Applications Project](https://sourceforge.net/projects/owaspbwa/) ofreciendo a nuestra disposición con una serie de aplicaciones web inseguras y rotas para poder hacer pruebas. Esto lo complementaremos con un contenedor Docker de [Kali  Linux](https://www.kali.org/), lo que junto a [Burp](https://portswigger.net/burp) nos dará todas las herramientas necesarias para realizar todas las pruebas de seguridad que deseemos.

- **Examen** realizado: [Certificado curso de desarrollo seguro](Certificados/certificado_curso_de_desarrollo_seguro.pdf).

----------

## Introducción al Esquema Nacional de Seguridad

### El Esquema Nacional de Seguridad  
El Esquema Nacional de Seguridad (ENS) es una normativa española que establece los **principios** y **requisitos** que deben cumplir las **administraciones públicas** en **materia** de **seguridad de la información**.
Su enfoque principal es **garantizar la protección adecuada de la información** que se maneja en el ámbito de la administración pública, incluyendo la **clasificación**, el **acceso**, el **tratamiento**, la **conservación** y la **destrucción** de la información.
El alcance del ENS **abarca todas las administraciones públicas españolas**, incluyendo las entidades del sector público local, autonómico y estatal. También se aplica a aquellas **empresas que prestan servicios** a las administraciones públicas y **que manejan información clasificada o sensible**.  
Entre los requisitos establecidos se encuentran la **identificación y análisis de riesgos**, la **elaboración de políticas y procedimientos de seguridad**, la **formación de los empleados** y la **gestión de incidentes de seguridad**.  
Es decir, el Esquema Nacional de Seguridad tiene como objetivo establecer un **marco de referencia común para garantizar la seguridad de la información** en el ámbito de la administración pública, siendo su aplicación obligatoria para todas las administraciones públicas y empresas que presten servicio a éstas.

### Marco organizativo  
El marco organizativo del ENS establece los **elementos necesarios** para garantizar la seguridad de la información en el ámbito de la administración pública. Entre estos elementos, destacan la política de seguridad, el comité de seguridad y los roles y responsabilidades.  
1. **Política de seguridad**  
Es el conjunto de directrices plasmadas en un document oescrito que rigen la forma en que una organización gestiona y protege la información y los servicios que considera críticos.  
Los apartados recomendados en ésta son los siguientes:
	- Misión u objetivo del organismo  
	- Marco normativo  
	- Orgnización de seguridad  
	- Concienciación y formación  
	- Postura para la gestión de riesgos  
	- Proceso de revisión de la Política  
2. **Comité de seguridad**  
El comité de seguridad es un órgano de dirección encargado de garantizar la aplicación de la política de seguridad. Este comité debe estar integrado por representantes de la dirección y de las áreas responsables de la gestión de la seguridad de la información. Entre sus funciones, se encuentran la definición de la estrategia de seguridad, la identificación de los riesgos y la supervisión de la aplicación de las medidas de seguridad.  
3. **Roles y responsabilidades**  
El ENS establece los roles y responsabilidades que deben asumir las diferentes áreas de una organización en la gestión de la seguridad de la información. En el siguiente gráfico se muestra el resumen de los mismos:  
	![image](https://github.com/Lissz3/RosadoRibasIsabel_Ciberseguridad/assets/93931447/97e6134c-49d7-423a-956e-7aa6b8fcdb69)  
### Marco operacional  
El marco operacional establece los elementos necesarios para la aplicación práctica de la política de seguridad definida en el marco organizativo. Entre estos elementos, destacan la planificación de la seguridad, el acceso a la información, la explotación de servicios internos y externos, y la continuidad de servicio y monitorización.  
1. **Planificación de la seguridad**  
	La planificación de la seguridad es el proceso que permite identificar los riesgos a los que está expuesta la información y definir las medidas necesarias para protegerla. La planificación de la seguridad debe ser basada en el análisis de riesgos, y debe incluir la definición de objetivos y la identificación de recursos necesarios para la gestión de la seguridad de la información.  
2. **Acceso a la información**  
	Se establecen los requisitos para el acceso a la información, que deben ser definidos en función de la naturaleza de la información y de los roles y responsabilidades de los usuarios. Entre los requisitos establecidos se encuentran la autenticación, la autorización y el control de acceso, así como la gestión de las contraseñas.  
3. **Explotación de servicios internos y externos**  
	Requisitos para la explotación de servicios internos y externos, incluyendo la selección de proveedores de servicios en función de su capacidad para garantizar la seguridad de la información, ya que la entidad también es responsable de los riesgos de estos servicios. También se establecen requisitos para la gestión de contratos, la gestión de incidentes y la auditoría de los servicios.  
4. **Continuidad de servicio y monitorización**  
	El ENS establece los requisitos para garantizar la continuidad de servicio en caso de interrupciones o incidentes,además de los requisitos para la monitorización de los sistemas y la gestión de incidentes de seguridad, incluyendo la notificación de incidentes a las autoridades competentes.  
### Medidas de protección
Anteriormente se ha comentado como el ENS busca establecer un marco de referencia común para garantizar la seguridad de la información. De la misma manera que establece directrices sobre el marco organizativo o el marco operacional también establece unas medidas de protección necesarias entre las que se encuentran:  
1. Protección de instalaciones  
2. Gestión del personal  
3. Protección de equipos  
4. Protección de las comunicaciones  
5. Protección de soportes  
6. Desarrollo seguro  
7. Protección de la información  
8. Protección de los servicios  

### Análisis de riesgos
El análisis de riesgos es un proceso fundamental en la gestión de la seguridad de la información, y una parte esencial del ENS. El objetivo del análisis de riesgos es identificar los posibles riesgos a la seguridad de la información, evaluar su impacto y probabilidad, y determinar las medidas necesarias para reducir o mitigar los riesgos identificados.  
Dentro de éste análisis haremos hincapié en:  
1. **Identificación de activos y amenazas**  
Esta fase consiste en identificar los activos de información y los recursos asociados que se deben proteger, y las amenazas que pueden afectarlos. Se debe considerar tanto las amenazas internas como las externas, incluyendo las amenazas físicas, lógicas y humanas.  
2. **Análisis de riesgos**  
En esta fase se evalúa la probabilidad e impacto de las amenazas identificadas en la fase anterior. Se debe evaluar la vulnerabilidad de los activos de información, la probabilidad de que se produzca una amenaza, y el impacto que tendría si se produjera. A partir de esta evaluación se determinan los niveles de riesgo asociados a cada amenaza.  

Como ya habíamos comentado anteriormente, el cálculo de la evaluación del riesgo es el siguiente: **RIESGO = PROBABILIDAD X IMPACTO**.
	
Para realizar esta sección, se puede hacer uso de la herramienta [PILAR del CCN](https://pilar.ccn-cert.cni.es/index.php), la cual nos ayudará a realizar una evaluación y la identificación de las debilidades y vulnerabilidad, proporcionando una evaluación objetiva y estandarizada que nos ayudará a comprender mejor el cumplimiento normativo del ENS.  

### Adecuación y mantenimiento  
Dentro de la adecuación y mantenimiento, concretamente hablaremos de la implatanción de medidas técnicas y de la redacción de procedimientos operativos. Además veremos el uso de la herramienta INES, la cual se puede implementar con PILAR.
1. **Implantación de medidas técnicas**  
Existen diferentes tipos de medidas técnicas, divididas en las siguientes categorías:  
	- **Prevención:** Impedir que la amenaza se materialice  
	- **Disuasión:** Informar de consecuencias  
	- **Protección:** Proteger de explotación de riesgos  
	- **Detección y reacción:** Localizar y reportar incidentes  
	- **Recuperación:** Volver al estado normal  
Los puntos clave para las médidas técnicas sewgún las propiedades de la seguridad son:  
	- **Integridad:** Protección de la información (_firewalls, antimalware_)  
	- **Confidencialidad:** Control de acceso  
	- **Disponibilidad:** Backups, redundancia, anti-DoS  
	- **Autenticidad:** Firmas y certificados  
	- **Trazabilidad:** Logs, inventario de activos
2. **Redacción de procedimientos operativos**  
El ENS requiere que existan evidencias de cumplimiento para adecuarse a éste, siendo:  
	- Documentación de los procedimientos  
	- Registro de incidencias o eventos  
	- Evaluación interna y prueba de funcionamiento
	Aunque en categoría Básica los procesos pueden ser reproducibles pero no definidos, se recomienda documentar y definir como prueba innegable de cumplimiento.  
Algunas de las recomendaciones para la redaccion de procedimientos son:  
	- Agrupar controles VS Separación de documento por control  
	- No utilizar nombres propios sino cargos  
	- Detalle solo en lo necesario  
	- Procedimientos personales de la entidad  
	Aunque en categoría Básica los procesos pueden ser reproducibles pero no definidos, se recomienda documentar y definir como prueba innegable de cumplimiento.  

Otra recomendación para la redacción de procedimientos sería cumplir con los requisitos y preguntas de la auditoría, que podemos consultar en el la Guía de Seguridad de las TIC - [CCN-STIC 808 - Anexo III](https://www.ccn-cert.cni.es/series-ccn-stic/800-guia-esquema-nacional-de-seguridad/2404-ccn-stic-808-anexo-iii-verificacion-del-cumplimiento-del-ens.html).


3. **Herramienta INES**  
INES es la herramienta del CCN para recogida de información y seguimiento del ENS. Dispone de las diferentes secciones:  
	1. **Identificación del organismo**: Datos de la entidad  
	2. **Categorización de los sistemas**: BÁSICA, MEDIA, ALTA → C I D A T  
	3. **Análisis y gestión de riesgos**: Información de su estado y activos  
	4. **Actividades organizativas**: Preguntas sobre roles, desarrollo de la política de seguridad y gestión de la seguridad.  
	5. **Recursos**: Equipo de seguridad, dedicación, tareas, presupuesto STIC 
	6. **Medidas de seguridad**: Controles ENS {org, op, mp}  
	7. **Medidas de interconexión**: Preguntas sobre conexión a internet y arquitectura de protección perimetral, acceso remoto y herramientas de seguridad que se disponen.  
	8. **Aplicación de la seguridad**: Preguntas sobre identificación y autenticación de usuarios internos y externos, servicios externos y subcontratados, direccionamiento IP, gestión de cambios, continuidad y formación.  
	9. **Gestión de incidentes**: Conteo de incidentes de interrupción y resto en número de días/horas y tiempo en resolverlos  
	10. **Auditorías**: Para categoría MEDIA y ALTA → superar auditoría al menos cada 2 años. Información sobre la auditoría (tipo, nº no conformidades)  
	11.** Indicadores clave de riesgo**  
		Puntos de seguridad de importancia:  
		- Gestión de equipos (dominio)
		- % Equipos personales con uso laboral y de eso, los administrados por la entidad (BYOD)  
		- Número de personas de Seguridad TIC que han causado baja  
Como podemos observar, alguno de los pasos anteriores lo hemos realizado con la herramienta PILAR, desde la cual podremos importar los valores y añadirlos a INES.
- **Examen** realizado: [Certificado curso de introducción al Esquema Nacional de Seguridad](Certificados/certificado_curso_de_introducción_al_esquema_nacional_de_seguridad_(ens).pdf)
