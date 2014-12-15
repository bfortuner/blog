#Blog
Personal blog using Jekyll and GitHub pages. Visit www.brendanfortuner.com

##Prerequisites
- sudo pip install nodeenv

##Create Workspace
- cd ~/workplace/blog
- nodeenv env
- . env/bin/activate
- npm install -g bower
- npm install -g grunt-cli

##Get App
- git clone https://github.com/bfortuner/blog.git
- cd blog/
- npm install

##Run App
- grunt serve

##Push Changes To GitHub
- grunt serve:dist
- grunt deploy

##Links
- https://github.com/robwierzbowski/generator-jekyllrb
