Bojan's dotfiles
===============

Installation
-------------------

    $ git clone https://gitlab.com/rbojan/dotfiles.git ~/.dotfiles
	
	$ echo '# Dotfiles' >> ~/.bashrc
	$ echo 'for f in `find ~/.dotfiles/ -mindepth 2 -not -path "*/.git/*" -type f`; do source $f; done' >> ~/.bashrc
	
Update
-------------------

    $ cd ~/.dotfiles && git pull origin master
