```mermaid
graph TD
    A(Sensor) --> B(Signal Conditioning)
    B --> C(Analog-to-Digital Converter)
    C --> D(Microcontroller/Processor)
    D --> E(Memory)
    D --> F(Communication Interface)
    D --> G(Output/Display)
    H(Power Management) --> A
    H --> B
    H --> C
    H --> D
    H --> E
    H --> F
    H --> G
