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
