```mermaid 
graph TD
    A[Sensor Upgrade Program] --> B[Program Management]
    A --> C[Requirement Analysis]
    A --> D[System Design]
    A --> E[Testing and Validation]
    C --> F[Hardware Development Integration]
    B --> F
    D --> F
    E --> F
    F --> F1[Prototype Manufacturing]
    F --> F3[Hardware Integration]
    F --> F4[Integration Testing]
    F1 --> G[Deployment]
    F3 --> G[Deployment]
    F4 --> G[Deployment]
    G --> G1[Field Installation]
    G --> G2[Operational Testing]
    G --> G3[Performance Monitoring]
    G1 --> G4[Project Closure]
    G2 --> G4[Project Closure]
    G3 --> G4[Project Closure]
