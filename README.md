# Honeypot T-Pot

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/T-Pot_logo.png/480px-T-Pot_logo.png" alt="T-Pot Logo" height="150" />
</div>

---

## 📖 **Descripción**

T-Pot es una plataforma todo-en-uno de **honeypots** desarrollada por T-Mobile para la detección, registro y análisis de ciberataques. Diseñada para ser modular y flexible, esta solución integra múltiples servicios para capturar información detallada sobre actividades maliciosas en redes.

---

## ✨ **Características principales**

- **Multi-Honeypot**: Incluye varios honeypots como Cowrie, Ddospot, y Dionaea para capturar diferentes tipos de ataques.
- **Integración de Elastic Stack**:
  - **Elasticsearch**: Para almacenar los datos recopilados.
  - **Logstash**: Para procesar y enriquecer los logs.
  - **Kibana**: Para visualización y análisis interactivo.
- **Soporte para Docker**: Facilita la instalación y despliegue.
- **Supervisión de ataques en tiempo real**: Usa herramientas como CyberChef, Spiderfoot y Attack Maps.
- **Amigable para analistas de ciberseguridad**: Simplifica el proceso de correlación de eventos y análisis de logs.

---

## 🛠 **Componentes incluidos**

| **Componente**          | **Función**                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| **Ddospot**              | Detección de ataques DDoS basados en peticiones de DNS.                    |
| **Cowrie**               | Honeypot SSH/HTTP para registrar intentos de acceso.                       |
| **Suricata**             | Motor de detección de intrusos (IDS) y monitoreo de tráfico.               |
| **Elastic Stack**        | Procesamiento, almacenamiento y análisis de logs en tiempo real.           |
| **Spiderfoot**           | Herramienta de análisis de amenazas de código abierto.                     |
| **Fatt**                 | Monitoreo de tráfico de red con capacidades de captura de paquetes.         |

---

## 📊 **Visualización en tiempo real**

T-Pot incluye dashboards preconfigurados en **Kibana** para analizar:
- Fuentes de los ataques.
- Métodos más utilizados (puertos, protocolos).
- Tendencias de tráfico malicioso.

Además, la herramienta **T-Pot Attack Map** te permite monitorear geográficamente la actividad maliciosa detectada.

---

## 🌟 **Beneficios**

- **Seguridad proactiva**: Detecta y analiza ataques antes de que comprometan sistemas productivos.
- **Aprendizaje continuo**: Facilita la investigación de tácticas y herramientas usadas por atacantes.
- **Flexibilidad**: Personalizable para adaptarse a necesidades específicas.
- **Escalabilidad**: Soporte para configuraciones desde pequeños entornos hasta implementaciones empresariales.

---

## 🚀 **Cómo empezar**

### **Requisitos del sistema**
- **CPU**: Al menos 4 núcleos.
- **RAM**: 16 GB mínimo.
- **Disco**: 128 GB SSD recomendado.
- **Sistema operativo**: Ubuntu 22.04 o Rocky Linux.

### **Instalación básica**
1. **Clona el repositorio oficial de T-Pot:**
   ```bash
   git clone https://github.com/telekom-security/tpotce
   cd tpotce
