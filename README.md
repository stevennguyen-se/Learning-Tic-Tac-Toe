# Learning-Tic-Tac-Toe

A simple browser-based tic-tac-toe game that depends on a locally-run nodejs server.  

![Learning-Tic-Tac-Toe-Screenshot](https://github.com/stevennguyen-se/Learning-Tic-Tac-Toe/assets/34677577/725f3a5f-ccb1-40d9-bc88-23bfeeb9b9a5)


## Steps to run

cd to project folder.

`npm run first` - npm script install packages for both server and client. 
This will install all the required packages on both the server and client sides. Once this process is completed, we can initiate both the server and client instances with a single command.

`npm run start` - npm script that runs both server and client instances.
Now, the server will be listening on the specified port (4001) while webpack compiles and hosts the client code, which will be accessible at a designated port (3000). A browser window should automatically open with the URL 'http://localhost:3000'. To run two clients simultaneously, open a new tab with the same URL. The two tabs will then enable gameplay between each other.
