it`s my program launcher
OProg - OpenProgram
his home dir is ~/oprog
and config file is ~/ProProg/ProProg.bp
but you can modify the home path and config file path in ~/ProProg/ProProg.bp after #systemValues and you can add you programs in ~/ProProg/ProProg.bp after #ProgramsPaths
you can run it ProProg or using a sh file at ProProg/usr/local/bin/ProProg
after i will add a installer or some think like this

if you want to install this with apt you need to use
`bash echo "deb [trusted=yes] https://bersbot.github.io/OProg/repo stable main" | sudo tee /etc/apt/sources.list.d/oprog.list`\
for update a rep
and then you can use
`bash sudo apt install proprog`
