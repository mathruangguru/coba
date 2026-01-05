graph LR
    subgraph "Himpunan P"
        P1(1)
        P2(2)
        P3(3)
    end
    subgraph "Himpunan Q"
        Q4(4)
        Q7(7)
        Q10(10)
    end

    P1 -->|f| Q4
    P2 -->|f| Q7
    P3 -->|f| Q10

    style P1 fill:#fff,stroke:#333,stroke-width:2px
    style P2 fill:#fff,stroke:#333,stroke-width:2px
    style P3 fill:#fff,stroke:#333,stroke-width:2px
    style Q4 fill:#fff,stroke:#333,stroke-width:2px
    style Q7 fill:#fff,stroke:#333,stroke-width:2px
    style Q10 fill:#fff,stroke:#333,stroke-width:2px
    style "Himpunan P" fill:none,stroke:#333,stroke-width:2px,stroke-dasharray: 5 5
    style "Himpunan Q" fill:none,stroke:#333,stroke-width:2px,stroke-dasharray: 5 5
