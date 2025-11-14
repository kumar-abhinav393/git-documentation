# Git Tutorial Documentation

## What is a Git?
Git is a version control system that helps developers to track changes in their code, work together without overwriting each other' work, and go back to any previous version whenever needed.

### Real-World Example:
A team is building a Room Booking App.
1. The team creates a Git repository (special database) for the app.
2. Each developer works on a feature in a separate branch (e.g, feature/login, feature/booking-filter, etc...)
3. once the feature is ready, Git allows them to merge it safely with everyone else's code.
4. if something breaks, Git lets them go back to the previosu working version.

This is exactly how software companies (Microsoft, Google, Amazon, etc) build large, complex systems.

## Types of Version Control System (VCS)
VCS are mainly of two types:
1. Centralized VCS
2. Distributed VCS

### Centralized VCS
A centralized system uses one main server that stores all code. Developers must connect to this server to get files or save updates. For example: Subversion or Team Foundation Server.

#### How it works
1. Main server stores all project files.
2. Developer downloads only the latest version (no full history).
3. Developer must stay connected to commit changes.
4. if server fails -> work stops.

### Distributed VCS
A distributed system lets every developer have a full copy of the project, including complete history. For example: Git(most popular), Mercurial

#### How it works?
1. Every developer gets a full copy of the project + history.
2. We can commit changes even without internet.
3. Copies can syncronize via 'push' and 'pull'.
4. if the main server crashes -> code is safe because everyone has a copy.

## Git (https://git-scm.com/)
Git can be used in 3 main ways:
1. Git using Command Line
2. Git using Code Editors & IDEs
3. Git using GUI Applications (Gitkracken, SourceTree, Tower)

Note: We need to first install Git to use git with the above mentioned ways.

### Configuring Git
After installing Git, we configure Git so that code editors can use it properly. Git has three levels of configuration:
1. System level (applies to all users + all repositories on the system)
2. Global level (The current user + all repositories)       ---- most used by developers
3. Local level (The specific repository only)

#### Global Level Git configuration
- 'git config --help'
- 'git config --global user.name "Abhinav Sharma"'
- 'git config --global user.email kumar.abhinav5670@gmail.com'
- 'git config --global core.editor "code --wait"'
- 'git config --global -e'    (To open the '.gitconfig' file)









