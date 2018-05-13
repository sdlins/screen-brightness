# Bright
Increases or decreases the screen brightness


## How to config
1. Download or clone this repo;
2. Exec `chmod +x bright`;
3. Move `bright` to your path: `sudo mv path/to/bright /usr/local/bin`

**IMPORTANT!**
You must execute `sudo chmod u+w /sys/class/backlight/intel_backlight/brightness` to set write permission. It is necessary so that this script to be able to work without ask sudo password everytime.


## How to use
- `bright up` will increase the screen brightness 5%.
- `bright down` will decrease the screen brightness 5%.


### NOTES
- *This was tested only for my personal needs (Ubuntu 18.04) since my new wireless keyboard has no function keys to control brightness. With this script, I was able to set new shortcuts to increase and decrease it.*
- *This script changes `/sys/class/backlight/intel_backlight` only. If you need to change `dell_backlight` or something else maybe you could adapt this.*
