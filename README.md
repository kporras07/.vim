Installation:

    git clone git://github.com/nelstrom/dotvim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update

PHP CodeSniffer Instructions

    composer global require drupal/coder:\>7
     ~/.composer/vendor/bin/phpcs --standard=/home/kevin/.composer/vendor/drupal/coder/coder_sniffer/Drupal /path/to/example.module
    pear install PHP_CodeSniffer
    sudo cp -r ~/Drupal/ /usr/share/pear/PHP/CodeSniffer/Standards/  ó carpeta Drupal de http://ftp.drupal.org/files/projects/drupalcs-7.x-1.x-dev.tar.gz

