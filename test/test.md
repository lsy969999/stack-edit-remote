
```mermaid
erDiagram
	CUSTOMER { int id string name string email }
	ORDER { int id date orderDate double amount }
	PRODUCT { int id string name double price }
	CUSTOMER ||--o{ ORDER : places ORDER ||--|{ PRODUCT : contains
```
sssss
![image](./image.jpg)

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAyMzUyMzk2LDUxODY2MDIyNCwtMTEzNj
MzNjU1Niw0NzI1OTg5MzBdfQ==
-->