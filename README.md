Deven
=====

DEVEN is script to set up my *dev*elopment *en*vironment on OS X

This project is heavily influenced by the work done on thoughtbot's laptop project. You can find more information on this project [here](https://github.com/thoughtbot/laptop).

Requirements
------------

1) Install a C compiler.

Use [OS X GCC Installer](https://github.com/kennethreitz/osx-gcc-installer/) for
Snow Leopard (OS X 10.6).

Use [Command Line Tools for XCode](https://developer.apple.com/downloads/index.action)
for Lion (OS X 10.7) or Mountain Lion (OS X 10.8).

2) Run the install command below.

Install
-------

Read and then run the script

    zsh <(curl -s https://raw.github.com/tschmidt/deven/master/build)

What is sets up
---------------

* Homebrew for managing operating system libraries on OS X
* ImageMagick for cropping and resizing images
* PostgreSQL for storing relational data
* QT for headless JavaScript testing via Capybara Webkit
* rbenv for managing versions of the Ruby programming language
* Ruby Build for installing different Rubies
* The Silver Searcher for finding things in files

Credits
-------

Deven is maintained by [Terry Schmidt](http://schmidt-happens.com).

Special thanks to [thoughtbot, inc](http://thoughtbot.com/) for inspiring this project with [laptop](https://github.com/thoughtbot/laptop).