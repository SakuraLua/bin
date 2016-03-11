这里存放的是 SakuraLua 运行所需的二进制文件。*0 0 数量很多，不过其实并不大……*

由于 SakuraLua 和 ssp 均运行在 Windows 平台下，且这些二进制文件变动较为频繁，故直接使用 git 进行版本管理，以方便最终用户获取和打包发布。

其中 SakuraLua-Shiori.dll 是 SakuraLua 与 ssp 交互的核心 Shiori 文件，其它文件都是其需要的运行库。

由于相关插件均采用 VC++2015 编译，故携带了 vcruntime140 及全套 api-ms-*.dll 文件用于兼容 Microsoft (R) Windows (R) XP.

除 SakuraLua-Shiori.dll 外，仓库内二进制文件均遵循 MIT 协议分发。SakuraLua-Shiori.dll 遵循 Apache License 2 分发。