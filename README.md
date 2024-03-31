# NGC-6218 Age Determination

This Jupyter Notebook, created by Collin Collins on 30 March 2024, demonstrates the process of determining the age of the star cluster NGC-6218 using a color-magnitude diagram (CMD).

## Overview

The notebook follows these main steps:

1. Convert .tbl files to .csv format
2. Read and filter the .csv files to extract relevant data
3. Process the 'Source-Sky' and coordinate columns
4. Convert RA and DEC coordinates to sexagesimal format
5. Normalize counts in B and V bands
6. Calculate the zero magnitude and apparent magnitudes for all stars
7. Compute the B-V color index for all stars
8. Create a CMD diagram
9. Estimate the age of the star cluster using the turnoff point

## Dependencies

- Python 3.x
- pandas
- numpy
- astropy
- matplotlib
- scienceplots

## Usage

1. Clone the repository and navigate to the project directory.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Place the input .tbl files in the `data` directory.
4. Run the Jupyter Notebook `ngc-6218-age-determination.ipynb`.

## Results

The notebook calculates the following results:

- Luminosity relative to the Sun for the turnoff point stars
- Estimated mass of the turnoff point stars
- Estimated age of the star cluster
- Distance modulus

The final result is an estimated age of the NGC-6218 star cluster of approximately 10-12 billion years.

## Visualizations

The notebook generates two main visualizations:

1. A color-magnitude diagram (CMD) of NGC-6218, plotting the V-band magnitude against the B-V color index.
2. A comparison of the processed B-band and V-band images of NGC-6218.

## Data

The input data files (.tbl) should be placed in the `data` directory. The notebook will convert these files to .csv format for further processing.

## References

- Simbad Astronomical Database: http://simbad.u-strasbg.fr/simbad/
- NASA/IPAC Extragalactic Database (NED): https://ned.ipac.caltech.edu/

## License

This project is open-source and available under the [MIT License](LICENSE).
