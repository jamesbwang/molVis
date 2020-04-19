## MolVis

Under development: an application that can visualize One (1) molecule.

Needs the [conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)
### Quick Start

1. Clone the repo
  ```
  $ git clone https://github.com/realpython/flask-boilerplate.git
  $ cd molVis
  ```

2. Initialize and activate the conda environment:
  ```
  $ conda env create -f environment.yml
  $ conda activate ipath
  ```

4. Run the development server:
  ```
  $ python app.py
  ```

6. Navigate to [http://localhost:5000](http://localhost:5000)

### How it works
Pretty simple. Navigate to [http://localhost:5000/single/CO2](http://localhost:5000/single/CO2). You should see a CO2 molecule.
Similarly, navigating to [http://localhost:5000/single/"molecule"](http://localhost:5000/single/"molecule") should give an image of the molecule.
  
The list of supported molecules can be found in /static/metabolites/kegg_compounds.json


