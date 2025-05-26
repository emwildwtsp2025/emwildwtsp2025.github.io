```mermaid
erDiagram
	PRODUCT ||--o{ CUSTOMER : ships
	PRODUCT {
	string shoes PK
	string socks PK
	string clothes PK
	}
	CUSTOMER ||--o{ PRODUCT : purchases
	SALE ||--o{ INVENTORY : decreases
	INVENTORY ||--o{ PRODUCT : stores
```
