CodeIgniter中文语言包
===================

用于[CodeIgniter](http://codeigniter.org/)框架的中文语言包，提供了框架内的系统语言的简体中文翻译。

> 更新:支持 CodeIgniter3.0，并兼容之前版本

## 安装方式 ##

在你的CI项目文件夹用命令行clone仓库：

    $ cd path/to/your/ci-project
    $ git clone https://github.com/mytharcher/CI-Chinese.git application/language/chinese_s

或者也可以使用git子模块来管理：

    $ cd path/to/your/ci-project
    $ git submodule add https://github.com/mytharcher/CI-Chinese.git application/language/chinese_s

然后在`applicaion/config/config.php`文件中找到：

    $config['language'] = 'english';

改成：

    $config['language'] = 'chinese_s'; // 这里大小写要与文件夹一致，否则Linux系统下会找不到报错。
