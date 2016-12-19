# babun-agnoster
This is my install and config for Babun on Windows
with oh-my-zsh and Agnoster theme.

## Installation
1. Create Windows environment variable "HOME" with value "C:\Users\\\<your-username\>"
2. Copy .babunrc, .minttyrc and .zshrc to your User home (same as in (1)).
3. Set DEFAULT_USER in .zshrc to your username
4. Install the Powerline fonts provided with this package

   Alternative:
   Put the fonts somewhere for permanent storage and _after_ Babun installation (see (5)) run following command from Windows cmd:
   <babun-install-directory>\fonts\RegisterFont.exe add "<path-to-powerline-fonts>\DejaVu Sans Mono for Powerline.ttf"
5. Install Babun from babun.github.io (ignore the "HOME variable set" warning and install anyway)

## Screenshot
![Screenshot](https://github.com/Koelli91/babun-agnoster/raw/master/screenshot.png "Screenshot of Babun with Agnoster theme")

## Credits
- [Babun](https://babun.github.io/)
- [mavnn/mintty-colors-solarized](https://github.com/mavnn/mintty-colors-solarized)
- [Take control of your console in Windows with Babun, Oh-My-ZSH, and Powerline Fonts](https://www.sorendam.com/take-control-of-your-console-in-windows-with-babun-oh-my-zsh-and-powerline-fonts/) (by Soren Dam)
- [Oh-My-ZSH Agnoster Theme Windows](https://blog.nevercodealone.de/oh-my-zsh-agnoster-theme-windows/) (by Sandra Parsick on NeverCodeAlone)