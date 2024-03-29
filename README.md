[![CodeFactor](https://www.codefactor.io/repository/github/danyb0/meet-attendance/badge)](https://www.codefactor.io/repository/github/danyb0/meet-attendance)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# A bad-looking Google Meet attendance :)

## Screenshots
[![Screenshot-136.png](https://i.postimg.cc/rpL38Z85/Screenshot-136.png)](https://postimg.cc/VJDDgR0N)
[![Screenshot-137.png](https://i.postimg.cc/mrRpxcww/Screenshot-137.png)](https://postimg.cc/18Crw3bn)

## Setup
### This project uses Helium, a Python library which is like Selenium but more high-level. You may need to download the chromedriver.exe.
- #### Install Python if you don't have it
  * #### Install Python [here](https://www.python.org/)
- #### Install the requirements
  * #### `pip install -r requirements.txt`
- #### Open the `credentials.txt` file and write your language (ita/eng) in the 1st row, your email in the 2nd row and your password in the 3rd row.
- #### Open the `meet-link.json` file and write the name of your class and the link you want to open.
- #### Open the `schedule.xlsx` file and write the names of your classes (the same you wrote in the json file)
- #### Open the terminal, change your working directory into the `meet-attendance` one and type: `python main.py`
