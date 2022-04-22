# FoxServer (1.18.2)

![](pic.jpg)

### 稍安勿躁, 狐端正在开发中.. (Don't be restless, FoxServer is in development..)
你可以参与开发或测试, 为项目作出贡献 ([分支: 1.18.2-dev](https://git.rbqcloud.cn/Luohuayu/FoxServer/src/branch/1.18.2-dev))

You can contribute to the project by join in development or testing. ([Branch: 1.18.2-dev](https://git.rbqcloud.cn/Luohuayu/FoxServer/src/branch/1.18.2-dev))

### 如何获取源码? (How to get the source code?)
你可以从我们的Git获取源码: [https://git.rbqcloud.cn/Luohuayu/FoxServer](https://git.rbqcloud.cn/Luohuayu/FoxServer)

You can get the source code from our Git: [https://git.rbqcloud.cn/Luohuayu/FoxServer](https://git.rbqcloud.cn/Luohuayu/FoxServer)

### 如何构建和开发? (How to build and develop?)
步骤:

1. 克隆源码: `git clone https://git.rbqcloud.cn/Luohuayu/FoxServer.git`, 然后切换到项目目录: `cd FoxServer`
2. 初始化项目: `gradlew setup`, 然后你就可以在IDEA里打开项目了
3. 生成补丁文件 (如果你修改了Minecraft代码): `gradlew genPatches`
4. 构建项目: `gradlew build`
5. 文件将生成在: `(项目目录)/projects/forge/build/libs/`

如果你需要贡献代码，使用git commit并生成补丁，上传到 [Issues](https://github.com/Luohuayu/FoxServer/issues)


Step:

1. Clone the source code: `git clone https://git.rbqcloud.cn/Luohuayu/FoxServer.git`, then into the project dir: `cd FoxServer`
2. Setup the project: `gradlew setup`, then you can use IDEA open the project
3. Generate patches file (If you change Minecraft code): `gradlew genPatches`
4. Build the project: `gradlew build`
5. The file will be generated in: `(Project-Dir)/projects/forge/build/libs/`

If you need to contribute code, use git commit and generate a patch, upload it to [Issues](https://github.com/Luohuayu/FoxServer/issues)

### 如何在IDEA里调试? (How to debug in IDEA?)
运行gradle任务: `FoxServer -> forge -> Tasks -> forgegradle runs -> forge_server`

然后使用IDEA调试或运行: `FoxServer:projects:forge [forge_server]` (记得修改`eula.txt`同意eula)

Run gradle task: `FoxServer -> forge -> Tasks -> forgegradle runs -> forge_server`

Then use IDEA to debug or run:  `FoxServer:projects:forge [forge_server]` (Remember to modify `eula.txt` to agree eula)

### 为什么没有Eclipse教程? (Why is there no Eclipse introduction?)
因为我不使用Eclipse, 你需要自己研究 (可以参考[Forge开发文档](https://mcforge.readthedocs.io/en/latest/forgedev/))

I don't use Eclipse, you'll need to do your own research. (You can refer [Forge dev doc](https://mcforge.readthedocs.io/en/latest/forgedev/))

### 如何获取构建? (How to get the build?)
你可以从构建站下载: [https://cdn.ci.loliidc.cn:30011/job/FoxServer-1.18.2/](https://cdn.ci.loliidc.cn:30011/job/FoxServer-1.18.2/)

You can download it from our Jenkins: [https://cdn.ci.loliidc.cn:30011/job/FoxServer-1.18.2/](https://cdn.ci.loliidc.cn:30011/job/FoxServer-1.18.2/)

**提示: 当前版本构建还无法直接运行, 直到启动器开发完成**

**Tip: Current version builds cannot run directly until the launcher development is complete**

### 其他版本 (Other Version)
[CatServer](https://github.com/Luohuayu/CatServer) (1.12.2)<br>
[LoliServer](https://github.com/Loli-Server/LoliServer) (1.16.5)<br>

### 看乐子 (See jokes)
因为 FoxServer 使用了 Magma 的一个类 (暂时用于调试, 计划重写的), Magma 直接无脑DMCA了 FoxServer 整个项目.

但是 Magma 抄袭了 CatServer 的大量代码(拥有中国版权保护中心著作权登记)我们都没说什么, 所以这次真的被惹火了, 我们直接反手把 Magma 所有版本给DMCA了.

[相关链接](https://github.com/github/dmca/blob/master/2022/04/2022-04-21-guangxi-infinity.md)

Sorry, my English is not good, please use a translator.
