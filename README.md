# PyWordlist-Toolset
![alt text](https://github.com/ngimb64/PyWordlist-Toolset/blob/main/ScrapeParser.gif?raw=true)
![alt text](https://github.com/ngimb64/PyWordlist-Toolset/blob/main/BinParser.png?raw=true)

## Prereqs
> This program runs on Windows and Linux, written in Python 3.9

## Purpose
PyWordlist-Toolset features numerous tools to create and format custom wordlists: 

> binParser.py  -  Generates wordlist from arg binary file contents<br>
> fileParser.py  -  Generates wordlist from arg text file contents<br>
> sanitizer.py  -  Strips leading and trailing whitespace from arg wordlist<br>
> scrapeParser.py  -  Generate wordlist from scraped web data from arg url list

Aside from the sanitizer, all scripts generate the wordlist in append mode.<br>
This allows the scripts to be executed in various combinations while still resulting in a single wordlist.

## Installation
- Run the setup.py script to build a virtual environment and install all external packages in the created venv.

> Example:<br>
> python3 setup.py "venv name"

- Once virtual env is built traverse to the (Scripts-Windows or bin-Linux) directory in the environment folder just created.
- For Windows in the Scripts directory, for execute the "activate" script to activate the virtual environment.
- For Linux in the bin directory, run the command `source activate` to activate the virtual environment.

## How to use
- Open a shell (cmd or terminal)
- Change directory to PyWordlist-Toolset<br>
<br>
Execution syntax:<br>
<br>
- `binParser.py <binary filename>`
- `fileParser.py <text filenname>`
- `sanitizer.py <wordlist name>`
- `scrapeParser.py <url list>`
