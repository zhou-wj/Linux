[重点：文件与目录管理](http://www.runoob.com/linux/linux-file-content-manage.html)

# 目录处理的常见命令

- **ls**
> 列出目录  
> -a ：全部的文件，连同隐藏档( 开头为 . 的文件) 一起列出来(常用)  
> -d ：仅列出目录本身，而不是列出目录内的文件数据(常用)  
> -l ：长数据串列出，包含文件的属性与权限等等数据(常用)  




- cd
> 切换目录  
- pwd
> 显示目前的目录  
- mkdir
> 创建一个新的目录  
>
> -p ：帮助你直接将所需要的目录(包含上一级目录)递归创建起来！（常用）


- cp
> 复制文件或目录  
- mv
> 移动文件与目录，或修改名称



- rmdir
>   删除一个空的目录  
- rm
> 移除文件或目录  



# Linux文件内容查看

- cat  由第一行开始显示文件内容
- tac  从最后一行开始显示，可以看出 tac 是 cat 的倒著写！
- nl   显示的时候，顺道输出行号！
- more 一页一页的显示文件内容
- less 与 more 类似，但是比 more 更好的是，他可以往前翻页！
- head 只看头几行
- tail 只看尾巴几行



# 远程文件传输

- [scp命令](http://blog.csdn.net/liangxanhai/article/details/8069781)


