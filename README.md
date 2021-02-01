# Go Task

A Go program to backup directories and databases and pushing it to S3 bucket with configuration provided.
#### Running the Program
In command prompt, go to the related directory and run the command 
> `go run main.go`

Use this command to download the library if the program doesn't execute. 
> `go get -u github.com/walle/targz`

When the program is run, it will read config.json and takes the input of the directories.
Later, it will copy the files into a temporary backup directory, which then will be compressed to tar.gz file.

#### Sub-tasks completed
###### 1: Reading configuration from JSON file
###### 2: Copying folders to a temporary backup directory
###### 3: Making a tar.gz file of the backup directory

#### Sub-tasks Pending
###### 1: Taking input from command line
###### 2: MySQL connection and backup
###### 3: Integrating with S3 bucket 
