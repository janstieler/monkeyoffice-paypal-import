# monkeyoffice-pecunia-import
Importscript bank statement from Paypal into MonkeyOffice

This importscript is for adding bank account statements from Paypal to [MonkeyOffice](http://www.monkey-office.de/ "Prosaldo Website").

Standard Paypal columns:

| Paypal Identifier Column | Monkey Office Column Index |
| --- | --- |
| Datum |  Spalte_001 |
| Uhrzeit | Spalte_002 |
| Zeitzone | Spalte_003 |
| Beschreibung | Spalte_004 |
| Währung | Spalte_005 |
| Brutto | Spalte_006 |
| Gebühr | Spalte_007 |
| Netto | Spalte_008 |
| Guthaben | Spalte_009 |
| Transaktionscode | Spalte_010 |
| Absender E-Mail-Adresse | Spalte_011 |
| Name | Spalte_012 |
| Name der Bank | Spalte_013 |
| Bankkonto | Spalte_014 |
| Versand- und Bearbeitungsgebühr | Spalte_015 |
| Umsatzsteuer | Spalte_016 |
| Transaktionscode | Spalte_017 |
| Zugehöriger Transaktionscode | Spalte_018 |

The paypal.txt is prefilled for this Paypal columns:

| Paypal Column | Monkey Office Column |
| --- | --- |
| Datum | Wertstellung |
| Transaktionscode | BelegNr |
| Rechnungsnummer | Referenz |
| Beschreibung + Transaktionscode + Rechnungsnummer | Text |
| Brutto | Betrag |
|  | Konto |
|  | Steuer |
|  | KSt1 |
|  | KSt2 |
| Beschreibung + Absender E-Mail-Adresse + Rechnungsnummer + Zugehöriger Transaktionscode | Notizen |

