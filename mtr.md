# Mac install mtr

**当遇到错误 -bash: `mtr: command not found` 和 `mtr: unable to get raw sockets.` 时，请按照以下6个步骤安装mtr**

- brew install mtr
- sudo vi ~/.bash_profile
- add "alias mtr=/usr/local/sbin/mtr" to bash_profile
- source ~/.bash_profile
- sudo chown root mtr
- sudo chmod u+s mtr 
