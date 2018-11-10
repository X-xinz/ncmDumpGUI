# ncmDumpGUI
网易云ncm格式转换工具

ncmDumpLite是ncmDumpGUI的精简版，如果没有选择输出格式和码率的需求，ncmDumpLite将是更好，更简单的选择。

当前最新版本：
ncmDumpGUI.v1.2.3.1
ncmDumpLite.v.1.0.0.1

更新日志：
1.修复了输出格式选择“自动”时仍用ffmpeg重新编码的问题。
2.修复了转换文件时可能丢失最后几秒声音的问题。
3.增加了选择输出码率的功能。
4.修复了其他已知错误。

使用方法：
ncmDumpGUI：解压后运行ncmDumpGUI.exe，拖动.ncm格式文件到列表，选择输出目录，格式和码率，点击“转换”，稍等片刻即可完成。
ncmDumpLite：解压后运行ncmDumpLite.exe，拖动.ncm格式文件到窗口，将自动输出文件到原文件所在目录。
