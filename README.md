# Pi-LED
RaspberryPi 5 LED
This serves as a first project on Github to gain a better understanding of how to use this enviroment. 

<pre> ```mermaid flowchart TD A[🚀 Project Start: Raspberry Pi 5 LED Blinker] --> B[📦 Install Dependencies] B --> C[🧰 Install WiringPi\nsudo apt install wiringpi] C --> D[📝 Write C++ Code\n(blink.cpp)] D --> E[🔧 Compile with g++\n g++ -o blink blink.cpp -lwiringPi] E --> F[🧪 Test LED Blinking] F --> G[✅ Success!] F --> H[🐞 Debug if Needed] subgraph Tools T1[💻 GitHub] T2[🔌 Raspberry Pi 5] T3[🧠 C++] T4[📎 WiringPi] T5[🛠 Terminal] end A --> T1 A --> T2 D --> T3 B --> T4 E --> T5 ``` </pre>
