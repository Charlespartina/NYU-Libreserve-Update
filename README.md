# NYU-Libreserve-Update
This script serves to automatically reserve a study room at NYU by multithreading, [selenium](http://selenium.googlecode.com/git/docs/api/py/index.html#installing) and [PhantomJS](http://phantomjs.org/download.html).

## Features
* Automatically read users' login information and reservation info from a text file. After reservation, modify the reservation date to the next preference.
* There is a list indicating the pripority of several options of room numbers. You can change it in the source code.
* The default "Select length" is 2 hours. You can change it in the source code.

## Usage
1. Make sure that you have the [selenium](http://selenium.googlecode.com/git/docs/api/py/index.html#installing)  and [PhantomJS](http://phantomjs.org/download.html) installed.
2. Create a text file named 'userinfo.txt' at the directory of the script.
3. Fill in users' information and reservation info in the following format (each line contains the reservation info of one user' account):
  * NetID Password Month Day Hour Am/Pm
  * For Example, the text `ph301 12345yhnbhy 9 4 8 pm` will tell the script to reserve a study room at 8pm on Sep 4th .
4. Launch the script and wait for the reservation complete 


