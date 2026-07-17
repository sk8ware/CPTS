## Resumen

HTB Academy fue creada para ofrecer una formación guiada y práctica en ciberseguridad, complementando el enfoque competitivo y de caja negra de las máquinas de Hack The Box.

Su metodología busca desarrollar conocimientos técnicos, pensamiento analítico y experiencia práctica mediante laboratorios, ejercicios y evaluaciones.

Para desempeñarse correctamente como pentester es necesario comprender distintas áreas de TI, entre ellas:

- Linux y Windows.
    
- Redes y protocolos.
    
- Aplicaciones web.
    
- Bases de datos.
    
- Scripting.
    
- Active Directory.
    
- Servicios corporativos.
    

Un pentester no necesita ser experto en todas las áreas, pero debe comprender las tecnologías que está evaluando para identificar errores, configuraciones inseguras y posibles rutas de ataque.

---

## Proceso de una prueba de penetración

El proceso general de pentesting se divide en las siguientes fases:

1. Pre-Engagement.
    
2. Information Gathering.
    
3. Vulnerability Assessment.
    
4. Exploitation.
    
5. Post-Exploitation.
    
6. Lateral Movement.
    
7. Proof of Concept.
    
8. Post-Engagement.
    

Estas fases no siempre son lineales. Durante una evaluación puede ser necesario regresar a etapas anteriores para recopilar más información o buscar nuevas rutas de ataque.

---

## 1. Pre-Engagement

En esta fase se establecen por escrito todos los aspectos de la evaluación:

- Alcance.
    
- Objetivos.
    
- Sistemas autorizados.
    
- Restricciones.
    
- Horarios de prueba.
    
- Reglas de enfrentamiento.
    
- Responsabilidades de cada parte.
    

El pentester debe confirmar que todas las actividades estén autorizadas antes de comenzar.

---

## 2. Information Gathering

Consiste en identificar y recopilar información sobre los sistemas objetivo.

Puede incluir:

- Direcciones IP.
    
- Dominios y subdominios.
    
- Puertos abiertos.
    
- Servicios expuestos.
    
- Tecnologías utilizadas.
    
- Usuarios y correos.
    
- Aplicaciones web.
    
- Información pública mediante OSINT.
    

Una recopilación completa evita perder tiempo durante la explotación y permite identificar rutas de ataque más efectivas.

---

## 3. Vulnerability Assessment

En esta fase se analiza la información recopilada para identificar vulnerabilidades y configuraciones incorrectas.

Se utilizan dos enfoques:

- Escaneo automatizado de vulnerabilidades conocidas.
    
- Análisis manual basado en la lógica, configuración y funcionamiento del sistema.
    

Los resultados pueden conducir a explotación, post-explotación, movimiento lateral o a una nueva fase de recopilación de información.

---

## 4. Exploitation

La explotación consiste en aprovechar una vulnerabilidad identificada para obtener acceso a un sistema o aplicación.

Después de conseguir acceso inicial, se debe recopilar información interna para determinar:

- Usuario comprometido.
    
- Privilegios disponibles.
    
- Sistema operativo.
    
- Servicios locales.
    
- Interfaces de red.
    
- Credenciales almacenadas.
    
- Posibles rutas de escalada.
    

---

## 5. Post-Exploitation

En esta fase se realizan actividades después de obtener acceso al sistema.

El principal objetivo suele ser escalar privilegios hasta obtener permisos administrativos o root.

También se realiza pillaging, que consiste en buscar información útil dentro del sistema, como:

- Credenciales.
    
- Archivos de configuración.
    
- Claves privadas.
    
- Tokens.
    
- Historiales de comandos.
    
- Bases de datos.
    
- Información de red.
    

---

## 6. Lateral Movement

El movimiento lateral consiste en utilizar un sistema comprometido para acceder a otros equipos de la red.

Puede realizarse mediante:

- Credenciales reutilizadas.
    
- Servicios internos.
    
- Protocolos de administración remota.
    
