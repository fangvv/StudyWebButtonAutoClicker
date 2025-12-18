# StudyWebButtonAutoClicker

基于网页的网络视频学习通常是非常无趣的，但通常为了完成任务拿电子证书又不得不做，因此自己设计实现一些小代码，实现自动化的、高速的“机器学习”（Let Machine Learn...）操作，省下宝贵的时间。

用于smartedu平台的"确定"按钮自动点击(每个视频播放完毕自动出现，点击之后再播放下一个视频，无法自动化），每隔三秒自动点一次页面弹出框的按钮。使用时按F12，在调试框里直接输入以下命令：
> setInterval(() => { const buttonEle = document.getElementsByClassName('layui-layer-btn0')[0]; if (buttonEle) buttonEle.click(); }, 3000)

学校的学习平台，用代码形式会崩溃，chrome安装插件 Global Speed: 视频速度控制，就可以全局定义速度为16倍速，不需要再输入代码。
