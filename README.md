# Web-Search-Engine-Using-Java
Modules Implemented:
  HTML to Text conversion
  String Tokenization
  Searching
  Sorting
  Finding patterns using regular expressions
JSOUP: jsoup is a Java library for working with real-world HTML. It provides a very convenient API for extracting and manipulating data, using the best of DOM, CSS, and jquery-like methods. jsoup implements the WHATWG HTML5 specification, and parses HTML to the same DOM as modern browsers do. (ref: jsoup.org)
With the help of JSOUP, all the html files are converted into txt files.

STRING TOKENIZATION:
  Delimiters or white spaces are used to separate characters and create tokens.
  This process allows the string to be broken into small parts known as tokens.
  The token can be a number, an identifier or any string.

SEARCHING:
  Used Booyermore Algorithm to find keywords.
  It Shows the occurrences of words in file
  Then after we stored it in hashmap.

SORTING:
  Used HashMap because it allows us to preserve the ordering of elements in which they are inserted. 
  To sort HashMap Comparator interface.

REGULAR EXPRESSIONS:
  Used regular expressions to find contact numbers and email ID from the web page which was entered by user.
  Regex used to search contact number is : (\\()?(\\d){3}(\\))?[- ](\\d){3}-(\\d){4}
  Regex used to search email id is : ([\\w\\-]?([\\.\\w])+[\\w]+@([\\w\\-]+\\.)+[A-Za-z]{2,4})
  User will get different word suggestion based upon on his input .
  Used Regex in order to find word suggestion for the user input.





