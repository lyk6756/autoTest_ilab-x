# 环境准备

已通过测试的运行环境：

* Google Chrome 92.0.4515.159
* Selenium IDE for Chrome 3.17.0

使用Google Chrome浏览器打开[https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd](https://chrome.google.com/webstore/detail/selenium-ide/mooikfkahbdckldjjndioackbalphokd)将Selenium IDE添加至Chrome即可。

或直接将项目中的`Selenium-IDE_v3.17.0.crx`文件拖拽至Chrome浏览器中进行安装。

## 前置条件：登陆

在运行自动化脚本前，**务必**先在Google Chrome浏览器中完成登陆：[国家虚拟仿真实验教学课程共享平台](http://www.ilab-x.com/login)。

## 运行脚本

1. 将项目中的自动运行脚本`autoTest.side`下载到本地。
2. 完成登陆后，在浏览器中打开安装好的Selenium IDE，在弹出的对话框中点击`Open an existing projct`，并选择刚才下载的脚本`autoTest.side`。

![Open project](https://dm2305files.storage.live.com/y4m4SjFM2Ofz1XXb_SH6Bx9fPZBnCKSZ6Qt39w3gimZPEc-YCq1Qw1mFpk2iA3GKizCIOwPJfyKvi_l1aHLJcNpqUnB8CjldhluNNz2KERoZOyXU3oOUJuCOCaCGVJTA9VNT3fyWor58f9ImxCPWuc75HhNlV88Khz77rlmnJg42bst952X8mvRTNJZZCmBI7ns?width=618&height=756&cropmode=none)

3. 在运行脚本之前，**务必**先将运行速度调整至最慢。在Selenium IDE窗口中，选择工具栏中的`Test execution speed`（显示为:stopwatch:图形），并将滑块拖动至最慢。

![Open project](https://dm2305files.storage.live.com/y4mtFy9M7JkQOkIU6iW-CCQdZiqWKpf7V4Q8ehevXaPU0OJePPGC0jjwuwJna3LXydVYha1s4V3fPhcBwxMN-D5F2Dmex6swQFDj8CHnFXT2KJg8OOHo-W_LmwtD-7km8gCgzSn1FigJfb1mt3oNTYNlsdcUbHyFF5FAKREtsiSCPN9jkrAkj_g4n66-vtdt-v1?width=618&height=756&cropmode=none)

4. 点击工具栏中的`Run current test`（显示为:arrow_forward:图形）。脚本开始自动运行，约10分钟左右完成实验操作，并自动提交。

**注意**：脚本运行过程中，请勿对浏览器窗口进行任何操作。

![Open project](https://dm2305files.storage.live.com/y4m2FNAOBaSe9QotT6YdK3jEXCPmjSkYYsgozNxTr0lmEtqKu8tB1l7rOP3idGYLxHWhkax8YIKY_QFyURWh2qUfN-3aAxYXvlAwFr7BOeFy9R-qz-AqNcNy14BnMaFIxU7lrLstoQrq_SRUfn_ycNuGyU4jipO-Ayvlu0n9Oq64QRTUEw2z8g_R0TZBoJkIBL4?width=618&height=756&cropmode=none)