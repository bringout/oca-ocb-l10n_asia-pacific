# Indonesia E-faktur


E-Faktur Menu(Indonesia)
Format: 010.000-16.00000001
* 2 (dua) digit pertama adalah Kode Transaksi
* 1 (satu) digit berikutnya adalah Kode Status
* 3 (tiga) digit berikutnya adalah Kode Cabang
* 2 (dua) digit pertama adalah Tahun Penerbitan
* 8 (delapan) digit berikutnya adalah Nomor Urut

To be able to export customer invoices as e-Faktur,
you need to put the ranges of numbers you were assigned
by the government in Accounting > Customers > e-Faktur

When you validate an invoice, where the partner has the ID PKP
field checked, a tax number will be assigned to that invoice.
Afterwards, you can filter the invoices still to export in the
invoices list and click on Action > Download e-Faktur to download
the csv and upload it to the site of the government.

You can replace an already sent invoice by another by indicating
the replaced invoice and the new one and you can reset an invoice
you have not already sent to the government to reuse its number.
    

## Installation

```bash
pip install odoo-bringout-oca-ocb-l10n_id_efaktur
```

## Dependencies

- l10n_id

## Source

- Repository: https://github.com/OCA/OCB
- Branch: 17.0
- Path: addons/l10n_id_efaktur

## License

This package preserves the original LGPL-3 license.
