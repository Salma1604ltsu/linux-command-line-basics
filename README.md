# Linux Basics Lab 🐧

A practical Linux command-line exercise covering navigation, files, directories, file content, and text searching.

## Objective

Practice the following Linux commands:

* `pwd`
* `ls`
* `cd`
* `mkdir`
* `touch`
* `echo`
* `cat`
* `grep`

## 1. Check Current Directory

```bash
pwd
```

Example output:

```text
/home/user/linux-basics-lab
```

`pwd` displays the current working directory.

## 2. List Files and Directories

```bash
ls
```

To see detailed information:

```bash
ls -la
```

## 3. Create a Directory

```bash
mkdir linux_test
```

Enter the directory:

```bash
cd linux_test
```

## 4. Create a File

```bash
touch notes.txt
```

Check that the file exists:

```bash
ls
```

Expected output:

```text
notes.txt
```

## 5. Write Data to a File

```bash
echo "Linux is easy" > notes.txt
```

Add another line:

```bash
echo "Linux is powerful" >> notes.txt
```

Here:

* `>` creates/overwrites the file.
* `>>` appends data to the file.

## 6. Read the File

```bash
cat notes.txt
```

Output:

```text
Linux is easy
Linux is powerful
```

## 7. Search Text Using grep

```bash
grep "Linux" notes.txt
```

Output:

```text
Linux is easy
Linux is powerful
```

`grep` searches for a specific word or pattern inside a file.

## 8. Navigate Back

```bash
cd ..
pwd
```

`cd ..` moves one directory up.

## Complete Practical Exercise

```bash
pwd
ls
mkdir linux_test
cd linux_test
touch notes.txt
echo "Linux is easy" > notes.txt
echo "Linux is powerful" >> notes.txt
echo "Windows is also an operating system" >> notes.txt
cat notes.txt
grep "Linux" notes.txt
cd ..
pwd
```

## Skills Demonstrated

```text
Linux Navigation
      │
      ├── pwd
      ├── ls
      └── cd
      │
      ▼
File Management
      │
      ├── mkdir
      └── touch
      │
      ▼
File Operations
      │
      ├── echo
      └── cat
      │
      ▼
Text Searching
      │
      └── grep
```

## Evidence

Screenshots of the terminal execution can be added to this repository to demonstrate practical execution of the commands.

## Learning Outcome

This lab demonstrates basic Linux command-line skills including filesystem navigation, directory and file creation, writing and reading files, and searching text using `grep`.
