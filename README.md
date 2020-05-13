# Shell Data Processing Notes

## Creating Project 

- I have created a sub folder named "shell-data-processing" in the 44517 folder using the command "mkdir"

``` mkdir shell-data-processing ```

- I have changed directory into subfolder "shell-data-processing" using command "cd"

``` cd shell-data-processing ```

- I have created a new file named README.md using "ni"

``` ni README.md ```

- I have created a new file named .gitignore using command "ni"

``` ni .gitignore ```

- TO list all the contents i used command "ls"

- Next i have the opened the folder "shell-data-processing" using vs code and used the typical .gitignore from my earlier project.

## CURL Commands 

- curl command used to retrieve page 

``` curl"https://en.wikipedia.org/wiki/Audi" ```

- Curl command used to return the page text and output to a file

``` curl "https://en.wikipedia.org/wiki/Audi" -O data.txt" ```

## Process Text Data

```  tr ' ' '\12' < data.txt ```

- This command is used to transform each space ' ' into a return character '\12'

``` tr ' ' '\12' < data.txt | sort ``` 

- This command is used to send the results of one command as input into another command

``` tr ' ' '\12' < data.txt | sort | uniq -c ```

- This command is used to Pipe the sorted output to uniq -c to count

``` tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr ```

- This command is used to Pipe the reduced output to sort with -nr flag

``` tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt ```

- this command is used to Redirect the output to result.txt

- After using these commands i have created an empty repo and intialized it .added all files and pushed it to cloud.

## BASH Commands 

``` ls > filelist.txt ``` used to to redirect the contents of your directory into a file. 

``` ls > temp.txt ``` used to Send the result to a new file called temp.txt
 
 ``` cat ``` command to display the contents of temp.txt.








