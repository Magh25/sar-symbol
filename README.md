# SAR Symbol Font

This repository provides a font for the Saudi Riyal (SAR) symbol (). You can easily integrate this symbol into your web projects or applications using CSS.

## How to use

1. **Download the font files:**
   - Clone this repository or download the font files directly.

2. **Include the CSS:**
   - Add the following CSS code to your project's stylesheet:

```css
@font-face {
  font-family: 'sar-symbol';
  src: url('fonts/sar-symbol.eot?ebwrxj');
  src: url('fonts/sar-symbol.eot?ebwrxj#iefix') format('embedded-opentype'),
       url('fonts/sar-symbol.ttf?ebwrxj') format('truetype'),
       url('fonts/sar-symbol.woff?ebwrxj') format('woff'),
       url('fonts/sar-symbol.svg?ebwrxj#sar-symbol') format('svg');
  font-weight: normal;
  font-style: normal;
  font-display: block;
}

.sar-currency {
  font-family: 'sar-symbol', sans-serif;
  font-size: 16px; /* Adjust as needed */
  font-weight: bold; /* Adjust as needed */
  color: #009688; /* Adjust as needed */
  margin-left: 5px; /* Adjust as needed */
}