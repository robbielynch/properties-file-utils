# Properties File Utils 

Properties File Utils is a small tool for devs to check one `*.properties` file against another.
It checks what properties are in one file, and missing from another.
This can useful when handling multiple properties files for different languages, and when not knowing how many properties need to updated. 
This tool helps you to pick out the specific properties that require action.

## Two Possible Options
* Find and output missing KEYS
* Find and output missing KEYS & VALUES

### Notes

* Any lines that not contain a property, will be ignored
* A line contains a property when an `=` splits two strings
* Multi line values are not supported (i.e., property values that end in `\`)  
* _All code located in one file for ease of use_