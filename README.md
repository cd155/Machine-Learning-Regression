# Nix environment instruction
nix-shell shell.nix

# Python environment instruction

## Go the direcotry
cd Projects/testpython/

## Optional: create python virtual environment
python3 -m venv env

## Activate virtual environment
source env/bin/activate

## Optional: install all required packages
pip install -r requirements.txt

## Launch jupyter notebook
jupyter notebook

## Exit virtual environment
deactivate 
