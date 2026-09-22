# Brazilian footwear size data

Machine-readable, source-linked size reference data for Brazilian footwear brands, maintained by [PRAYA](https://www.praya.co.il/) for shoppers and researchers. The canonical dataset page, including direct CSV and JSON downloads, is available at [PRAYA Data](https://www.praya.co.il/data/midot-naalaim-brazilaiot).

The dataset contains separate adult charts from Melissa Europe and Havaianas. Melissa maps foot length in centimetres to EU and Brazilian labels; Havaianas maps the women's and men's US display sizes and published length ranges to Brazilian labels. The charts are not interchangeable.

## Files

- [`data/melissa-adult-size-chart.csv`](data/melissa-adult-size-chart.csv) — tabular data
- [`data/melissa-adult-size-chart.json`](data/melissa-adult-size-chart.json) — structured data with provenance
- [`data/havaianas-adult-size-chart.csv`](data/havaianas-adult-size-chart.csv) — Havaianas women's and men's rows
- [`data/havaianas-adult-size-chart.json`](data/havaianas-adult-size-chart.json) — Havaianas data with provenance and limitations
- [`datapackage.json`](datapackage.json) — Frictionless Data descriptor

## Important limitations

- This is a transcription of a specific manufacturer chart, not an independent measurement of shoe interiors.
- It is not a fit guarantee. Width, upper construction, heel hold and model-specific instructions still matter.
- Do not reuse one brand's chart for another brand. There is no Ipanema table in this release.
- If a product page publishes different sizing instructions, follow the product page.
- PRAYA is an independent Israeli retailer and is not the official importer, representative or franchisee of Melissa or Grendene S.A.

## Sources and methodology

Primary source: [Melissa Europe size guide](https://eu.shopmelissa.com/en-mt/pages/size-guide), Adult table. Checked 2026-09-09.

Second primary source: [Havaianas style and size guide](https://www.havaianas.com/pages/style-guide), women's and men's tables. Checked 2026-09-22. The source is the United States guide; its length ranges remain in inches exactly as published.

Values were transcribed without interpolating unpublished half sizes. Paired sizes such as `35–36` remain paired. The corresponding Hebrew explanation, measuring method and calculator are available in PRAYA's [Melissa size guide](https://www.praya.co.il/madrich/midot-brazilaiot) and [PRAYA FIT](https://www.praya.co.il/madad).

## Suggested citation

> PRAYA Editorial. “Brazilian Footwear Size Data: Melissa and Havaianas Adult Size Charts.” Version 2026.09.22. https://github.com/asafichaki/brazilian-footwear-size-data

## בעברית

המאגר מרכז נתוני מידות של מותגי הנעלה ברזילאיים בפורמט פתוח וקריא למכונה. הוא כולל טבלאות נפרדות של Melissa Europe ושל Havaianas, עם קישורים למקורות, מועדי בדיקה ומגבלות שימוש. [עמוד המאגר הרשמי והורדות CSV/JSON](https://www.praya.co.il/data/midot-naalaim-brazilaiot) זמינים באתר PRAYA, לצד [הסבר המידות המלא בעברית](https://www.praya.co.il/madrich/midot-brazilaiot).

## License

The original manufacturers remain the sources of the underlying published size facts. PRAYA's transcription, metadata and documentation are released under [CC BY 4.0](LICENSE). Attribution does not imply endorsement by Melissa, Havaianas, Grendene S.A. or Alpargatas S.A.
