# vimrc使用方法
## 安装插件管理

插件的用途就是可以很方便的管理 vim 的各种插件，快速安装配置以及清除。这里是介绍 vim-plug
```
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

## 配置插件

插件的配置也非常简单，只要将所有的插件配置在 call plug#begin('~/.vim/plugged') 和 call plug#end() 之间即可，常见的插件基本上都可以从 github 中找到

- 将vimrc文件内容复制到～/.vimrc中
- 然后输入 :w 保存配置，再输入 :PlugInstall安装插件

如下：
```
:w
:PlugInstall
```

## 插件删除
如果想要删除插件，只要将不需要的插件注释或者删除，执行 :PlugClean 就可以自动清理了

# tmux_config使用方法

## 安装tmux

```
sudo apt-get install tmux
```

## 配置tmux config

将tmux_config内容复制到～/.tmux.comf中
