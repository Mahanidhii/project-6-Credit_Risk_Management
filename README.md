# House Price Prediction

### Description
A regression type prediction model usin Random Forest Regressor algorithm that uses MSE (Mean Squared Error) as metric for prediction.

### Git and other commands used:
1. `mkdir <file_name>` to create the folder
2. `cd <file name>` to go inside the folder
3. `git init`, initializing folder as git repository
5. `git add .` to add all the files into git track
6. `git commit -m "<message>"`, it commits whatever is there in the track
7. `git remote add origin <GitHub repository link>`, builds connection between git and github
8. `git push --set-upstream origin master`, sends all the files from git to github.

Docker Commands:
1. `docker build -t <file_name> .`
2. `docker run <file_name`

### Steps:
1. Create the required files such as the dataset csv file(house-price-prediction.csv), requirements txt file, training model python file, Dockerfile
2. Create a new item under the Freestyle Project in Jenkins
3. Select Git in Source Code Management
4. Add Execute Windows Batch Command Step in Build Steps
5. Save the configurations
6. Build now and visualize console output
7. Now open the command prompt with the path of the folder containing the required files
8. Execute the Docker commands mentioned above
9. The output can be visualized in the command prompt and the Docker Desktop app

Output:
![image](https://github.com/user-attachments/assets/53e32c46-2010-4392-8238-733d7f1f606a)
![image](https://github.com/user-attachments/assets/bddcc797-8759-496e-bae0-e5f154307325)


