# 推荐使用on-my-tmux

```
$ git clone https://github.com/gpakosz/.tmux.git
$ ln -s -f .tmux/.tmux.conf
$ cp .tmux/.tmux.conf.local .
```

然后在`.tmux.conf.local`末添加

```
unbind %
bind | splitw -h

bind -r p previous-window
bind -r n next-window
```