- Sistemas con múltiples interfaces de red.
    
- Pivoting y tunneling.
    
- Relaciones de confianza en Active Directory.
    

No siempre es necesario tener privilegios administrativos para moverse lateralmente.

---

## 7. Proof of Concept

La prueba de concepto demuestra que una vulnerabilidad existe y puede ser explotada.

Debe permitir que el cliente reproduzca el hallazgo de manera controlada.

Una PoC puede incluir:

- Pasos de reproducción.
    
- Solicitudes HTTP.
    
- Comandos utilizados.
    
- Capturas de pantalla.
    
- Código de explotación.
    
- Evidencias obtenidas.
    
- Impacto demostrado.
    

La PoC debe ser clara, segura y evitar causar daños innecesarios.

---

## 8. Post-Engagement

Esta es la fase final de la evaluación.

Incluye:

- Eliminación de archivos transferidos.
    
- Cierre de shells o accesos creados.
    
- Eliminación de usuarios temporales.
    
- Restauración de cambios realizados.
    
- Organización de evidencias.
    
- Revisión de notas.
    
- Elaboración del informe.
    
- Presentación de resultados al cliente.
    

Todos los cambios realizados durante el pentest deben quedar documentados.

---

## Módulos fundamentales

Antes de realizar ataques avanzados, HTB recomienda dominar:

- Learning Process.
    
- Linux Fundamentals.
    
- Windows Fundamentals.
    
- Introduction to Networking.
    
- Introduction to Web Applications.
    
- Web Requests.
    
- JavaScript Deobfuscation.
    
- Introduction to Active Directory.
    
- Getting Started.
    

Estos módulos proporcionan las bases necesarias para comprender los sistemas que serán evaluados.

---

## Módulos de enumeración

La recopilación de información se desarrolla mediante:

- Network Enumeration with Nmap.
    
- Footprinting.
    
- Information Gathering – Web Edition.
    
- OSINT: Corporate Recon.
    

El objetivo es construir una visión completa del entorno antes de intentar explotar vulnerabilidades.

---

## Módulos de explotación

La ruta incluye técnicas relacionadas con:

- Password Attacks.
    
- Attacking Common Services.
    
- Pivoting, Tunneling and Port Forwarding.
    
- Active Directory Enumeration and Attacks.
    
- Web Proxies.
    
- Ffuf.
    
- Login Brute Forcing.
    
- SQL Injection.
    
- SQLMap.
    
- XSS.
    
- File Inclusion.
    
- Command Injection.
    
- Web Attacks.
    
- Common Applications.
    

---

## Módulos de post-explotación

Después de conseguir acceso, se estudian:

- Linux Privilege Escalation.
    
- Windows Privilege Escalation.
    
- Pillaging.
    
- Movimiento lateral.
    
- Automatización mediante Python.
    

El objetivo es determinar hasta dónde podría avanzar un atacante dentro del entorno comprometido.

---

## Documentación y reporte

La toma de notas debe realizarse durante toda la evaluación.

Se deben registrar:

- Fecha y hora.
    
- Dirección IP.
    
- Sistema afectado.
    
- Comando ejecutado.
    
- Resultado obtenido.
    
- Credenciales encontradas.
    
- Archivos transferidos.
    
- Cambios realizados.
    
- Evidencias.
    
- Recomendaciones.
    

Un pentest no está completo hasta que los resultados se comunican mediante un informe claro, técnico y reproducible.

---

## Comandos utilizados

Esta clase es conceptual y no presenta comandos específicos.

Los comandos prácticos se estudian posteriormente en módulos como:

- Nmap.
    
- Footprinting.
    
- File Transfers.
    
- Shells and Payloads.
    
- Metasploit.
    
- Password Attacks.
    
- Active Directory.
    
- Linux y Windows Privilege Escalation.
    

## Idea principal

> Un pentest profesional no consiste únicamente en explotar vulnerabilidades. Requiere planificación, recopilación exhaustiva de información, análisis, documentación, control del alcance y comunicación clara con el cliente.