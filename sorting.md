# Sorting Script

This bash script sorts a given input text file.

## Usage

```bash
sorting.sh <input_file>
```

- `input_file` - Text file to sort

## What it does 

- Reads the input text file line by line
- Sorts the lines alphabetically 
- Prints the sorted lines to console

## Example

Input file `data.txt`:

```
zebra
apple
cat
dog
```

Running `sorting.sh data.txt` will print:

```
apple
cat
dog
zebra
```

## How it works

- Reads each line into an array using `readarray`
- Sorts the array using `sort`
- Prints each element using `for` loop

## Code

```bash
#!/bin/bash

input_file=$1

readarray -t array < "$input_file"

sorted_array=($(sort <<<"${array[*]}"))

for element in "${sorted_array[@]}"
do
  echo "$element"
done
```

```bash
touch sorting.sh
```

```bash
nano sorting.sh
```

<img width="590" alt="Screenshot 2023-11-04 at 08 55 38" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/08ff2453-235c-4401-8507-0c36cf6c0e24">

```bash
sudo chmod +x sorting.sh
```

```bash
 ./sorting.sh
```

<img width="590" alt="Screenshot 2023-11-04 at 08 57 39" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/7d310e2c-130f-4137-8ff9-0bac6d99e1d2">
