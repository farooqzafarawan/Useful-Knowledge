# Python Basic Task Libraries
## Python File Split Library
A python module that can split files of any size into multiple chunks, with optimum use of memory and without compromising on performance. 
The module determines the splits based on the new line character in the file, therefore not writing incomplete lines to the file splits.

### Usage
The module is available as a part of PyPI and can be easily installed using pip
`pip install filesplit`

Create an instance of the FileSplit object by passing file path and split size as arguments.
```python
from fsplit.filesplit import FileSplit
fs = FileSplit(file='path/to/file', splitsize=500000000, output_dir='/path/to/output directory/')
fs.split
```

# Python Urdu Libraries
Some noteable librariesL
- urduhack
- 

## UrduHack
Urduhack is a NLP library for urdu language. It comes with a lot of battery included features to help you process Urdu data in the easiest way possible.
- Normalization
- Tokenization
- Data pre-processing




