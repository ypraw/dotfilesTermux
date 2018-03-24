# Termux Dotfiles Configuration

## Introduce
Termux is an android terminal emulator and
Linux environtment app for android.
available on [google play store](https://play.google.com/store/apps/details?id=com.termux) or [f-droid](https://f-droid.org/repository/browse/?fdid=com.termux).
For detail information [TERMUX](https://github.com/termux/termux-app)

![ss](/screenshoot/photo.jpg)
## Setup 
I used termux with some custom package and configuration.


> **__Note : you must install termux-style before add zsh and neofetch if not, icon possibilty will not appear__**

* termux-api
    ```bash
    pkg install termux-api
    ```

* Python
    ```bash
    pkg install python
    ```

* clang
    ```bash
    pkg install clang
    ```

* make
    ```bash
    pkg install make
    ```
* git
    ```bash
    pkg install git
    ```
 * curl
    ```bash
    pkg install curl
    ```

* ruby
    ```bash
    pkg install ruby ruby-dev
    ```

* coreutils, ncurses-utils, openssh    
    ```bash
    pkg install coreutils ncurses-utils openssh
    ```

* vim [1]
    ```bash
    pkg install vim && git clone --depth=1 https://github.com/amix/vimrc.git ~/.vim_runtime && sh ~/.vim_runtime/install_awesome_vimrc.sh 
    ```

* oh-my-termux and zsh [2]
    ```bash
    bash -c "$(curl -fsSL https://git.io/oh-my-termux)" 
    ```
* neofetch
    ```bash
    pkg install neofetch
    ```
* youtube-dl (required python)
    ```python
    pip install youtube-dl
    ```
* ffmpeg
    ```bash
    pkg install ffmpeg
    ```

## Config dotfiles
in the fact, i just copy-paste my .zshrc on linux dekstop conf to my termux XD, you can find [here](https://github.com/ypraw/myDotfiles//tree/master/zsh)

##  References
1. [https://github.com/amix/vimrc](https://github.com/amix/vimrc)
2. [https://github.com/4679/oh-my-termux](https://github.com/4679/oh-my-termux)

## Screenshoot

* cpp program
    ![ssc](/screenshoot/c.png)
* flask program
    ![ssflask](/screenshoot/flask.png)
* django program
    ![ssdjango](/screenshoot/django.png)

## Lisence
Source is available under the [MIT LICENSE](LICENSE.md)
