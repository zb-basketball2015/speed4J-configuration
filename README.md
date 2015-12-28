####1、下载eclipse-AllInOne.7z及workspace-pt.zip。
####2、解压缩eclipse-AllInOne.7z及workspace-pt.zip到桌面或任意位置，双击eclipse下的eclipse.exe文件打开集成开发环境，在弹出的Workspace Launcher中选择刚解压的workspace-pt文件夹。
####3、初始化完成后进入Eclipse主界面，下面配置Eclipse依赖的Maven。点击Window-Preference，跳出配置框，选择Maven-Installations，点击右侧Add，在弹出框中点击Directory，选择解压缩的eclipse目录下tools\maven\apache-maven-3.0.4，点击Finish完成配置，勾选添加的apache-maven-3.0.4。选择Maven-User-Settings，点击Global Settings右侧的Browse，选择解压缩的eclipse目录下tools\maven\settings.xml，点击Update Settings完成配置。
####4、打开桌面Symantec Software Portal工具，搜索JDK 1.7软件并安装，接着配置Eclipse依赖的JDK。选择Java-Installed。 JREs，点击右侧Add，选择Standard VM，Next，点击Directory，选择本地安装的JDK目录，Finish后，勾选添加的JDK，点击OK完成配置。
####5、添加系统环境变量配置。右击计算机，点击属性，点击左侧高级系统设置，点击高级，点击环境变量。在用户变量中添加JAVA_HOME及M2_HOME，路径分别为刚刚安装的JDK位置以及eclipse目录下的tools\maven\apache-maven-3.0.4。
####6、详细配置参考实战开发手册。
