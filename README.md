# shell-data-processing
This is a shell-data-processing app

## Powershell Commands

- mkdir

It is used to create new directories

- cd

It is used for changing the directory

- ni

It is used for creating a new item

- ls

Listing the files and directories


## Curl Commands

- curl "https://en.wikipedia.org/wiki/Indian_Premier_League" -O

- curl "https://en.wikipedia.org/wiki/Indian_Premier_League" -O "data.txt"


## Bash Commands

- tr ' ' '\12' < returnedfile

Each space can be transformed into a return character

- tr ' ' '\12' < returnedfile | sort

Pipe the output to sort

- tr ' ' '\12' < returnedfile | sort | uniq -c

Piping the sorted output to uniq -c to count

- tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr

Piping the reduced output to sort with -nr flag

- tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr > result.txt

Redirecting the output to result.txt

## File Links

[data file](data.txt)

[result file](result.txt)
