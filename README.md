# Python Coordinate Conversion

This Python project converts northing and easting coordinates to latitudes and longitudes using the `pyproj`, `pandas`, `geopandas`, and `shapely` libraries. The input data is read from a CSV file, and the results are saved to another CSV file.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
  - [Usage](#usage)
- [License](#license)
- [Contact](#contact)

## Features

- Northing to Latitude
- Easting to Longitude
- Output is saved as CSV file


## Getting Started
### Dependencies

Make sure to install the required dependencies before running the script:

```bash
pip install pandas
pip install geopandas
pip install pyproj
```
### Usage
1. **Ensure you have a CSV file (data.csv) with columns 'Easting' and 'Northing' containing the coordinates to be converted.**

2. **Update the script if necessary, specifying the correct UTM zone code in the proj_utm initialization.**
3. **Run your code**
4. **The converted coordinates will be saved to a new CSV file (converted_coordinates.csv).**

## License
This project is licensed under the [MIT License](#LICENSE).
## Contact
If you have any questions, or feedback, or just want to get in touch, feel free to reach out via email:
- Email: aasiafjwu@gmail.com
