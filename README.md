# Nitrox-Setup-Script
A script to help automate setting up your Nitrox!

# Automatic
Install and run the script via a single command:
```
bash <(
  curl -fsSL "$(
    curl -fsSL https://api.github.com/repos/SubnauticaNitrox/Linux-Setup-Script/releases/latest \
    | grep 'browser_download_url.*\.sh' \
    | cut -d '"' -f 4 \
    | head -n 1
  )"
)
```

# Manual
Manually install and run the script:
1. Download the latest script from the Release tab.
2. `chmod +x nitroxsetup.x.x.x.x.x.sh` the script so it has executable permissions.
3. Run the script via `./nitroxsetup.x.x.x.x.x.sh` in your terminal.
