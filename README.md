<div align="center">
  <img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo">
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>



<div align="center">



# novabot-plugin-bupt-ncov

_✨ 让 BOT 手动帮你打卡叭✨_

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/Nova-Noir/novabot-plugin-BUPT-ncov.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/novabot-plugin-BUPT-ncov">
    <img src="https://img.shields.io/pypi/v/novabot-plugin-BUPT-ncov.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

## 📖 介绍

重写的 BUPT 手动疫情打卡 BOT

## 💿 安装

<details>
<summary>使用 nb-cli 安装</summary>
在 Nova-Bot 项目的根目录下打开命令行, 输入以下指令即可安装



    nb plugin install novabot-plugin-bupt-ncov

</details>

<details>
<summary>使用包管理器安装</summary>
在 Nova-Bot 项目的插件目录下, 打开命令行, 根据你使用的包管理器, 输入相应的安装命令



<details>
<summary>pip</summary>



    pip install novabot-plugin-bupt-ncov

</details>

<details>
<summary>pdm</summary>



    pdm add novabot-plugin-bupt-ncov

</details>

<details>
<summary>poetry</summary>



    poetry add novabot-plugin-bupt-ncov

</details>

<details>
<summary>conda</summary>



    conda install novabot-plugin-bupt-ncov

</details>

打开 Nova-Bot 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('novabot_plugin_bupt_ncov')

</details>

<details>
<summary>从 github 安装</summary>
在 Nova-Bot 项目的插件目录下, 打开命令行, 输入以下命令克隆此储存库



    git clone https://github.com/owner/novabot-plugin-bupt-ncov.git

打开 Nova-Bot 项目的 `bot.py` 文件, 在其中写入

    nonebot.load_plugin('src.plugins.novabot_plugin_example')

</details>

## 🎉 使用

### 指令表

|                             指令                             | 权限 | 需要@ | 范围 |     说明     |
| :----------------------------------------------------------: | :--: | :---: | :--: | :----------: |
|                             ncov                             | 所有 |  否   | 私聊 |     打卡     |
|            ncov add [-h] [-t TIME] user password             | 所有 |  否   | 私聊 | 添加新的用户 |
|                       ncov remove [-h]                       | 所有 |  否   | 私聊 |   删除用户   |
| ncov modify [-h] [-u USER] [-p PASSWORD] [-t TIME] [-s STATUS] | 所有 |  否   | 私聊 |   修改用户   |
|                        ncov list [-h]                        | 所有 |  否   | 私聊 | 显示用户状态 |

所有指令都可以通过添加 `-h` 或 `--help` 都可以查看具体信息

