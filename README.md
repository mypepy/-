在使用winform开发上位机的过程中，通常客户所使用的登陆方式为刷卡登录，并不允许直接手动输入密码：
为此我使用一个timer控件设置一段事件间隔（手动输入达不到的间隔即可）定时将定时器禁用，并清空文本框，之后启用定时器
