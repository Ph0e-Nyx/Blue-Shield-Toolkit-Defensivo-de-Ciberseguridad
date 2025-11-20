# 🛡️ Awesome Blue Team Tools

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> Una colección curada de herramientas, recursos y software esenciales para equipos de **Blue Teaming**, Respuesta a Incidentes y Ciberdefensa.

---

## 📋 Tabla de Contenidos

- [SIEM (Security Information and Event Management)](#siem)
- [Network Security Monitoring](#network-security-monitoring)
- [Incident Response & Forensics](#incident-response--forensics)
- [Threat Intelligence](#threat-intelligence)
- [Endpoint Security & EDR](#endpoint-security--edr)
- [Malware Analysis](#malware-analysis)
- [Honeypots](#honeypots)
- [Recursos Adicionales](#recursos-adicionales)
- [Contribuir](#contribuir)

---

## <a name="siem"></a>👁️ SIEM

Gestión de información y eventos de seguridad para centralizar y analizar logs.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[Wazuh](https://wazuh.com/)** | Plataforma unificada XDR y SIEM gratuita y de código abierto. Protege cargas de trabajo en entornos locales, virtualizados, en contenedores y en la nube. | Open Source |
| **[Elastic Stack (ELK)](https://www.elastic.co/what-is/elk-stack)** | Elasticsearch, Logstash y Kibana. Muy potente para búsqueda, análisis y visualización de logs en tiempo real. | Open Source / Free |
| **[AlienVault OSSIM](https://cybersecurity.att.com/products/ossim)** | SIEM de código abierto que proporciona una visión unificada de los controles de seguridad y el estado de cumplimiento. | Open Source |
| **[Splunk Free](https://www.splunk.com/en_us/software/splunk-enterprise/free-trial.html)** | Versión gratuita de la popular plataforma para buscar, monitorizar y analizar datos de máquinas (limitada por volumen diario). | Propietario (Free Tier) |

## <a name="network-security-monitoring"></a>🌐 Network Security Monitoring

Herramientas para monitorizar y analizar el tráfico de red en busca de anomalías.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[Zeek (formerly Bro)](https://zeek.org/)** | Potente marco de análisis de red. No es solo un IDS, sino que proporciona registros de transacciones de red de alto nivel. | Open Source |
| **[Suricata](https://suricata.io/)** | Motor de detección de amenazas de red de alto rendimiento, IDS, IPS y monitorización de seguridad de red. | Open Source |
| **[Snort](https://www.snort.org/)** | Sistema de prevención de intrusiones en red (NIPS) y detección de intrusiones en red (NIDS) de código abierto. | Open Source |
| **[Wireshark](https://www.wireshark.org/)** | El analizador de protocolos de red más utilizado del mundo. Esencial para el análisis profundo de paquetes. | Open Source |
| **[Arkime (formerly Moloch)](https://arkime.com/)** | Sistema de captura de paquetes e indexación a gran escala, con una interfaz web para explorar los datos PCAP. | Open Source |

## <a name="incident-response--forensics"></a>🔍 Incident Response & Forensics

Herramientas para la respuesta ante incidentes, adquisición de evidencias y análisis forense digital.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[Velociraptor](https://docs.velociraptor.app/)** | Herramienta avanzada de forense digital y respuesta a incidentes que permite consultar el estado de los endpoints de forma rápida y escalable. | Open Source |
| **[TheHive](https://thehive-project.org/)** | Plataforma de orquestación de respuesta a incidentes de seguridad escalable y gratuita. | Open Source |
| **[Cortex](https://github.com/TheHive-Project/Cortex)** | Motor de análisis potente y escalable para analizar observables (IPs, hashes, dominios) a escala. Complemento ideal para TheHive. | Open Source |
| **[Autopsy](https://www.autopsy.com/)** | Plataforma forense digital y una interfaz gráfica para The Sleuth Kit y otras herramientas forenses digitales. | Open Source |
| **[Volatility](https://www.volatilityfoundation.org/)** | Framework avanzado de forense de memoria y análisis de respuesta a incidentes. | Open Source |

## <a name="threat-intelligence"></a>🧠 Threat Intelligence

Plataformas para gestionar, compartir y analizar inteligencia sobre amenazas.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[MISP](https://www.misp-project.org/)** | Plataforma de intercambio de información sobre malware y amenazas. Estándar de facto en la industria para compartir IOCs. | Open Source |
| **[OpenCTI](https://www.opencti.io/)** | Plataforma para gestionar el conocimiento de ciberamenazas y observables. Estructura, almacena, organiza y visualiza información técnica y no técnica. | Open Source |

## <a name="endpoint-security--edr"></a>💻 Endpoint Security & EDR

Seguridad a nivel de endpoint y detección y respuesta.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[OpenEDR](https://www.openedr.com/)** | EDR de código abierto que proporciona análisis de comportamiento, prevención de amenazas y visibilidad en tiempo real. | Open Source |
| **[Bluespawn](https://github.com/ION28/BLUESPAWN)** | Herramienta activa de defensa y detección para Windows. Actúa como EDR y herramienta de respuesta. | Open Source |
| **[Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon)** | Utilidad de Windows Sysinternals que monitoriza y registra la actividad del sistema en el registro de eventos de Windows. | Freeware |

## <a name="malware-analysis"></a>🦠 Malware Analysis

Entornos y herramientas para analizar software malicioso de forma segura.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[Cuckoo Sandbox](https://cuckoosandbox.org/)** | Sistema líder de análisis de malware automatizado de código abierto. | Open Source |
| **[REMnux](https://remnux.org/)** | Kit de herramientas Linux para ingeniería inversa y análisis de malware. | Open Source |
| **[Ghidra](https://ghidra-sre.org/)** | Suite de herramientas de ingeniería inversa de software (SRE) desarrollada por la NSA. | Open Source |

## <a name="honeypots"></a>🍯 Honeypots

Sistemas señuelo para detectar y analizar ataques.

| Herramienta | Descripción | Licencia |
| :--- | :--- | :--- |
| **[T-Pot](https://github.com/telekom-security/tpotce)** | Plataforma de honeypot todo en uno que incluye múltiples honeypots y herramientas de visualización (ELK). | Open Source |
| **[Cowrie](https://github.com/cowrie/cowrie)** | Honeypot de interacción media SSH y Telnet diseñado para registrar ataques de fuerza bruta y la interacción del shell. | Open Source |

---

## <a name="recursos-adicionales"></a>📚 Recursos Adicionales

*   **[Blue Team Handbook](https://www.amazon.com/Blue-Team-Handbook-Incident-Response/dp/1500734756)** - Un libro de referencia rápida para respuesta a incidentes.
*   **[SANS Blue Team Wiki](https://wiki.sans.blue/)** - Wiki de la comunidad SANS para defensa.
*   **[Mitre ATT&CK](https://attack.mitre.org/)** - Base de conocimiento de tácticas y técnicas de adversarios.

---

## <a name="contribuir"></a>🤝 Contribuir

¡Las contribuciones son bienvenidas! Por favor, lee las [guías de contribución](CONTRIBUTING.md) antes de enviar un PR.

1.  Haz un Fork del proyecto.
2.  Crea tu rama de funcionalidad (`git checkout -b feature/AmazingFeature`).
3.  Haz Commit de tus cambios (`git commit -m 'Add some AmazingFeature'`).
4.  Haz Push a la rama (`git push origin feature/AmazingFeature`).
5.  Abre un Pull Request.

---

## 📄 Licencia

Distribuido bajo la licencia MIT. Ver `LICENSE` para más información.
