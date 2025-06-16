# ElectroSim-Industrial
Máquina virtual educativa que simula los sistemas usados por una empresa eléctrica: control de consumo, monitoreo industrial y ciberseguridad básica.
# ElectroSim Industrial ⚙️⚡

**ElectroSim Industrial** es una máquina virtual educativa diseñada para simular cómo funciona una empresa eléctrica moderna en términos de monitoreo, gestión de consumo, automatización y seguridad de infraestructuras críticas.

Este entorno está pensado para estudiantes, docentes y profesionales que deseen explorar cómo se integran tecnologías como PLCs, bases de datos, protocolos de comunicación, dashboards y ciberseguridad básica en una red eléctrica simulada.

---

## 🧩 Componentes principales

| Componente         | Descripción                                                             |
|--------------------|--------------------------------------------------------------------------|
| **OpenPLC**         | Simulación de lógica de control industrial (PLCs)                       |
| **Node-RED**        | Flujos automatizados para datos de sensores simulados                   |
| **InfluxDB**        | Almacenamiento de series temporales (consumo eléctrico simulado)        |
| **Grafana**         | Visualización de datos en dashboards dinámicos                          |
| **Mosquitto (MQTT)**| Comunicación IoT entre sensores/medidores y backend                     |
| **MariaDB**         | Gestión de datos de clientes, contratos o registros                     |
| **Suricata**        | Monitorización básica de red (IDS)                                      |
| **UFW + Fail2Ban**  | Seguridad de red y protección ante accesos no autorizados               |

---

## 🚀 Cómo usar

1. Descarga la máquina virtual desde el enlace proporcionado en este repositorio.
2. Importa el archivo `.ova` en VirtualBox:
   - **Archivo → Importar servicio virtualizado**
   - Selecciona `ElectroSim-Industrial.ova` y sigue los pasos.
3. Inicia la máquina y accede con las credenciales:
   - **Usuario**: `vboxuser`
   - **Contraseña**: `insecure`
4. Abre tu navegador (desde el host) y accede a los siguientes servicios:
   - **Grafana**: `http://<IP_VM>:3000`
   - **Node-RED**: `http://<IP_VM>:1880`
   - **InfluxDB** (si deseas conectar desde otra herramienta): `http://<IP_VM>:8086`

> 💡 Recuerda sustituir `<IP_VM>` por la IP real de la máquina virtual (puedes verla con `ip a`).

---

   ## 📜 Licencia

Este proyecto está bajo la licencia **Creative Commons CC BY-ND 4.0**.  
Puedes compartirlo y usarlo para prácticas educativas, pero **no puedes modificar ni distribuir versiones alteradas**.

🔗 [Ver términos de la licencia](https://creativecommons.org/licenses/by-nd/4.0/)

© 2025 Ivanka Fernández Leivas

