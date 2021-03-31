Threads

## Prerequisite for setting up the Lab

1. Install Node.js for your system

```
# Check these commands
node -v
npm -v
```

2. Install MongoDB

NOTE: Be carefull while installing mongodb, as if the installation is not done properly the debugging of the error is very tedious.

## Setting Up the project

```
1) Run the command "git clone https://github.com/enciphers/ThreadsApp.git"
2) cd Threads
3) Open the "config.env" file and fill in the required information given in the file. The application won't run if all information is not filled in. For the AWS s3 bucket, you need to create an account on AWS and create a s3 bucket, then fill the ACCESSKEYID, SECRETACCESSKEY, REGION, BUCKET_NAME values of your account in the env file.
4) MongoDB database is used in the application.MongoDB database should be configured properly and should be running. Otherwise, the app won't run.
5) Run the command "npm install" in the "Threads" folder to install all dependencies required for API.
6) Run the command "npm run client_install" to install all dependencies of react app.
   Note: If above steps does not ask to add dummy users to the app, use "npm run add_users" command to add dummy users manually.
6) Run the command "npm start" to start the application. The application will run on "http://localhost:4000/". Here "3000" is the value of the "PORT" provided in the ".env" file in the client folder. Feel free to change the default port number. "4000" is the default value of "PORT".
```

## Starting the Project

```
npm start
```

You should see a message `Connected to Moongose` in the terminal, if that's the case then the project setup is done and all the prerequisite were installed properly
if that's not the case, create an issue with the error and screenshot.

#### Using the application

```
Visit --> http://localhost:3000/home
Here "3000" is the value of the "PORT" provides the ".env" file in the client folder. So you need to replace the value of "3000" with the value of "PORT" in the ".env" file of the client.
"3000" is the default value of "PORT".
Create some users, then signin, play with API's etc
```

### NOTE:

1. Filling all information in both environment files is necessary to run the app.
2. Admin email address is "[admin@threadsapp.co.in](mailto:admin@threadsapp.co.in)". You can visit "http://localhost:3000/management" for the admin page.
3. For the AWS s3 bucket, you need to fill correct information in the "config.env" file.
4. User profile pictures are saved in the "uploads" folder.
5. Post pictures are uploaded on s3 bucket.
6. You will get the option to add dummy data while installing dependencies of API. It will create 25 users and 25 posts and this user will follow each other randomly.
7. Follow all the steps properly to run the application.
8. You can use the command "npm run add_users" to add dummy data again. New dummy data will replace old dummy data.
9. The app is designed to add some random dummy users and posts when the app us being installed. You will be asked whether you want to add the dummy data or not, while the app set up is being done. 

### Some points about the app:
1. All Users and New Users section will show other users, but not yourself. 
2. Want to use a live version of the app {Hosted by Enciphers}, for training? Drop us an email at training@enciphers.com


### Some Screenshots
![Alt text](/uploads/screely-1614355834783.png?raw=true "Optional Title")
![Alt text](/uploads/screely-1614355791180.png?raw=true "Optional Title")
![Alt text](/uploads/screely-1614355858120.png?raw=true "Optional Title")
![Alt text](/uploads/screely-1614355873639.png?raw=true "Optional Title")


--------------------
