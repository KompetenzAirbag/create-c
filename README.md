# Create C
A simple cli tool for creating c programs from my c-template. This will automatically clone the template, remove old commits and initialize a new repository. This will also rename the executable and update the README.
# Installation
Clone the repository and run
```{bash}
sudo ln -s <dir>/create-c /usr/bin/
```
# Usage
```{bash}
create-c <path> [name]
    <path> ~/example/<project-name> | <project-name> (will default to ./<project-name>)
    [name] (optional) alternative name to <project-name>
```
