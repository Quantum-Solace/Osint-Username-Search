# Osint-Username-Search
This tool will crawl specific websites for a 200 status code in the url and try to verify if the desired username is associated on that website.

## Installation
Linux - 
sudo apt update && sudo apt full-upgrade -y 
git clone https://github.com/Quantum-Solace/Osint-Username-Search.git
cd Osint-Username-Search
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt

Windows - 
git clone https://github.com/Quantum-Solace/Osint-Username-Search.git
cd Osint-Username-Search
python.exe -m virtualenv .venv
.venv/Scripts/activate.ps1
pip install -r requirements.txt

## Usage
Linux - 
python3 main.py

Windows - 
.\main.py
