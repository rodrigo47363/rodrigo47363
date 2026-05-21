# 🛡️ Rodrigo — Offensive Security Specialist

<div align="center">

![Cyber Security](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=4000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=600&lines=Ethical+Hacking+Specialist;Network+Security+Analyst;WiFi+Security+Researcher;Bug+Bounty+Hunter)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rodrigo-v-695728215)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Rodrigo-47363)
[![Email](https://img.shields.io/badge/Email-Contact-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:rodrigovil@proton.me)

</div>

---

## 👨‍💻 Sobre mí

Soy un practicante de seguridad ofensiva especializado en **penetration testing**, **investigación de seguridad inalámbrica** y **bug bounty**. Me enfoco en auditorías con metodología reproducible, automatización de tareas operativas y técnicas de enumeración silenciosa que maximizan hallazgos con bajo ruido en la red.

> **Filosofía táctica:** *Impacto real > Teoría.* Automatizo las tareas de reconocimiento iterativo para concentrar el esfuerzo analítico en la explotación de vulnerabilidades complejas, la validación manual exhaustiva y la redacción de reportes técnicos claros.

---

## 🔧 Arsenal y Entorno Operativo

**Lenguajes y Scripting**  
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Herramientas de Auditoría**  
![Nmap](https://img.shields.io/badge/-Nmap-000000?style=flat-square&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/-Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/-Metasploit-000000?style=flat-square&logo=metasploit&logoColor=white)
![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Aircrack-ng](https://img.shields.io/badge/-Aircrack--ng-000000?style=flat-square&logo=aircrack-ng&logoColor=white)

**Entorno de Trabajo**  
Mi infraestructura de auditoría está diseñada para la velocidad y el control absoluto mediante teclado, minimizando la latencia entre el pensamiento y la ejecución:  
![Parrot OS](https://img.shields.io/badge/-Parrot_OS-4DBCE9?style=flat-square&logo=parrotos&logoColor=white)
![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Debian](https://img.shields.io/badge/-Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![bspwm](https://img.shields.io/badge/-bspwm-333333?style=flat-square&logo=windowsterminal&logoColor=white)
![sxhkd](https://img.shields.io/badge/-sxhkd-555555?style=flat-square)

---

## 🎯 Áreas de Especialización

| Dominio | Vectores y Técnicas Clave |
|---------|---------------------------|
| **Web Application Security** | XSS (Reflejado, Persistente, DOM/Template), SQLi (Blind/2nd Order), Auth Bypass (IDOR, Token Reuse), CSRF. |
| **Network & Wireless** | PT Red Interna/Externa, Auditorías WPA/WPA2/WPS, AP Rogue, Passive OS Fingerprinting. |
| **Metodología Ofensiva** | Reconocimiento pasivo (OSINT), Enumeración dirigida, Explotación controlada, Evasión de ruido y escalada de privilegios. |

---

## 🚀 Proyectos Destacados

### 📡 [NekoFi.sh](https://github.com/rodrigo47363/NekoFI) — Automated WiFi Security Framework
Framework modular en Bash para auditorías WiFi en entornos reales. Automatiza la detección de interfaces, la orquestación de modos monitor/managed y despliega asistentes para ataques WPS.

* **Enfoque:** Reproducibilidad técnica y reducción de errores operativos (OpSec).
* **Parámetros clave:** Implementa comprobaciones de dependencias e inyección de paquetes sin intervención manual continua.

```bash
# Instalación y uso
git clone [https://github.com/rodrigo47363/NekoFI.git](https://github.com/rodrigo47363/NekoFI.git) && cd NekoFI
chmod +x nekofi.sh
sudo ./nekofi.sh --auto

# Output esperado:
# [*] Iniciando NekoFi.sh...
# [+] Interfaz wlan0 detectada.
# [+] Levantando interfaz en modo monitor (wlan0mon)...
# [*] Escaneando redes objetivo cercanas (Ctrl+C para detener)...

```

### 🕵️ [OSIdentifier.py](https://github.com/rodrigo47363/OSIdentifier) — Passive OS Fingerprinting

Herramienta en Python que infiere sistemas operativos remotos mediante análisis heurístico de valores TTL (ICMP) sin generar tráfico activo ruidoso en la red.

* **Enfoque:** Reconocimiento sigiloso (Stealth) y normalización de datos capturados.
* **Stack:** Python 3, `scapy` para la disección de paquetes a bajo nivel.

```bash
# Ejecución pasiva en interfaz específica
sudo python3 OSIdentifier.py --interface wlp3s0 --capture-time 60

# Output esperado:
# [*] Escuchando tráfico en wlp3s0 durante 60 segundos...
# [+] Host: 192.168.1.15 | TTL: 64  | OS Inferido: Linux/Unix
# [+] Host: 192.168.1.45 | TTL: 128 | OS Inferido: Windows

```

---

## 📊 Estadísticas de GitHub

---

## 🌐 Perfiles CTF y Plataformas

*Únete mediante mis referidos:* [HackTheBox](https://referral.hackthebox.com/mz7ZtlJ) | [TryHackMe](https://tryhackme.com/signup?referrer=64f0d7665fde58f3ec71379b)

---

## 📜 Disclaimer y Contribuciones

* **Reglas de Opción (ROEs) y Ética:** Todo el contenido, código y pruebas de concepto (PoCs) en mis repositorios están orientados **exclusivamente a investigación y pruebas en entornos autorizados**.
* **Pull Requests:** Para contribuir, realiza un Fork, crea tu rama y envía un PR con una descripción técnica exhaustiva. Si alteras el comportamiento de red, es obligatorio incluir un `safety-check` en el código.

*  `bc1qkzmpd0hry99qms7ef23vsyx9vt34pzzaslpp8y`
*  `0xB75bC57C54FCBFF139EBF981A596B019C537d018`
*  `ELekuGHcmZjhXrtHNqHuu8QmdCZr3oCWtTmu3QUQ5hac`

---
