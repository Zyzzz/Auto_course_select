# auto_course_select
A python program for selecting course automatically on http://grdms.bit.edu.cn , based on Selenium
可以在 http://grdms.bit.edu.cn 自动选课的工具

### Dependencies & Requirements
1. Windows 7/8/8.1/10, 32-bit or 64-bit
2. Python 3.5
3. Selenium python bindings (http://selenium-python.readthedocs.io/), 可以用```pip install selenium```命令安装
4. Internet Explorer driver for Selenium (可以从 http://www.seleniumhq.org/download/ 下载)，IEDriverServer.exe 需要在系统的PATH环境变量里面或者和auto.py处于同一目录下

### Notes
1. 请参考 (https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver#required-configuration) 正确地配置IE浏览器
2. 程序每次启动都会打开一个新的IE窗口，脚本运行时请尽量保持这个窗口有焦点 参考：(https://github.com/SeleniumHQ/selenium/wiki/InternetExplorerDriver#browser-focus)
