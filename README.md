## Proyecto Final de Ciberseguridad – 4Geeks Academy

<p align="center">
  <img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/c1c9164f-a3c4-4807-b0ab-91d2be80f9f8" />
</p>

Este repositorio documenta un proyecto completo de **pentesting** y **respuesta a incidentes (DFIR)** realizado como pentester / analista de ciberseguridad para **4Geeks Academy**, sobre un servidor Debian crítico que presenta indicios de compromiso.

El objetivo es reconstruir el ataque (DFIR), validar técnicamente los vectores (Red Team) y aplicar contención / erradicación / hardening (Blue Team) bajo marcos como **OWASP Top 10**, **NIST** e **ISO 27001**.

---

### Alcance y entorno

Laboratorio aislado en red interna (Host-Only / Internal Network) con las siguientes máquinas:

- **Kali Linux (Red Team / Auditoría)**: reconocimiento, enumeración y explotación controlada.
- **Debian vulnerable (Víctima / Blue Team)**: servidor comprometido con servicios expuestos (Apache/WordPress, SSH, FTP, MySQL/MariaDB).
- **Entorno forense**: análisis dinámico (logs y sistema) y análisis post-mortem (imagen forense + Autopsy).

---

### Objetivos del proyecto

- **Análisis forense**: identificar vector de ataque, acciones del atacante e IOCs.
- **Gestión de vulnerabilidades**: detectar y explotar fallos (mapeo OWASP Top 10) para después mitigarlos.
- **Hardening y cumplimiento**: bastionado y plan de respuesta alineado con NIST / ISO / ENS.

---

### Nota ética y legal

Todo el contenido corresponde a un entorno **controlado de laboratorio** y se presenta con fines **educativos**, siguiendo buenas prácticas de auditoría y respuesta a incidentes.

**No debe utilizarse para actividades no autorizadas.**

<br></br>

<p align="center">
  <img width="750" height="550" alt="image" src="https://github.com/user-attachments/assets/d227c665-1d3c-4c82-8469-64d16c1df7b4" />
</p>


