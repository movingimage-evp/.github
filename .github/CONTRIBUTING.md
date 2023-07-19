* Your branch name and pull request title needs to contain the Jira Ticket you are working on. `feature/MYPROJECT-123` and "MYPROJECT-123: ..."  respectively.
* `main` is the protected main branch
* Any merge to `main` requires the following 
  * `CODEOWNERS` approval, you'll see the code owners are automatically added as reviewers
  * Passing of the Snyk security scans
  * Passing of the unit tests
  * All open review tasks need to be ticked off
