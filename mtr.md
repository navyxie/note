# Mac install mtr

当遇到错误 -bash: `mtr: command not found` 和 `mtr: unable to get raw sockets.` 时，请按照以下6个步骤安装mtr

1 brew install mtr
2 sudo vi ~/.bash_profile
3 add "alias mtr=/usr/local/sbin/mtr" to bash_profile
4 source ~/.bash_profile
5 sudo chown root mtr
6 sudo chmod u+s mtr 