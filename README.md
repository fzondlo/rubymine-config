# rubymine

    git clone https://github.com/fzondlo/rubymine-config.git ~/rubymine-config
    ln -s ~/rubymine-config/ideavimrc ~/.ideavimrc
    
Install acejump and ideavim plugins

Download the latest karabiner : https://pqrs.org/osx/karabiner/

    rm ~/Library/Application\ Support/Karabiner/private.xml
    ln -s ~/rubymine-config/karabiner/private.xml ~/Library/Application\ Support/Karabiner/private.xml

Open Karabiner, click the reload XML button, and check the top 3 Disable Logout, Disable Cmd H, Disable force logout

Last step, open ruby mine and do File, Import Settings, and select `~/rubymine-config/settings.jar`

All done!

Some short cuts:
https://paper.dropbox.com/doc/Rubymine-otezCbxN5TQeG0aHpDo5C
