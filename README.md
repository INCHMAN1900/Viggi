# Viggi

一个将视频转换为GIF图片的工具.
a small tool to convert video files into gif images.

这个仓库只是用来放release的地方，并不会上传代码。我写这个只是为了熟悉一下 `Xamarin.Mac` 和 `C#`。如果你在使用中发现什么问题，可以提issue，我尽可能解决。

### 体积问题

因为直接打包了 `ffmpeg` 二进制文件，所以体积比较大，这块儿暂时不打算优化，后续有时间可能做选项：由使用者提供 `ffmpeg` 路径供app调用。
