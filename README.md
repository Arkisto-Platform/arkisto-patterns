# arkisto-patterns

Arkisto Design Patterns

---

## Seafood Safety Group Arkisto Example

#### People
The Seafood Safety Group is led by [Shauna Murray](mailto:Shauna.Murray@uts.edu.au), and comprised of:
* [Penny Ajani](mailto:penelope.ajani@uts.edu.au): Does mathematical modelling from the data and has been primary contact for getting example data and discussing data pipeline
* [Hazel Farrell](mailto:hazel.farrell@dpi.nsw.gov.au): Partner from the NSW Department of Primary Industries who  helps clean and distribute the data
    

#### Data

The Seafood Safety Group has sensors (provided by *The Yield*) located in various estuarys around NSW, collecting data about the salinity, temperature, pressure and water depth at regular intervals.
This data is uploaded from the sensors to an Azure database and then downloaded in monthly csv files.
It is also currently avaialble for consumers via a live website.

For testing purposes, a simple script has been written which generates sample data for each estuary and month from 2010-2020.
It's contained in the generated data directory and when run with `python3 test_folder_generation.py` creates sub-folders in the current directory containing both simulated raw data and the associated ro-crate-metadata.json file.

After that's created, you can use the ro-crate-deposit script from [OCFL Demos](https://code.research.uts.edu.au/eresearch/ocfl-demos):
```bash
node ro-crate-deposit.js --repo=fake_ocfl --name seafood *
```
in the same directory to create an ocfl repo called 'fake_ocfl' which contains all of those RO-Crates and data.

---

Directories:
* RO-Crate Data: Stores explanations and examples of RO-Crates as well as the data contained in them.
    - examples: Stores example RO-Crates 
    - generated data: Stores code which generates RO-Crates (and the data contained in them) for testing.
* Configuration: Stores configuration files for ONI