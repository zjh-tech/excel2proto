# python运行环境:
## window:
* python: 2.7 ==>  software/python-2.7.18.amd64.msi
* pip install xlrd==1.2.0
* pip install protobuf==3.13.0
* pip list
## linux: (Ubuntu)
* sudo apt-get install python2.7
* sudo update-alternatives --install /usr/bin/python python /usr/bin/python2.7  150
* pip : python  software/get-pip.py
* pip install xlrd==1.2.0
* pip install protobuf==3.13.0
* pip list

# 功能
## 支持跨平台: excel2proto.bat(window),excel2proto.sh(linux)
## 支持多语言: Go,C++,C#;其他语言待添加
## 一个excel多个sheet: 某一个系统含有多张表
## 支持基础类型和复杂类型,实例:example.xlsx
## 支持key和mixkey查找数据接口
## 支持key中重复字段检查
## uint32,int32,uint64,int64类型支持数据范围检查
## 服务器客户端标志区分
## sheet内支持备注:作者或者功能备注
## Go支持全表/单表热更,C#,C++支持全表更新

# 微信/手机号: 15722485380