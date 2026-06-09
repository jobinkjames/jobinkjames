<div align="center">

<!-- Animated banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=Jobin%20K%20James&fontSize=50&fontColor=00d4ff&animation=fadeIn&fontAlignY=38&desc=Embedded%20Systems%20Engineer%20%7C%20AI%20Integrator%20%7C%20IoT%20Builder&descAlignY=58&descColor=ffffff"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=800&color=00D4FF&center=true&vCenter=true&multiline=false&width=1000&lines=Embedded+Systems+Engineer;Designing+Reliable+Firmware+for+Connected+Devices;Industrial+Automation+%7C+IoT+%7C+Edge+AI;PIC32+%7C+STM32+%7C+ESP32+%7C+Linux;Building+Scalable+Solutions+from+Prototype+to+Production;MQTT+%7C+Modbus+%7C+CAN+%7C+RS485;Creator+of+Nova+AI+Voice+Assistant;Exploring+AI-Powered+Embedded+Systems;M.Sc+Electronics+%7C+Maker+%7C+Innovator;Building+Technology+That+Makes+a+Difference)](https://git.io/typing-svg)
<br/>

<img src="https://komarev.com/ghpvc/?username=jobinkjames&label=Profile+Views&color=00d4ff&style=flat-square" />
&nbsp;
<img src="https://img.shields.io/github/followers/jobinkjames?label=Followers&style=flat-square&color=00d4ff" />
&nbsp;
<img src="https://img.shields.io/badge/Open%20to-Collaborate-00d4ff?style=flat-square" />

</div>

---

## ⚡ `jobin.c` — System Boot

```c
/**
 * @file    jobin.c
 * @author  Jobin K James
 * @brief   Self-initializing engineer firmware
 * @version 3.0.0
 * @date    2023 - present
 */

#include <embedded_systems.h>
#include <ai_integration.h>
#include <iot_builder.h>
#include <human.h>

/* ─── Configuration Registers ─────────────────────────────── */
#define NAME            "Jobin K James"
#define ROLE            "Embedded Systems Engineer"
#define COMPANY         "Emirates Automation Pvt Ltd"
#define LOCATION        "Bengaluru, India  📍"
#define EDUCATION       "M.Sc Electronics — MG University, Kerala"
#define EXPERIENCE_YRS  2

/* ─── Peripheral Interfaces ───────────────────────────────── */
typedef struct {
    const char *linkedin;
    const char *email;
    const char *github;
} contact_t;

static const contact_t ME = {
    .linkedin = "linkedin.com/in/jobin-k-james-334811262",
    .email    = "jobinkjames3112@gmail.com",
    .github   = "github.com/jobinkjames",
};

/* ─── Skill Registers (active HIGH) ──────────────────────────*/
static const char *CORE_SKILLS[] = {
    "Bare-metal C/C++",    "Zephyr RTOS",        "FreeRTOS",
    "PIC18 / PIC32 / STM32 / ESP32",             "Linux / Yocto",
    "Edge AI & TFLite",    "YOLO v8 / Roboflow", "Google Gemini",
    "Flutter / Dart",      "AWS / Firebase",      "Altium Designer",
    "TCP/IP / MQTT",       "Hardware Design",     "Power Electronics",
    NULL  /* sentinel */
};

/* ─── Main Routine ────────────────────────────────────────── */
int main(void) {
    engineer_init(&ME);
    skills_load(CORE_SKILLS);

    while (1) {
        problem   = sense_environment();
        solution  = design_and_build(problem);
        feedback  = deploy_and_iterate(solution);
        knowledge = learn_from(feedback);
        share(knowledge);          /* open source ❤️  */
    }

    return 0;   /* never reached — engineer runs forever */
}
```

---

## 🔬 `skill_map.h` — Full Capability Register

<div align="center">

