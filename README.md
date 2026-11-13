# Excess electronic component stock-list template

Use this template to turn an OEM or EMS inventory export into a lot list a buyer can review. The template works for excess and obsolete electronic components, including integrated circuits. [Download the CSV template](icultra-seller-stock-list-template.csv)

## Prepare the list

1. Confirm who owns the stock and who can approve its release. Keep held stock, customer-owned material without release approval, and service reserves out of the quantities offered.
2. Open a local copy of the CSV and remove the illustrative row. Add one row per complete manufacturer part number, lot and condition. Split rows when stock locations, lot codes, package formats or seal conditions differ.
3. Import the part-number and date-code columns as text so the spreadsheet preserves leading zeros and punctuation. State the unit alongside the quantity, mark estimated counts, and enter `unknown` for missing codes or handling history.
4. Export a dated or numbered revision for review. Keep the internal mapping to bins or containers separately so you can reconcile the list with physical stock.

## CSV columns

| Columns | What to record |
| --- | --- |
| `row_type` | Replace the illustrative marker with `actual` for real inventory rows. |
| `manufacturer`, `full_mpn` | Original manufacturer and full ordering code, including suffixes. |
| `quantity`, `quantity_unit` | Count and unit, such as pieces or reels. Identify estimates in `notes`. |
| `packaging`, `date_or_lot_codes`, `condition` | Actual carrier and seal status, readable lot or date codes, observed condition, and any known gaps. |
| `stock_country_city` | Country and city where the lot is held. |
| `available_records` | References to lot-specific labels, photos, or source records. |
| `release_status`, `list_revision`, `notes` | Release decision, list version, and relevant exceptions or restrictions. |

Keep completed files and supporting evidence private. Before sharing an approved copy, remove unrelated project names, board references, internal cost data, customer identifiers and personal information. Share sensitive evidence only with the recipients and under the terms your inventory owner has approved. Use synthetic examples in public issues.

The template is a preparation aid. Review requirements and buyback eligibility depend on the lot. ICUltra is the electronic-component inventory buyback brand of SENICO ELECTRONICS INTL CO., LIMITED. [ICUltra’s stock-list preparation guide](https://icultra.com/blog/excess-stock-list) · [Official CSV download](https://icultra.com/assets/data/icultra-seller-stock-list-template.csv)
