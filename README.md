# Upstream-Git

The git set-upstream allows you to set the default remote branch for your current local branch. By default, every pull command sets the master as your default remote branch.

```

1. Create a repo in Github

2. Add the remote repository to the local repository using HTTPS url 
$ git remote add origin <Your HTTPS_URL>

3. Run the following command to verify the setup of remote repository:
$ git remote -v

4. Add upstream to the remote repository by executing the below command:
$ git remote add upstream <Your HTTPS_URL>
$ git remote -v

5. Fetch upstream
$ git fetch upstream

6. Update the local branch with respect to the upstream branch
$ git checkout main
$ git merge upstream/main --allow-unrelated-histories

```



