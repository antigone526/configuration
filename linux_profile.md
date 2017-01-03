```bash
#below is the customized profile by Kevin She
export PS1="[\u@`/sbin/ifconfig eth0|grep 'inet '|sed 's/^.*inet addr:/MFDataServer_/g'|sed 's/ Bcast.*//g'`\W]\\$"
#source /opt/rh/devtoolset-3/enable
#source /opt/rh/python27/enable
echo "did you know that:"; whatis $(ls /bin | shuf -n 1i)
alias la='ls -al'
alias sudo='sudo '  #using aliases expansion, otherwishe sudo ignores your aliases
alias su='su -'
alias mygit='cd /home/kevin/moldflow/gitbase/pythonrepo/'
alias less='less -N'
alias gitserver='cd /home/git/work/pythonrepo.git/'
alias cman='man -M /usr/local/kevin/share/man/zh_CN'
export PATH="/home/kevin/personalcommands:/home/kevin/pycharm-community-4.0.4/bin/:/sbin:$PATH"
alias grep='grep --color'
#mount -o loop /home/kevin/rh7.iso /mnt/iso
export TERM=xterm-256color
umask 022
mount 10.148.210.184:/home/kevin/moldflow /kevindata/shechuanfu
```
