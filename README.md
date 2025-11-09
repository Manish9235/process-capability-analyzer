# Process Capability (Cp/Cpk) Analyzer

An automated web-based tool for conducting process capability studies in production environments. This tool streamlines data entry, calculation, and reporting for critical part parameters.

## Features

- **Multi-Part Support**: Handle up to 5 different parts with separate tabs
- **50 Sample Data Entry**: Enter measurements for 50 samples per check item
- **Comprehensive Metrics**: Calculate AVE, MAX, MIN, USL-LSL, sigma, Cp, Cpk, Ppk, PpU, PpL
- **Color-Coded Results**: 
  - Green: > 1.33 (Excellent)
  - Yellow: 1.00-1.33 (Acceptable)
  - Red: < 1.00 (Needs Improvement)
- **Control Charts**: X-bar & R charts for statistical process control validation
- **CSV Export**: Download comprehensive reports with all check items, characteristics, metrics, and sample data
- **Data Generator**: Generate test data for validation and testing

## Parts Supported

1. **FRS (M14)** - Part Number: 33121 - 0K061
2. **RBF (M15)** - Part Number: 33121 - 0K011
3. **ROR (M16)** - Part Number: 33121 - 0K010
4. **Fork-1 (M04)** - Part Number: 33121 - 0K111
5. **Fork-2 (M17)** - Part Number: 33121 - 0K070

## Usage

1. Open `index.html` in a web browser
2. Select a part from the top navigation tabs
3. Choose a check item/parameter from the sub-tabs
4. Enter 50 sample measurements or use "Generate Data" for testing
5. Click "Calculate" to view results and control charts
6. Download CSV reports using "Download All Parameters CSV" or individual parameter downloads

## CSV Export Format

The comprehensive CSV export includes:
- Check Item names (columns)
- Characteristic values
- Measuring Instruments
- All calculated metrics (USL, LSL, AVE, MAX, MIN, USL-LSL, σ, Cp, Cpk, PpU, PpL)
- All 50 sample values for each check item

## Technologies

- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- Chart.js (for control charts)

## Browser Compatibility

Works on all modern browsers (Chrome, Firefox, Edge, Safari)

## License

Proprietary - Internal Use Only

