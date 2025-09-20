it`s my program launcher
his home dir is ~/proprog
and config file is ~/ProProg/ProProg.bp
but you can modify the home path and config file path in ~/ProProg/ProProg.bp after #systemValues and you can add you programs in ~/ProProg/ProProg.bp after #ProgramsPaths
you can run it ProProg or using a sh file at ProProg/usr/local/bin/ProProg
after i will add a installer or some think like this

if you want to install this package you need to write
this -> echo "deb [trusted=yes] https://bersbot.github.io/ProProg/repo stable main" | sudo tee /etc/apt/sources.list.d/proprog.list
and for instaling or remove you can use "proprog"
!NOW ITS WORKING ONLY IN DEBIAN-BASED LINUX
