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

![alt text](https://mermaidjs.github.io/mermaid-live-editor/#/view/eyJjb2RlIjoiZ3JhcGggTFJcbkEoQ0RCKVxuQigoQ0RCUykpXG5DKChDUykpXG5EKChDTSkpXG5FKChTQ1MpKVxuRigoU0NJKSlcbkcoKE1TKSlcbkgoKFNTKSlcbkkoKFNJUFMpKVxuSigoTG9nREJTKSlcbksoKEdBKSlcbkwoKEJyb3dzZXIpKVxuTVtQQUJYXVxuTihMb2dEQilcbk8oREIpXG5QKChMQ0EpKVxuUSgoR0RBKSlcblxuQiAtLT4gQVxuQyAtLT4gQlxuRCAtLT4gQyBcbkUgLS0-IENcbkUgLS0-IEdcbkUgLS0-IFBcbkYgLS0-IENcbkYgLS0-IEVcbkYgLS0-IEpcbkcgLS0-IENcbkcgLS0-IEpcbkggLS0-IENcbkggLS0-IEdcbkggLS0-IElcbkkgLS0-IENcbkkgLS0-IEdcbkkgLS0-IE1cbkogLS0-IENcbkogLS0-IE5cbksgLS0-IENcbksgLS0-IEZcbksgLS0-IEpcbksgLS0-IFFcbkwgLS0-IEtcbiIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19 "Framework")
