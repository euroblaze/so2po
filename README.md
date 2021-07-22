## What does this Odoo module do?

This module creates a consolidated PurchaseOrder by reading SaleOrder-positions unavailable stock.

- It reads all SaleOrders that are selected.
- Notes all the positions and quantities that are 
    - not in stock, or
    - below threshold level.
- Creates a PO in respective quantities to respective vendors
- When all the SOs are selected, a pop-up appears listing all the product lines, allowing purchase-manager to select the vendor to whom PO must be issued. Quantities to be purchased from Vendor can be modified. 


Available apps.odoo.com modules

- https://apps.odoo.com/apps/modules/14.0/bi_convert_purchase_from_sales/
- Several [purchase orders related modules](https://apps.odoo.com/apps/modules/browse?price=Free&search=purchase+order) available.
