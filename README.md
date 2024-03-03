![Logo of the project](https://raw.githubusercontent.com/jehna/readme-best-practices/master/sample-logo.png)

# Numerical Aspects References
> Just a bunch of references up to now. I use macOS 14.2 operative system, but many commands can be easily used in Linux with slightly changes. 

Here I collect useful guides to set up the working environment for the [Numerical Aspects course](https://github.com/paolofinelli)

## Table of Contents
- [Numerical Aspects References](#numerical-aspects-references)
  - [Table of Contents](#table-of-contents)
  - [Setting up the terminal with iTerm2](#setting-up-the-terminal-with-iterm2)
    - [References](#references)
    - [Problems and Improvements](#problems-and-improvements)
  - [Git and Github](#git-and-github)
    - [Useful guides](#useful-guides)
    - [Random References](#random-references)
    - [README.md file](#readmemd-file)
  - [C++](#c)
    - [Giaco](#giaco)
    - [Useful References](#useful-references)
  - [Python](#python)
    - [Anaconda and Spyder](#anaconda-and-spyder)
    - [Useful Guides](#useful-guides-1)
    - [Useful References](#useful-references-1)
  - [Doxygen](#doxygen)

## Setting up the terminal with iTerm2

This is a non-necessary section to install and setup iTerm2 in macOS. There's no difference with the built-in terminal, but the graphics is more a more satisfactory.

### References

Have a look at these links to install and configure iTerm 2:
- [Make Your MacOS Terminal Look Great](https://blog.protein.tech/make-your-macos-terminal-look-great-76dceb96607e)
- [Beautify your iTerm2 and prompt](https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49)


If you mess something up with the `.zshrc` file, the following guide may be useful
- [How do I reset and put the zshrc file back to default?](https://stackoverflow.com/questions/45112197/how-do-i-reset-and-put-the-zshrc-file-back-to-default)

```shell
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```


To set up and understand what `zplug` is, first, install it with

```shell
brew install zplug
```

and then have a look at the documentation:
- [zplug documentation](https://github.com/zplug/zplug)

### Problems and Improvements
If the terminal shows `(base)` in front of the terminal prompt, it is due to Conda environment, see:
- [Why does "(base)" appear in front of my terminal prompt?](https://askubuntu.com/questions/1026383/why-does-base-appear-in-front-of-my-terminal-prompt)

You can hide it with

```shell
conda config --set changeps1 False
```


## Git and Github

### Useful guides
### Random References
### README.md file

## C++ 

### Giaco
### Useful References

## Python

### Anaconda and Spyder

To install anaconda [here](https://www.anaconda.com/download). At the end of the installation procedure, it is asked to install `doxygen`.

### Useful Guides
### Useful References

## Doxygen
To install `doxygen`

```shell
brew install doxygen
```

If you don't like the icon of the program, have a look here:
- https://macosicons.com/#/u/ale.fdezsuarez