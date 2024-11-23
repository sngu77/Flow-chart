```mermaid 
graph TD
    A[Sensor Upgrade Software Program] --> B[Software Requirement Analysis]
    A --> C[Software Architecture Design]
    A --> D[Software Development System Design]
    A --> E[Software Testing and Validation]
    C --> F[Software Development Integration]
    B --> F
    D --> F
    E --> F
    F --> F1[Functional Requirement Specification ]
    F --> F3[Non-Functional Requirements]
    F --> F4[Integration Testing]
    F1 --> G[Deployment]
    F3 --> G[Deployment]
    F4 --> G[Deployment]
    G --> G1[Module Development Installation]
    G --> G2[Software User Acceptance Testing]
    G --> G3[Software Performance Monitoring]
    G1 --> G4[Project Closure]
    G2 --> G4[Project Closure]
    G3 --> G4[Project Closure]
