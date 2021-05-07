# Git

## Git 全局配置

设置用户信息

    git config --global user.name your_name
    git config --global user.email your_email

设置 Alias

    git config --global alias.ch checkout
    git config --global alias.co commit
    git config --global alias.st status
    git config --global alias.br branch
    git config --global alias.hist "log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short"

设置 includIf 从其他文件中读取配置

    git config --global includeIf."gitdir:**/company/**".path ~/.gitconfig.company
