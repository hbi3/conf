# Vagrant

## 初始化配置

### 修改 boxes 保存目录

Vagrant 的 boxes 默认是保存在 `VAGRANT_HOME` 目录下面， `VAGRANT_HOME` 默认值为 `~/.vagrant.d`。

通过修改 `VAGRANT_HOME` 来修改 boxes 保存目录

    mkdir -pv /path/to/vagrant/data
    cp -r ~/.vagrant.d /path/to/vagrant/data
    export VAGRANT_HOME=/path/to/vagrant/data/.vagrant.d
