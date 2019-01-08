# OFCR-2019-AutoUpdate

**本文档将引导如何设置并进行OFCR rFactor mod热升级功能**.

用户可从以下两种选项中任选一项进行设置: (1) 使用 `Git`命令提示符(效率较高); (2) 带有图形界面的[GitHub桌面版](https://desktop.github.com/)，易于上手操作

## 命令提示符

1. [下载Git](https://git-scm.com/downloads)，选择适用于你的操作系统版本（32/64位）_参与过公测的用户请忽略这一步_;  
2. 在 `\\rFactor\GameData\Vehicles\`文件夹下新建`OFCR2019`文件夹;  
3. 右击 `OFCR2019`文件夹, 并选择 `Git Bash Here`，弹出如下窗口  
![image](https://i.ibb.co/BV6Q86j/TIM-20190107234748.png)  
**或者**  
3. 打开Windows的命令提示符，使用cd指令指向`OFCR2019`文件夹，如图所示  
![image](https://i.ibb.co/8NZjC8g/TIM-20190107234945.png)  
4. 输入`git init.`进行初始化;  
5. 设置git下载节点，海外用户推荐使用GitHub节点`git remote add origin https://github.com/OMGCA/OFCR2019.git`;  
中国大陆用户推荐使用阿里云节点`git remote add origin https://code.aliyun.com/OMGCA/OFCR2019.git`;  
**注意：这里命令行中的`origin`可以是你任意设置的词**  
6. 从节点下载文件，输入`git pull origin master`(origin处要和你之前设置的词相匹配)。  
**以上为初始化设置过程，若进行更新操作，只需执行步骤6即可**  
注意：如果想要修改节点，只需在更新前输入`git remote set-url `后接你想要更换的节点即可。  


## GitHub桌面版设置  

1. [下载GitHub桌面版](https://desktop.github.com/)，由于GitHub没有大陆节点，下载速度比较慢，请耐心等待;  
2. 首次打开GitHub桌面版可能会提示注册账号，该步骤可以跳过，如果想要通过GitHub进行涂装/车手更新则需要注册账户;  
3. 打开后出现如下界面，选择最右侧的`Clone a repository`  
![image](https://i.ibb.co/z4vgckn/TIM-20190107235732.png)  
4. 首先选择Vehicles文件夹，如图所示  
![image](https://i.ibb.co/xHSmFH0/TIM-20190107235902.png)  
5. 其次设置下载节点，国外用户推荐使用GitHub节点，在上方输入`https://github.com/OMGCA/OFCR2019.git`  
中国大陆用户推荐使用阿里云节点，在上方输入`https://code/aliyun.com/OMGCA/OFCR2019.git`  
6. 出现如下界面表示正在进行下载  
![image](https://i.ibb.co/jk78sX3/TIM-20190108000121.png)  

### 进行更新操作（桌面版）  
1. 打开如下界面后点击如图所示fetch  
![image](https://i.ibb.co/GHBQnJb/TIM-20190108000314.png)  
2. 右上角按钮更改为`pull origin`时代表有更新可用，此时再点击`pull origin`即可完成更新  
![image](https://i.ibb.co/cvwgF8t/TIM-20190108000432.png)
