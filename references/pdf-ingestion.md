# PDF Ingestion

Use this reference when the selected financial-report source is a PDF.

## Create a structured analysis representation

Convert the PDF into a structured Markdown or equivalent text representation with an available document-conversion tool.

Use the converted representation as the primary layer for:

- document navigation and search;
- headings and section structure;
- management commentary;
- guidance text;
- footnotes;
- narrative disclosures;
- simple tables that preserve their structure reliably.

Do not require a specific conversion tool. Use a suitable tool available in the execution environment.

## Preserve the original PDF

Keep the original PDF unchanged and available throughout the workflow.

The converted Markdown is an analysis representation, not the authoritative financial record. When the converted content conflicts with the original document, use the original PDF to resolve the discrepancy.

## Verify financially material tables

Do not rely on Markdown conversion alone for dense or layout-sensitive financial tables.

Verify material values against the original PDF or a layout-preserving extraction when a table contains features such as:

- multi-level or merged headers;
- multiple reporting periods across columns;
- segment or geographic breakdowns;
- GAAP and Non-GAAP reconciliations;
- parenthetical negative values;
- indentation that conveys accounting hierarchy;
- complex footnotes or superscripts;
- wide tables that may be reordered during conversion.

Values used in headline KPIs, the income-statement Sankey, guidance, profitability comparisons, or accounting reconciliations should receive source-level verification.

## Record source location

For each material reported value, retain enough source-location information to return to the original disclosure efficiently.

Use the most useful locator available, such as:

- PDF page number;
- statement or table name;
- section heading;
- footnote identifier;
- Markdown heading when it maps reliably to the PDF.

Keep reported values distinct from values derived by calculation.

## Handle extraction discrepancies

If Markdown conversion, layout-preserving extraction, and the visual PDF disagree:

1. inspect the original PDF;
2. confirm the relevant row, column, unit, period, and sign;
3. use the value supported by the authoritative source;
4. note any ambiguity, derivation, or rounding difference that materially affects the dashboard.

Do not silently resolve uncertain financial data by guessing.
