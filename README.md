# **CLI Commind Line in linux**
## **How update `Ubuntu`**
``` bash
sudo apt update # sudo parmission as root 
```
## **Remove file or dir in linux**
### **Use `rm` with Optinons**
```bash
rm __name_file_dir_ ## Remove
rm -r __name_file_dir_recrentry
rm -rf __ === & force
```
## **How create new Dir by CLI**:
```bash
   mkdir __name__fold
```
## **List Show & Arguemnts**
```bash 
ls # For show lish
ls -a # Showing all files with hideen
ls -la # Showing all files with parmisions
```
# **Create Python Enviromint**
1. ## **Create Env by `venv`**
   ``` bash
   apt install python3.12-venv
   python -m venv __name_env
   ```
2. ## **Activate Env**
   ```bash
   source __name_env/bin/activate
   ```
## **git CLI**
### **initi** repo:
```bash
git init
```
### **add file or all files**:
```bash
git add __name_file
git add . ## For add all things not in .gitignore
```
### **Commit**:
```bash
git commit -m "MSG here refer to change in code for like this"
git commit -a "MSG wihtout add."
```
## **push for repo**
```bash
git push origin main
```
- **Requireds Acces Tokines**:
   - user_name
   - password (access_token)