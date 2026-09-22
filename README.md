# Brazilian footwear size data

Machine-readable, source-linked size reference data for Brazilian footwear brands, maintained by [PRAYA](https://www.praya.co.il/) for shoppers and researchers. The canonical dataset page, including direct CSV and JSON downloads, is available at [PRAYA Data](https://www.praya.co.il/data/midot-naalaim-brazilaiot).

The first release contains the adult Melissa Europe size chart as checked on 2026-09-09. It maps foot length in centimetres to the EU and Brazilian (BR) labels published by the manufacturer.

## Files

- [`data/melissa-adult-size-chart.csv`](data/melissa-adult-size-chart.csv) — tabular data
- [`data/melissa-adult-size-chart.json`](data/melissa-adult-size-chart.json) — structured data with provenance
- [`datapackage.json`](datapackage.json) — Frictionless Data descriptor

## Important limitations

- This is a transcription of a specific manufacturer chart, not an independent measurement of shoe interiors.
- It is not a fit guarantee. Width, upper construction, heel hold and model-specific instructions still matter.
- Do not reuse this chart for Havaianas, Ipanema or another brand.
- If a product page publishes different sizing instructions, follow the product page.
- PRAYA is an independent Israeli retailer and is not the official importer, representative or franchisee of Melissa or Grendene S.A.

## Sources and methodology

Primary source: [Melissa Europe size guide](https://eu.shopmelissa.com/en-mt/pages/size-guide), Adult table. Checked 2026-09-09.

Values were transcribed without interpolating unpublished half sizes. Paired sizes such as `35–36` remain paired. The corresponding Hebrew explanation, measuring method and calculator are available in PRAYA's [Melissa size guide](https://www.praya.co.il/madrich/midot-brazilaiot) and [PRAYA FIT](https://www.praya.co.il/madad).

## Suggested citation

> PRAYA Editorial. “Brazilian Footwear Size Data: Melissa Adult Size Chart.” Version 2026.09.22. Source checked 9 September 2026. https://github.com/asafichaki/brazilian-footwear-size-data

## בעברית

המאגר מרכז נתוני מידות של מותגי הנעלה ברזילאיים בפורמט פתוח וקריא למכונה. הגרסה הראשונה כוללת את טבלת המבוגרות והמבוגרים של Melissa Europe, עם קישור למקור, מועד בדיקה ומגבלות שימוש. [עמוד המאגר הרשמי והורדות CSV/JSON](https://www.praya.co.il/data/midot-naalaim-brazilaiot) זמינים באתר PRAYA, לצד [הסבר המידות המלא בעברית](https://www.praya.co.il/madrich/midot-brazilaiot).

## License

The original manufacturer remains the source of the underlying published size facts. PRAYA's transcription, metadata and documentation are released under [CC BY 4.0](LICENSE). Attribution does not imply endorsement by Melissa or Grendene S.A.
