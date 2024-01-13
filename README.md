
# Explain Version Control 
`git status`

## Explain Difference Between Git and GitHub
Git and GitHub are two distinct tools in software development. Git is a distributed version control system, used for tracking code changes and collaboration. It operates locally and stores repositories on local files. Conversely, GitHub is a web-based service for hosting Git repositories. It offers a centralized platform for code sharing, collaboration, and project hosting, featuring user management and a graphical interface. While Git emphasizes version control and code sharing, GitHub focuses on centralized hosting and collaborative features. Together, they form a comprehensive toolkit for code management in software development.

### List Three Other GitHub Alternatives
- **GitLab:** A web-based DevSecOps platform, GitLab offers tools for the entire software lifecycle, available both as a cloud service and a self-hosted solution.
- **Bitbucket:** Owned by Atlassian, Bitbucket supports Git and Mercurial, provides free private repositories, and integrates with other Atlassian products like Jira.
- **SourceForge:** A longstanding platform supporting Git, Mercurial, and SVN, SourceForge offers various project management features.

#### Explain the Difference Between `git fetch` and `git pull`
The primary difference between `git fetch` and `git pull` lies in their operations. `git fetch` retrieves the latest changes from a remote repository to the local repository without merging them into the current branch. In contrast, `git pull` not only fetches changes but also merges them into the current branch.

##### Explain Git Rebase and the Command for It
Git rebase is a process of reapplying a series of commits on top of a new base commit. It provides a linear merging approach, as opposed to the three-way merge in Git merge. The command for Git rebase is: `git rebase <base>`. Here, `<base>` is the new commit or branch onto which you want to rebase. For interactive rebasing, use `git rebase --interactive <base>`, which allows for editing, removing, or altering commits during the rebase process.

###### Explain Git Cherry-Pick and the Command for It
Git cherry-pick is a command for selectively applying a specific commit from one branch to another. It's useful for correcting mistakes like committing to the wrong branch or transferring changes from a feature branch to the main branch. The command for Git cherry-pick is: `git cherry-pick <commitSha>`, where `<commitSha>` is the reference of the commit to apply. To find a commit reference, use `git log`.

