# mypackage

mypackage is a Python library that contains a module used to arrange an array of numbers in a descending order.

myModule defines a function top_n which takes two arguments i.e an array of numbers and n number of elements to be returned in a descending order

## Installation

use the package manager [pip] (https://github.com/rmawuli/mypackage) to install mypackage.

```bash
pip install mypackage
```

## Usage

```python
from myModule import top_n
# examples
top_n([8, 3, 2, 7, 4], 3) 
# Returns[8, 7, 4]
top_n([10, 1, 12, 9, 2], 2)
#Returns[12, 10]
top_n([1, 2, 3, 4, 5], 5) 
#Returns[5, 4, 3, 2, 1]
```
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

please make sure to update tests as appropriate. 

## Author
rogermawuli

## License
MIT