📥 Importar ElectroSim Industrial (.ova)

Esta guía explica cómo importar las máquinas virtuales educativas **ElectroSim Industrial**, creadas por Ivanka Fernández Leivas, en VirtualBox. Estas VMs están diseñadas para simular entornos eléctricos modernos con monitoreo, consumo y ciberseguridad básica.

---

📁 Descarga de máquinas virtuales

Puedes descargar las versiones disponibles desde los siguientes enlaces:

🔹 [ElectroSim-Industrial.ova] (https://drive.google.com/file/d/1aNL5RMOqwz4K3IqzReoBddE98N0kS_tY/view?usp=sharing)
    Versión ligera sin entorno gráfico (modo terminal)

🔸 [ElectroSim-Industrial-GUI.ova] (https://drive.google.com/file/d/1msG14d3ItzIRtTVhaLd9n29EHWXlOiDR/view?usp=sharing)  
    Versión completa con entorno gráfico XFCE

> 📝 Asegúrate de que los archivos `.ova` estén completos tras la descarga antes de importarlos en VirtualBox.

---

🛠️ Requisitos

- VirtualBox (v6.1 o superior recomendado)
- Al menos 4 GB de RAM disponibles
- 15–20 GB de espacio libre en disco

---

🚀 Cómo importar una máquina virtual en VirtualBox

1. Abre **VirtualBox**
2. Ve a: **Archivo → Importar servicio virtualizado**
3. Selecciona el archivo `.ova` descargado
4. Haz clic en **Siguiente** y luego en **Importar**
5. Espera unos minutos mientras se completa el proceso

---

🔐 Credenciales de acceso

- **Usuario**: `vboxuser`
- **Contraseña**: `insecure`

---

📋 Servicios incluidos en ambas versiones

| Servicio        | Puerto | Descripción                                       |
|------------------|--------|---------------------------------------------------|
| InfluxDB         | 8086   | Almacenamiento de datos simulados                |
| Grafana          | 3000   | Visualización de datos a través de dashboards    |
| Node-RED         | 1880   | Creación visual de flujos de automatización      |
| MariaDB          | 3306   | Gestión de datos tipo cliente/contrato           |
| Mosquitto (MQTT) | 1883   | Comunicación IoT para sensores simulados         |
| Suricata         | —      | Detección básica de intrusos (IDS)               |

---

🌐 Acceder a los servicios desde el navegador del host

- Grafana → `http://<IP_VM>:3000`
- Node-RED → `http://<IP_VM>:1880`
- InfluxDB API → `http://<IP_VM>:8086`

> ℹ️ Puedes ver la IP real de la VM con: `ip a`

---

🧑‍🏫 Propósito

ElectroSim Industrial está diseñado para enseñar y practicar:
- Visualización de consumo eléctrico
- Simulación de dispositivos IoT industriales
- Automatización con PLCs y flujos lógicos
- Introducción a la ciberseguridad industrial (ICS/SCADA)

---

© 2025 Ivanka Fernández Leivas – Proyecto educativo con licencia CC BY-ND 4.0
