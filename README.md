# ToucheggKDE (meaw's version)
My TouchEgg configuration for Touchpad Gestures like Windows for KDE Plasma.

## Installation
[Install touchegg first if you haven't already](https://github.com/JoseExposito/touchegg)   
```shell
git clone https://github.com/meawto/ToucheggKDE.git
cd Touchegg*
mkdir ~/.config/touchegg
cp touch* ~/.config/touchegg/
```
**That's it!**

## Usage
### Swipe Gestures:
  - **3** Fingers LEFT/RIGHT: **Move back or forward**   

  - **4** Fingers UP/DOWN: **Control System Volume**

  - **4** Fingers LEFT/RIGHT: **Next track or previous track** 

### [More gestures](https://github.com/NayamAmarshe/ToucheggKDE)

## Troubleshoot
If you're using OpenSUSE or other distros which don't have the `qdbus` package,
do this:
```shell
nano ~/.bashrc
````
Then at the end of the file, add: `alias qdbus=”qdbus-qt5”`   
Exit with Ctrl+O, Enter then Ctrl+X..
Then
```shell
source ~/.bashrc
```