salt-pkgs
=============

该项目为[salt-formulas](http://git.dev.qianmi.com/tda/salt-formulas.git)项目的子项目。
仅用于存放组件的pkgs目录下的文件，这些文件基本都是从外网下载下来。
以tomcat目录为例：
tomcat
└── pkgs
    ├── apache-tomcat-7.0.54.tar.gz
    └── apache-tomcat-7.0.54.tar.gz.md5

- 文件apache-tomcat-7.0.54.tar.gz为安装需要的包。
- apache-tomcat-7.0.54.tar.gz对应的md5用于描述该包的md5值，用于检查该包完整性。
