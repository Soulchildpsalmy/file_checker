# File Checker Script

A simple Bash script to check whether a file exists or not.

## 📝 Description

This script takes a filename as an argument and checks whether the specified file exists in the current directory (or at the provided path). It prints a message indicating whether the file exists or not.

## 📄 Usage

### 1. Make the script executable

```bash
chmod +x file-checker.sh

**### 2.Run the script** 

./file-checker.sh <filename>

Replace <filename> with the name or path of the file you want to check.

🧪 Output

File 'test.txt' exists.
File 'test.txt' does not exist.

⚠️ Notes
The script must be run in a UNIX-like environment (Linux, macOS, or WSL).

Ensure line endings are in LF format if you created the file on Windows.

If you encounter the ^M error (bad interpreter: No such file or directory), convert the line endings using:
dos2unix file-checker.sh
