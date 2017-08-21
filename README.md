## Test 1:
You can use whatever programming language you feel most comfortable in (replace “Python datetime” with whatever the native object is in the language to express a Date & Time).
Given the CSV File that will be given to you, write a function find_open_restaurants(csv_filename, search_datetime) which takes as parameters a filename and a Python datetime object and returns a list of restaurant names which are open on that date and time. Optimized solutions are nice, but correct solutions are more important!
### Assumptions:
* If a day of the week is not listed, the restaurant is closed on that day
* All times are local — don’t worry about timezone-awareness
* The CSV file will be well-formed


## Test 2:
Your task is to write a simple script to transform data.tsv into a properly formatted tab-separated values (TSV) file that can be read by any standard CSV/TSV parser. The resulting file should have the following properties:
* Each row contains the same number of fields
* Fields are separated by tabs \t
* Fields that contain reserved characters (e.g. \t, \r, \n) are quoted (hint hint)
* The file is UTF-8 encoded (data.tsv is UTF-16LE encoded)
* Scripts can be written in any language and use any tools with which the candidate is familiar. The solution does not need to be generic enough to apply to similar issues in other files; your algorithm can be designed specifically for this data set. * * Extra points are awarded for resource-efficient and scalable solutions.
