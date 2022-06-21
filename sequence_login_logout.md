```mermaid
sequenceDiagram
    actor u as User
    participant I as Interface
    participant L1 as Login
    participant L2 as Logout
    participant S as Search
    participant A as Search All Courses
    participant P as Search Courses by Parameters
    u->>I: Select User
    I->>L1: Select Login
    I->>L2: Select Logout
    I->>S: Select Search Courses
    S->>A: Seleect Search All
    S->>P: Select Search by Parameters
