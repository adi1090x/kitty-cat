<!-- Links -->
[bmac]: https://www.buymeacoffee.com/adi1090x
[ko-fi]: https://ko-fi.com/adi1090x
[paypal]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U3VK2SSVQWAPN
[patreon]: https://www.patreon.com/adi1090x

# 😺 Kitty Cat

<p align="left">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/adi1090x/kitty-cat?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/adi1090x/kitty-cat?style=for-the-badge">
  <img src="https://img.shields.io/github/forks/adi1090x/kitty-cat?color=teal&style=for-the-badge">
  <img src="https://img.shields.io/github/issues/adi1090x/kitty-cat?color=violet&style=for-the-badge">
</p>

Simple script to change color-schemes and fonts for [kitty](https://github.com/kovidgoyal/kitty) terminal.

![gif](images/main.gif) <br />

### How to install

Follow the steps below - 

```bash
# go to home dir - 
cd $HOME

# clone this repository - 
git clone https://github.com/adi1090x/kitty-cat

# change to kitty-cat dir -
cd kitty-cat

# to install it, run -
./install

# And Follow the steps, it'll be installed on your system.
```

### Run

Run `kitty-cat` & select the right option -

```bash
$ kitty-cat

    /\___/\ 			         
    \ -.- /  ┃ ┃┛━┏┛━┏┛┃ ┃  ┏━┛┏━┃━┏┛  
    '-.^.-'  ┏┛ ┃ ┃  ┃ ━┏┛  ┃  ┏━┃ ┃   
      /'\    ┛ ┛┛ ┛  ┛  ┛   ━━┛┛ ┛ ┛   

    [*] By- Aditya Shakya // adi1090x

    [C] Colors (240)
    [F] Fonts (27)
    [R] Random
    [I] Import
    [A] About
    [Q] Quit
    
    [Select Option]: 
```

### Features

+ 240+ popular color-schemes.
+ 25+ powerline patched fonts.
+ Randomly change color-schemes.
+ Import color-schemes from *local file* and *file URL*.
+ Use `remote api` to set colors in place.

### Use Import
```bash
    [Select Option]: i

    [L] Local File (Enter path to file)
    [I] Internet File (Enter File URL)

    [Select Option]: I

    [Enter Color-scheme URL]: https://raw.githubusercontent.com/dexpota/kitty-themes/master/themes/Batman.conf

    [*] Reloading Settings...
    [*] Applied Successfully.
```

+ To import *local file*, enter the full path (ie - `/home/aditya/dracula.conf`) of the color-scheme.
+ To import *web file*, enter the file url (ie - `https://raw.githubusercontent.com/dexpota/kitty-themes/master/themes/Batman.conf`) of the color-scheme.
<br />

|Sample - Colorschemes|Sample - Fonts|
|--|--|
|![img](images/colors.gif)|![img](images/fonts.gif)|

### FYI
+ Kitty does not support bitmap fonts, i've only got `terminus (ttf)` font work in it.
+ You've to restart kitty to set the new fonts, as there's no way to set fonts using `kitty remote api`.
+ Again... If you can improve it, sure...
+ Have fun!
