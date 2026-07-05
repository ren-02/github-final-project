# Simple Interest Calculator Project

A repository created as part of the IBM Data Science / Software Engineering Hands-on Lab on Git and GitHub. This project provides a simple Bash script to calculate simple interest based on user inputs for principal amount, annual rate of interest, and time period in years.

## Overview

Simple interest is calculated with the following standard mathematical formula:
$$I = \frac{P \times R \times T}{100}$$

Where:
* **P** = Principal amount (initial investment or loan amount)
* **R** = Annual rate of interest (percentage)
* **T** = Time period in years
* **I** = Simple Interest earned or paid

## Files in this Repository

* **`LICENSE`**: Apache 2.0 open-source license governing the redistribution and use of this software.
* **`README.md`**: Comprehensive project overview and documentation (this file).
* **`CODE_OF_CONDUCT.md`**: Community standards and behavioral guidelines for all contributors and maintainers.
* **`CONTRIBUTING.md`**: Guidelines and instructions for contributing code, reporting bugs, and submitting pull requests.
* **`simple-interest.sh`**: A Bash shell script that calculates simple interest interactively.

## Prerequisites

To execute the shell script, you must have a Unix-like shell environment installed:
* **Linux / macOS**: Bash is pre-installed on most distributions.
* **Windows**: You can use Git Bash, WSL (Windows Subsystem for Linux), or Cygwin.

## Installation and Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<your-username>/<your-repository-name>.git
   cd <your-repository-name>
   ```

2. **Make the script executable (if not already):**
   ```bash
   chmod +x simple-interest.sh
   ```

3. **Run the calculator:**
   ```bash
   ./simple-interest.sh
   ```

4. **Example Interaction:**
   ```text
   Enter the principal:
   1000
   Enter rate of interest per year:
   5
   Enter time period in years:
   3
   The simple interest is: 
   150
   ```

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE](file:///c:/Users/vince/OneDrive/Documents/githubProject/LICENSE) file for details.
