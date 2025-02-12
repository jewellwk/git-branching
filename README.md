# git-branching

# CSC 330 ∙ Activity 2

## Git and Workflows

In this activity, you'll practice working with branches in Git, which is a core part of modern software engineering workflows. By the end of this activity, you should be comfortable creating, switching between, and merging branches, while adhering to a standard SE workflow.

---

### Exercise 1

1. Clone the repository created from GitHub classroom to your local machine (Refer to the screenshot below for where to find the url).
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```
<img width="451" alt="Screenshot 2025-02-12 at 10 14 32" src="https://github.com/user-attachments/assets/ee287567-e009-4025-a774-8e3b2204cf45" />

2. Always start by creating a new branch for any feature or fix. Name the branch `feature/<your-name>`.
   ```bash
   git checkout -b feature/<your-name>
   ```
3. Open the main.py file from the repo. If using VS code then you can open the repository as the current project and navigate to the file using explorer.
4. Update the main.py file by debugging the python code in the file. Save your changes.
5. Stage and commit the changes to the repo. Do not forget your commit message:
    ```bash
    git add <filename>
    git commit -m "Corrected code in <filename>"
    ```
6. Push your feature branch to the remote repository.
   ```bash
   git push origin feature/<your-name>
   ```
7. Type: `git log`. Take a screenshot of the output.

---

### Exercise 2

1. Choose a group member to work with and add one another as a contributor to each other's repo.
2. In your repository, go to Settings (the last menu item within the repo).
3. In the lefthand menu under Access, select Collaborators.
4. Under Manage Access, click the button to Add People and search for your team member's GitHub handle.
5. Add them as a collaborator.
<img width="1232" alt="Screenshot 2025-02-12 at 10 16 57" src="https://github.com/user-attachments/assets/9c89e9b9-3d41-47b0-bea3-a0ef2245c2f1" />

6. Share the URL of your repo of with your team member.
7. Go up a directory (so that you’re no longer in your project directory).
8. Clone your group member’s repo to your local machine.
   ```bash
   git clone <other_repositories_url>
   cd <other_repository_directory>
   ```
9. Checkout your teammate's branch.
   ```bash
   git checkout feature/<teammate-name>
   ```
10. Open the main.py file. If using VS code then you can open the repository as the current project and navigate to the file using explorer.
11. Update the main.py file by placing/converting the existing python code into a properly formatted script.
12. Place the current code into a function. Add a main method. Invoke the function via the main method and confirm it works. Then, save your changes.
13. Stage and commit the changes with the message:
    ```bash
    git add <filename>
    git commit -m "Converted code in <filename> to a function."
    ```
14. Push your changes to the feature branch.
   ```bash
   git push 
   ```
15. Type: `git log`. Take a screenshot of the output.
16. Go to the repository's page on GitHub and select Pull requests.
17. Then click the button to create a New pull request to merge the `feature/<teammate-name>` branch into the `main` branch of the original repository.
<img width="1482" alt="Screenshot 2025-02-12 at 10 21 04" src="https://github.com/user-attachments/assets/b8682b15-39fa-492e-90fc-bfe38f2b0504" />

18. Submit the PR and have your teammate review/approve your changes.
19. After the PR is approved, merge the feature branch. 

---

### Submission Instructions

Save the screenshots into a file named `activity2.pdf` or zip all three images and submit them on Blackboard.
