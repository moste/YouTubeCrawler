**本工具需要 Linux 环境，有 SSR 代理，且安装了 youtube-dl 和 ffmpeg**

最近将代码结构根据**命令模式**完全改写了，`interface`中定义了所有接口，`Task`接口是命令接口。

## 使用方法

在`config`文件中设置工作目录，工作目录中可以有若干文件夹，
文件夹中需要有个明教`url`的文本文件。程序会识别名称为`url`的文件，
读取其中的 url 作为视频链接，自动下载视频和英文字幕并使用`ffmpeg`工具将字幕和视频合并，
产出一个`mp4`格式的视频文件，名称是当前文件夹的名称。

`main`函数中可以设置并发的最大 goroutine。

<a href="https://www.upsuperdeals.com/posts/Kids-Lunch-Box.html">Kids Lunch Box</a>

<a href="https://www.hongquekol.com/blog/archives/wang-hong-ying-xiao-kol-ying-xiao-2022-nian-ru-he-zuo-hao-wang-hong-ying-xiao--wang-hong-ying-xiao-ping-tai-tui-jian">网红营销</a>
