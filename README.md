This project creates a gulp script and runs tasks to automate the build and reloading of our webserver. We used Uglfy to shortend or get rid of any cooments that might take any space.
Also, we concatenate so that the browser will only have to request one file when our page loads.
Used task "copy" all files in the /src/assets/ should be copied to /dist/assets/
used task "watch" to monitor any changes.
used task "serve" to run or restart a server when needed
Set up a "default" task to run gulp without any arguments.