# 提醒

勿**加星**，勿**传播**，谢谢！

# 公告

修改自 **[lolisaikou](https://github.com/lolisaikou) / [LazyStudy](https://github.com/lolisaikou/LazyStudy)** 自动学习，为本人auto.js编程习作，只供个人**学习Auto.js**使用，不得**传播**和用于**违法或商业用途**，否则造成的一切**后果自负！**

## 使用说明

- 文章和视频：点击“切到 强国”，在强国主界面点击“开始浏览”，即可自动浏览，**并且会记录已阅读的文章和视频到数据库（不同账号单独记录，解决多账号问题；自动清除7天以上记录）**，挑战答题、双人对战、争上游答题和每日答题自动完成，集满全部得分结束。（部分手机停在"获取学号"，点击"切到强国"，可解决）
- 挑战答题：进入挑战答题界面，点击“挑战答题”，开始答题，答对50题自动停止;在答题练习界面，点击挑战答题，进行10轮答题，用于增加新题时刷新题库，一般情况下不需要。
- 争上游：在答题界面，点击“争上游”，自动答题两轮；在答题练习界面，点击争上游，进行10轮答题。
- 每日答题：进入每日、专项、每周界面，点击"每日答题等"。程序会自行进行答题，得到6分停止。在答题练习界面，运行每日答题，用于增加新题时刷新题库，一般情况下不需要。
- 手动改题：手动查改删增，支持以题目或答案关键字查询，或列出最后二十条入库记录
- 题库：由于网络题库的不确定性，将逐步摒弃网络题库。通过挑战答题，自主更新题库。

## 我爱学习

一款基于auto.js，安卓自动学习脚本，支持看文章视频、收藏分享评论、挑战答题、每日答题、每周答题。
本项目仅供autojs交流学习，请勿用于商业

[release下载](https://github.com/james-bond-007/lovexuexi/releases/)如何自动学习

##  环境依赖

- 手机为安卓7.0以上版本
- 安装程序后，点击加载悬浮窗，弹出授权界面。请授权 无障碍 和 悬浮窗。

## 版本更新

- 2021.1.13

    增加随机模块学习

    优化代码，提高稳定性

- 2021.1.3

    修复数据库显示0错误。

    优化部分代码。

- 2020.12.25
    
    修复争上游和双人对战找不到答案问题。

- 2020.12.21
    
    修复挑战答题无法识别正确答案错误。
    
    修复争上游有答案点错选项错误。

- 2020.12.13
    
    修复订阅遇到无可订阅时错误。

- 2020.12.12

    紧急修复“选择正确的读音。”题型错误。

- 2020.12.11

    适应最新版，修改订阅方法。

    争上游提速，稳定性有待确认。

    提速有极限，网速最关键。选择好时段，拿分笑开颜。切记，切记，不传播，不加星。

- 2020.12.2

    修复[#26](https://github.com/james-bond-007/lovexuexi/issues/26) 反馈，有答案但不在选项中时，无法继续答题的问题。
    
    修复视频新闻学习，无视频可学习时，不能退出的错误。
    
    更新了题库(4580)。不知道如何更方便的更新题库，求助见[#30](https://github.com/james-bond-007/lovexuexi/issues/30) 。
    
- 2020.11.23

    优化了挑战答题、每日答题、争上游答题答题逻辑：在答题练习界面点击，运行10次（相当于点击了10次），方便刷新题库；答题过程中出现问题，点击也能完成本次答题。
    
    每日答题显示题目类型。
    
- 2020.11.18

    紧急修复等待加载错误。

- 2020.11.16

  - 改进
  
    一键学习：争上游答题加入一键学习。
  
    每日答题：在答题练习界面，自动运行10次，用于刷新题库；出现题目后运行，完成本次答题。
  
    每日答题，单选题答案记录答案内容，不再记录字母。

  - 修复bug

    修复每日答题无法获取提示错误。

    修复每日答题遇词形题找不到答案问题。
    
    修复遇到答案是英语单词时出错的问题。
    
    修复订阅到底线时不订阅就退出的问题。
    
  - 试验项目

    一键学习：打开电台、视频学习前，关闭音量，学习结束恢复音量。  

- 2020.11.5

修复挑战答题答案含小数点时总是答错的问题。

修复双人对战遇答错题进入死循环错误，提高稳定性。

提高争上游答题稳定性。

浏览文章和视频时间长不再固定，变为随机时长。

修复视频新闻学习跳过"国内新闻"、"国际新闻"等问题。

修复订阅多订阅的问题。

- 2020.10.22

双方对战加入到一键学习中。

增加了争上游答题，完善了答题功能（由于答题的不确定性，没有加进一键学习中）。

修复了无法订阅强国号的问题。

- 2020.10.12

修复部分手机视频学习不翻页的问题。

- 2020.10.12

重新调整了一键学习方式，修复了部分手机视频时长学不完的问题。

- 2020.10.04

修复视频学习时长学不完的错误。

- 2020.10.01

适配V2.17版。

更新了题库。

初步实现答题争上游（方法：在出现“开始”提示时，点击“挑战答题”，就可以坐等结果了。友情提示：进行第二次答题前，要先退出浮窗，重新打开浮窗，切记切记！因为不知道啥原因，第二次点击“挑战答题”程序会死掉，影响成绩）

- 2020.09.26

尝试修复V2.26.0.2版无法获取学号问题，有待验证。

V2.26.0.2解决办法，点击“我的”，然后退回主界面，就能正常浏览了。

.2和.3版想要实现自动更新题库功能，即在挑战答题时，找到正确答案，自动更新题库。想通过此功能摆脱网络题库（有很多错误），实现自主更新。

如果V2.26.0.3还不行，请参考V2.26.0.2解决办法或退回不包含自主更新功能的V2.16.0.1版，不影响使用。

- 2020.09.23

挑战答题添加自动查找正确答案功能，并将正确答案更新到题库，**自主完成题库更新**。

界面添加随机背景。

- 2020.09.17

更换网络题库源，修复更新网络题库问题。

挑战答题添加更新题库功能，随机点击正确答案后，更新到题库。

"选择词语的正确词形"类型题，增加区别标识，尝试解决无法识别正确答案问题。

- 2020.09.12

适应新版本变化，修复挑战答题失效问题。

- 2020.09.08

修复无法更新网络题库错误。

- 2020.09.05

视频学习《新闻联播》条数不够时，自动学习小视频。

- 2020.08.22

适应学习强国2.15.1版最新积分规则;
修正有时无法获取文章标题错误。

- 2020.08.01

修复2.15.0版无法阅读文章;
修复了一些小问题。


## **特别感谢**

###### 以下排名不分先后

> [**lgpersonal**](https://github.com/lgpersonal/)
>
> [**kessil**](https://github.com/kessil/AutoXue)
>
> [**ivanwhaf**](https://github.com/ivanwhaf/xxqg-helper)
>
> [**studyhelperhelper**](https://github.com/studyhelperhelper/studyhelper)
>
> [**lolisaikou**](https://github.com/lolisaikou)



[]: https://github.com/james-bond-007/lovexuexi/issues/26]的问题。
