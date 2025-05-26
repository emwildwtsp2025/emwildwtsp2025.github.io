```mermaid
---
Title: Nike
---
erdiagram
	PRODUCT ||--||{CUSTOMER : ships}
	CUSTOMER ||--|{PRODUCT : purchases}
	SALE {
	INVENTORY {
