- 👋 Hi, I’m @BraceLiu
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

# 我的中期答辩

## 我的完成度

### 学位论文研究目标及研究内容
* 研究目标  
    在充分研究相关论文、了解国内外深度强化学习在游戏中的发展现状后，利用现有的基于值函数和基于策略的深度强化学习方法，让模型通过对每个学生积分情况的区别，训练出在游戏中由不同表现的模型，并计算模型达到预期效果训练时间；在此基础上，利用高并发问题解决多人游戏下的游戏速度较慢的问题，能顺利完成学生的游戏匹配任务并保证游戏中人物角色和电脑角色运行顺利且流畅。   
  
* 研究内容     
      
    针对基于深度强化学习在游戏中的任务，需要明确的问题包括：  
1.	研究如何基于原来的模型进行改进，对游戏速度进行提升  
2.	研究如何对不同学生、不同积分的模型进行训练，针对不同的积分模型，如何差异化游戏模型，使得模型在游戏中的表现根据积分情况有一定区别    
3.	研究如何进行匹配机制，何时出现玩家与玩家的匹配，何时出现学生与电脑角色的匹配，匹配时如何设置玩家上限，要基于服务器的可容纳量进行匹配  
4.	研究如何处理训练多个模型的速度问题，要保证服务器不会在训练多个模型的时候出现卡顿导致游戏速度变慢的情况  
5.	研究训练模型的时间节点问题，主要包括何时对学生的游戏模型进行训练，是后台自动训练还是学生前端手动操控训练过程    

### 目前已完成学位论文工作的内容  

    目前已完成的任务主要包括一生一宠物模块，一生一宠物模块可以正常部署到智慧教育平台模块中，供学生登陆后获取一定的学习积分后使用，每个学生通过在智慧教育平台学习，获得一定的学习积分，后台会为每个用户生成一个游戏角色，用户的学习积分越高，用户的游戏模型在后台训练时间会越长，故积分越高的用户的游戏角色在游戏中表现就会越好；后端会根据数据库中各个学生的积分信息，会逐个训练数据库中有效的用户，把训练好的模型保存到后台，前端会把当前用户的游戏角色录入，并且在用户点击开始游戏的时候为用户匹配四个其他用户的游戏模型进行比赛，前端的显示主要是包括游戏的介绍、游戏的主界面、当前用户的信息和当前用户的积分以及游戏开始后该用户匹配到的其他四个用户的信息。  
    
1.  为每一个同学创建一个宠物模型，并部署到一生一宠物项目中，投入正常的使用和展示工作<https://plazauuw.club/index.html?userId=152152>。  
2.  匹配机制设计完成，学生在进行游戏的时候不再与机器人模拟对战，而是与真实的学生对战，学生在进行游戏的时候与四个玩家一起参加比赛。  
3.  新学生在加入进来并通过学习获取积分后，后台会对学生宠物进行创建和训练，以达到预期的游戏表现。  
4.  网页的设计初步完成，前端展示游戏进行界面，显示游戏说明，显示学生的学生账号和积分信息。  
5.  目前模型的训练纯手动，不存在模型的训练影响游戏进行的问题，加上自动训练的流程后，会考虑模型的训练是否影响游戏正常进行的问题。  

### 现阶段完成的工作与开题报告内容不相符的情况说明  
  
  无  

### 下一步工作计划及需要完成的研究内容和需要解决的关键技术
  
  下一阶段的任务在于当前游戏的持续改进，并且还需要运用当前的深度强化学习模型向系统中添加更多的小游戏供学生使用，具体内容如下：  
  
  1.  通过现在的深度强化学习模型后，分数过高的学生（积分大于15000）因为训练时长已经非常多了，所以在游戏中的区分度不明显，目前的解决方案是不让积分过高的学生在一场游戏中匹配到。  
  2.  将目前网页做成系统，学生可以选择不同的游戏进行体验。  
  3.  关于本文提出的系统，计划发表一篇关于智慧教育，增强学生学习体验的论文，论文的创新点和方向在于深度强化学习是如何影响学生学习生活、游戏是如何融合到教学系统的。  
  
### 已发表的与学位论文相关的学术论文、其他研究结果以及拟发表的研究结果  
    
  拟发表的研究结果：  
  1. 














![first](https://github.com/Kyushik/DRL/raw/master/Image/breakout.gif)  
![second](https://github.com/Kyushik/DRL/raw/master/DQN_GAMES/pong.PNG)  
![third](https://github.com/Kyushik/DRL/blob/master/DQN_GAMES/tetris.PNG)













西安电子科技大学智慧教育平台
后端开发
2020年06月 - 至今
西安
1开发智慧教育平台课程学习模块主要涉及Springboot+redis的使用，该模块包括教师端、学生端、管理端，学生可以学习网站上的所有课程，可以看到该课程
界面下的各个知识点对应的视频，并计入学习积分，并设计定时任务，保证网站在高峰时段提供给用户正常使用

2开发智慧教育平台答题闯关模块，主要涉及Springboot框架的使用，该模块包括学生端、教师端、管理端，教师端、管理端可以进行各个课程题目关卡的修改
和添加，并设置关卡数目和题目，题目包括单选题、多选题、填空题，学生可以通过答题完成闯关；教师可以通过数据可视
化模块对学生成绩、班级成绩进行监控

3开发智慧教育平台邮件发送模块，主要涉及springboot邮件发送功能，教师可以通过发送邮件功能向学生们发送信息

4开发智慧教育平台积分游戏模块，通过游戏进行可视化，主要涉及python、flask和tensorflow的使用，后台选择不同的深度强化学习模块对学生用户在Flappybird
游戏中的角色进行训练，学生学习积分越高，该游戏中的小鸟能飞得更远

后端开发
2020年09月 - 2021年01月
西安
1专技教育平台的开发，该模块包括机器人端和后台管理端，前端可以咨询机器人有关学习的相关内容，并让用户选择该问题
是否符合咨询意向，后台能看到用户的反馈及时作出问题的调整。
2后台模块开发主要包括登录以及基于Spring security登录权限的开发，不同用户登录能访问不同界面
3后台模块开发还包括基于Springboot+mybatisplus的问题管理功能，还针对问题管理做了基于easyexcel的问题导入导出功能
4后台模块开发还包括基于echarts的数据可视化功能的实现，让管理员能看到网页的数据信息



华为
后端开发工程师 2012实验室 PLM应用开发部
2022年06月 - 2022年09月
深圳
1PLM流程框架公共组件的开发，主要是开发一套ipd电子审批流程，开发内容包括流程图和功能设计、基于华为后端jalor框架的后端开发、通过调用内部ipd ui来实现前端组件的渲染
2华为可信理论知识和IT安全知识的学习，主要包括可读、可维护、安全、可靠、可测试、高效和可移植，学习后能有岗位上
的安全意识和开发可信软件的意识，保证自己写的代码和维护的代码是安全可靠的
3通过学习部门的Committer机制，培养自己的Committer意识，了解Committer的作用和重要性
4学习华为内部的开发规范手册和内部开发流程框架





<!---
BraceLiu/BraceLiu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
