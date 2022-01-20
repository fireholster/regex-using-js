# regex-using-js
Something about regex using javascript

#####Tools: regex pal, VS Code

##### exec - retains the index for next execution
e.g. 
- txt = My ass is alwayS on the lines that are drawn by other people.
- regEx = /s\s/gi 
    - regEx.exec(txt); //output = s (pulled from ass )
    - regEx.exec(txt); //output = S (pulled from alwayS) i.e. search will start from the index where the previous match was found i.e. ass in this example.
    - regEx.exec(txt); //output = s (pulled from lines )
    - regEx.exec(txt); //output = null (no other s)

##### match - search the whole string


##### Meta Characters
    - Wildcard ( . ) : Single wildcard character 
    - Escape ( \ ) : using literal value right after escape
    - . : 
    - * :  