🧭 ¿Por qué ElectroSim no usa herramientas gráficas genéricas?

Muchas personas están acostumbradas a entornos visuales y herramientas como monitores del sistema, gestores de bases de datos o configuradores gráficos de red. Sin embargo, **ElectroSim Industrial está diseñado para reflejar el tipo de entornos reales utilizados por empresas eléctricas y de infraestructura crítica**.

---

⚡ En el mundo real, ¿qué usan las empresas eléctricas?

Las empresas del sector eléctrico no utilizan herramientas gráficas de propósito general. En su lugar, emplean soluciones específicas, robustas y orientadas a operación continua, tales como:

| Área                         | Soluciones comunes (reales)                             |
|------------------------------|----------------------------------------------------------|
| SCADA/PLC                    | Siemens WinCC, ABB 800xA, Schneider EcoStruxure         |
| Monitorización de red        | Zabbix, PRTG, Nagios XI, SolarWinds                     |
| Ciberseguridad OT            | Nozomi, Claroty, Dragos                                 |
| Gestión energética           | OSIsoft PI System, Matrikon OPC, GE Grid Solutions      |

Estas herramientas suelen ser:
- Web-based o CLI (poco uso de GUI local)
- Ejecutadas en servidores dedicados
- Controladas por equipos técnicos especializados

---

🎯 ¿Qué busca ElectroSim?

**ElectroSim Industrial no busca parecerse a un entorno doméstico, sino a uno industrial realista.**

Por eso:
- Se utilizan servicios web como **Grafana** y **Node-RED**
- No se incluyen programas visuales genéricos como "monitores de sistema"
- Todo está orientado a simular:
  - Un sistema de supervisión
  - Comunicación con sensores (IoT)
  - Base de datos de medición
  - Supervisión de red y seguridad

---

👨‍🏫 Conclusión

ElectroSim puede parecer minimalista a nivel visual, pero su arquitectura imita de forma práctica cómo trabajan los sistemas industriales reales.

Es un entorno ideal para **formación técnica** en:
- Automatización
- Monitorización industrial
- Seguridad en infraestructuras críticas

---

© 2025 Ivanka Fernández Leivas
