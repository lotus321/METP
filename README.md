METP
====

METP目标是提供一个自动化运行的综合工具，它可以运行monkey，Uiautomator和Robotium自动化case。 其特点在于图形化界面，便于使用，自动扫描手机，反射解析自动化case，配置灵活以全面覆盖各种执行需求 目前完成了Monkey的功能 使用步骤： 按照图形界面要求选择测试包，配置测试轮数及每轮执行时间 选择要执行的手机 点击开始，执行monkey测试  如果中途想停止某部手机或者全部手机，则将手机重置回左边框，选择停止即可 即使monkey中途停止，仍会发送报告  要想发送邮件，需要在res\params.xml里配置邮箱信息  本程序需要运行在java 7以上版本
