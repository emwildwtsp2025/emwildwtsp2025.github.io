```mermaid
erDiagram
    CAR ||--o{ NAMED-DRIVER : allows
    PERSON }o..o{ NAMED-DRIVER : is
```


```mermaid
erDiagram
	PRODUCT ||--o{ CUSTOMER : ships
	CUSTOMER ||--o{ PRODUCT : purchases
	SALE ||--o{ INVENTORY : decreases
	INVENTORY |--o{ PRODUCT : holds
```
