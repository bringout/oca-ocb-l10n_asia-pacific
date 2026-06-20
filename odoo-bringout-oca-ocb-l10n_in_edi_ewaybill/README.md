# Indian - E-waybill


Indian - E-waybill
====================================
To submit E-waybill through API to the government.
We use "Tera Software Limited" as GSP

Step 1: First you need to create an API username and password in the E-waybill portal.
Step 2: Switch to company related to that GST number
Step 3: Set that username and password in Odoo (Goto: Invoicing/Accounting -> Configration -> Settings -> Indian Electronic WayBill or find "E-waybill" in search bar)
Step 4: Repeat steps 1,2,3 for all GSTIN you have in odoo. If you have a multi-company with the same GST number then perform step 1 for the first company only.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_in_edi_ewaybill
```

## Dependencies

- l10n_in_edi

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 18.0
- Path: addons/l10n_in_edi_ewaybill

## License

This package preserves the original LGPL-3 license.
