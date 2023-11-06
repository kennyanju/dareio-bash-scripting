# Directory Manipulation Script

This bash script can perform various directory manipulation operations.

## Usage

```bash
dir_manage.sh [options]
```

**Options:**

- `-h`: Display help 
- `-l`: List files recursively
- `-a`: List all files including hidden
- `-s <dir>`: Search for a directory
- `-c <dir>`: Create directory
- `-d <dir>`: Delete directory

## What it does

- Displays help with `-h`
- Recursively lists all files with `-l` 
- Lists hidden files also with `-a`
- Searches for a directory with `-s`
- Creates a directory with `-c`
- Deletes a directory with `-d`

## Examples

List all files recursively:

```bash
dir_manage.sh -l
```

Create a directory:

```bash
dir_manage.sh -c mydir 
``` 

Delete a directory:

```bash
dir_manage.sh -d mydir
```

```bash
touch navigating-linux-filesystem.sh
```

```bash
nano navigating-linux-filesystem.sh
```

<img width="598" alt="Screenshot 2023-11-04 at 08 49 11" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/2ccca3c3-ba68-42d1-8983-9d195729b95b">

```bash
sudo chmod +x navigating-linux-filesystem.sh
```

```bash
./navigating-linux-filesystem.sh
```

<img width="590" alt="Screenshot 2023-11-04 at 08 52 32" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/b970b577-4b7c-42bb-b46a-1ba226ecfd95">

