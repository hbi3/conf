# Pipenv

## 安装

Pipenv 安装见 [Installation](https://github.com/pypa/pipenv#installation)

安装 virtualenv-autodetect 以自动识别虚拟环境，安装见 [Installation](https://github.com/RobertDeRose/virtualenv-autodetect#installation)

## 配置

配置 `~/.zshrc` 或 `~/.bashrc`

    export PIPENV_VENV_IN_PROJECT=1
    source /path/to/virtualenv-autodetect.sh

配置后，会在 project 目录下创建一个 `.venv` 目录，存储虚拟环境信息

