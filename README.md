# Pi-LED
RaspberryPi 5 LED
This serves as a first project on Github to gain a better understanding of how to use this enviroment. 


# Pi-LED: C++ GPIO Control on Raspberry Pi 5 This project demonstrates how to control a GPIO pin using C++ and WiringPi to blink an LED on a Raspberry Pi 5. ## 🛠 Tools Used - Raspberry Pi 5 - C++ - WiringPi - GitHub ## 📈 Project Flow ```mermaid flowchart TD A[🚀 Start: Pi-LED Project] --> B[📦 Install WiringPi] B --> C[📝 Write blink.cpp] C --> D[🔧 Compile: g++ blink.cpp -lwiringPi] D --> E[⚡ Run and Test on Raspberry Pi] E --> F[✅ Success!] E --> G[🐞 Debug if Needed] subgraph Tools T1[💻 GitHub] T2[🔌 Raspberry Pi 5] T3[🧠 C++] T4[📎 WiringPi] T5[🛠 Terminal] end A --> T1 A --> T2 C --> T3 B --> T4 D --> T5 ```
