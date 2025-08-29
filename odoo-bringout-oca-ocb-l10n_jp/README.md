# Japan - Accounting



Overview:
---------

* Chart of Accounts and Taxes template for companies in Japan.
* This probably does not cover all the necessary accounts for a company. You are expected to add/delete/modify accounts based on this template.

Note:
-----

* Fiscal positions '内税' and '外税' have been added to handle special requirements which might arise from POS implementation. [1]  Under normal circumstances, you might not need to use those at all.

[1] See https://github.com/odoo/odoo/pull/6470 for detail.

    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_jp
```

## Dependencies

This addon depends on:
- account
- l10n_multilang

## Manifest Information

- **Name**: Japan - Accounting
- **Version**: 2.3
- **Category**: Accounting/Localizations/Account Charts
- **License**: LGPL-3
- **Installable**: False

## Source

Based on [OCA/OCB](https://github.com/OCA/OCB) branch 16.0, addon `l10n_jp`.

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
