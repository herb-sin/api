# Stndr dev week 2023
última entrega do curso Java Back-end Dio

## Diagrama de Classes
```mermaid
classDiagram
  class User {
    - name: String
    - features: Feature[]
  }
  class Feature {
    - buttonRed: String
    - buttonBlue: String
  }

  User *--|> Feature
```
