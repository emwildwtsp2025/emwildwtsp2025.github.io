```mermaid
erDiagram
    CAR ||--o{ NAMED-DRIVER : allows
    PERSON }o..o{ NAMED-DRIVER : is
```


```mermaid
erDiagram
	PRODUCT ||--o{ CUSTOMER : ships
	}
	CUSTOMER ||--|{ PRODUCT : purchases
	}
	SALE ||--| { INVENTORY : decreases
	}
	INVENTORY |--| { PRODUCT : holds
	}
```
