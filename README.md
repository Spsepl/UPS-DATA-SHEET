# TRIJOSHH UPS Technical Datasheet Generator

## Overview
This web app generates technical datasheets for TRIJOSHH UPS products in both PDF and Excel formats. Users can input customer and company details, select UPS models, specify backup time and battery type, and add custom notes. The datasheet includes warranty information and is suitable for sharing and documentation.

## Features
- Bootstrap-powered responsive UI
- Form collects all required datasheet details
- PDF generation with jsPDF, including company logo and formatted sections
- Excel generation with xlsx.js for tabular data export
- Warranty and signature section on PDF
- Footer with contact information

## Usage

1. Open `index.html` in your web browser.
2. Fill out the form with customer, company, product, backup time, battery type, and any notes.
3. Click **Generate PDF & Excel**.
4. Downloaded files: `[CompanyName]_Datasheet.pdf` and `[CompanyName]_Datasheet.xlsx`.

## Requirements

- No installation needed; works directly in the browser.
- Requires internet access for Bootstrap, jsPDF, and xlsx libraries (CDN).

## File Structure

- `index.html` – Main app file (includes all HTML, JS, and CDN links)
- `Trijoshh logo.png` – Logo referenced by the app (place in same directory)

## Dependencies

- [Bootstrap 4.6](https://getbootstrap.com/)
- [jsPDF 2.5.1](https://github.com/parallax/jsPDF)
- [xlsx.js 0.18.5](https://github.com/SheetJS/sheetjs)

## Customization

- To update logo, replace `Trijoshh logo.png` with your own image.
- To add or modify UPS models, edit the `<select>` options in the HTML.

## License

MIT License

## Contact

For support or questions, contact:

- Email: sales@shreeprarambha.com
- Phone: 09594347775 / 09769979724

---

**SHREE PRARAMBHA SMARTENERGIES PVT LTD**
