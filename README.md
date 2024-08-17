# pdup - PixelDrain File Uploader

`pdup` is a convenient Bash script for uploading files to [PixelDrain](https://pixeldrain.com/) directly from the terminal. This script simplifies sharing log files with developers or making quick backups of remote files via SSH.

This Script uploads files directly to our PixelDrain account through API key .So, we can get our files anytime from [here](https://pixeldrain.com/user/filemanager#files)

## Installation

To install `pdup`, run the following commands:

```
sudo wget https://raw.githubusercontent.com/Saikrishna1504/PixelDrain_Upload/main/pdup -O "/usr/local/bin/pdup"
sudo chmod +x "/usr/local/bin/pdup"
```

## Configuration

1) Obtain Your API Key: [Here](https://pixeldrain.com/user/api_keys)
2) Edit the Script: ``` sudo nano /usr/local/bin/pdup ```
 replace your_api_key_here with yout original Api key
3) Save the file and exit the editor (press CTRL+S, then X, and Enter).

## Usage

To upload a file, use the following command:
```
pdup /path/to/your/file
```

If you want to uninstall pdup you can run

```
sudo rm "/usr/local/bin/pdup"
```

Be careful for typos! You don't want to accidentally remove your [/usr](https://github.com/MrMEEE/bumblebee-Old-and-abbandoned/issues/123) ;)

## Note
1) You need root access to your system.
2) You need to generate your own API key.
3) You also need to insatll jq package : ```sudo apt install jq```

This Script Inspired From [Fornax96](https://github.com/Fornax96/pdup)
