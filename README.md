# Basic Git and Node setup task

### Config your git username and email in terminal (only for first time use)
  1. Open your terminal and type the following 
  2. `git config --global user.name "<write your github username>"`
  3. `git config --global user.email "<write your github email>"`
  
  
### Clone this repository to your local machin
1. Navigate your terminal or git bash to desktop
2. Clone this repo by typing `git clone https://github.com/SE-GUC/<Task1-X-Y>.git` X={BI, ENG} and Y={your tutorial}
3. You should now have a folder containing the example code

### Open the project and edit a file
1. Open server/index.js
2. Add your name and id (as a string) to the students array

### Install the required node packages
1. Navigate to server/ folder and type `npm i`
![alt text](https://github.com/SE-GUC/Task1-BI-19/blob/master/screenshots/ss3.png)


### Run the node server and check if your name is displayed !
1. write `node index.js` to run the server
![alt text](https://github.com/SE-GUC/Task1-BI-19/blob/master/screenshots/ss4.png)
2. the server should start running locally on port 3000
3. Open your browser and go to this url `localhost:3000`
![alt text](https://github.com/SE-GUC/Task1-BI-19/blob/master/screenshots/ss5.png)
4. You should see one link called `Students`, press this link to go to students' page
![alt text](https://github.com/SE-GUC/Task1-BI-19/blob/master/screenshots/ss6.png)
5. At this point, you should see your name in the list of students
6. Now, come back on this github page and create a pull request adding your name and id to this repo's index.js file
7. To make sure everything is correct, you should see that your pull request is changing 1 file (index.js) and you add 1 line which is simply your name and id in the array
8. Your pull request and its changes are the proof that you have successfully learned how things work so far ! 
