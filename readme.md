                                     								feature-branch→ user given branch name									
CASE 1: PROJECT ALREADY EXISTS ON GITHUB   	  
         
VS Code Terminal                                                                                        	
1. Download project from GitHub
git clone <GitHub-Repo-URL>
cd <project-folder>

2. Go to main branch and get latest code
git checkout main
git pull

3. Create a new branch to work on
git checkout -b feature-branch

4. Do your coding, then save changes
git add .
git commit -m "Describe your change"

5. Push branch to GitHub (first time only)
git push -u origin feature-branch

6. Continue working and pushing changes
git add .
git commit -m "More changes"
git push

7. Open Pull Request
Base branch → main
Compare branch → feature-branch
Click Create Pull Request → Merge

VS Code Terminal (after merge)                                      

8. Update your local main branch
git checkout main
git pull

Repeat again from step 3 for the next feature.

git init
git add .
git commit -m "First commit"
git branch -M main
git remote add origin <GitHub-Repo-URL>
git push -u origin main



