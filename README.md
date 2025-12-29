# PAX Calculator Data

Official PAX (Performance Adjustment Index) and PSI (ProSolo Index) data files for autocross/Solo competition.

## Files

- **pax.json** - PAX factors for standard SCCA Solo competition
- **psi.json** - PSI factors for SCCA ProSolo competition

## Format

Both files contain an array of class data in the following format:
```json
[
  {
    "class": "SS",
    "factor": 0.818
  },
  ...
]
```

## Usage

These files are used by the PAX Calculator iOS app to provide up-to-date class factors without requiring app updates.

**Raw file URLs:**
- PAX: `[https://github.com/Davidss2/Pax-Calculate-Data/blob/main/pax.json](https://github.com/Davidss2/Pax-Calculate-Data/blob/main/pax.json)`
- PSI: `https://github.com/Davidss2/Pax-Calculate-Data/blob/main/psi.json`

## Data Source

PAX and PSI values are official factors published by the SCCA (Sports Car Club of America) for competitive autocross events.

## Updates

These files are updated as new official PAX/PSI values are released by SCCA, typically once or twice per year.

## License

MIT License - This data represents official SCCA competition factors and is made available for use by the autocross community.
