# Nitrox-Setup-Script
A script to help automate setting up your Nitrox!

# Automatic
Install and run the script via a single command:
```sh
bash <(
  curl -fsSL https://raw.githubusercontent.com/SubnauticaNitrox/Linux-Setup-Script/refs/heads/master/nitroxsetup.sh 
)
```

# Manual
Manually install and run the script:
1. Copy paste [the script](https://raw.githubusercontent.com/SubnauticaNitrox/Linux-Setup-Script/refs/heads/master/nitroxsetup.sh ) into a new nitroxsetup.sh file.
2. `chmod +x nitroxsetup.sh` the script so it has executable permissions.
3. Run the script via `./nitroxsetup.sh` in your terminal.

# Script Arguments
Add arguments to your script in order to customise it:
```sh
Usage:
     nitroxsetup.sh [OPTIONS]

Options:
     -nitrox-path <path>
         Select the install location of Nitrox.
         Default: "$HOME/.Nitrox/"
     -dotnet-path <path>
         Select the install location of Dotnet.
         Default: "$HOME/.dotnet/"
         **NOTE:** If you execute this script **again** without this arg pointing to the new selected dotnet path, the script will not find it and it will install dotnet in the default path.
     --no-desktop
         Skip desktop shortcut creation.
     -h, --help
         Show this message.
```
