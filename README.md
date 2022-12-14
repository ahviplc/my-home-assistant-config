# my-home-assistant-config

> 🏡 My Home Assistant Configs. 🏡我的Home Assistant配置.

> https://github.com/ahviplc/my-home-assistant-config.git

> https://gitee.com/ahviplc/my-home-assistant-config

# 一些链接

```markdown

https://www.home-assistant.io/

https://github.com/home-assistant/core

﻿使用 docker 快速安装 Home Assistant - MINWS BLOG
https://blog.minws.com/archives/685/

智能家居学习笔记（一）：威联通TS-453Dmini安装HomeAssistant的三种方法_NAS存储_什么值得买
https://post.m.smzdm.com/p/aenrog6z/

使用此docker命令快速搭建:

docker run -d -p 8123:8123 \
--name=my_home_assistant \
-e TZ="Asia/Shanghai" \
-v /your-path/home_assistant_data/config:/config \
-v /your-path/home_assistant_data/dev/bus/usb:/dev/bus/usb \
-v /your-path/home_assistant_data/var/run/dbus:/var/run/dbus \
--net=host \
--privileged \
--restart=unless-stopped \
homeassistant/home-assistant:latest

===========================================================================================

其他信息:
http://your-ip:8123/onboarding.html

http://your-ip:8123/onboarding.html

目录:
/your-path/home_assistant_data/

===========================================================================================
官方版
GitHub - hacs/integration: HACS gives you a powerful UI to handle downloads of all your custom needs.
https://github.com/hacs/integration

GitHub - hacs-china/integration: 🇨🇳 HACS 极速版
https://github.com/hacs-china/integration

使用其他方法解决 具体请看

===========================================================================================
配置 – Home Assistant
http://your-ip:8123/config/lovelace/resources

直接可以访问HA的资源路径

http://your-ip:8123/local/card-mod.js

http://your-ip:8123/hacsfiles/button-card/button-card.js?hacstag=146194325342

http://your-ip:8123/hacsfiles/swipe-card/swipe-card.js?hacstag=192732887400

http://your-ip:8123/hacsfiles/lovelace-auto-entities/auto-entities.js?hacstag=1677445841110

下面这个在这里无法加载

https://ghproxy.com/https://raw.githubusercontent.com/bramkragten/swipe-card/master/dist/swipe-card.js

===========================================================================================

Homekit Infused 5 | Homekit Infused 5 2022
https://jimz011.github.io/homekit-infused/installation.html

Homekit Infused – Home Assistant
http://your-ip:8123/homekit-infused/home

Homekit Infused v5 If you see this message and see no other errors you have successfully installed Homekit Infused 5!

Before you continue you should 【http://your-ip:8123/config/person】 create persons and add pictures to them, this is not required, but it will make your top right button look more personalized.

A user and person is created by default when starting Home Assistant for the first time, just make sure that the person and username are both 1 word, this is important.
If your username has underscores, create a new one with only your first name!

Please read the documentation 【https://github.com/jimz011/homekit-infused/tree/5.x.x-docs】 for information on how to configure HKI!

You can remove this message by opening /hki-user/config/views.yaml and remove the welcome_message: lines.

主要编辑即可定制你自己的UI

"my-home-assistant-config/config/hki-user/config/views.yaml"

Enjoy...

这是配置灯光的模板

homekit-infused/04.lights.yaml at 5.x.x-personal · jimz011/homekit-infused · GitHub
https://github.com/jimz011/homekit-infused/blob/5.x.x-personal/hki-user/views/04.lights.yaml

也可以参考这个进行HA的hki设置 此为模板

home_assistant/Config/hki-user/views at Potato · Potato501/home_assistant · GitHub
https://github.com/Potato501/home_assistant/tree/Potato/Config/hki-user/views

参考了很多这个

view_config(进阶教程完整的参考配置).yaml - Potato501/home_assistant - GitHub1s
https://github1s.com/Potato501/home_assistant/blob/Potato/Config/hki-user/config/view_config(%E8%BF%9B%E9%98%B6%E6%95%99%E7%A8%8B%E5%AE%8C%E6%95%B4%E7%9A%84%E5%8F%82%E8%80%83%E9%85%8D%E7%BD%AE).yaml#L447

下面两个为lovelace-mushroom教程视频
https://www.youtube.com/watch?v=gouMnPxYHDc
https://www.bilibili.com/video/BV1DP411L7B7

GitHub - piitaya/lovelace-mushroom: Mushroom Cards - Build a beautiful dashboard easily 🍄 这个极其不错的
https://github.com/piitaya/lovelace-mushroom

lovelace-mushroom/light.md at main · piitaya/lovelace-mushroom · GitHub | lovelace-mushroom 中的灯光配置说明
https://github.com/piitaya/lovelace-mushroom/blob/main/docs/cards/light.md

Homekit Infused 5 | Homekit Infused 5 2022 | addons/custom 使用自定义卡片 比如 lovelace-mushroom 中的卡片
https://jimz011.github.io/homekit-infused/addons/custom.html

Homekit Infused 5 | Homekit Infused 5 2022 | addons 插件 所有的插件类型 均可配置条件 conditional | conditions (满足条件才可以显示此具体插件)
https://jimz011.github.io/homekit-infused/addons.html

Homekit Infused 5 | Homekit Infused 5 2022 | button 按钮配置说明 其中配置项 type: color-temp | rgb | cover | switch | graph | sensor | fan 默认为 auto | 默认情况下，HKI 会尝试自行判断按钮的类型，但如果它弄错了，则通过设置类型来强制它
https://jimz011.github.io/homekit-infused/addons/button.html

GitHub - custom-cards/button-card: ❇️ Lovelace button-card for home assistant | 其 tap_action | hold_action | double_tap_action >【more-info, toggle, call-service, none, navigate, url】动作的具体配置说明
https://github.com/custom-cards/button-card#Action

homekit-infused/04.lights.yaml at 5.x.x-personal · jimz011/homekit-infused · GitHub | jimz011 灯光控制源码
https://github.com/jimz011/homekit-infused/blob/5.x.x-personal/hki-user/views/04.lights.yaml

homekit-infused/03.devices.yaml at 5.x.x-personal · jimz011/homekit-infused · GitHub | jimz011 设备控制源码 | 插座控制
https://github.com/jimz011/homekit-infused/blob/5.x.x-personal/hki-user/views/03.devices.yaml

lovelace-mushroom/fan.md at main · piitaya/lovelace-mushroom · GitHub | lovelace-mushroom 中的风扇配置说明
https://github.com/piitaya/lovelace-mushroom/blob/main/docs/cards/fan.md

homekit-infused/08.media.yaml at 5.x.x-personal · jimz011/homekit-infused · GitHub | jimz011 多媒体控制源码
https://github.com/jimz011/homekit-infused/blob/5.x.x-personal/hki-user/views/08.media.yaml

lovelace-mushroom/media-player.md at main · piitaya/lovelace-mushroom · GitHub | lovelace-mushroom 中的多媒体控制配置说明
https://github.com/piitaya/lovelace-mushroom/blob/main/docs/cards/media-player.md

lovelace-mushroom/media-player-view.yaml at main · piitaya/lovelace-mushroom · GitHub | lovelace-mushroom 中的多媒体控制配置源码栗子
https://github.com/piitaya/lovelace-mushroom/blob/main/.hass_dev/views/media-player-view.yaml

lovelace-mushroom/chips.md at main · piitaya/lovelace-mushroom · GitHub | lovelace-mushroom 中的碎片chips卡片的配置说明
https://github.com/piitaya/lovelace-mushroom/blob/main/docs/cards/chips.md

lovelace-mushroom/chips-view.yaml at main · piitaya/lovelace-mushroom · GitHub  | lovelace-mushroom 中的碎片chips卡片的配置源码栗子
https://github.com/piitaya/lovelace-mushroom/blob/main/.hass_dev/views/chips-view.yaml

homekit-infused/notifications.yaml at 5.x.x-personal · jimz011/homekit-infused · GitHub | jimz011 通知 作者个人使用源码
https://github.com/jimz011/homekit-infused/blob/5.x.x-personal/hki-user/notifications.yaml

Enjoy...

===========================================================================================
```

