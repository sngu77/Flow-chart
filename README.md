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

graph TB
    A(Fielded System) --> B(Control Interface)
    B --> C(Upgraded Sensor Unit)
    C --> D(Power Supply Interface)
    C --> E(Data Processing Unit)
    E --> F(Communication Module)
    F --> G(External Systems)
    E --> H(User Interface)
