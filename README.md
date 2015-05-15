# NYU_Libreserve_2.0
This script serves to automatically reserve a study room at NYU by and multithreading and [selenium](http://selenium.googlecode.com/git/docs/api/py/index.html#installing).

## Features
* Automatically read users' login information and reservation info from a text file, and then modify the reservation date to the next preference.
* There is a list indicating the pripority of several options of room numbers.
* The default "Select length" is 2 hours. You can change it in the source code.

## Usage
1 Make sure that you have the python module selenium installed.
2 Create a text file named 'userinfo.txt' at the directory of the script.
3 Fill in users' information and reservation info in the following format (each part is separated by single space):
  * NetID Password Month Day Hour Am/Pm
  * 


