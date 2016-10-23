## 安装nginx & Installing nginx

nginx可被差异化的安装，依赖于处于的操作系统环境。

> nginx can be installed differently, depending on the operating system.

#### Linux上的安装 & Installation on Linux

对于Linux，可以使用官网的nginx工具包。

> For Linux, nginx [packages](http://nginx.org/en/linux_packages.html) from nginx.org can be used.

#### FreeBSD上的安装 & Installation on FreeBSD

在FreeBSD上，nginx可以从工具包被安装或者通过系统端口。系统端口提供较大的灵活性，允许选择在一个大范围的选项之间。

端口方式使用指定的选项编译nginx然后安装它。

> On FreeBSD, nginx can be installed either from the [packages](http://www.freebsd.org/doc/handbook/pkgng-intro.html) or through the [ports](http://www.freebsd.org/doc/handbook/ports-using.html) system. The ports system provides greater flexibility, allowing selection among a wide range of options. The port will compile nginx with the specified options and install it.

#### 从资源构建 & Building from Sources

如果需要一些指定的功能，使用工具包或者端口是无效的，nginx也可以通过资源文件被编译。当灵活性更大时，这种方式可能对于新手来说比较复杂。获得更多信息，参见[使用资源构建nginx。](http://nginx.org/en/docs/configure.html)

> If some special functionality is required, not available with packages and ports, nginx can also be compiled from source files. While more flexible, this approach may be complex for a beginner. For more information, see [Building nginx from Sources](http://nginx.org/en/docs/configure.html).

