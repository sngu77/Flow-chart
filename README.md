```mermaid
graph TD;
    A(Start) --> B(Initialize Sensor);
    B --> C(Read Sensor Data);
    C --> D(Preprocess Data);
    D --> E(Analyze Data);
    E --> F{Is Data Valid?};
    F --> |Yes| G(Decision Making);
    F --> |No| C;
    G --> H(Generate Alert);
    H --> I(Log Data);
    I --> J(Communicate Results);
    J --> K(End);