# 一些说明

## HA学习笔记

`分享了很多`

> https://github.com/shaonianzhentan

`来鸭来鸭一起来鸭的个人空间_哔哩哔哩_bilibili`

> https://space.bilibili.com/39523884

```markdown
HomeAssistant学习笔记
https://ha.jiluxinqing.com/#/

ha-docs: HomeAssistant学习笔记的视频文档
https://gitee.com/shaonianzhentan/ha-docs

GitHub - shaonianzhentan/ha-docs: HomeAssistant学习笔记
https://github.com/shaonianzhentan/ha-docs

GitHub - shaonianzhentan/ha_file_explorer: 在HA里使用的文件管理器
https://github.com/shaonianzhentan/ha_file_explorer

GitHub - shaonianzhentan/ha-extension: HomeAssistant浏览器扩展
https://github.com/shaonianzhentan/ha-extension

卡片集合
https://ha.jiluxinqing.com/#/plug_dev_card

自定义Lovelace卡片
https://ha.jiluxinqing.com/#/plug_dev_custom_card

pip安装
https://ha.jiluxinqing.com/#/install_pip

MDI图标
https://ha.jiluxinqing.com/#/website_icon

MDI图标预览 | 只有MDI图标 | unpkg.com加速的预览页
https://unpkg.com/@mdi/font@5.3.45/preview.html

@mdi/font - npm
https://www.npmjs.com/package/@mdi/font

@mdi/font - MDI图标源码地址
https://github.com/Templarian/MaterialDesign-Webfont

Material Design Icons | 只有MDI图标 | 官网
https://materialdesignicons.com/

GitHub - Templarian/MaterialDesign: ✒7000+ Material Design Icons from the Community
https://github.com/Templarian/MaterialDesign

icones - 图标搜索 支持多个图标库 | 推荐 666
https://icones.js.org/

GitHub - ⚡️Icon Explorer with Instant searching, powered by Iconify
https://github.com/antfu/icones

Iconify - 图标搜索 支持多个图标库 | 推荐 6
https://iconify.design/

iconify/iconify: Universal icon framework. One syntax for FontAwesome, Material Design Icons, DashIcons, Feather Icons, EmojiOne, Noto Emoji and many other open source icon sets (100+ icon sets, 100,000+ icons). SVG framework, React, Vue and Svelte components!
https://github.com/iconify/iconify

iconify/icon-sets: 100+ open source icon sets. Icons are validated, cleaned up, optimised, ready to render as SVG. Updated automatically 3 times a week.
https://github.com/iconify/icon-sets
```

