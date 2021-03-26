# MIUI ODEX

##### An Odex shell script for the Chinese version of MIUI automation
Contributor
> Xiong's old party DavidPisces [[Github](https://github.com/DavidPisces)] | [[CoolApk](http://www.coolapk.com/u/665894)]

> Pomelo Childish Child Paper zjw2017 [[Github](https://github.com/zjw2017)] | [[CoolApk](http://www.coolapk.com/u/1548958)]

> Domestic Gitee address of this warehouse [[Gitee warehouse](https://gitee.com/David-GithubClone/MIUI-Auto-Odex)]

##### What can you do
> This script can compile Odex and odex2oat of the system software, and is suitable for the models whose Odex has been officially deleted by MIUI

> Support Complete (Complete) and Simple (Simple) compilation modes, Speed ​​and Everything two dex2oat compilation modes

> Support to automatically generate Magisk module after generating odex file and install it automatically

> Support optional compilation mode

> Support online update (download from Github)

Operating environment
necessary
* Must have Root permission
* Need to use MT manager or other terminals to execute scripts, such as Ansole terminal, Termux, etc.
Suggest
* Recommend to use MIUI11-12 based on Android10
* Recommend to use Magisk 20.4 and above Magisk version
* It is recommended to install the full Busybox
Execution error
:- If you encounter errors such as "syntax error" or "inaccessible or not found" during initialization, please execute the [dos2unix] command to remove the ^M in the file, because the Windows system editor will express the newline as the ^M symbol, if you When a script is executed and an error is reported directly, you can first use the [cat] command to check whether the script contains the "^M" symbol, and then decide to use the [dos2unix] command to convert.

* dos2unix usage: dos2unix filename (for example: dos2unix odex.sh)
* Use cat to get the content of the file: cat filename (for example: cat odex.sh)

how to use
MT manager

After downloading the script, click the script to execute and check Root
  >
  >![](http://image.coolapk.com/feed/2020/0623/15/665894_f922a721_8810_5677@1080x2160.jpeg.m.jpg)

* Other terminal

  > su
  >
  > cd Script storage directory
  >
  > sh odex.sh
  >
  >![](http://image.coolapk.com/feed/2020/0623/15/665894_16498409_8810_5679@1080x2160.jpeg.m.jpg)
