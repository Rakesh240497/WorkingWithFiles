# WorkingWithFiles

The main aim of the program is to work with Files, and to copy files from source file to destination file or destination file to source file. 

##Testing. 

First we check for the errors so that the program won't crash. 

In the first if we check weather the argc count is 3 or not, if it is not 3 than it means the file names that need to be passed to programs or missing. 

Second we check for the file names. 
If the source and destination file names are different than there is no point in copying a same content to same file. 

#Program
Here we create varibles for read and write for the open function. The open function returns -1 if there is an error with file opening. We check this by an if statement. Then using a while loop we copy the content from source file to destination file or destination file to source file. If there is any error while doing this process we print the error and terminate. 

After the program is run we close the source and destination files using close function. 
