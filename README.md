# aqora-h2

# Installation

```bash
gti clone https://github.com/akaliutau/aqora-h2.git
cd ./aqora-h2/
conda create -n aqora-h2 python=3.13 -y
conda activate aqora-h2
python --version
```

```bash
pip install -r requirements.txt
```

# First steps and setup

Download a competition template

```bash
aqora login
aqora template h2-groundstate-energy
```

NOTE: aqora-cli uses venv for python deps and creates a separate git repository

run from working directory the jupiter notebook server:

```bash
aqora lab -j
```

Run all cells, then
```bash
aqora test
```
The last command will convert all code cells into execuable python file. Note: the variable `output` should contain the result of execution, it will be passed to platform

The command:
```bash
aqora submit
```
submits the code to the platform