### 🔩 Silicon & Firmware

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![PIC18](https://img.shields.io/badge/PIC-BF360C?style=for-the-badge&logo=microchip&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=Raspberry%20Pi&logoColor=white)

### 🌀 OS & Real-Time

![Zephyr](https://img.shields.io/badge/Zephyr%20RTOS-6E4AE8?style=for-the-badge&logo=zephyr&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-003153?style=for-the-badge)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Yocto](https://img.shields.io/badge/Yocto%20Project-5A87BE?style=for-the-badge)
![ROS](https://img.shields.io/badge/ROS-22314E?style=for-the-badge&logo=ros&logoColor=white)

### 📡 Protocols & Connectivity

![I2C](https://img.shields.io/badge/I2C-0288D1?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-0288D1?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-0288D1?style=for-the-badge)
![CAN](https://img.shields.io/badge/CAN%20Bus-FF6F00?style=for-the-badge)
![RS485](https://img.shields.io/badge/RS485-FF6F00?style=for-the-badge)
![TCP](https://img.shields.io/badge/TCP%2FIP-00796B?style=for-the-badge)
![UDP](https://img.shields.io/badge/UDP-00796B?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white)

### 🧠 AI · ML · Computer Vision

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini%202.0%20Flash-4285F4?style=for-the-badge&logo=google&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-222222?style=for-the-badge)
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=for-the-badge)
![TFLite](https://img.shields.io/badge/TFLite%20Edge%20AI-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00897B?style=for-the-badge&logo=google&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)
![RAG](https://img.shields.io/badge/RAG%20Server-412991?style=for-the-badge)
![OpenWakeWord](https://img.shields.io/badge/OpenWakeWord-1565C0?style=for-the-badge)

### 🌐 Web · Mobile · Cloud

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

### 🔌 Hardware Design & Power

![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![PCB Design](https://img.shields.io/badge/PCB%20Design-006600?style=for-the-badge)
![Power Electronics](https://img.shields.io/badge/Power%20Electronics-F57F17?style=for-the-badge)
![Schematic](https://img.shields.io/badge/Schematic%20Design-455A64?style=for-the-badge)

</div>

---

## 📊 `proficiency.map` — Skill Depth Matrix

```
/* Proficiency levels: ████ Expert  ███░ Advanced  ██░░ Intermediate  █░░░ Learning */

[FIRMWARE]
Bare-metal C/C++     ████████████████████  ████ Expert
PIC18 / PIC32        ████████████████████  ████ Expert
STM32 / ESP32        ████████████████░░░░  ███░ Advanced
Zephyr RTOS          ███████████████░░░░░  ███░ Advanced
FreeRTOS             ████████████░░░░░░░░  ███░ Advanced
Linux / Yocto        █████████████░░░░░░░  ██░░ Intermediate

[PROTOCOLS]
I2C / SPI / UART     ████████████████████  ████ Expert
CAN Bus / RS485      █████████████████░░░  ████ Expert
TCP/IP / UDP         ████████████░░░░░░░░  ███░ Advanced
MQTT                 ████████████░░░░░░░░  ██░░ Intermediate

[AI & VISION]
Python               ███████████████░░░░░  ███░ Advanced
Edge AI / TFLite     ████████████░░░░░░░░  ██░░ Intermediate
YOLOv8 / Vision      ████████████░░░░░░░░  ██░░ Intermediate
Gemini / LLM APIs    ███████████████░░░░░  ███░ Advanced

[WEB & MOBILE]
Flutter / Dart       ████████████░░░░░░░░  ██░░ Intermediate
FastAPI              █████████████░░░░░░░  ███░ Advanced
HTML / CSS / JS      █████████████░░░░░░░  ███░ Advanced
AWS / Firebase       ██████████░░░░░░░░░░  ██░░ Intermediate

[HARDWARE]
Altium / PCB         ████████████░░░░░░░░  ██░░ Intermediate
Power Electronics    ██████████░░░░░░░░░░  ██░░ Intermediate
```

---

## 💼 `career.log` — Work Experience

```
[2023-08-01 00:00:00] INFO  : Joined Emirates Automation Pvt Ltd
[2023-08-01 00:00:01] BOOT  : Role loaded — Embedded Systems Engineer
[2023-08-15 09:00:00] TASK  : PIC18F97J94 driver suite development started
[2023-10-01 11:00:00] TASK  : Zephyr RTOS driver integration — production target
[2024-01-10 10:00:00] TASK  : YOLOv8 camera detection pipeline deployed
[2024-03-05 14:00:00] TASK  : Flutter IoT dashboard shipped to client
[2024-06-20 09:00:00] TASK  : Edge AI (TFLite) embedded on STM32 target
[2025-01-01 00:00:00] INFO  : 1.5 years strong — still shipping ✅
[2026-06-09 00:00:00] NOW   : Building, learning, innovating — RUNNING ⚡
```

**Emirates Automation Pvt Ltd — Bengaluru** *(Aug 2023 – Present)*
- ⚡ Bare-metal & RTOS firmware for industrial embedded platforms
- 🔧 Full register-level driver development for **PIC18F97J94** custom motherboard (SPI, I2C, UART, CAN, RS485)
- 🤖 Computer vision pipelines with **YOLOv8** and **Roboflow** on embedded Linux
- 🌐 IoT product development: Flutter apps, web dashboards, AWS/Firebase cloud
- 🧠 Edge AI model deployment using **TFLite** on constrained hardware
- 🔌 Hardware design reviews and **Altium Designer** schematic work
- 📡 Network protocol integration: **TCP/IP, UDP, MQTT** for connected devices

---

## 🎓 `education.hex` — Academic Foundation

```
0x0000: Institution  = Mahatma Gandhi University, Kottayam, Kerala
0x0001: Degree       = Master of Science — Electronics
0x0002: Focus        = Embedded Systems, Signal Processing, VLSI
0x0003: Status       = GRADUATED ✅
0x0004: Impact       = Foundation for deep silicon-level engineering
```

---

## 🚀 `projects[]` — Build Log

<table>
<tr>
<td width="50%" valign="top">

### 🏠 Nova — AI Smart Home Assistant
![Status](https://img.shields.io/badge/Status-Active%20Dev-00d4ff?style=flat-square)

> *"Hey Nova!" → Raspberry Pi hears you, sees you, responds in Malayalam*

**Stack:** Pi Zero 2W · Gemini 2.0 Flash · OpenWakeWord · MediaPipe · LD2410 mmWave · Gemini TTS

- Wake word detection ("Hey Nova")
- Face recognition-based user identification
- mmWave presence sensing
- Multimodal AI responses in Malayalam

</td>
<td width="50%" valign="top">

### 🎓 Embedded AI Tutor
![Status](https://img.shields.io/badge/Status-Shipped-00c853?style=flat-square)

> *30-topic bare-metal curriculum with an AI teaching assistant*

**Stack:** FastAPI · DeepSeek AI · Upstash Redis · Electron IDE · PIC32CM

- Custom IDE built with Electron
- SSE streaming responses
- Prompt caching for fast replies
- Beginner → Expert progression

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 RAG Server
![Status](https://img.shields.io/badge/Status-Shipped-00c853?style=flat-square)

> *Ground your AI in real documents — no hallucinations*

**Stack:** Python · Vector DB · LLM APIs

- Retrieval-Augmented Generation pipeline
- Domain-specific Q&A from custom docs
- REST API interface

</td>
<td width="50%" valign="top">

### 🌸 Aroma 24/7 Diffuser
![Status](https://img.shields.io/badge/Status-Shipped-00c853?style=flat-square)

> *IoT-connected smart perfume diffuser with full app control*

**Stack:** Flutter · BLE/WiFi · Desktop App

- Mobile + desktop control interface
- Scheduling & automation
- Remote fragrance management

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔧 PIC18F97J94 Driver Suite
![Status](https://img.shields.io/badge/Status-Production-ff6f00?style=flat-square)

> *Zero HAL. Pure registers. Full control.*

**Stack:** Bare-metal C · PIC18F97J94

- SPI Flash, DAC, I2C IMU, OLED
- CAN bus, RS485, Motor driver
- 100% register-level, no abstraction

</td>
<td width="50%" valign="top">

### ⚡ Zephyr Driver Development
![Status](https://img.shields.io/badge/Status-Production-ff6f00?style=flat-square)

> *Production RTOS drivers from device tree to runtime*

**Stack:** Zephyr RTOS · Device Tree · C

- Device tree configuration
- Peripheral driver integration
- Real-time task scheduling

</td>
</tr>
</table>

---

## 📈 `github --stats`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=jobinkjames&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=jobinkjames&layout=donut&theme=tokyonight&hide_border=true" width="38%" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=jobinkjames&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" width="70%" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=jobinkjames&theme=tokyo-night&hide_border=true&area=true" width="95%" />

</div>

---

## 🏆 `achievements[]`

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=jobinkjames&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7" />
</div>

---

## 🔗 `connect(jobin)`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-jobin--k--james-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://in.linkedin.com/in/jobin-k-james-334811262)
[![Gmail](https://img.shields.io/badge/Gmail-jobinkjames3112@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jobinkjames3112@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-jobinkjames-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jobinkjames)

📍 **Bengaluru, India** &nbsp;|&nbsp; 🕐 **IST (UTC +5:30)** &nbsp;|&nbsp; 💬 **Open to collaborations**

</div>

---

<!-- Footer wave -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=120&section=footer&animation=fadeIn"/>

<div align="center">

```c
/* EOF jobin.c — See you in the codebase! ⚡ */
return EXIT_SUCCESS;
```

⭐ *Star my repos if you find them useful — it fuels the next build!*

</div>
