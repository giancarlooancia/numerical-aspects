![Logo of the project](https://raw.githubusercontent.com/jehna/readme-best-practices/master/sample-logo.png)

# Numerical Aspects References
> Just a bunch of references. I use macOS 14.2 operative system, but many commands can be easily used in Linux with slightly changes. 

Here I collect useful guides to set up the working environment for the [Numerical Aspects course](https://github.com/paolofinelli)

## Table of Contents
- [Numerical Aspects References](#numerical-aspects-references)
  - [Table of Contents](#table-of-contents)
  - [Setting up the terminal with iTerm2](#setting-up-the-terminal-with-iterm2)
  - [Git and Github](#git-and-github)
    - [Useful guides](#useful-guides)
    - [Random References](#random-references)
    - [README.md file](#readmemd-file)
  - [C++](#c)
    - [Giaco](#giaco)
    - [Doctest](#doctest)
    - [Useful References](#useful-references)
  - [Python](#python)
    - [Anaconda](#anaconda)
    - [Spyder](#spyder)
    - [Useful Guides](#useful-guides-1)
    - [Useful References](#useful-references-1)
  - [Doxygen](#doxygen)

## Setting up the terminal with iTerm2

This is a non-necessary section to install and setup iTerm2 in macOS. There's no difference with the built-in terminal, but the graphics is more a more satisfactory.


Have a look at these links to install and configure iTerm 2:
- [Make Your MacOS Terminal Look Great](https://blog.protein.tech/make-your-macos-terminal-look-great-76dceb96607e)
- [Beautify your iTerm2 and prompt](https://medium.com/airfrance-klm/beautify-your-iterm2-and-prompt-40f148761a49)


If you mess something up with the `.zshrc` file, the following guide may be useful
- [How do I reset and put the zshrc file back to default?](https://stackoverflow.com/questions/45112197/how-do-i-reset-and-put-the-zshrc-file-back-to-default)

```shell
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```

```bash
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
```


To set up and understand what `zplug` is, first, install it with

```shell
brew install zplug
```

and then have a look at the documentation:
- [zplug documentation](https://github.com/zplug/zplug)



## Git and Github

### Useful guides
Have a look at the following repo, which collects many well-written guides concerning git:
- [Git Tutorials](https://gist.github.com/jaseemabid/1321592)

In particular, I'd suggest to start with the following PDF written by [Scott Chacon](https://github.com/schacon) and published by PeepCode. For a more in depth study, have a look at the Pro Git Book:
- [PeepCode Git Internals PDF](https://github.com/pluralsight/git-internals-pdf)
- [Pro Git Book](https://git-scm.com/book/en/v2)


### Random References
Here I'll collect some useful references about random stuff concerning Git:
- [Interactive Staging](https://git-scm.com/book/en/v2/Git-Tools-Interactive-Staging)
- [Git Rebase](https://www.simplilearn.com/what-is-git-rebase-command-article#:~:text=A%20Git%20rebase%20changes%20the,branch%20from%20a%20different%20commit)
- [Changing GitHub username](https://www.freecodecamp.org/news/a-quick-guide-to-changing-your-github-username/)


### README.md file
If you need a ready-to-copy-paste template for the `README.md` file for you repo, look at
-[Readme Best Practices](https://github.com/jehna/readme-best-practices)

If you use Visual Studio and you want to automatically generate the table of contents, download the plugin `Markdown All in One`:
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

## C++
This section is about `C++` language

### Giaco
Here the repo of `Programmazione per la fisica` course from UNIBO physics bachelor:
- [Configurazione dell'ambiente di lavoro su macOS](https://github.com/Programmazione-per-la-Fisica/howto/blob/main/other-OSes/macOSGuide.md)
- [Programmazione per la Fisica 2022/2023](https://github.com/Programmazione-per-la-Fisica/pf2022?tab=readme-ov-file)
- [Laboratori Programmazione per la Fisica 2022/2023](https://github.com/Programmazione-per-la-Fisica/labs2022)

### Doctest
To test the code one could use [Doctest](https://github.com/doctest/doctest), which can be included downloading its header:
- [Doctest Header](https://raw.githubusercontent.com/doctest/doctest/master/doctest/doctest.h)

```c++
#define DOCTEST_CONFIG_IMPLEMENT_WITH_MAIN

#include "doctest.h"

TEST_CASE("Testing the sum_n function") { }
```

### Useful References

## Python

```python
pass
```
as a placeholder

```python
isinstance(var, type)
```
to check `var` is of that particular `type`

### Anaconda

To install `anaconda`, [here](https://www.anaconda.com/download).

If, after the installation, the terminal shows `(base)` in front of the terminal prompt, it is due to Conda environment, see:
- [Why does "(base)" appear in front of my terminal prompt?](https://askubuntu.com/questions/1026383/why-does-base-appear-in-front-of-my-terminal-prompt)

You can hide it with

```shell
conda config --set changeps1 False
```

### Spyder
To easily write and compile python codes, let's use `spyder`, inside `anaconda`. The program itself gives a quick starting guide, based on these notes by [Hans Fangohr](https://fangohr.github.io)
- https://fangohr.github.io/blog/spyder-the-python-ide-spyder-23.html

Here, we collect some useful settings and commands.

```shell
%reset
```

### Useful Guides
### Useful References

## Doxygen
To install `doxygen`

```shell
brew install doxygen
```

If you don't like the icon of the program, have a look here:
- https://macosicons.com/#/u/ale.fdezsuarez
