# Private-Transport-Sector-Optimization-Model

This repository contains the code for an optimization-based approach to addressing the decarbonization problem within the transportation sector, one of the primary sources of CO$_2$ emissions. The approach considers detailed models, encompassing various transportation modes and the compositions of their respective vehicle fleets.

## Overview

The code in this repository numerically solves the optimization problem using real data, subject to monetary and CO$_2$ emissions constraints, as well as constraints ensuring the feasibility of the transition to more sustainable transportation methods. The control actions obtained from this optimization provide valuable insights into the transition process.

## Features

- Detailed modeling of different transportation modes and vehicle fleet compositions.
- Optimization under multiple constraints: monetary, CO$_2$ emissions, and feasibility.
- Analysis of the dependency of resolution time on budget values.
- Numerical assessment using real-world data.

## Keywords

- Decarbonization
- Non-convex Quadratic Programming
- Resource allocation

## Installation

To run the code, you need to have Python installed along with the necessary libraries. You can install the required libraries using:

```bash
pip install -r requirements.txt
```

## Usage

Jupyter-Notebook.

## Data

The real data used for the numerical assessments should be placed in the `data` directory. Ensure that the data files are correctly formatted and named as expected by the code.

## Results

The results of the optimization, including the control actions and analysis of resolution times, will be saved in the `results` directory. Detailed logs and intermediate steps are also stored for review and further analysis.

## Contributing

Contributions to this project are welcome. Feel free to open issues or submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact [your name] at [your email address].

---

Thank you for using this code for your research on the decarbonization of the transportation sector. We hope you find it useful and insightful!
