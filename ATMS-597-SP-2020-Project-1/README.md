# Temperature Converter
## ATMS-597 Project-1

Tired of searching the internet for temperature conversion calculations? Looking
to make converting lists, arrays, integers, or floats to a different temperature
unit? Look no further!

This program makes it easy for the user to input temperature values and the native
units, then convert those input values to the desired new unit.

## Dependencies
Other required packages
- NumPy


## Suppported Units
The units supported are:
- Celsius
    - degC, c, or C
- Fahrenheit
    - degF, f, or F
- Kelvin
    - kelvin, k, or K
 
 
 ## Example Syntax
 The syntax would like look this
```python
from modules.tempconvert import TempConvert

# Input the temperature and its associated units
tmpf = TempConvert(45, 'degF')

# Convert to degrees celsius
tmpc = tmpf.to('degC')
```

[Full Example Notebook](https://colab.research.google.com/github/szymbor2/ATMS-597-SP-2020/blob/master/ATMS-597-SP-2020-Project-1/examples/examples.ipynb)

## Primary Developers:
- Divyansh Chug
- Sarah Szymborski
- Max Grover