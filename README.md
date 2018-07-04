# Genesys-Framework
Foundation

```mermaid
graph LR
A(CDB)
B((CDBS))
C((CS))
D((CM))
E((SCS))
F((SCI))
G((MS))
H((SS))
I((SIPS))
J((LogDBS))
K((GA))
L((Browser))
M[PABX]
N(LogDB)
O(DB)
P((LCA))
Q((GDA))

B --> A
C --> B
D --> C 
E --> C
E --> G
E --> P
F --> C
F --> E
F --> J
G --> C
G --> J
H --> C
H --> G
H --> I
I --> C
I --> G
I --> M
J --> C
J --> N
K --> C
K --> F
K --> J
K --> Q
L --> K
