### What does this Odoo module do?

This module creates a consolidated PurchaseOrder by reading SaleOrder-positions unavailable stock.

- It reads all SaleOrders that are selected.
- Notes all the positions and quantities that are 
    - not in stock, or
    - below threshold level.
- Creates a PO in respective quantities to respective vendors
- When all the SOs are selected, a pop-up appears listing all the product lines, allowing purchase-manager to select the vendor to whom PO must be issued. Quantities to be purchased from Vendor can be modified. 

### Who uses this module?

Online retailers who use a "just in time (JIT) purchasing strategy" can use this module to make larger POs for all sales performed in a specific time-period.

### Available apps.odoo.com modules

- https://apps.odoo.com/apps/modules/14.0/bi_convert_purchase_from_sales/
- Several [purchase orders related modules](https://apps.odoo.com/apps/modules/browse?price=Free&search=purchase+order) available.

### What Settings are possible?
For every product-line on the PO, it is possible to select a vendor and load his respective purchase-price for the product.
Ensure all buttons, messages, views etc. are multilingual translatable
### User Experience
Upon multiple-selection of SOs, show a button on top of Sales -> Orders list view.
Once PO is successfully created, transfer user automatically to the newly created PO page.

