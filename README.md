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
