# Dujiao Copilot Activator

Dujiao Copilot Activator 是一款 Github Copilot 远程授权工具。该工具未对 Copilot 以及其他相关软件做任何修改，非破解软件。该工具仅供学习交流使用，如有侵权请联系删除。

## 远程授权原理
远程授权的原理是远程服务器回传一个能用copilot的账号信息到你的copilot上,只有这一步是要和我们的服务器做交互的,之后账号信息就在你的本地了,完全是copilot他自己的处理逻辑了,我们完全没有改动。所以激活器只是给你们分配权限,没办法帮你们解决连接copilot服务器的问题!就算你是10美元买的官方copilot该连不上还是连不上。大家所遇到的,所谓的不稳定的问题,和远程授权并没关系。除非他显示出你当前登录的账号没有权限或者提示你未登录,这才是远程授权出问题了。一般来说,copilot在国内网络下本就不很稳定,因为Copilot服务器在国外,再加上国内运营商的各种屏蔽,想要稳定好用,请自行配置hosts信息或者寻找合适的网络工具。

## 招代理
🎉🎉🎉 【全网源头】
线上团队独立研发，Github Copilot远程授权
相比较于学生包，更加稳定耐用，无封号风险

自助文档：https://ao7wj03age.feishu.cn/docx/Zdf1dQ5woo6RwTxAE9gcC86enQf

发卡站下单地址：http://www.chat888.chat/
【淘宝】：https://m.tb.cn/h.5pu8BT7cUHwdAfN?tk=juBKWhkbZKm
QQ群：602395397  【招收代理，无代理费用】
1. 源头供应，全网最快的软件更新速度
2. 激活客户端代码开源，只开源1.62版本（截止2024年1月8日版本为1.70），二进制js文件闭源
3. 帮助搭建发卡网站（私域下单使用）
4. 帮助搭建淘宝店（公域下单使用）
5. 指导如何与大V产生交集合作（走量路径）
6. 代理请联系管理员


## 特点

使用简单的授权密钥激活 Copilot 插件。
支持多种版本的 Copilot 插件。
授权密钥会与机器绑定，确保合法使用。
![Vscode Chat](http://m.qpic.cn/psc?/V54GpCCc2UpjM012sJD83Q8ldl1OhqBH/ruAMsa53pVQWN7FLK88i5tf7yd*oWM7yq3XjRBVtu5cm7FmwV9*YXBFDYlMsCHEyWBbuSjeXBuOkHEiNRpr*biG*eyAbjAufPwmB09vL8pA!/b&bo=4wLBAgAAAAADBwA!&rf=viewer_4)

![激活软件界面](http://m.qpic.cn/psc?/V54GpCCc2UpjM012sJD83Q8ldl1OhqBH/ruAMsa53pVQWN7FLK88i5uw8So1E*QZ4Qt*ROmq6tFJfL4VeWuK0CUYnvOe5KJWgL8DsaCFquzUC4IeQorkYemtAphmzm2Ha4p4VxV2xTOI!/b&bo=wAPMAQAAAAADByw!&rf=viewer_4)

## 免责声明

请在使用本工具前，详细阅读并理解以下声明：

> Copilot Activator 是一个用于学习交流的工具，不得用于非法用途。请确保你拥有合法的 Copilot 授权，以便合法使用该工具。

## 配置文件

Copilot Activator 使用一个配置文件来管理参数。配置文件默认名为 config.ini ，可参考 config_template.ini 配置。以下是一个示例配置文件的内容：

```
[General]
version = 0.6.1
```

根据需要修改配置文件中的参数。确保配置文件中的敏感信息（如服务器地址和授权密钥）得到妥善保护，以防止泄露。

## Git LFS 下载大文件
存在大文件需要下载，请确保已安装 Git LFS。可以使用以下命令来安装 Git LFS：

```bash
sudo apt-get install git-lfs
```

然后，使用以下命令来拉取 Git 仓库，并下载大文件：


```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
git lfs pull
```

这将下载仓库中由 Git LFS 管理的大文件。

## 使用

1. 确保配置文件配置和 git-lfs 下载大文件
2. 在项目根目录下创建虚拟环境（可选），并激活虚拟环境：

    ```bash
    python3 -m venv .venv
    . .venv/bin/activate  # 在 Windows 上使用 `.venv\Scripts\activate`
    ```

3. 安装依赖包

    ```bash
    pip install -r requirements.txt
    ```

4. 执行main.py

    ```bash
    python main.py
    ```

## 代码格式化

本仓统一使用 [black](https://black.readthedocs.io/en/stable/) 格式化代码，遵循 "less is more" 的原则，无任何额外参数。同时，本仓使用 isort 排序 import 语句。

```bash
black .
isort .
```
