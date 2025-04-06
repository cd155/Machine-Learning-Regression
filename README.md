# Nix environment instruction
nix-shell shell.nix

# Python environment instruction

## go the direcotry
cd Projects/testpython/

## Optional: create python virtual environment
## python3 -m venv env

## activate virtual environment
source env/bin/activate

## Optional: install all required packages
## pip install -r requirements.txt

## launch jupyter notebook
jupyter notebook

## exit virtual environment
deactivate 