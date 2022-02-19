# LoR_Chinese_Simplified
# LoR简中汉化程序

## 汉化文件更新至版本3.2；
汉化教程（文字版），请参阅：https://www.loryx.wiki/ （其他攻略→简中化教程）

汉化教程（视频版），请观看：https://www.bilibili.com/video/BV1Cf4y1W77y

本汉化文件由游戏自带的繁中文件逐字替换成成简中而来，对英雄名字和部分卡牌和词条的名称进行了修改，没有进行文字的增删。

本教程适用于电脑端，汉化过程遇到问题欢迎在B站私信yx5932。

## 【文件准备】
**下载LoR汉化v3.2.zip即可**

本压缩包已准备好3.2版本的汉化文件，汉化时请将汉化文件重命名成自己需要的语言的版本，推荐将游戏语言改为英语后进行汉化。

## 【路径示例】

（如何寻找路径不在本教程范围内，汉化失败极有可能是路径有问题）
1.游戏自带语言文件所在目录。示例：

> D:/Riot Games/LoR/live/PatcherData/PatchableFiles/GamePlayData

2.LoR.exe所在的目录，路径中包括LoR.exe。示例：

> D:\Riot Games\LoR\live\Game\LoR.exe

3.简中汉化文件所在的目录，注意选择正确的语言的汉化文件，例如当前游戏语言为英文，则启动前自行准备好LocalizedText_en_us.bin，路径中包括汉化文件的文件名("LocalizedText_en_us.bin")。示例：

> C:\Users\你的用户名\Downloads\LocalizedText_zh_tw.bin


## 【正式汉化】

### 第一次汉化：

1、更改游戏语言为你想要的语言（推荐英文，日韩或其他语言也可，游戏语音和汉字字体根据此步骤的设置而变化），如使用当前语言汉化则省略本步骤。
（具体步骤：打开lor客户端，退出登录，在登录界面右上角语言设置改为你需要的语言，记得是改LoR游戏的语言而不是登陆客户端的语言，输入用户名/密码，记住账号密码，登陆游戏，确保语言修改成功）

2、关闭游戏，打开LoR汉化.exe，程序会自动寻找系统内的游戏目录并填充，如果未能找到，需要按要求自行填写【游戏自带语言文件所在目录】和【LoR.exe所在的目录】，如果填写错误将导致汉化失败；

3、将简中文件重命名为LocalizedText_en_us.bin（如果第一步修改为了日文或韩文，则将en_us换成ja_jp / ko_kr）

4、在LoR汉化程序的第三栏中选择我们的简中文件，如果操作正确，【当前游戏语言地区】会自动填写。

5、点击汉化，游戏会自动启动并开始汉化，如果游戏未启动，请检查以上三个路径是否全部填写正确，或是否开启了加速器。如果一次汉化不成功，则多试几次，不确保所有语言和设备可以汉化成功。

### 后续汉化：

如游戏版本没有变化、文件路径没有变更且无需更改语言，运行lor汉化.exe后点击汉化即可。版本更新后需要下载新的汉化文件并重新选择/填写路径，方可继续进行简中汉化。


## 【注意事项】

1.汉化失败（提示Permission Denied）多为路径填写错误，仔细检查；

2.请勿更改游戏启动文件（LoR.exe）的位置，将导致游戏无法运行；

3.由于游戏每次启动时都会检测语言文件是否会更改，关闭游戏后再次打开仍需通过本汉化程序打开。汉化程序会储存上次汉化成功后的三个路径与语言，每次使用仅需打开汉化程序并点击汉化即可。如果路径有变更，记得下次使用汉化程序的时候修改路径；

4.有python基础的朋友可以试着修改网盘中的“汉化(悲梦b版本).py”文件中的路径，修改其中内容，后续每次运行py文件即可，也不用填写路径。


## 【参考内容】
1.帖子：【符文之地传奇】1.1版本现已实装（https://www.iyingdi.com/web/article/search/102263）
2.帖子：【汉化教程】自动替换汉化文件的python脚本（https://www.iyingdi.com/web/bbspost/detail/2330229）
3.视频：Lor符文之地 1.9最新版本新的简体中文汉化教程-Lol☆英雄联盟（https://www.bilibili.com/video/BV1Z54y1C7Uy）
