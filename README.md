# Michael Scott is Not a Juror  
**Limits of AI in Simulating Human Judgment**

## Authors  
- **Sean Harrington** – Director of Technology and Innovation, University of Oklahoma College of Law  
- **Hayley Stillwell** – Associate Professor of Law, University of Oklahoma College of Law  

## Funding  
This research was supported by a grant from the Research Council of the University of Oklahoma Norman Campus.

## About  
This repository contains the data, code, and figures that underpin the paper’s analysis of how large language models compare with 1,200 human mock jurors across multiple criminal-law scenarios.

## Directory Structure  
```

data/       anonymised human responses and model outputs
scripts/    notebooks and utilities to reproduce results
paper/      camera-ready manuscript and figures
models/     fine-tuned Mistral-7B checkpoint (optional download)

````

## Quick Start  
```bash
# clone and set up
git clone https://github.com/your-org/juror-sim-paper.git
cd juror-sim-paper
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
# run analysis
jupyter lab               # open scripts/01_analysis.ipynb and Run All
````

## License

Code: MIT
Data: CC BY-NC 4.0 (non-commercial use, attribution required)

*Pull requests and issues are welcome.*

```
