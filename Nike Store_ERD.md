```mermaid
erDiagram
	PRODUCT ||--||{CUSTOMER : ships}
	CUSTOMER ||--|{PRODUCT : purchases}
	SALE ||--| {INVENTORY : decreases}
	INVENTORY |--| {PRODUCT : holds}
```
