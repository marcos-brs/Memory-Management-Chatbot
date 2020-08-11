<h1 align="center">Welcome to Memory Managment Chatbot 👋</h1>
<p>
  <a href="LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/mbrsantana" target="_blank">
    <img alt="Twitter: mbrsantana" src="https://img.shields.io/twitter/follow/mbrsantana.svg?style=social" />
  </a>
</p>

> A chatbot made in C ++ and wxWidgets that talks about Memory Management.

![](.github/chatbot_demo.gif)

The ChatBot code creates a dialogue where users can ask questions about some aspects of memory management in C++. After the knowledge base of the chatbot has been loaded from a text file, a knowledge graph representation is created in computer memory, where chatbot answers represent the graph nodes and user queries represent the graph edges. After a user query has been sent to the chatbot, the Levenshtein distance is used to identify the most probable answer.

## Dependencies for Running Locally
* cmake >= 3.11
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
* wxWidgets >= 3.0
  * Linux: `sudo apt-get install libwxgtk3.0-dev libwxgtk3.0-0v5-dbg`
  * Mac: There is a [homebrew installation available](https://formulae.brew.sh/formula/wxmac).
  * Installation instructions can be found [here](https://wiki.wxwidgets.org/Install). Some version numbers may need to be changed in instructions to install v3.0 or greater.

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory in the top level directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./membot`.


## Author

👤 **Marcos Santana**

* Twitter: [@mbrsantana](https://twitter.com/mbrsantana)
* Github: [@zerocoolbr](https://github.com/zerocoolbr)
* LinkedIn: [@marcosbrs](https://linkedin.com/in/marcosbrs)

## Show your support

Give a ⭐️ if this project helped you!

## 📝 License

Copyright © 2020 [Marcos Santana](https://github.com/zerocoolbr).<br />
This project is [MIT](LICENSE) licensed.