CodeIgniter中文语言包
===================

用于[CodeIgniter](http://codeigniter.org/)框架的中文语言包，提供了框架内的系统语言的简体中文翻译。

## 安装方式 ##

在你的CI项目文件夹用命令行clone仓库：

    $ cd path/to/your/ci-project
    $ git clone https://github.com/mytharcher/CI-Chinese.git system/language/zh-CN

或者也可以使用git子模块来管理：

    $ cd path/to/your/ci-project
    $ git submodule add https://github.com/mytharcher/CI-Chinese.git system/language/zh-CN

然后在`applicaion/config/config.php`文件中找到：

    $config['language'] = 'english';

改成：

    $config['language'] = 'zh-CN'; // 这里大小写要与文件夹一致，否则Linux系统下会找不到报错。
