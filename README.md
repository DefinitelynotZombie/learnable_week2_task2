**Version Control and Git**
# Explain Version Control
Version control is a critical aspect of software development that allows developers to track changes in their code over time. It provides a systematic way to manage different versions of a project, enabling collaboration, bug tracking, and the ability to revert to previous states if needed. One popular version control system is Git.

## Explain the Difference between Git and GitHub
Git is a distributed version control system that tracks changes locally, while GitHub is a web-based hosting service that provides a centralized platform for collaborative development. Git focuses on version control and collaboration, whereas GitHub is a platform for hosting Git repositories, offering additional features like a graphical user interface and user management.

### GitHub Alternatives
Three Other GitHub Alternatives are;
1. GitLab: A web-based DevSecOps platform supporting both cloud-based and self-hosted solutions.
2. Bitbucket: Owned by Atlassian, supporting both Git and Mercurial, and integrating well with Jira.
3. SourceForge: A long-standing platform supporting Git, Mercurial, and SVN, with various project management features.

#### Explain the Difference between ‘git fetch’ and ‘git pull’
The main distinction is that ‘git fetch’ retrieves changes from the remote repository to the local repository without merging them into the current branch. Conversely, ‘git pull’ not only retrieves changes but also merges them into the current branch.

##### Explain in Simple Terms git rebase and the Command for It
Git rebase is a process that combines or moves commits onto a new base commit, providing a linear way of merging changes. The command for Git rebase is ‘git rebase <base>’, where <base> is the commit or branch to base the changes on. For an interactive rebase, use ‘git rebase --interactive <base>’.


###### Explain in Simple Terms git cherry-pick and the Command for It
Git cherry-pick selectively applies a specific commit from one branch to another. It is useful for fixing mistakes or applying changes from a feature branch to the main branch. The command is ‘git cherry-pick <commitSha>’, where <commitSha> is the commit reference. You can find the commit reference using the git log command.


