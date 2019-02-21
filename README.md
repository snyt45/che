# che
Call your multiple cheat sheets from the command line anytime and anywhere to become a cheetah.

![cheetah](https://user-images.githubusercontent.com/18102695/53196507-97e80580-365b-11e9-90a5-2f53fb07f882.jpg)

## Why che?
Why `cheetah`? Too long

`cheeta` is still long

`cheet` easy to understand, but still long

`chee` long

`che` It is just right for me

## Description
A shell script that invokes a list of multiple text files and opens in vim.

Three functions of opening, adding, and deleting cheat sheets (. Txt) on the command line are easy to use.

## Demo
![che](https://user-images.githubusercontent.com/18102695/53206581-ad1d5e00-3674-11e9-9be4-89fb7a581fb4.gif)

## Usage
che is executed from the command line.

`che` Select the cheat sheet and open it.

`che add` I will create a new cheat sheet.

`che delete` Select the cheat sheet and delete it.

The cheat sheet is just a text file, let's create your own cheat sheet.

## Directory Structures
~/<br>
└ dotfiles/ # User configuration file<br>
　　└ cheatsheets/ # Cheat sheet list 

## Install

### Preparation

Things necessary:
* Directory ⇒ Please make a directory referring to Directory Structures.

Shell script place:
* `che` is a shell script, either pass a new path or move to an existing shell script storage place.

### Installation method
```
$ git clone https://github.com/snyt45/che.git
```

## Licence

[MIT](https://github.com/snyt45/che/blob/master/LICENSE)

## Author

[Yuta Sano](https://github.com/snyt45)

## inspire

[mattn/cho](https://github.com/mattn/cho)
