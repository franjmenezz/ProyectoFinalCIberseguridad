Proyecto Final de Ciberseguridad – 4Geeks Academy (Pentesting + DFIR)
Este repositorio documenta un proyecto completo de pentesting y respuesta a incidentes realizado como si estuviera trabajando como pentester/analista de ciberseguridad para 4Geeks Academy, sobre un servidor Debian crítico que presenta indicios de compromiso.
​

El objetivo es reconstruir el ataque (DFIR), validar técnicamente los vectores (Red Team) y aplicar contención/erradicación/hardening (Blue Team) bajo marcos como OWASP Top 10, NIST e ISO 27001.
​

Alcance y entorno
Laboratorio aislado en red interna (Host-Only/Internal Network) con las siguientes máquinas:
​

Kali Linux (Red Team / Auditoría): reconocimiento, enumeración, explotación controlada.

Debian vulnerable (Víctima / Blue Team): servidor comprometido con servicios expuestos (Apache/WordPress, SSH, FTP, MySQL/MariaDB).

Forense: análisis dinámico (logs/sistema) y post-mortem (imagen forense + Autopsy).

Objetivos del proyecto
Análisis forense: identificar vector de ataque, acciones del atacante e IOCs.
​

Gestión de vulnerabilidades: detectar y explotar fallos (mapeo OWASP Top 10) para después mitigarlos.
​

Hardening y cumplimiento: bastionado y plan de respuesta alineado con NIST/ISO/ENS.
​
Nota ética y legal
Todo el contenido corresponde a un entorno controlado de laboratorio y se presenta con fines educativos, siguiendo buenas prácticas de auditoría y respuesta a incidentes.
​
No debe utilizarse para actividades no autorizadas.
