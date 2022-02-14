<h1 align="center" >EmailAll</h1>

<h3 align="center" > A powerful Email Collect tool</h3>

## 0x1 介绍

:astonished: `EmailAll` is a powerful Email Collect tool

![example1](img/example1.png)

![example2](img/example2.png)

## 0x2 安装&使用

```bash
$ git clone https://github.com/Taonn/EmailAll.git
$ cd EmailAll
$ pip3 install -r requirements.txt
```

```python
EmailAll is a powerful Email Collect tool

Example:
    python3 emailall.py check
    python3 emailall.py --domain example.com run
    python3 emailall.py --domains ./domains.txt run
```

` python3 emailall.py --domain example.com run`

`python3 emailall.py --domains ./domains.txt run`

## 0x3 配置

proxy配置在 [setting.py](config/setting.py)文件

```python
proxy={'http': '127.0.0.1:2333', 'https': '127.0.0.1:2333'}
```

API配置在 [api.py](config/api.py)文件

```python
# http://veryvp.com/
veryvp_username = ''
veryvp_password = ''
```

## 0x4 模块

邮箱信息收集主要来源如下：

- Search
  - Ask
  - Baidu
  - Bing
  - Google
  - QWant
  - SO
  - Sougou
- DataSets
  - Email-Format
  - Skymem
  - Veryvp

> 后续还会更新~

## 0x5 参考

参考了以下优秀的工具，并修改而来:

- https://github.com/shmilylty/OneForAll
- https://github.com/laramies/theHarvester
- https://github.com/m4ll0k/Infoga

感谢这些师傅们的分享！！！

## 0x6 感谢

感谢网上开源的各大项目！！！

## 0x7 免责声明

​	本工具仅能在取得足够合法授权的企业安全建设中使用，在使用本工具过程中，您应确保自己所有行为符合当地的法律法规。 如您在使用本工具的过程中存在任何非法行为，您将自行承担所有后果，本工具所有开发者和所有贡献者不承担任何法律及连带责任。 除非您已充分阅读、完全理解并接受本协议所有条款，否则，请您不要安装并使用本工具。 您的使用行为或者您以其他任何明示或者默示方式表示接受本协议的，即视为您已阅读并同意本协议的约束。
