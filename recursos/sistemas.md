# Sistemas y bastionado

[← Catálogo](../README.md) · [Etiquetas](../docs/ETIQUETAS.md) · [Apuntes](apuntes.md) · [Proyectos](proyectos.md) · [Redes →](redes.md)

Administración Linux y Windows, virtualización, automatización, resolución de problemas y configuración segura. Para cloud e identidad, consulta [cloud y despliegue](cloud.md).

## En esta categoría

- [Ansible Documentation](#ansible)
- [ArchWiki](#archwiki)
- [CIS Benchmarks](#cis-benchmarks)
- [Debian Administrator's Handbook](#debian-handbook)
- [Docker Documentation](#docker)
- [Microsoft PowerShell Documentation](#powershell)
- [Proxmox VE Documentation](#proxmox)
- [Red Hat Documentation](#red-hat)
- [SadServers](#sadservers)
- [Ubuntu Server Docs](#ubuntu-server)

## Recursos

<a id="ansible"></a>

### [Ansible Documentation](https://docs.ansible.com/)

Documentación oficial de automatización de configuración e inventario. Útil para pasar de tareas manuales en un servidor a playbooks reproducibles en laboratorio y aula.

`ASIR · CE · sistemas · despliegue · Intermedio–Avanzado · EN · documentación · lab · Gratis · Oficial`

**Acceso:** documentación pública; las prácticas requieren un entorno controlado con SSH. Existe documentación y comunidad en varios idiomas; la referencia canónica está en inglés. **Revisión:** 2026-09-21.

<a id="archwiki"></a>

### [ArchWiki](https://wiki.archlinux.org/)

Enciclopedia técnica de administración Linux: red, servicios, arranque y solución de problemas. Aunque nace en Arch, muchas páginas aplican a otras distribuciones si se adaptan rutas y gestores de paquetes.

`ASIR · CE · sistemas · redes · bastionado · Intermedio–Avanzado · EN · documentación · Gratis · Comunidad`

**Acceso:** lectura pública. Hay [traducciones](https://wiki.archlinux.org/title/ArchWiki:Translation_Team) incompletas; priorizar la página en inglés cuando la versión traducida esté desactualizada. **Revisión:** 2026-09-21.

<a id="cis-benchmarks"></a>

### [CIS Benchmarks](https://www.cisecurity.org/cis-benchmarks)

Guías de configuración segura por producto y versión. Útiles para justificar, aplicar y verificar medidas de bastionado; seleccionar el perfil adecuado antes de modificar un sistema.

`ASIR · CE · bastionado · Intermedio–Avanzado · EN · documentación · Gratis · Oficial`

**Acceso:** PDF gratuitos para uso no comercial según las condiciones de CIS; la descarga puede pedir datos. Herramientas, formatos y servicios adicionales pueden exigir membresía o pago. **Revisión:** 2026-09-18.

<a id="debian-handbook"></a>

### [Debian Administrator's Handbook](https://debian-handbook.info/)

Libro de Raphaël Hertzog y Roland Mas para comprender Debian desde la instalación hasta los servicios y la seguridad. Aporta una explicación continua que complementa las referencias de comandos.

`ASIR · CE · sistemas · redes · bastionado · Inicial–Intermedio · ES/EN · teoría · documentación · Gratis · Comunidad`

**Acceso:** lectura digital libre; comprobar la versión de Debian cubierta y el avance de cada traducción. Ediciones impresas de pago. **Revisión:** 2026-09-18.

<a id="docker"></a>

### [Docker Documentation](https://docs.docker.com/)

Guías para construir, ejecutar y publicar contenedores. Base práctica antes de orquestación o despliegues cloud; conviene separar imagen, volumen, red y secretos en los ejercicios de clase.

`ASIR · DAW · DAM · CE · sistemas · cloud · despliegue · Inicial–Intermedio · EN · documentación · lab · Gratis · Oficial`

**Acceso:** documentación abierta; instalar Docker Desktop o el motor en Linux puede tener requisitos de licencia o cuenta según el caso de uso. Hay interfaz y parte de la docs en varios idiomas; la referencia técnica principal está en inglés. **Revisión:** 2026-09-21.

<a id="powershell"></a>

### [Microsoft PowerShell Documentation](https://learn.microsoft.com/es-es/powershell/)

Documentación y aprendizaje de PowerShell para automatizar administración en Windows y entornos híbridos. Complementa Microsoft Learn con el lenguaje y los módulos que se usan en sistemas reales.

`ASIR · DAM · CE · sistemas · Inicial–Avanzado · ES/EN · documentación · lab · Gratis · Oficial`

**Acceso:** material autodirigido gratuito; preferir la vista en español cuando esté completa y contrastar con la versión en inglés si hay divergencias. Requiere Windows, PowerShell 7 u otro entorno compatible para practicar. **Revisión:** 2026-09-21.

<a id="proxmox"></a>

### [Proxmox VE Documentation](https://pve.proxmox.com/pve-docs/)

Documentación del hipervisor Proxmox VE: máquinas virtuales, contenedores LXC, almacenamiento y alta disponibilidad. Referencia habitual en laboratorios de virtualización de ASIR.

`ASIR · CE · sistemas · cloud · Inicial–Intermedio · EN · documentación · lab · Gratis · Oficial`

**Acceso:** manuales públicos en inglés; la interfaz del producto puede configurarse en español. Desplegar un nodo de laboratorio exige hardware o anidamiento de virtualización. Soporte comercial aparte. **Revisión:** 2026-09-21.

<a id="red-hat"></a>

### [Red Hat Documentation](https://docs.redhat.com/en)

Documentación de RHEL para administración, redes, almacenamiento y SELinux. Referencia para contrastar procedimientos en sistemas empresariales y estudiar decisiones de configuración.

`ASIR · CE · sistemas · bastionado · Intermedio–Avanzado · EN · documentación · Gratis · Oficial`

**Acceso:** documentación pública; elegir Red Hat Enterprise Linux y la versión utilizada. Suscripciones de producto, cursos y exámenes tienen condiciones independientes. **Revisión:** 2026-09-18.

<a id="sadservers"></a>

### [SadServers](https://sadservers.com/)

Escenarios de diagnóstico sobre servidores Linux reales. Permite practicar la búsqueda de causas en procesos, almacenamiento, redes y servicios sin limitarse a seguir un tutorial.

`ASIR · CE · sistemas · redes · Intermedio–Avanzado · EN · lab · Mixto · Oficial`

**Acceso:** escenarios gratuitos y planes de pago; disponibilidad, duración y registro dependen de la modalidad. Requiere bases de terminal Linux. **Revisión:** 2026-09-18.

<a id="ubuntu-server"></a>

### [Ubuntu Server Docs](https://ubuntu.com/server/docs/)

Tutoriales, guías prácticas y referencias de administración de Ubuntu Server. Buen punto de partida para instalar un servidor, administrar servicios y trabajar con red, usuarios y seguridad.

`ASIR · DAW · CE · sistemas · redes · bastionado · Inicial–Intermedio · EN · documentación · lab · Gratis · Oficial`

**Acceso:** lectura abierta; las prácticas requieren una máquina o VM propia. Comprobar la versión objetivo y los requisitos de funcionalidades opcionales. **Revisión:** 2026-09-18.

---

[← Catálogo](../README.md) · [Apuntes](apuntes.md) · [Proyectos](proyectos.md) · [Redes →](redes.md)
