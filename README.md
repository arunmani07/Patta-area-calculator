# 🌾 Patta Land Converter

A simple, responsive web application to convert Tamil Nadu Patta/Chitta land extent values from **Hectare + Are** into commonly used land measurements.

## Features

- Enter Patta details
- Add multiple owners
- Add multiple survey/sub-division entries
- Select land type:
  - Punjai
  - Nanjai
  - Other
- Enter land extent in Hectare and Are
- Automatic conversion to:
  - Acre
  - Cent
  - Ground
  - Sq. Ft.
  - Sq. M
- Automatic total calculation across all survey entries
- English / Tamil language toggle
- Copy conversion details
- Share details through WhatsApp
- Print a clean Patta-style conversion statement
- Responsive design for desktop and mobile

## Conversion Logic

The application converts the entered Hectare and Are values into square metres first.

```text
Square Metres = (Hectare × 10,000) + (Are × 100)

Acre   = Square Metres ÷ 4046.8564224
Cent   = Square Metres ÷ 40.468564224
Ground = Square Metres ÷ 222.967104
Sq. Ft. = Square Metres × 10.7639104167
