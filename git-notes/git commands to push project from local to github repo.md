# 🚀 Push a Local Project to GitHub

Follow these steps to push your local project to a new or existing GitHub repository.

1️⃣ Initialize a Git repository  
git init

2️⃣ Check the current status  
git status

3️⃣ Stage all files for commit  
git add .

4️⃣ Commit the staged files  
git commit -m "Initial commit: springboot-rabbitmq-producer-consumer-demo"

5️⃣ Rename the default branch from 'master' to 'main'  
git branch -M main

6️⃣ Add the remote GitHub repository (replace with your actual repo URL)  
git remote add origin https://github.com/YourUsername/YourRepoName.git  
# Example  
git remote add origin https://github.com/JakilSyed/jakil-dev-notes.git

7️⃣ Push your local main branch to GitHub and set upstream tracking  
git push -u origin main

✅ Done! Your project is now live on GitHub 🎉