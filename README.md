windows nt 3.5 源码

想要编译该代码,需要使用patch包,并根据附图方法编译,
信息来源https://www.betaarchive.com/forum/viewtopic.php?t=45142

Building

For first, make sure that you're meeting following requirements
A virtual machine with Windows 2000 or older OS (up to NT 3.1)
At least 15 GB of free space
A bit of patience.
Then do the following steps:
Download the NT 3.5's source code and extract it into C:\NT. Otherwise it will won't binplace items and cause some errors.
Download the patches with this link: https://drive.google.com/file/d/19FJj26Scdz3I3hx6mms7rBYNROX9UvKs/view?usp=drive_link and extract the NT folder onto the source code folder. Click Yes and replace all files.
Open Command Prompt, switch to the C:\NT and write attrib -r -h * /s /d for removing attributes. If you're on Windows XP and newer, just uncheck "Read-only" for folder.
Then write public\tools\razzle
If it will ask for a file placing, choose "F". It copies a file from ntx86bld folder.
You're done!
Note that installations of Visual Studio are NOT recommended, because they will cause build problems.


