## MintConfig
First I want to explain, why I choose this Distro/Desktop and why it might be just the Linux Distro for you.
For my Desktop-PC, i wanted a stable Distrobution (I use Arch btw on my Laptop), which is why i settled for Linux Mint (also Cinnamon 
is just such a comfortable experience).

Now, in the following lines i will explain, how i made my Desktop look, how it looks (xD).



![Alt text](https://github.com/w8ste/screenshotsMint/blob/main/rofi.png)

# Preconditions 
To start things off i recommend, that you update your system:
```
  sudo apt-get update && sudo apt-get upgrade
```
Afterward you have to install the following packages:
```
  sudo apt install rofi exa arc-theme git 
```
- Create a new Folder in your home Directory called mint_conig and clone this repo (you can copy the following in case you have
  ssh configured with github:
```
  mkdir mint_config && cd mint_config && git clone git@github.com:w8ste/screenshotsMint.git
```
- [nitch (fetching tool)](https://github.com/ssleert/nitch)

# Theme Desktop 
First go into your System Setting -> Themes, apply the following changes:
| Setting  | apply: |
| ------------- | ------------- |
| Mouse Pointer  | breeze_cursors  |
| Applications  | Arc-Dark  |
| Icons  | Papirus-Dark  |
| Desktop  | Arc  |

- !["Wallpaper"]("https://github.com/catppuccin/wallpapers/blob/main/minimalistic/dark-cat.png")

![Alt text](https://github.com/w8ste/screenshotsMint/blob/main/Screenshot%20from%202023-03-20%2021-11-34.png)

# Theme Terminal 
In order to theme for the terminal you need to install the "catpuccin mocha" via the 
following repo:
- ![Gogh](https://github.com/Gogh-Co/Gogh)
- Afterwards (from your home directory) override your .bashrc file with mine (i recommend to back up your's first like so):
 ```
 cp .bashrc mint_config
```
- Now that you have a copy in mint_config, run the following code:
 ```
 'cp' ~/mint_config/.bashrc .bashrc
```
  
# Rofi 
- Just replace configuration code from your rofi config (~/.config/rofi) with the configuration code in my configRofi.rasi.
- Choose to Dark Blue Theme via the rofi-theme-selector

# Bar 
Attention: If you complete this step, you will not be able to open application via the taskbar.
I recommend to set a keybinding for rofi / look at the appendix.
- Enter "Panel Edit Mode"
- Move the bar to the top 
- Remove all the Applets
- Add the following Applets: 
  - Left Side: Workspace Switcher
  - Middle: Calander
  - Right side (from left to right):
    - Window list
    - Separator
    - Favorites
    - Sound
    - Printers
    - Power Manager
    - Corner Bar
    
![Alt text](https://github.com/w8ste/screenshotsMint/blob/main/lvim.png)

# Appendix 
- For new to linux users, i recommend the following guide by DistroTube: ![DT](https://www.youtube.com/watch?v=TKX29fJ8U2Y)
- https://www.youtube.com/watch?v=TKX29fJ8U2Y
- I also want to thank everyone who contributes to the software i used for this config ^^
 
    
