```mermaid
sequenceDiagram
    actor u as User
    participant I as Enter Interface
    participant L1 as Login
    participant L2 as Logout
    u->>I: Select User
    I->>L1: Select Login
    I->>L2: Select Logout
    
