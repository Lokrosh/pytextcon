# pytextcon

pytextcon is a lightweight, simple package designed to make basic changes to the text color, text emphasis, and background color of print statements to the console simple.
## Getting Started
Download pytextcon:
```python
pip install pytextcon
```
## Usage
Use an f-string to include text formatting to print statements. Formatting will continue 
until cleared. Use `RESET` to end all formatting. Use `DEFAULT` to clear text color only. 
### Example:
```Python
import pytextcon as text

print(f"{text.BOLD}{text.BLUE}Some text that will be bold and blue.{text.DEFAULT}\
Some other text that will be bold but not blue")

print(f"{text.UNDERLINE}{text.BLUE}Some text that will be bold, underlined, and blue.\
{text.RESET}Some other text that will not be bold, underlined or blue")
```
![img.png](img.png)


## Formatting Options
### Basic Colors:
BLACK,
RED,
GREEN,
YELLOW,
BLUE,
MAGENTA,
CYAN,
WHITE

### Bright Colors:
BLACK_BR,
RED_BR,
GREEN_BR,
YELLOW_BR,
BLUE_BR,
MAGENTA_BR,
CYAN_BR,
WHITE_BR

### Basic Color Backgrounds:
BLACK_BG,
RED_BG,
GREEN_BG,
YELLOW_BG,
BLUE_BG,
MAGENTA_BG,
CYAN_BG,
WHITE_BG

### Bright Color Backgrounds:
BLACK_BRBG,
RED_BRBG,
GREEN_BRBG,
YELLOW_BRBG,
BLUE_BRBG,
MAGENTA_BRBG,
CYAN_BRBG,
WHITE_BRBG

### Emphasis:
BOLD,
DIM,
ITALIC,
UNDERLINE,
UNDERLINE2,
BLINK,
STRIKE

### Clear:
DEFAULT,
RESET
