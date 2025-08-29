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

This addon depends on:
- l10n_in_edi

## Manifest Information

- **Name**: Indian - E-waybill
- **Version**: 1.03.00
- **Category**: Accounting/Localizations/EDI
- **License**: LGPL-3
- **Installable**: True

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_in_edi_ewaybill`.

## License

This package maintains the original LGPL-3 license from the upstream Odoo project.

## Documentation

- Overview: doc/OVERVIEW.md
- Architecture: doc/ARCHITECTURE.md
- Models: doc/MODELS.md
- Controllers: doc/CONTROLLERS.md
- Wizards: doc/WIZARDS.md
- Reports: doc/REPORTS.md
- Security: doc/SECURITY.md
- Install: doc/INSTALL.md
- Usage: doc/USAGE.md
- Configuration: doc/CONFIGURATION.md
- Dependencies: doc/DEPENDENCIES.md
- Troubleshooting: doc/TROUBLESHOOTING.md
- FAQ: doc/FAQ.md
