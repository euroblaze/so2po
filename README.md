## What does this Odoo module do?

This module creates a consolidated PurchaseOrder by reading SaleOrder-positions unavailable stock.

- It reads all SaleOrders that are selected.
- Notes all the positions and quantities that are not in stock.
- Creates a PO in respective quantities to respective vendors
