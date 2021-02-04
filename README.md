# Padavan 固件自定义修改并全自动编译

直接 Fork 修改好之后点击 Star 按钮即可开始自动编译 ( 自己点击 Star 才会运行 请不要重复点击 点一次运行一次 ) 

点击 [Actions]按钮查看项目运行状态 编译好的固件也在里面 

Hanwckf_Padavan_CI 源码使用 [Hanwckf](https://github.com/hanwckf/rt-n56u.git)

ChongshengB_Padavan_CI 源码使用 [ChongshengB](https://github.com/chongshengB/rt-n56u.git) ( 已修复自定义菜单语言和英文界面下不能重置 )

用户名: admin

登录密码: admin

IP地址: 10.10.1.1

WiFi名称: 2G: Padavan 5G: Padavan_5G

WiFi密码: 1234567890


编译脚本带有启用和禁用插件设置 ENABLED_CFG 为启用 DISABLED_CFG 为禁用 ( 先执行这项再执行自定义的 )

示例:

          ENABLED_CFG: |
            CONFIG_FIRMWARE_INCLUDE_LANG_CN
            CONFIG_FIRMWARE_ENABLE_IPV6
          DISABLED_CFG: |
            CONFIG_FIRMWARE_INCLUDE_LANG_UK
            CONFIG_FIRMWARE_INCLUDE_VLMCSD
            CONFIG_FIRMWARE_INCLUDE_TTYD

