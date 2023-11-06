# Backup Script

This is a simple bash script to backup files.

## Usage

```bash
backup.sh <source_folder> <target_folder>
```

- `source_folder`: The folder to backup
- `target_folder`: The backup destination folder

## What it does

- Creates the target folder if it doesn't exist 
- Copies all files from the source folder to the target folder
- Adds a timestamp to the backup folder name for versioning
- Prints out log messages indicating the progress

## Example

```bash
backup.sh /home/user/documents /backups
```

This will:

- Create the `/backups` folder if it doesn't exist
- Copy all files from `/home/user/documents` to `/backups/documents-11-06-2023` 
- Print log messages like:

```
Starting backup of /home/user/documents to /backups/documents-11-06-2023
Copy /home/user/documents/file1.txt
Copy /home/user/documents/file2.txt 
Backup complete!
```

```bash
touch backup.sh
```

```bash
nano backup.sh
```

<img width="590" alt="Screenshot 2023-11-04 at 09 04 03" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/fc92bde7-af10-4f0f-a8b4-0c4b0e066f93">

```bash
sudo chmod +x backup.sh
```

```bash
./backup.sh
```

<img width="590" alt="Screenshot 2023-11-04 at 09 13 41" src="https://github.com/kennyanju/dareio-bash-scripting/assets/10983149/d5d3c92c-2805-4c29-994d-a32d2d52730a">
