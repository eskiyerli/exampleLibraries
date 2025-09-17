# Example Libraries for Analog and SG13G2_PR

This repository contains example libraries for analog and SG13G2_PR components, organized for use in design software workflows. The libraries are structured to provide symbols, parameter cells, and other resources for circuit design and simulation.

## Directory Structure

- `analogLib/`
  - `reveda.lib`: Main library file for basic schematic symbols to be used with Xyce Netlister.
  - Subfolders for each component (e.g., `cap/`, `nmos/`, `res/`), each containing:
    - `symbol.json`: Symbol definition for the component.
    - `pcell.json`: Parameter cell definition (where applicable).
    - `veriloga.json`: Verilog-A model (where applicable).
    - Other files as needed for simulation or plugin support.

- `sg13g2_pr/`
  - `reveda.lib`: Main library file for IHP SG13G2_PR components to be used with Xyce Netlister. 
  - Subfolders for each component (e.g., `cap_cmim/`, `npn13G2/`, `sg13_lv_nmos/`), each containing:
    - `symbol.json`: Symbol definition for the component.
    - `pcell.json`: Parameter cell definition (where applicable).

## Usage

These libraries are intended to be imported into Revolution EDA design software for analog circuit design. Each component folder contains the necessary files for symbol representation and simulation.

## Contributing

Feel free to submit issues or pull requests for improvements, new components, or bug fixes.

## License
This project is licensed under the GNU Public License v2.

## Contact

For questions or support, please contact the repository maintainer.
