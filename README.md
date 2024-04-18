# Damn Vulnerable Python Flask Web Application

Make [Flask Tutorial Project](https://github.com/pallets/flask/blob/main/examples/tutorial) to be security vulnerable

## Installation

Run bellow commands:
```bash
$ git clone https://github.com/khanhnt2/DVPFWA
$ python3 -m venv DVPFWA
$ cd DVPFWA
$ source bin/active
$ pip3 install -r requirements.txt
```

## Run application

If it's your first time or you want to clear the database, run:
```bash
$ python3 main.py --init
```

If you want to keep the old database, run:
```bash
$ python3 main.py
```

Then open http://127.0.0.1:5000 in a browser.