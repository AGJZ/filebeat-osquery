# :tw-1f31e: Filebeat + Osquery :tw-1f31e:

[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/) [![stability-alpha](https://img.shields.io/badge/stability-alpha-f4d03f.svg)](https://github.com/mkenney/software-guides/blob/master/STABILITY-BADGES.md#alpha)

------------

#### PLAYBOOK
**Instalación:**
- Filebeat
- Osquery

**Configuración (Prediseñada):**
- Filebeat
 - Archivo de configuración servicio Filebeat
   - ** playbooks/filebeat/conf/filebeat.yml **
 - Archivo de activación del modulo Osquery
   - ** playbooks/filebeat/modules/osquery.yml **

- Osquery
  - Archivo configuración datos del sistema mediante queries.
   - ** playbooks/osquery/conf/osquery.conf **

**Reinicio de servicios Filebeat & Osqueryd**


