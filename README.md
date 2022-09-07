# OPSWAT README

Rough Documentation and thoughts are python comments.

1) The code if written in Python 3.6 as a jupyter notebook(ipyn) and uses 4 imports:
hashlib
requests
json
os

There are two ways to run the code.

1) In order to run the python notebook there are two main variables that you need to fill out
  1) fill out the API_key variable in the first cell
  2) fill out the file string variable in the second cell
    - Note: the payload variable might have to be adjusted
  3) change the stop variable when the file is being scanned. If the file requires more scanning then increase the variable.

2) Run the function run_program(API_key:str, file_name:str) -> None:
  - this function will print values or errors that your file may fun into

Thanks for your time and consideration with my code.


