Hace tiempo que empecé a tener curiosidad por la ciberseguridad y cada día tenía más ganas de aprender de ello. Cada día que buscaba información por internet y empezaba a entender como funcionaba a alto nivel, me di cuenta que es la rama de la informática que más me ha apasionado aprender en menos tiempo. Entonces empecé a mirar qué certificación realizar, que fuera apta para mis pocos conocimientos prácticos en ciberseguridad y elegí EJPT - eLearnSecurity Junior Penetration Tester. 

Decidí estudiar esta certificación por 2 motivos:
- Es 100% práctica y es todo lo que necesitaba, a nivel teórico hay muchas webs por internet donde aprender y a nivel práctico claro, por supuesto, tenemos Tryhackme y HTB. Pero necesitaba sentir como sería realizar Pentesting de forma real y aunque no sea lo mismo que a nivel laboral, es un modo fantástico de estar cerca de ello.
- El aprendizaje es gratuito, no pagas NADA. Sé que muchos al leer esto pensarán - tio, que son 50€ al mes por aprender y adquirir conocimientos, no es para tanto! 
Bueno, cuando pagas más de 2000€ en conseguir ciertas certificaciones de alto nivel, días y días de estudio con duro trabajo, casi sin dormir, dejando cosas importantes de lado, importantes como la familia, amigos, aficciones, etc.. pensando cada momento que tenía ganas de descansar, que esto iba a ser para mejorar y desarrolar mi carrera. Y después de todo ese esfuerzo, satisfacción, alegría, emoción, inexplicable, el único comentario "si hay Feedback" es que no tienes experiencia.


Esta vez me gustaría hacer un review de como me fué en la certificación,  que sentí realizando el proceso. Quizás esto responde a tus preguntas de si estás preparado para ello, si te ves con fuerzas.
https://github.com/sromanhu/EJPT/blob/main/ElearnSecurity%20EJPT%20Junior%20Penetration%20Tester.JPG

1- En primer lugar, para preparar la certificación no necesitas más que ganas de aprender y esfuerzo por practicar. Todo ello de forma gratuita en la web de INE.
https://my.ine.com/CyberSecurity/learning-paths/a223968e-3a74-45ed-884d-2d16760b8bbd/penetration-testing-student   - Lukaskz Mikula 
Aquí tienes un temario que te explica todos los apartados necesarios de aprendizaje, con videos y labs de práctica.

2- Es un exámen 100% práctico, empiezas el exámen cuando quieras y tienes 72 horas para realizarlo, las respuestas son tipo test.
¿A qué se refiere con tipo test?, pues tienes 20 preguntas que responder con 4 respuestas (multirespuesta) y las respuestas las encuentras realizando pentesting a las máquinas.
Es importante saber, que tienes que saber hacer de todo y es correlativo:
       - Si no sabes entender una PCAP de Wireshark, no puedes conocer las redes a las que no accedes directamente.
       - Si sabes las redes pero no hacer pivoting, no puedes acceder a los targets.
       ...

El modo es a través VPN que abrirás en la máquina de KALI, con el acceso que te dan en la propia web donde realizas la compra del exámen. Es importante conocer lo siguiente, ya que en mi caso tuve un problema realizando un ataque con Metasploit, que no entendía porqué no funcionaba y resulta que la máquina se quedó colgada.
Para resolverlo accedes a la web del exámen y haces un "Reset". No un reset a la vpn de KALI, si no en la propia web.

3- Su dificultad depende de tus conocimientos y la práctica que hayas llevado acabo. Si es verdad que al principio acabé algo estresado, ¿pero lo consideras dificil? No.
Los motivos son que puedes probar y probar lo que quieras, intentar con diferentes herramientas, buscar información del uso de esas herramientas que en principio desconocias, vamos lo que se define como prueba - error - prueba - aprendizaje.
        - Nunca he trabajado de Ciberseguridad
        - He leído mucho y mucho por internet
        - Realizo habitualmente CTF y HTB
        - Estudié meses y conseguí aprobar el CBROPS 200-201
        - He estudiado y probado todo lo aprendido en INE, tanto a nivel de los laboratorios que nos ofrecen como en las propias máquinas HTB.
        
4- Cuando me preguntan si me ha servido de algo siempre digo lo mismo, no. Por no tener experiencia en ciberseguridad, casi da igual lo que tengas, si no es aprobando una certificación de nivel como el CeH o el OSCP, no te va a servir de mucho el EJPT, pienso lo mismo del CBROPS.

5- La preparación del EJPT seún la web de Elearning es la siguiente:
        - TCP/IP
        - IP routing
        - LAN protocols and devices
        - HTTP and web technologies
        - Essential penetration testing processes and methodologies
        - Basic vulnerability assessment of networks
        - Basic vulnerability assessment of web applications
        - Exploitation with Metasploit
        - Simple web application manual exploitation
        - Basic information gathering and reconnaissance
        - Simple scanning and profiling the target

6- Tips de Examen:
        - Escanear con Wireshark para descubrir ciertos objetivos que te pedirá el exámen.
        - Descubrimiento de Hosts, puertos, servicios y sus vulnerabilidades (Pueder usar nmap, Nessus, todo lo que necesites)
        - Pentesting de Servicios 
        - Pivoting
        - Forzar contraseñas con Hydra
        - Descifrar contraseñas con John the Ripper
        - Descubrir directorios ocultos con Dirbuster o scripts (nmap)
        - Fuzzing
        - Descubrir respuestas en web, pueden estar ocultas en el código fuente o tienes que realizar inyección XSS, SQL, etc.
        - SQLMAP
        - Wireshark
        - Metasploit
 
7 - Es muy importante que realices una buena enumeración, es una de las cosas que tenía en cuenta en los CTF, pero aquí es mucho más importante. Y esto es porque atacas varias máquinas diferentes, no es una en concreto como harías en HTB y aparte tienes tiempo (suficiente si llevas la situación controlada y poco a poco sin estrés).
En mi caso lo realicé tipo s4vitar, es la persona que hico despertar mi curiosidad mucho más allá que lo que sentía. 
Te creas un directorio de trabajo, realizas carpetas para cada apartado de enumeración y vas almacenando distintos tipos de escaneo. 

8 - El proceso de resolución es conseguir ciertos objetivos. Averiguar contraseñas (a nivel local, FTP), descifrar hashes, acceso a BBDD, etc.. 
Si necesitas ayuda puedes encontrarme en Linkedin y puedes preguntarme lo que necesites!!
https://www.linkedin.com/in/sergio-roman-hurtado-033a8023/
