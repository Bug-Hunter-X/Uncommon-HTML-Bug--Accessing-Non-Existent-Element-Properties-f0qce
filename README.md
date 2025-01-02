# Uncommon HTML Bug: Accessing Non-Existent Element Properties

This repository demonstrates an uncommon bug in HTML related to accessing properties of HTML elements that do not exist.  In some browsers, this does not throw a JavaScript error, leading to silent failures or unexpected behavior. 

The `bug.html` file contains the buggy code.  The `bugSolution.html` file provides a solution by checking if the property exists before attempting to access it. 

This bug highlights the importance of robust error handling and checking for the existence of properties before accessing them, even in seemingly simple HTML code.