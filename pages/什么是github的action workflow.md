- $GITHUB_WORKSPACE 似乎是一个环境变量
- 每一个action都是一个单独的文件
- 我能可以搭积木使用他人的action
- `.github/workflows`配置文件root位置
  yaml文件格式
	- workflow 代表配置文件执行动作
		- job 任务
		- ...
			- step 步骤
			- ...
				- action 动作
	-
- 在虚拟机环境下运行命令的流程化工具🔧
- DONE 是否gh_pages分支默认是部署github pages的分支
  :LOGBOOK:
  CLOCK: [2022-01-12 Wed 23:07:30]--[2022-01-12 Wed 23:08:05] =>  00:00:35
  :END:
  好像不是，无关紧要了，细枝末节
- github action配置中的trigger的分支main，没有匹配我正在使用的master
  > git branch -m main