# Obsidian Updater
Downloads and installs the latest Obsidian version for Linux (Debian).

## Setup
```bash
# Clone the repository
git clone https://github.com/Pantonius/Obsidian-Update.git

# Change into the directory
cd Obsidian-Update

# Make the script executable
chmod +x obsidian-update.sh
```

## Usage
```bash
./obsidian-update.sh
```

### Optional
You may prefer to run the script from anywhere on the system.
The best way is to make a symlink to a scripts folder and adding it to your `$PATH` environment varibale.  
Assuming the directory of the repository is on your Desktop and your scripts folder is in your home directory, you can do it like so:
```bash
ln -s /home/user/Desktop/Obsidian-Update/obsidian-update.sh /home/user/scripts/obsidian-update
```

The scripts folder can be added to your `$PATH` variable, so you can run the script from anywhere. To do this, add the following line to your `.bashrc` file:
```bash
export PATH=/home/user/scripts:$PATH
```
**DO NOT FORGET TO ADD `$PATH` TO THE END. We don't want to break your cmdline!**  

Now you can simply run the script by typing `obsidian-update` in your terminal:
```bash
obsidian-update
```
