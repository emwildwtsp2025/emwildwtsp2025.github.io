```mermaid
erDiagram
	PRODUCT ||--o{ CUSTOMER : ships
	PRODUCT {
	string shoes PK
	string socks PK
	string clothes PK
	}
	CUSTOMER ||--o{ PRODUCT : purchases
	CUSTOMER {
	string name PK
	string age PK
	string gender PK
	}
	SALE ||--o{ INVENTORY : decreases
	SALE {
	string time PK
	string cost PK
	}
	INVENTORY ||--o{ PRODUCT : stores
	INVENTORY {
	string product PK
	string amount
	string origin
	}
```

#### Descriptions
* Product – the product ships to and ends up in the possession of the customer. The type of product is important for sales information.
* Customer – the customer purchases the product. The demographic of the customers and what products they are purchasing is important.
* Sale – The sale decreases inventory and increases profit. Information about each sale such as the time and total cost is important.
* Inventory – The store inventory stores all available product. Information about the inventory such as the products, amount of product, and origin of the products is important.
