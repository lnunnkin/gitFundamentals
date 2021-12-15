# git remote

When working with git, a **remote** is any git repos itory that is not on the machine you're working on. The counterpart to this **local**, or the machine that is being developed on.

Take GitHub for example. WHile git is the technology that allows you to create local repositories, GitHub is the site that will host your remote repositories. Once stored remotely, you can bring that repository back down or share it with other.

**Note**: WHile the repositories (local and remote) are related and track the same project, they can have different statues if changes are not shared between the two.

### Adding a remote

A remote can be added with the 'git remote add' commamd. followed by the name and location of the remote.

The  ame is a local na,e. meaning it's your label and does not impact the actual remote whatsoever.

'''
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
'''

### Removing a remote

a remote can be removed with the 'git remote remove'

'''
git remote remove origin
'''

### Resources

- [Git Remote Documentation]9https://hit-scm.com/docs/git-remote)

---

[Back to home](../README.md)