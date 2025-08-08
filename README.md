⚡ ElectroSim Industrial

**ElectroSim Industrial** es una máquina virtual educativa diseñada para simular cómo funciona una empresa eléctrica moderna en términos de automatización, monitoreo de consumo energético y ciberseguridad básica de infraestructuras críticas.

Este entorno está pensado para estudiantes, docentes y profesionales que deseen explorar la integración de tecnologías como PLCs, bases de datos, protocolos de comunicación, visualización de datos y detección de amenazas en redes industriales simuladas.

---

🧩 Componentes principales

| Componente         | Descripción                                                                 |
|--------------------|------------------------------------------------------------------------------|
| **OpenPLC**         | Simulación de lógica de control industrial (PLC)                            |
| **Node-RED**        | Flujos de datos automatizados que simulan sensores de consumo eléctrico     |
| **InfluxDB**        | Almacenamiento de series temporales (mediciones simuladas)                  |
| **Grafana**         | Visualización de datos a través de dashboards interactivos                  |
| **Mosquitto (MQTT)**| Comunicación tipo IoT entre sensores y backend                              |
| **MariaDB**         | Gestión de datos simulados de clientes, contratos y servicios eléctricos    |
| **Suricata**        | Monitorización de red como IDS (detección de intrusiones)                   |
| **UFW + Fail2Ban**  | Seguridad perimetral contra accesos no autorizados                          |

---

📦 Versiones disponibles

| Archivo                          | Descripción                                       |
|----------------------------------|---------------------------------------------------|
| `ElectroSim-Industrial.ova`      | Versión sin entorno gráfico (modo terminal)       |
| `ElectroSim-Industrial-GUI.ova`  | Versión con entorno gráfico XFCE                  |

---

📁 Descarga

Puedes descargar las máquinas virtuales desde los enlaces a Google Drive incluidos en este repositorio:

- 🔹 [ElectroSim-Industrial.ova](ENLACE_AQUÍ)
- 🔸 [ElectroSim-Industrial-GUI.ova](ENLACE_AQUÍ)

---

🚀 Cómo usar

1. Importa la `.ova` en VirtualBox:
   - `Archivo → Importar servicio virtualizado`
2. Inicia la VM y accede con:
   - Usuario: `vboxuser`
   - Contraseña: `insecure`
3. Accede desde tu navegador (host) a:
   - Grafana → `http://<IP_VM>:3000`
   - Node-RED → `http://<IP_VM>:1880`
   - InfluxDB → `http://<IP_VM>:8086/ping`

> ℹ️ Reemplaza `<IP_VM>` por la IP de la máquina virtual (`ip a`)

---

🧪 Entorno listo para prácticas

Esta máquina virtual no incluye flujos, dashboards ni datos precargados. Está intencionadamente configurada como un entorno limpio para que el usuario pueda practicar desde cero:

- Crear flujos en Node-RED
- Diseñar dashboards en Grafana
- Insertar y consultar datos en InfluxDB
- Aplicar configuraciones propias de automatización y seguridad

---

🔐 Credenciales de acceso

- **Maquinas Virtuales**:
     - Usuario: `vboxuser`  
     - Contraseña: `insecure`
- **Grafana**:  
     - Usuario: `admin`  
     - Contraseña: `admin`

---

📜 Licencia

Este proyecto está bajo la licencia **Creative Commons CC BY-ND 4.0**.  
Puedes compartirlo y usarlo para prácticas educativas, pero **no puedes modificarlo ni redistribuir versiones alteradas**.

🔗 [Ver términos de la licencia](https://creativecommons.org/licenses/by-nd/4.0/)

---

👩‍💻 Autora

Ivanka Fernández Leivas  
💼 [LinkedIn](https://www.linkedin.com/in/ivankafernandez/)  
📺 Canal: [@CiberPractica](https://www.youtube.com/@CiberPractica)  
📧 ivankafdez@gmail.com

---

© 2025 Ivanka Fernández Leivas


