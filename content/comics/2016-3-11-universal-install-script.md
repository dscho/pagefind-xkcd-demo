---
date: 2016-03-11
title: "Universal Install Script"
num: 1654
alt: >-
  The failures usually don't hurt anything, and if it installs several versions, it increases the chance that one of them is right. (Note: The 'yes' command and '2>/dev/null' are recommended additions.)
img: https://imgs.xkcd.com/comics/universal_install_script.png
---
[In the panel is a shell script which, unusual for xkcd, uses only lower case. At the top the title of the program is inlaid in the frame, which has been broken here.]

<big>Install.sh</big>

#!/bin/bash

pip install "$1" &

easy\_install "$1" &

brew install "$1" &

npm install "$1" &

yum install "$1" & dnf install "$1" &

docker run "$1" &

pkg install "$1" &

apt-get install "$1" &

sudo apt-get install "$1" &

steamcmd +app\_update "$1" validate &

git clone https://github.com/"$1"/"$1" &

cd "$1";./configure;make;make install &

curl "$1" | bash &