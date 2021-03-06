# GitHub Snippets

## What is GitHub
I am of the view that skill, the ability to do something well, is essential when one has the experience, 
and knowledge, as skill is what allows one to express the experience and knowledge that one possesses. 
This folder will contain the Git command snippets that I employ and express for daily work. Git is a free 
and open-source distributed version control system that's responsible for everything. Source control 
software operates within two paradigms, centralised, and distributed. Source control that is centralised 
such as SVN employs a central repository to store all files for collaborative file sharing. In a centralised 
system such as SVN, a server is employed to holds all versions of the files. Typically, a developer employs 
a "check-out" operation, to download the files from the server onto our local machine. This creates a 
"working copy", and employs a "commit" to synchronise with the server from the local machine A team employing 
a centralised system such as SVN, shares the same repository, but everyone has their working copy on their machines. 
When one person commits a change, everyone else can perform an "update" to get the latest changes and apply them to 
their local working copy. A distributed system such as Git differs in that there is no centralised repository. 
The centralised repository is on each developer's local machine, the "working copy", and the “index”. 
The index is a staging area where we gather our changes before committing them. As with all software tools, 
interacting with the software effectively requires the use of commands. It is the knowledge, and experience 
in using these commands, that a DevOps, software engineer should aim to understand, and express effectively 
in their daily duties.
Git is software for tracking changes in any set of files, usually used for coordinating work among 
software engineers involved in collaboratively developing. Its goals include 
speed, data integrity, and support for distributed, non-linear workflows.
Git is now that

### Getting Help
If you need help while using Git, access to a comprehensive manual page is vailable via the commands below. 

```shell
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
```
### Setup and Config

#### git
#### config
#### help
#### bugreport

### Getting and Creating Projects
#### init
#### clone

### Basic Snapshotting
#### add
#### status
#### diff
#### commit
#### notes
#### restore
#### reset
#### rm
#### mv

### Branching and Merging
#### branch
#### checkout
#### switch
#### merge
#### mergetool
#### log
#### stash
#### tag
#### worktree

### Sharing and Updating Projects
#### fetch
#### pull
#### push
#### remote
#### submodule

### Inspection and Comparison
#### show
#### log
#### diff
#### difftool
#### range-diff
#### shortlog
#### describe

### Patching
#### apply
#### cherry-pick
#### diff
#### rebase
#### revert
#### Debugging
#### bisect
#### blame
#### grep