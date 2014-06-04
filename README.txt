Name: JavaScript Bypass

Description: A user is presented with a login function in javascript. They must figure out how to bypass the login function in order to find the key.

How to Solve: They must go through the bootstrap.js file and find the login function that checks to see if the fields contain the correct username and password. Once found, they have to reverse the obfuscation of the code in order to find the username and password. (This can be done by pasting _0x838e in the javascript console, note that _0x838e[301] gives you the username and _0x838e[303] gives you the password.) Once the user is logged in, they have to view source to find the secretpage.html file and then navigate to that file. On that page in the source they will find the key. 

Note that this challenge works in every browser but chrome while debugging, if you put the files on a remote server then they work fine in any browser.

Flag: 3f428e6081076c1904b1315e23dc6dff856af4e1