用 vs2013 打开 taskbar.sln, 点"编译"得到 taskbar.exe
此时的 taskbar.exe 是 cmd.exe 的一个外壳
用 reshack/exesope 修改 taskbar.exe 的图标资源和字符串资源就能得到自定义的任意 console 程序的外壳了
比如 goagent.exe

或者在启动软件时，加上参数"-s"，即可使用静默模式。已知BUG：console窗口还是会一闪而过。
