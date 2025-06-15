# 📥 Importar ElectroSim Industrial (.ova)

Esta guía explica cómo importar la máquina virtual educativa **ElectroSim Industrial**, creada por Ivanka Fernández Leivas, en VirtualBox. Esta VM está diseñada para simular entornos de empresas eléctricas con monitoreo, consumo y ciberseguridad básica.

---

## 📦 Requisitos

- VirtualBox instalado (v6.1 o superior recomendado)
- Al menos 4 GB de RAM disponibles
- 15–20 GB de espacio libre en disco
- Archivo: `ElectroSim-Industrial.ova` (descargar desde el enlace proporcionado en el repositorio)

---

## 🛠️ Cómo importar la máquina virtual

1. Abre **VirtualBox**
2. Ve a: **Archivo → Importar servicio virtualizado**
3. Selecciona el archivo `ElectroSim-Industrial.ova`
4. Haz clic en **Siguiente** y luego en **Importar**
5. Espera unos minutos mientras se completa el proceso

---

## 🔐 Credenciales de acceso

- **Usuario**: `vboxuser`
- **Contraseña**: `insecure`

---

## 📋 Servicios incluidos en la VM

| Servicio        | Puerto | Descripción                                       |
|------------------|--------|---------------------------------------------------|
| InfluxDB         | 8086   | Almacenamiento de datos de sensores simulados    |
| Grafana          | 3000   | Visualización de consumo, voltaje, etc.          |
| Node-RED         | 1880   | Simulación visual de sensores/automatización     |
| MariaDB          | 3306   | Datos de clientes o gestión interna               |
| Mosquitto (MQTT) | 1883   | Comunicación tipo IoT                            |
| Suricata         | —      | IDS básico para monitoreo de red                 |

---

## 🔧 Recomendaciones

- Al iniciar, abre Grafana (`http://<IP_VM>:3000`) y Node-RED (`http://<IP_VM>:1880`) desde el navegador del host.
- Puedes conectar directamente con InfluxDB desde Grafana para crear dashboards personalizados.
- Usa `systemctl` para verificar que todos los servicios estén activos.

---

## 🧑‍🏫 Propósito

Este entorno está diseñado como laboratorio de prácticas para aprender:
- Cómo funcionan los sistemas eléctricos modernizados
- Visualización de datos de consumo
- Ciberseguridad industrial básica
- Automatización y monitoreo en tiempo real

---

© 2025 Ivanka Fernández Leivas – Proyecto educativo con licencia CC BY-ND 4.0
