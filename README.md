# poetryai

A brief description of project-

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [Poetry Commands](#poetry-commands)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you set up and run your project on your local machine for development and testing purposes.

### Prerequisites

- Python 3.12 (or a compatible version)
- Poetry (Dependency Management)

### Installation

To get started with the project, clone the repository and install dependencies using Poetry:

```bash
# Clone the repository
git clone https://github.com/ajaykumaretw/poetryai.git

# Navigate into the project directory
cd poetryai

# Install Poetry if not already installed
python -m pip install poetry

# Install project dependencies
poetry install

Poetry Commands-
  Adding Dependencies-
   ------------------------------------------------------------------------------------
   - Add a new package (e.g., pandas)
     poetry add pandas

   - Add a specific version of a package (e.g., requests version 2.12.1)
     poetry add requests@2.12.1

   - Add a package with version compatibility (e.g., requests compatible with 2.12.1)
      poetry add requests^2.12.1
   -------------------------------------------------------------------------------------
   Updating Dependencies-
   -------------------------------------------------------------------------------------
   - Update a specific package to the latest compatible version (e.g., pytest)
      poetry update pytest

   - Upgrade a package to the latest available version
      poetry add pytest@latest
   ---------------------------------------------------------------------------------------
    
    Removing Dependencies-

    ---------------------------------------------------------------------------------------
    - Remove a package (e.g., pandas)
      poetry remove pandas

    - Remove a specific package (e.g., requests)
      poetry remove requests
    -----------------------------------------------------------------------------------------

    Listing Installed Packages-

    -----------------------------------------------------------------------------------------

    -Show all installed packages with their versions
     
     poetry show
    
    ------------------------------------------------------------------------------------------

    - Setting Python Version

    -------------------------------------------------------------------------------------------
     -Set the environment to use Python 3.12
      poetry env use python3.12
    --------------------------------------------------------------------------------------------

    - Additional Help

    ---------------------------------------------------------------------------------------------
      Show all available Poetry commands
      poetry --help
    ---------------------------------------------------------------------------------------------









