# data-preparation-in-qa-fomat
The script takes an xlsx file and converts each cell in the format of : &lt;s>[INST] question [/INST] answer&lt;/s>

## Prepare environment
- python3 -m venv venv
- cd venv/bin
- source activate
- cd ../..
- pip install -r requirements.txt

## Run code
- python prepare-excel.py 

## Close 
- cd venv/bin
- source deactivate