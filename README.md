# 生产效率

[TOC]

## 常用工具

### Server

0. [Dotfiles](https://github.com/sleepyblackcat/dotfiles) ：个人配置文件

      ```bash
      git clone https://github.com/sleepyblackcat/dotfiles.git
      ```

1. [Tmux](https://github.com/tmux/tmux) ：终端复用

   手册：[tmuxcheatsheet](https://tmuxcheatsheet.com/)

   ```bash
   sudo apt-get install tmux
   # install the Tmux Plugin Manager
   git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
   # copy config file 
   cp dotfiles/.tmux.conf ~/
   # open tmux
   # press Ctl-a I to install plugins
   # press Ctl-a R to resource the config
   ```

2. Vim ：文本编辑器

   Ref： [terminal 工作环境配置](https://www.jianshu.com/p/5396676ea6e9)

   手册：[vimcheatsheet](https://github.com/KevinsBobo/cheat-sheet/blob/master/VimCheatSheet-color.pdf)

   ```bash
   cp dotfiles/.vimrc ~/
   git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
   # you_complete_me 安装非常慢，耐心等
   vim +PluginInstall +qall
   ```

3. Tree ：树形目录查看

   ```bash
   sudo apt-get install tree
   ```

4. [Zsh](https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH) / [Oh My Zsh]()

     Zsh:

     ```bash
     sudo apt-get install zsh
     chsh -s $(which zsh)
     ```

     Oh My Zsh:

     ```bash
     sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
     ```

     Config:

     ```bash
     
     ```

5. [feh](https://feh.finalrewind.org/) / [ffmpeg](https://github.com/FFmpeg/FFmpeg) ：视频工具

     ```bash
     sudo apt-get install feh
     sudo apt-get install ffmpeg
     ```

6. [Rsync](https://rsync.samba.org/) ：同步文件夹

     ```bash
     sudo apt-get install rsync
     ```

     

### Mac

1. [ShadowsocksX-NG](https://github.com/shadowsocks/ShadowsocksX-NG) 

2. [SSHFS](https://github.com/libfuse/sshfs) ：远程挂载硬盘

   ```bash
   brew cask install osxfuse (?)
   brew install sshfs
   ```

3. [VSCode](https://code.visualstudio.com/) ：代码编辑器

4. [iTerm](https://www.iterm2.com/) ：终端

5. [XQuartz](https://www.xquartz.org/) ：Mac X server

6. [Alfred](https://www.alfredapp.com/) ：管家 (licence见邮件)

7. [Typora](https://typora.io/) ：Markdown编辑器

8. Magnet ：窗口快捷布局 ( App Store )

9. [MindMaster](http://www.edrawsoft.cn/mindmaster/) ：思维导图

10. Pages / Number ：Mac文档 ( App Store )

11. [Chrome](https://www.google.com/chrome/) ：浏览器 ( 需ss )

    - Vimium 插件

