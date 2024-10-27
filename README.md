# House Price Prediction

### Description
A regression type prediction model usin Random Forest Regressor algorithm that uses MSE (Mean Squared Error) as metric for prediction

### Git commands used:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.

### Steps:
1. In Jenkins creaset a new item under Freestyle Project item type
2. Selec Git in Source Code Management and paste your github repository url in the given space
3. Add Execute Windows batch command step
4. Save the configuration
5. Build now and visualize console output
6. Now open command prompt with the required folder path
7. Execute the Docker commands
8. Now you can visualize the output in both the command prompt and in the containers from Docker Desktop app.

### Docker commands used:
1. `docker build -t <folder_name> .`
2. `docker run <folder_name>`

Output:
![image](https://github.com/user-attachments/assets/53e32c46-2010-4392-8238-733d7f1f606a)
![image](https://github.com/user-attachments/assets/bddcc797-8759-496e-bae0-e5f154307325)


