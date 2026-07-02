# Kilcornan Parish Pastoral Council

This repository contains four printable A4 pages for the Parish Pastoral Council nomination and election process in the Parish of St John the Baptist, Kilcornan.

Each page is available in two forms:

- an editable HTML page;
- a PNG image showing the finished page design.

## Pages

### Editable HTML pages

- [Page 1 — Election Process and Missionary Mandate](page-1.html)
- [Page 2 — Role of the PPC and Portfolios](page-2.html)
- [Page 3 — PPC Structure](page-3.html)
- [Page 4 — Nominations and Elections Timeline](page-4.html)

### Finished PNG page images

- [Page 1 PNG](page-1.png)
- [Page 2 PNG](page-2.png)
- [Page 3 PNG](page-3.png)
- [Page 4 PNG](page-4.png)

## Repository structure

```text
page-1.html
page-2.html
page-3.html
page-4.html

page-1.png
page-2.png
page-3.png
page-4.png

css/
  page-1.css
  page-2.css
  page-3.css
  page-4.css

icons/
images/
```

## What each part is for

### HTML files

The four root-level HTML files contain the editable text and semantic page structure. Each HTML file represents one finished A4 page.

### `css/`

The `css` folder contains one dedicated stylesheet for each page:

- `page-1.css` styles `page-1.html`;
- `page-2.css` styles `page-2.html`;
- `page-3.css` styles `page-3.html`;
- `page-4.css` styles `page-4.html`.

The stylesheets control page layout, typography, colours, borders, tables, portfolio cards, arrows and print settings.

### `icons/`

The `icons` folder contains the smaller visual assets used throughout the pages, including:

- diocesan crests and the papal coat of arms;
- missionary-mandate icons used on Page 1;
- PPC portfolio icons used on Pages 2 and 3;
- timeline, eligibility and mission icons used on Page 4.

### `images/`

The `images` folder contains the larger photographic or illustrative assets, including:

- the missionary scene with Jesus and the people;
- the Holy Spirit, cross and dove image;
- the image of Pope Francis;
- the parish church image.

### PNG page images

The four root-level PNG files are complete visual versions of the four pages. They are useful for quick viewing, comparison, sharing and reference when editing the HTML and CSS versions.

## Editing

All headings, quotations, portfolio names, lists and tables are editable in the corresponding HTML file. Visual layout changes should be made in that page's stylesheet inside the `css` folder.

Keep the existing relative paths intact so that the HTML pages continue to find their CSS, icons and images.

## Printing

Open the required HTML page in Chrome or Edge and use:

- Paper size: A4;
- Orientation: Portrait;
- Margins: None;
- Scale: 100%;
- Background graphics: Enabled.
