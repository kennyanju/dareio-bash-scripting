# First Bash Script

This is a simple bash script to demonstrate basic concepts. 

## What it does

- Prompt the user for their name 
- Display a greeting with the entered name

## Code Overview

```bash
!/bin/bash
#Prompt the user for their name
echo "Enter your name:"
read name
# Display a greeting with the entered name
echo "Hello, $name! Nice to meet you."
```

- `#!/bin/bash` shebang specifies to run with bash interpreter
- `echo` prints the string
- `read` reads input from echo

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

