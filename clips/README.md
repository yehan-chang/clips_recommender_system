Tested on Ubuntu 16.04 LTS
Uses Python 2 as Python 3 is not supported by the CLIPS integration library

### To install
```
$ sudo apt-get install python-clips
$ pip install -r requirements.txt
```

### To run
```
$ python app.py
```

### Local URLs
To test interface (very few questions, hardcoded results): http://127.0.0.1:5000/bto_test/units_booked
To test logic and data with random booking state (full program flow, may not have result): http://127.0.0.1:5000/bto/units_booked
To test with all units available: http://127.0.0.1:5000/bto/units

### To update new CLIPS source
1. Put it in the same folder and comment out the CLIPS section at the top with the interface functions
2. Visit the link http://127.0.0.1:5000/<new clips filename without .clp extension>/units_booked
