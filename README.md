<div align="center">
  <img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/nbp_logo.png" width="180" height="180" alt="NoneBotPluginLogo">
  <br>
  <p><img src="https://github.com/A-kirami/nonebot-plugin-template/blob/resources/NoneBotPlugin.svg" width="240" alt="NoneBotPluginText"></p>
</div>



<div align="center">



# novabot-plugin-bupt-ncov

_✨ 让 BOT 手动帮你打卡叭✨_

<a href="./LICENSE">
    <img src="https://img.shields.io/github/license/owner/nonebot-plugin-example.svg" alt="license">
</a>
<a href="https://pypi.python.org/pypi/nonebot-plugin-example">
    <img src="https://img.shields.io/pypi/v/nonebot-plugin-example.svg" alt="pypi">
</a>
<img src="https://img.shields.io/badge/python-3.8+-blue.svg" alt="python">

</div>

这是一个 Nova-Bot 插件项目的模板库, 你可以直接使用本模板创建你的 Nova-Bot 插件项目的仓库

模板库使用方法:

1. 点击仓库中的 "Use this template" 按钮, 输入仓库名与描述, 点击 "  Create repository from template" 创建仓库
2. 在创建好的新仓库中, 在 "Add file" 菜单中选择 "Create new file", 在新文件名处输入`LICENSE`, 此时在右侧会出现一个 "Choose a license template" 按钮, 点击此按钮选择开源协议模板, 然后在最下方提交新文件到主分支
3. 全局替换`owner`为仓库所有者ID; 全局替换`novabot-plugin-bupt-ncov`为插件名; 全局替换`novabot_plugin_bupt_ncov`为包名; 修改 python 徽标中的版本为你插件的运行所需版本
4. 修改 README 中的插件名和插件描述, 并在下方填充相应的内容

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

