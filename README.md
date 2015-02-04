<<<<<<< HEAD
# Kasper

This is a port of Ghost's default theme [Casper](https://github.com/tryghost/casper) for Jekyll. 
Feel free to fork, change, modify and re-use it.

## How to use it

Simply clone this repository, and then run `jekyll serve` inside the directory.

Kasper theme includes:

* Pagination
* Rss
* Google Analytics Tracking code
* Code Syntax Highlight
* Author's profile with picture
* Disqus comments

## Screenshots

![index page](https://raw.github.com/rosario/kasper/master/assets/images/kasper-theme-index.png)
![post page](https://raw.github.com/rosario/kasper/master/assets/images/kasper-theme-post.png)


## Thanks 
Most of the work has been already done by the Ghost team, I've just ported Casper to Jekyll. 
I've also added few things specific to Jekyll and some minor style changes.

## Copyright & License

Copyright (C) 2013 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
=======
# 安装Ruby环境和DevKit

直接到[rubyInstaller](http://rubyinstaller.org/downloads/) 官网下载，目前最新的版本分别是 Ruby 2.1.4-p247 (x64) 和 DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe ，我的系统是64位，32位的话选择对应版本， 先安装Ruby环境，注意，必须先安装Ruby环境，为免混乱，可以解压至 C:\Ruby ,ruby安装成功之后安装DevKit，同样解压至 C:\DevKit 。

## 配置

a.打开CMD，运行以下命令：

```
cd C:\DevKit

ruby dk.rb init

ruby dk.rb install
```

b.完成之后安装jekyll：

```
gem install jekyll
```

可以用 jekyll --version 来检查是否安装成功

c.安装rdiscount，这个是用来解析Markdown标记的解析包。

```
gem install rdiscount
```
##运行

cd 到工程目录，目前网上大部分教程说的启动服务命令 jekyll --serve 都已过时，正确的应该是：
```
jekyll serve
```

#Jekyll主题
本次使用的是Kasper主题
>>>>>>> gh-pages
