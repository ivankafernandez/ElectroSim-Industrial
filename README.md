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

 🚀 Cómo usar

1. **Descarga la máquina virtual `.ova` desde el enlace incluido en este repositorio** (hay versión con y sin entorno gráfico).
2. **Importa la VM en VirtualBox**:
   - Menú → `Archivo → Importar servicio virtualizado`
   - Selecciona el archivo `.ova` correspondiente y sigue los pasos
3. **Credenciales de acceso**:
   - Usuario: `vboxuser`
   - Contraseña: `insecure`
4. **Accede a los servicios desde tu navegador (host):**
   - Grafana → `http://<IP_VM>:3000`
   - Node-RED → `http://<IP_VM>:1880`
   - InfluxDB (API HTTP) → `http://<IP_VM>:8086`

> ℹ️ Reemplaza `<IP_VM>` por la IP real de la máquina virtual. Puedes verla desde la terminal con `ip a`.

---

📦 Versiones disponibles

- `ElectroSim-Industrial.ova` → Versión básica (sin entorno gráfico)
- `ElectroSim-Industrial-GUI.ova` → Versión con entorno gráfico XFCE

---

📖 Consulta la carpeta [`docs/`](./Doc) para conocer más sobre el diseño y las decisiones técnicas del proyecto.

---

📜 Licencia

Este proyecto está bajo la licencia **Creative Commons CC BY-ND 4.0**.  
Puedes compartirlo y usarlo para prácticas educativas, pero **no puedes modificarlo ni redistribuir versiones alteradas**.

🔗 [Ver términos de la licencia](https://creativecommons.org/licenses/by-nd/4.0/)

© 2025 Ivanka Fernández Leivas