## HA与Node-RED的搭配

> 两者搭配使用 可做更多的事情

`相关链接`

```markdown
Node.js
https://nodejs.org/en/

GitHub - nodejs/node: Node.js JavaScript runtime
https://github.com/nodejs/node

Node-RED
https://nodered.org/

GitHub - node-red/node-red: Low-code programming for event-driven applications
https://github.com/node-red/node-red

Documentation : Node-RED
https://nodered.org/docs/

node-red - npm
https://www.npmjs.com/package/node-red

Library - Node-RED - 节点搜索库 - 官方
https://flows.nodered.org/

Home Assistant Community Add-ons
https://addons.community/

GitHub - hassio-addons/repository: Home Assistant Community Add-ons
https://github.com/hassio-addons/repository

GitHub - hassio-addons/addon-node-red: Node-RED - Home Assistant Community Add-ons
https://github.com/hassio-addons/addon-node-red

node-red-contrib-home-assistant-websocket
https://zachowj.github.io/node-red-contrib-home-assistant-websocket/

GitHub - zachowj/node-red-contrib-home-assistant-websocket: Node-RED integration with Home Assistant Core
https://github.com/zachowj/node-red-contrib-home-assistant-websocket

GitHub - zachowj/hass-node-red: Companion Component for node-red-contrib-home-assistant-websocket to help integrate Node-RED with Home Assistant Core
https://github.com/zachowj/hass-node-red
```

## HA中的 `call-service` 模板

