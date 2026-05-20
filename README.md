# 🚀 Infrastructure Monitoring & Threat Interception (VIGIL)

A practical project demonstrating real-time system observability and declarative infrastructure threat mitigation. This project focuses on capturing core hardware metrics and establishing zero-latency multi-channel incident alerting using industry-standard protocols.

---

## 📂 Repository Architecture

| Component | Path | Technical Responsibility |
| :--- | :--- | :--- |
| 🐍 **Backend Core** | `/backend` | Python & Flask API engine for infrastructure telemetry and log harvesting. |
| 💻 **Frontend UI** | `/templates` | Lightweight HTML & CSS admin dashboards for real-time visualization. |
| 📁 **Media Assets** | `/media` | Project documentation, functionality verification videos, and logs snapshots. |
| 🚨 **Notification Engine** | `* / core` | Integration bridges routing instant alerts through Twilio and SMTP relays. |
| 🛡️ **Security Protocol** | `.gitignore` | Excludes local runtime code architectures, secure variable strings, and API tokens. |

---

## 🛠️ Tools & Technologies Used

* **Python (Flask):** Used to create the core analytical engine, log harvester, and micro-web server dashboard.
* **Twilio REST API:** Used to bridge telemetry alert triggers with mobile devices via instant WhatsApp nodes.
* **SMTP Server Protocol:** Configured for automated background email relays with attached logs diagnostics.
* **psutil / OS Substrates:** Python runtime bindings used to scrape live CPU and RAM allocation metrics from the host.
* **Git & GitHub:** Used for version control, data masking implementation, and secure project deployment.

---

## 🌟 Key Functional Features

* **Authentication & Gatekeeping Gateway:** Multi-role access control panel preventing unauthorized modifications to metric parameters (`media/01_auth_flow.mp4`, `media/02_dashboard.png`).
* **Asynchronous Resource Watchdog:** Continuous backend orchestration running threads to intercept memory leaks and server storage spikes (`media/03_infra_logs.png`, `media/06_system_config.png`).
* **Multi-Channel Dispatch Response:** Automated, zero-latency incident alerting that forwards telemetry streams upon threshold violations (`media/05_security_node_alpha.png`, `media/04_backend_proof.png`, `media/07_email_alert_proof(1).png`).

---

## 💻 Local Environment Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/anmolkorla111-tech/VIGIL-Infrastructure-Sentinel.git](https://github.com/anmolkorla111-tech/VIGIL-Infrastructure-Sentinel.git)
