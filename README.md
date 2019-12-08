![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 使用Windows为CMDER设置默认文件夹
#### Setting Default Folder For CMDER Using Windows
**发布-日期: 2017年06月23日 (评论)**

## Contents

- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
如果你像我一样做网络工作的，你可以在Mac或PC上找到很多有用的工具，这样你就可以开展工作了。就我而言，我用的这两台机器，通常会使用Windows的Cmder控制台模拟器。

好，如果你下载了.msi文件，然后安装很顺利，但现在要设置默认文件夹。

你可以使用/ start开关为快捷方式设置默认文件夹。以下是我怎么做的。
转到CMDER程序文件并在Cmder.exe文件上创建快捷方式。


## English
If you’re like me and do any amount of web work; you’ll find lots of useful tools out there for the Mac or PC so you can carry out your work. In my case; I use both machines, and usually will use the Cmder console emulator for Windows.

Ok; so you download the .msi file, and the installation goes great, but now you want to set the default folder.
You can set the default folder with the /start switch for the short cut. Below is how I made that happen.
Go to the CMDER program files and create a short cut on the Cmder.exe file.


![#](images/Setting-Default-Folder-For-CMDER-Using-Windows-01.png?raw=true "#")

Just add the /start “C:MyFolderPath” next to the original shortcut Target. Remember to add the quotes. The path you specify will be the location where Cmder will open each and every time.
For example; I want mine to open under my Projects folder so this is what I have.
"C:Program FilesProductivityToolscmderCmder.exe" /start "C:Program FilesProductivityToolsProjects"
You could create multiple shortcuts with new /start paths, and you can simply open Cmder to a new folder for each one.

只需在原始快捷方式Target旁边添加 / start“C：MyFolderPath” 即可。请记住添加引号。你指定的路径将是Cmder每次打开的位置。

例如，我希望在我的项目文件夹下打开。 “C：Program FilesProductivityToolscmderCmder.exe”/ start“C：Program FilesProductivityToolsProjects”

![#](images/Setting-Default-Folder-For-CMDER-Using-Windows-02.png?raw=true "#")

Next to drop your shortcuts under your System32 folder, and you have your own start-run shortcut
接下来将快捷方式放在System32文件夹下，你就拥有了自己的开始运行快捷方式

C:windowsSystem32

![#](images/Setting-Default-Folder-For-CMDER-Using-Windows-03.png?raw=true "#")

Here is my start run shortcut.
这是我的开始快捷方式。

![#](images/Setting-Default-Folder-For-CMDER-Using-Windows-04.png?raw=true "#")

Hope this gets you started on what you need for having a default home folder.

希望这能让你开始拥有默认主文件夹所需的内容。


[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