> HA中的 `call-service`

` 调用服务` | `空调按钮 开冷空调` | 原始HA调用模板

```yaml
service: xiaomi_miot_raw.execute_text
data:
silent: true
entity_id: media_player.l05c_cloud_249900
text: 开冷空调
```

` 调用服务` | `推送通知消息到HA的app上的服务` | 可优先使用 蘑菇 Action chip 卡片

```yaml
- type: action
    icon: mdi:bell
    tap_action:
      action: call-service
      service: notify.persistent_notification # 这个是推送通知消息到HA的app上的服务
      service_data:
        message: This is notification from mushroom dashboard
```

## 一些技巧

```markdown
====================================================================================================
注意 以后尽量手动更新 hacs 避免下面的cdn加速base.py文件被覆盖 
并且使用hacs自动更新的hacs的文件夹和其文件权限太高 属于admin 不好diy 不好写入.

====================================================================================================
当前使用的hacs版本【1.26.1】2022-07-13
Release 1.26.0 · hacs/integration · GitHub
https://github.com/hacs/integration/releases/tag/1.26.1

在下面的目录中的base.py文件 line 680 左右 新增代码

具体请看下面添加好的文件
"my-home-assistant-config/config/custom_components/hacs/base.py"

即可使用

Enjoy......

====================================================================================================
基本在base.py文件的 line 680 行左右插入下面代码即可

        self.log.error("===Before===Downloading %s", url)
        
        if ("raw.githubusercontent.com" in url):
            url = url.replace("https://raw.githubusercontent.com/",
                                   "https://ghproxy.com/https://raw.githubusercontent.com/")
        elif ("github.com" in url):
            url = url.replace("https://github.com/", "https://ghproxy.com/https://github.com/")

        self.log.error("===After===Downloading %s", url)

====================================================================================================
```

## github代理设置

灵感来自 -> https://blog.csdn.net/LLY_A_/article/details/120390446

`执行git指令` | 只对GitHub进行代理

> git config --global http.https://github.com.proxy http://192.168.192.192:7893

> git config --global https.https://github.com.proxy http://192.168.192.192:7893

`取消代理` | 好像失灵了 直接在git配置文件删除上面相关内容也可

> git config --global --unset http.proxy

> git config --global --unset https.proxy

`查看git已有配置`

> git config --global -l

`查看git配置文件内容` | 添加下面的内容之后是可用的 有效果的

指令执行之后 git配置文件 `.gitconfig` 内容变为

```yaml
[user]
	name = ahviplc
	email = ahlc@sina.cn
[winUpdater]
	recentlySeenVersion = 2.37.1.windows.1
[http "https://github.com"]
	proxy = http://192.168.192.192:7893
[https "https://github.com"]
	proxy = http://192.168.192.192:7893
```

# 什么是 pyc
```markdown
什么是pyc文件呢？
=> 简单来说，pyc文件就是Python的字节码文件，我们都知道Python是一种全平台的解释性语言，全平台其实就是Python文件在经过解释器解释之后（或者称为编译）生成的pyc文件可以在多个平台下运行，这样同样也可以隐藏源代码。其实，Python是完全面向对象的语言，Python文件在经过解释器解释后生成字节码对象PyCodeObject，pyc文件可以理解为是PyCodeObject对象的持久化保存方式。

什么时候会生成pyc文件呢？
=> pyc文件只有在文件被当成模块导入时才会生成。也就是说，Python解释器认为，只有import进行的模块才需要被重用。 生成pyc文件的好处显而易见，当我们多次运行程序时，不需要重新对该模块进行重新的解释。主文件一般只需要加载一次不会被其他模块导入，所以一般主文件不会生成pyc文件。
```

# Git提交说明

```markdown
提交信息书写模板指南:

注意前面有个空格
> ### 代表是具体的文字描述

*
* 做杂务 零工 杂事的时候
* chore: ###
*
* 修复bug的时候
* fix: ###
*
* 有功绩 有重大功能添加的时候
* feat: ###
*
* 性能提升的时候
* perf: ###
*
* 文档编辑相关的时候
* docs: ###
*
```
