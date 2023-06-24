# findr
*Recursively search files.*
<br>
<br>
<br>

<h4 align="center">Search for a match in the contents of files.</h4>
<p align="center">  
  <img width="600" src="https://i.imgur.com/bku2Ad0.png">
</p>
<br>

<h4 align="center">Search for a match in the file names.</h4>
<p align="center">  
  <img width="600" src="https://i.imgur.com/vgWI2QP.png">
</p>
<br>

## Installation
The following commands will download the latest version of findr from this repository 
and install it in your `/usr/bin/` directory:
```
git clone https://github.com/Julynx/findr /tmp/findr
sudo chmod +x /tmp/findr/findr
sudo cp /tmp/findr/findr /usr/bin/findr
```
The program can now be ran from a terminal with the command `findr`.

<br>

## Usage
```
  Usage: findr [key] [flags]
  Flags:
  --mode=contents|filenames
  --max-depth=999
```

<br>

## Uninstalling
To uninstall [findr](https://github.com/julynx/findr), delete the executable using the command:
```
sudo rm /usr/bin/findr
```
