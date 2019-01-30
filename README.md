# Default C++ repo
## Intention
this is intended as a starting point for VS Code projects in C++ and includes:

* tasks.json for compilation
* launch.json for debugging
* c_cpp_properties.json for the C/C++ for Visual Studio Code extension, intellisense, etc.
* a folder structure for sourcecode, external dependencies, etc.

## Useage:

1. Clone this repo using 'git clone https://github.com/SimWalh/Default-CPP-Repo.git', resulting in a 'Default-CPP-Repo/' folder
1. Create a new project repo and clone it too, resulting in a 'projectrepo/' folder
1. Copy everything inside 'Default-CPP-Repo/', **except .git and ReadMe.md** into 'projectrepo/'
1. You can now delete the 'Default-CPP-Repo/' folder
1. Inside 'projectrepo/', 
    1. commit everything using 'git add .' and 'git commit -m "initial commit, starting point"'
    1. push the commit using 'git push'