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
#!bin/bash
# Create three files
echo "Creating files..."
echo "This is file3." > file3.txt
echo "This is filel." > file1.txt
echo "This is file2." > file2.txt
echo "Files created."

# Display the files in their current order
echo "Files in their current order:"
ls

# Sort the files alphabetically
echo "Sorting files alphabetically..."
ls | sort > sorted_files.txt
echo "Files sorted."

# Display the sorted files
echo "Sorted files:"
cat sorted_files.txt

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
