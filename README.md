```mermaid
graph TD
    A(Start System) --> B(Sensor Activation)
    B --> C(Data Acquisition)
    C --> D(Data Filtering)
    D --> E(Data Analysis)
    E --> F{Validate Data}
    F --> |Valid| G(Trigger Action)
    F --> |Invalid| C
    G --> H(Log Results)
    H --> I(End System)
