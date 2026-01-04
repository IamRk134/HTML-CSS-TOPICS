# 05 – Tables in HTML

This topic explains how to create and manage tables in HTML. Tables are used to organize data in rows and columns.

## File Included

- `05-tables.html`  
  Demonstrates basic and advanced table features.

## Table Components

- `<table>` – Defines a table.
- `<tr>` – Table row.
- `<th>` – Table header cell.
- `<td>` – Table data cell.
- `<caption>` – Table title or caption.
- `colspan` – Merge cells horizontally.
- `rowspan` – Merge cells vertically.
- `border` – Adds a border around the table (inline attribute for practice).

## Semantic Table Sections

HTML provides special elements that help **structure a table into clear parts**:

### `<thead>` — Table Header
Wraps the header row(s) of the table, usually containing column labels. This helps browsers and assistive technologies recognize the header separately from other rows.  
Use `<thead>` before `<tbody>` and `<tfoot>`. :contentReference[oaicite:0]{index=0}

### `<tbody>` — Table Body
Contains the main data rows of the table. Browsers automatically wrap rows inside a `<tbody>` even if it’s not explicitly written, but including it improves structure and styling control. :contentReference[oaicite:1]{index=1}

### `<tfoot>` — Table Footer
Used for summary or footer rows (like totals). The `<tfoot>` element must be placed after `<caption>`, `<colgroup>`, and `<thead>` but can appear before or after `<tbody>` in HTML markup; browsers correctly render it at the bottom. :contentReference[oaicite:2]{index=2}

## Types of Tables Covered

1. **Basic Table**
   - Simple rows and columns with headers.
   
2. **Table with Colspan and Rowspan**
   - Cells spanning multiple columns or rows.

3. **Table with Caption**
   - Adds a title above the table.

4. **Table with `<thead>`, `<tbody>`, `<tfoot>`**
   - Organizes table into header, body, and footer sections.

## How to Use

1. Open `05-tables.html` in a web browser.
2. Observe how rows, columns, and merged cells work.
3. Notice how grouped sections (`thead`, `tbody`, `tfoot`) make the structure clearer.
4. Modify data to practice creating your own tables.

## Purpose

This topic helps beginners understand:
- How to structure tabular data.
- How to merge cells using `colspan` and `rowspan`.
- How to add captions for better understanding.
- How to semantically organize table sections using `<thead>`, `<tbody>`, and `<tfoot>`.

## Next Steps

After learning tables, you can move on to:
- HTML Forms
- CSS table styling
- Responsive tables
