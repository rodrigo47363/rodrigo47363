# 🛡️ Rodrigo — Offensive Security Specialist

<div align="center">

![Cyber Security](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=4000&pause=1000&color=7AA2F7&center=true&vCenter=true&width=600&lines=Ethical+Hacking+Specialist;Red+Team+%26+Pentesting;WiFi+Security+Researcher;Bug+Bounty+Hunter)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rodrigo-v-695728215)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@Rodrigo-47363)
[![Email](https://img.shields.io/badge/Email-Contact-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:rodrigovil@proton.me)

</div>

---

## 👨‍💻 Sobre mí

Soy un especialista en seguridad ofensiva centrado en **penetration testing**, **operaciones de Red Team** y **bug bounty**. Mi enfoque metodológico abarca el ciclo completo de intrusión: desde la enumeración exhaustiva de la superficie de ataque, hasta la explotación, escalada de privilegios y post-explotación en entornos complejos.

> **Filosofía táctica:** *Impacto real > Teoría.* Priorizo la automatización de flujos de trabajo operativos con Python y Bash para optimizar el reconocimiento, permitiendo destinar el máximo esfuerzo analítico a la explotación manual, la evasión de defensas y la redacción de reportes técnicos accionables.

---

## 🔧 Arsenal y Entorno Operativo

**Desarrollo y Automatización** ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Reconocimiento y Explotación Web** ![Nmap](https://img.shields.io/badge/-Nmap-000000?style=flat-square&logo=nmap&logoColor=white)
![Burp Suite](https://img.shields.io/badge/-Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Metasploit](https://img.shields.io/badge/-Metasploit-000000?style=flat-square&logo=metasploit&logoColor=white)
![FFUF](https://img.shields.io/badge/-FFUF-20232A?style=flat-square&logo=fuzzing&logoColor=white)
![SQLMap](https://img.shields.io/badge/-SQLMap-1A1A1A?style=flat-square)

**Active Directory, Cracking & Post-Explotación** ![Impacket](https://img.shields.io/badge/-Impacket-4B8BBE?style=flat-square)
![CrackMapExec](https://img.shields.io/badge/-CrackMapExec-DC382D?style=flat-square)
![Enum4Linux](https://img.shields.io/badge/-Enum4Linux-000000?style=flat-square)
![Hashcat](https://img.shields.io/badge/-Hashcat-333333?style=flat-square)
![JohnTheRipper](https://img.shields.io/badge/-John_The_Ripper-E34F26?style=flat-square)

**Análisis Inalámbrico y de Red** ![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Aircrack-ng](https://img.shields.io/badge/-Aircrack--ng-000000?style=flat-square&logo=aircrack-ng&logoColor=white)

**Infraestructura Táctica (Tiling & Low-Latency)** Mi entorno de auditoría está estrictamente diseñado para la velocidad y el control absoluto mediante teclado, minimizando la latencia entre la toma de decisiones y la ejecución:  
![Parrot OS](https://img.shields.io/badge/-Parrot_OS-4DBCE9?style=flat-square&logo=parrotos&logoColor=white)
![Kali Linux](https://img.shields.io/badge/-Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Debian](https://img.shields.io/badge/-Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![bspwm](https://img.shields.io/badge/-bspwm-333333?style=flat-square&logo=windowsterminal&logoColor=white)
![sxhkd](https://img.shields.io/badge/-sxhkd-555555?style=flat-square)

---

## 🎯 Dominio Técnico

| Fase / Vector | Técnicas y Herramientas Destacadas |
|---------|---------------------------|
| **Web Application Security** | XSS (Reflected/Stored/DOM), SQLi (Blind/Time-Based), Auth Bypass, IDOR, SSRF, CSRF. |
| **Network & Wireless** | PT Red Interna/Externa, Auditorías WPA/WPA2/WPS, AP Rogue, Passive OS Fingerprinting. |
| **Directorio Activo & Post-Explotación** | AS-REP Roasting, Kerberoasting, Pass-The-Hash, volcado de NTDS.dit, Escalada de Privilegios (Linux/Windows). |
| **Metodología Ofensiva** | OSINT pasivo, enumeración agresiva controlada, evasión de AV/EDR básica y persistencia. |

---

## 🚀 Herramientas y Proyectos

### 📡 [NekoFi.sh](https://github.com/rodrigo47363/NekoFI) — Automated WiFi Security Framework
Framework modular en Bash diseñado para la automatización de auditorías WiFi en despliegues reales. Orquesta interfaces, inyección de paquetes y ataques WPS/WPA.

* **Objetivo:** Reproducibilidad técnica y OPSEC (reducción de errores humanos en operaciones en vivo).
* **Highlights:** Comprobación dinámica de dependencias, modo desatendido (`--auto`) y gestión transparente de `wpa_supplicant` y `NetworkManager`.

```bash
# Despliegue rápido
git clone [https://github.com/rodrigo47363/NekoFI.git](https://github.com/rodrigo47363/NekoFI.git) && cd NekoFI
chmod +x nekofi.sh
sudo ./nekofi.sh --auto

# Output esperado:
# [*] Iniciando NekoFi.sh framework...
# [+] Interfaz wlan0 detectada. Aislando procesos conflictivos.
# [+] Levantando interfaz en modo monitor (wlan0mon)...

```

### 🕵️ [OSIdentifier.py](https://github.com/rodrigo47363/OSIdentifier) — Passive OS Fingerprinting

Herramienta de Python que clasifica sistemas operativos remotos analizando heurísticamente los valores TTL de paquetes ICMP, garantizando cero interacción activa con el target.

* **Objetivo:** Reconocimiento sigiloso (Stealth) en redes altamente monitorizadas.
* **Stack:** Python 3 + `scapy` para manipulación y disección de tráfico a bajo nivel.

```bash
# Ejecución en modo escucha (Sniffing)
sudo python3 OSIdentifier.py --interface wlp3s0 --capture-time 60

# Output esperado:
# [+] Host: 192.168.1.15 | TTL: 64  | OS Inferido: Linux/Unix
# [+] Host: 192.168.1.45 | TTL: 128 | OS Inferido: Windows

```

---

## 📊 Telemetría Operativa (GitHub Stats)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=rodrigo47363&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117" alt="Estadísticas de Rodrigo" height="195">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rodrigo47363&layout=compact&theme=tokyonight&hide_border=true&langs_count=5&bg_color=0D1117" alt="Lenguajes Top" height="195">
</div>

<br>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=rodrigo47363&theme=tokyonight&hide_border=true&background=0D1117" alt="Racha de GitHub">
</div>


## 🏴‍☠️ Entrenamiento Continuo y CTFs

Mantener el filo táctico requiere práctica constante. Puedes seguir mi progresión en entornos de simulación y laboratorios de vulnerabilidades aquí:

<div align="center">
  <a href="https://referral.hackthebox.com/mz7ZtlJ"><img src="https://img.shields.io/badge/-HackTheBox-111927?style=for-the-badge&logo=hackthebox&logoColor=9FEF00" alt="HackTheBox"></a>
  <a href="https://tryhackme.com/signup?referrer=64f0d7665fde58f3ec71379b"><img src="https://img.shields.io/badge/-TryHackMe-111927?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe"></a>
</div>

---

## 📜 Rules of Engagement (RoE) y Contribuciones

> **⚠️ Aviso Legal y Ética:**  
> Todo el código, frameworks y pruebas de concepto (PoCs) alojados en mi perfil están desarrollados **estrictamente para auditorías autorizadas, operaciones de Red Teaming y entornos de laboratorio**. El uso indebido de estas herramientas fuera del marco legal y ético aplicable es responsabilidad exclusiva del operador final.

* **Política de PRs:** Fomento la colaboración técnica orientada al *stealth* y la optimización operativa. Si deseas contribuir: realiza un *fork*, trabaja en una rama descriptiva y documenta el impacto de red de tus cambios. Cualquier modificación que altere payloads debe integrar obligatoriamente validaciones de seguridad (`safety-checks`).

---

### ⚡ Apoyo a la Investigación Operativa

Si mis herramientas de automatización han optimizado tus flujos de auditoría o te han servido de referencia técnica, considera respaldar el desarrollo continuo y mi estrategia de acumulación (**HODL**):

<div align="center">

| Criptoactivo | Red | Dirección de Destino |
| :--- | :---: | :--- |
| ![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=flat-square&logo=bitcoin&logoColor=white) | **BTC** | `bc1qkzmpd0hry99qms7ef23vsyx9vt34pzzaslpp8y` |
| ![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white) | **ETH** | `0xB75bC57C54FCBFF139EBF981A596B019C537d018` |
| ![Solana](https://img.shields.io/badge/Solana-14F195?style=flat-square&logo=solana&logoColor=black) | **SOL** | `ELekuGHcmZjhXrtHNqHuu8QmdCZr3oCWtTmu3QUQ5hac` |

</div>
