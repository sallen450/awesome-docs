## shell

1. 打开 shell 窗口
```bash
# vim 中打开 shell
$ :shell

# 回到 vim 中
$ exit
```

2. 执行单条 shell 命令

```bash
:! {command}
:w !{command}   # 将命令执行结果写入光标所在处
```

3. 全局搜索关键字

```bash
:vim /pattern/gj folder/** | copen
```

4. 关闭 buffer (qpkorr/vim-bufkill )
```bash
:BD
```

## 选择
1. 多光标
> 需要安装 vim-multiple-cursors
```bash
# visual mode 选择多行，然后
<C-n>
```

## 参考
* http://ikuduku.com/blog/find-text-in-project-within-vim
