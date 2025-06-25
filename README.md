# SightSnap
Overview of SightSnap
```mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call];

    subgraph "  &nbsp;&nbsp;&nbsp;**SightSnap Process**"
        X[" "]
        C[Following surgery, patients receive an SMS from Ufonia<br>reminding them to attend their optometrist for a sight test<br>and to request a free copy of their refraction result.]
        D[Patients are sent a personalised link<br>and asked to take a photo of their result.]
        E[The refraction result is then recorded<br>alongside the patient details.]

        X --> C
        C --> D
        D --> E
    end

    B --> X;
    E --> F[12 Weeks Post-Op PROMS Dora Call];

    style X fill:transparent,stroke:transparent;
    style C fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style D fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style E fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
