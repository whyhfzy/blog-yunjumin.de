上一次写了一篇利用cloudflare的R2搭配obsidian自己的S3 Image Uploader插件给obsidian搭建图床的超级简单零成本方案！[[打造笔记神器Obsidian 的“零成本”丝滑图床：Cloudflare R2 完美方案]]

但该方案有点美中不足，就是无法对这些图片进行有效管理。也无法对图片进行压缩等操作。

今天不上一个更优方案：利用Piclist平台对图床图片进行批量管理。
- 图片管理功能(可以查看、删除已上传的图片)
- 图片压缩(有损/无损)
- 格式转换(转 WebP 等)
- 添加水印


这里需要用到第三方软件Piclist。我们先下载Piclist！[https://github.com/Kuingsmile/PicList/releases]()按你自己的设备和系统去下载！

Cloudflare里面R2的设置还是延用之前的教程[[打造笔记神器Obsidian 的“零成本”丝滑图床：Cloudflare R2 完美方案]]不用更改。

打开Piclist。点击左侧“图床”，选中AWS S3！



按照我们保存好的信息如下图一一对应来填写：![image|0](https://img.nitama.de/obsidian/2026/03/0556f8e48e5b72ddee9683b5eca1494a.jpg











