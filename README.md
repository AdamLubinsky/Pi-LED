# Pi-LED
RaspberryPi 5 LED

This serves as a first project on Github to gain a better understanding of how to use this enviroment. 


```mermaid
flowchart TD
    A[Start: Raspberry Pi Boot] --> B[Initialize GPIO Pins]
    B --> C[Run C++ Control Program]
    C --> D{User Input Received?}
    D -- Yes --> E[Set GPIO Pin High]
    D -- No --> F[Wait for Input]
    E --> G[LED Turns On]
    G --> H[Delay or Wait]
    H --> I[Set GPIO Pin Low]
    I --> J[LED Turns Off]
    J --> K[End]
    F --> D
```


