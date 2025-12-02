# 🛡️ Rodrigo — Cybersecurity Specialist

<div align="center">

![Cyber Security](https://readme-typing-svg.demolab.com?font=Fira+Code\&weight=600\&size=26\&duration=4000\&pause=1000\&color=7AA2F7\&center=true\&vCenter=true\&width=600\&lines=Ethical+Hacking+Specialist;Network+Security+Analyst;WiFi+Security+Researcher;Bug+Bounty+Hunter)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://linkedin.com/in/rodrigo-v-695728215)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge\&logo=youtube\&logoColor=white)](https://youtube.com/@Rodrigo-47363)
[![Email](https://img.shields.io/badge/Email-Contact-8B89CC?style=for-the-badge\&logo=protonmail\&logoColor=white)](mailto:rodrigovil@proton.me)

</div>

---

## 👨‍💻 Sobre mí

Soy **Rodrigo**, practicante de seguridad ofensiva especializado en **penetration testing**, **investigación de seguridad inalámbrica** y **bug bounty**. Me enfoco en auditorías con metodología reproductible, automatización de tareas repetitivas y técnicas de enumeración silenciosa que maximizan hallazgos con bajo ruido.

> **Filosofía:** impacto real > teoría; automatizo tareas que no agregan valor analítico para concentrarme en la explotación, la validación y el reporte claro.

---

## 🔧 Stack técnico (resumen)

**Lenguajes / Scripting:** Python · Bash · JavaScript
**Herramientas:** Nmap · Burp Suite · Metasploit · Aircrack-ng · Wireshark · Hashcat · John
**SO / Entornos:** Kali Linux · Parrot OS · Debian (Linux)
**Plataformas bug bounty:** HackerOne · Bugcrowd · Intigriti

---

## 🎯 Áreas de especialización

### Web Application Security

* XSS (reflejado, persistente, DOM), XSS en templates y contexts
* SQLi (clásico y segundo orden), blind SQLi, lógica de negocio
* Autenticación y autorización (bypass, token reuse, IDOR)
* CSRF y abuso de workflows

### Network & Wireless

* Penetration testing de red interna/externa
* Auditorías WiFi (WPA/WPA2/WPS, AP rogue)
* Passive OS fingerprinting, escaneo sigiloso
* API security & mobile app testing

---

## 🚀 Proyectos destacados

### NekoFi.sh — Automated WiFi Security Framework

**Repositorio:** `github.com/rodrigo47363/NekoFI`
**Descripción:** framework modular en Bash para auditorías WiFi en entornos reales — automatiza la detección de interfaces, manejo de modos (monitor/managed), orquestación con aircrack-ng y asistentes para ataques WPS.

**Características clave**

* Detección inteligente de interfaces y gestión del estado.
* Flujo automatizado para captura de handshakes y ataque WPS.
* Modular: easy-to-extend hooks para añadir payloads/post-proc.
* Enfoque en reproducibilidad y reducción de errores operativos.

**Instalación rápida (ejemplo)**

```bash
# clona el repo
git clone https://github.com/rodrigo47363/NekoFI.git
cd NekoFI

# otorgar permisos e iniciar (usa con sudo)
chmod +x nekofi.sh
sudo ./nekofi.sh --help
```

**Uso recomendado**

* Ejecutar en entorno controlado / laboratorio antes de pruebas en producción.
* Tener drivers y firmware compatibles (airmon-ng/iw).
* Leer el README del repositorio para flags avanzadas.

---

### OSIdentifier.py — Passive OS Fingerprinting

**Repositorio:** `github.com/rodrigo47363/OSIdentifier.py`
**Descripción:** herramienta en Python que utiliza análisis de TTL (ICMP) y heurísticas pasivas para inferir sistemas operativos sin generar tráfico activo ruidoso.

**Características**

* Escaneo pasivo — adecuado para fases de reconocimiento sigiloso.
* Normalización de TTL y reglas heurísticas configurables.
* Output estructurado para pipelines de reconocimiento.

**Ejemplo de uso**

```bash
# ejecutar (requiere scapy y permisos)
sudo python3 OSIdentifier.py --interface wlp3s0 --capture-time 60
# salida: JSON con hosts detectados y probables SOs
```

**Notas**

* No reemplaza fingerprinting activo en todas las situaciones; es una capa adicional cuando se requiere discreción.

---

## 🧠 Metodología (quick reference)

1. **Reconocimiento pasivo** — maximizar información con bajo ruido.
2. **Enumeración dirigida** — priorizar vectores con mayor probabilidad de impacto.
3. **Validación manual** — confirmar falsos positivos antes de carta/POC.
4. **Explotación con control de impacto** — pruebas en entornos permitidos.
5. **Post-Explotación y Reporte** — evidencia reproducible, mitigaciones claras.
6. **Automatización selectiva** — automatizo chequeos repetitivos, no la toma de decisiones.

---

## 📝 Buenas prácticas y disclaimer

* Todo el contenido y herramientas compartidas están **orientadas a investigación y pruebas autorizadas**.
* No ejecutes scripts ni ataques fuera de entornos donde tengas permiso explícito.
* Si quieres colaborar o pedir auditoría: **usa un contrato o permiso por escrito**.

---

## 📂 Cómo contribuir

1. Fork → crea un branch con tu feature/bugfix → PR con descripción técnica y pruebas.
2. Incluye tests o un playbook de validación para la funcionalidad que agregas.
3. Para contribuciones que cambian comportamiento de red/dispositivo, añade un `safety-check` en el script.

---

## 🌐 Conecta conmigo

* LinkedIn: [https://linkedin.com/in/rodrigo-v-695728215](https://linkedin.com/in/rodrigo-v-695728215)
* YouTube: [https://youtube.com/@Rodrigo-47363](https://youtube.com/@Rodrigo-47363)
* Email: [rodrigovil@proton.me](mailto:rodrigovil@proton.me)
* HTB: [https://app.hackthebox.com/profile/2072477](https://app.hackthebox.com/profile/2072477)
* THM: [https://tryhackme.com/p/Rodrigo.47363](https://tryhackme.com/p/Rodrigo.47363)

---

## 💝 Apoya mi trabajo (opcional)

Si valoras mi investigación y herramientas, puedes apoyarme:

**Bitcoin:** `bc1qkzmpd0hry99qms7ef23vsyx9vt34pzzaslpp8y`
**Ethereum:** `0xB75bC57C54FCBFF139EBF981A596B019C537d018`
**Solana:** `ELekuGHcmZjhXrtHNqHuu8QmdCZr3oCWtTmu3QUQ5hac`

---

## 📜 Licencia

Los repositorios individuales contienen sus propias licencias. Revisa cada `LICENSE` dentro del repo antes de usar en producción. Código, scripts y PoCs son para **fines educativos y pruebas autorizadas** únicamente.

---

# Bienvenido a mi Perfi👋

## Sobre Mí

Soy **Rodrigo**, un profesional apasionado por la **ciberseguridad**, especializado en **hacking ético** y **pentesting**. A lo largo de mi carrera, he trabajado en diversos proyectos que me han permitido desarrollar habilidades técnicas y analíticas. Este espacio está diseñado para que conozcas más sobre mi experiencia, certificaciones y proyectos que reflejan mi pasión por la tecnología.

## 🛠️ Stack Tecnológico

![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/-Metasploit-000000?logo=metasploit&logoColor=white)
![Nmap](https://img.shields.io/badge/-Nmap-000000?logo=nmap&logoColor=white)

---

## 🚀 Proyectos Destacados

Explora mis principales contribuciones en seguridad ofensiva y automatización:

### 🔍 NekoFi.sh - Auditoría WiFi Automatizada

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repositorio-181717?style=for-the-badge&logo=github)](https://github.com/rodrigo47363/NekoFI)

```bash
✔️ Automatiza procesos de auditoría WiFi  
✔️ Detección inteligente de interfaces de red  
✔️ Gestión avanzada de modos monitor/managed  
✔️ Integración con herramientas de pentesting (Aircrack-ng, Reaver)  
```

**Tecnologías**:
![Bash](https://img.shields.io/badge/-Bash-4EAA25?logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![Aircrack-ng](https://img.shields.io/badge/-Aircrack--ng-000000?logo=aircrack-ng&logoColor=white)

---

### 🖥️ OSIdentifier.py - Detección de SO por TTL

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repositorio-181717?style=for-the-badge&logo=github)](https://github.com/rodrigo47363/OSIdentifier)

```python
🕵️‍♂️ Identificación pasiva de sistemas operativos  
📊 Análisis de valores TTL para reconocimiento  
🧩 Fácil integración con herramientas de seguridad  
🔧 Configuración personalizable para entornos específicos  
```

**Tecnologías**:
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
![Scapy](https://img.shields.io/badge/-Scapy-FFD43B?logo=python&logoColor=blue)
![Networking](https://img.shields.io/badge/-Networking-00599C?logo=cisco&logoColor=white)

---

## 💡 Características Clave de Mis Proyectos

| Ventaja | NekoFi.sh | OSIdentifier.py |
|---------|-----------|-----------------|
| **Automatización** | ✔️ Auditoría WiFi completa | ✔️ Detección automática de SO |
| **Eficiencia** | ✔️ Procesos optimizados | ✔️ Análisis rápido de paquetes |
| **Precisión** | ✔️ Gestión precisa de interfaces | ✔️ Identificación exacta por TTL |
| **Integración** | ✔️ Compatible con suite aircrack | ✔️ Funciona con herramientas de red |

---

<div align="center">

<a href="https://github.com/rodrigo47363">
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api?username=rodrigo47363&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true"
    alt="GitHub Stats"
  />
  <img
    height="180"
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=rodrigo47363&layout=compact&theme=radical&hide_border=true&langs_count=8"
    alt="Top Languages"
  />
</a>
<div align="center">

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=rodrigo47363&theme=radical&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)

</div>

</div>


---

## 🛠️ Herramientas y Plataformas Favoritas

<div align="center">

[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Parrot OS](https://img.shields.io/badge/Parrot_OS-4DBCE9?style=for-the-badge&logo=parrotos&logoColor=white)](https://www.parrotsec.org/)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/profile/2072477)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Rodrigo.47363)

</div>

---

## 🌐 Conecta Conmigo

<div align="center">

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)](https://youtube.com/@Rodrigo-47363?sub_confirmation=1)
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rodrigo-v-695728215)
[![HackTheBox](https://img.shields.io/badge/HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/profile/2072477)
[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/Rodrigo.47363)
[![ProtonMail](https://img.shields.io/badge/Email-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:rodrigovil@proton.me)

</div>

---

## 🔗 Enlaces de Referido

<div align="center">

[![HackTheBox Referral](https://img.shields.io/badge/Únete_a_HackTheBox-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://referral.hackthebox.com/mz7ZtlJ)
[![TryHackMe Referral](https://img.shields.io/badge/Únete_a_TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/signup?referrer=64f0d7665fde58f3ec71379b)

</div>

---

## 💖 Apoya Mi Trabajo

<div align="center">

[![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)](bitcoin:bc1qkzmpd0hry99qms7ef23vsyx9vt34pzzaslpp8y)
[![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)](https://etherscan.io/address/0xB75bC57C54FCBFF139EBF981A596B019C537d018)
[![Solana](https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white)](https://solscan.io/address/ELekuGHcmZjhXrtHNqHuu8QmdCZr3oCWtTmu3QUQ5hac)

</div>

### 📍 Direcciones de Criptomonedas

```crypto
BTC:  bc1qkzmpd0hry99qms7ef23vsyx9vt34pzzaslpp8y  
ETH:  0xB75bC57C54FCBFF139EBF981A596B019C537d018  
SOL:  ELekuGHcmZjhXrtHNqHuu8QmdCZr3oCWtTmu3QUQ5hac
```
