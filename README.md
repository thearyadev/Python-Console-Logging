# Python Console Logging

An extension of the Python Rich: Console to allow for easier and more consistent logging. 

## Installation (Compatible with Python 3.6.1 and above)

1. Install dependencies from the requirements.txt file from the `./utils` directory.
2. Place `./utils` in the root directory of your project (or run `./example.py`

```bash
pip install -r requirements.txt
```

## Usage
From: `./example.py`.
```python
from utils import Console

if __name__ == '__main__':
    console = Console()
    console.info_log("Hello World")
    console.server_log("Hello World")
    console.error_log("Hello World")
```
Output:
![example output](https://i.imgur.com/rSJdSoy.png)

## Extras

Please read the documentation for console markup from the [Rich Documentation](https://rich.readthedocs.io/en/stable/introduction.html) to make customized console output. 


## License
[MIT](https://choosealicense.com/licenses/mit/)
