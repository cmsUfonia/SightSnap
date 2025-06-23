# SightSnap
Overview of SightSnap
```mermaid
graph TD
    A[Surgery] --> B[3 Weeks Post-Op Dora Call];

    subgraph SightSnap Process
        direction TD; %% ADDED SEMICOLON HERE
        C[6 Weeks Post-Op SMS from Ufonia requesting photo of prescription];
        D[Patient takes photo and sends to Ufonia];
        E[Ufonia converts Photo to Data];

        %% Internal flow within SightSnap
        C --> D;
        D --> E;
    end

    B --> C; %% Connect B to the start of the SightSnap subgraph
    E --> F[12 Weeks Post-Op PROMS Dora Call]; %% Connect the end of SightSnap to F

    %% Styling for the SightSnap core process nodes (C, D, E) with identical borders
    style C fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style D fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
    style E fill:#E0FFFF,stroke:#4CAF50,stroke-width:2px;
