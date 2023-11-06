# First Bash Script

This is a simple bash script to demonstrate basic concepts. 

## What it does

- Prints "Hello World" 
- Prints the current date and time
- Prints the username of the logged in user
- Prints the home directory path
- Lists files in the home directory

## Code Overview

```bash
#!/bin/bash

# Print hello world
echo "Hello World"

# Print date and time 
date

# Print username
whoami

# Print home directory 
echo "Home directory is $HOME"

# List files in home directory
ls ~
```

- `#!/bin/bash` shebang specifies to run with bash interpreter
- `echo` prints the string
- `date` prints current date and time
- `whoami` prints current username
- `$HOME` prints home directory path
- `ls ~` lists home directory contents

## How to use

Save the code in a file `first_script.sh` and run:

```bash
bash first_script.sh
```
```bash
cd documents

mkdir dareio lessons

mkdir shell-scripting

touch user-input.sh

nano user-input.sh
```


![image](https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/6a7670e1-10f2-4c9f-9730-49c7759af639)

```bash
sudo chmod +x user-input.sh
```

<img width="598" alt="Screenshot 2023-11-04 at 08 45 00" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/0b6ccbb9-6d58-4d9c-9bc6-1768bee8cc8a">

