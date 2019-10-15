---
layout:     post
title:      Accounting Project
subtitle:   ANU_BUSN2011
date:       2019-07-20
author:     Phillip
header-img: img/post-bg-universe.jpg
catalog: true
tags:
    - research project
    - accounting
---


> Group Assignment Projects for Accounting

<font face="Times New Roman">
This semester is quite busy for me because apart from backend development learning, I also have three accounting research projects at the same time. Now, since most of research projects have completed, I want to sort out all my current individual and group research accounting projects, maybe I will add more in my further studying.  <br><br>

Accounting is a subjective discipline. Compared with traditional accounting, t seems most of my friends prefer to choose consulting. For me, accounting is a tool (or skill). I'm not sure whether I will be able to a eligible accountant in the future. But maybe I need to pass CPA exams at first and then consider later things.

<font size="1"><font face="Times New Roman">***Notice**: The requirements of the projects are reserved by ©Australian National University, the projects are all reserved by ©authors written in the report.*</font><br />

## BUSN 2011 Management Accounting

In this assignment, my primiary mission is to calculate three different types of ornaments with ABC method and do regression analysis. I complete all the calculated tables and regression diagrams by Excel and R.

Team assignemnt: <a href="https://raw.githubusercontent.com/u5656487/u5656487.github.io/master/img/Ass_2011_S1.pdf" target="_blank">BUSN 2011 Group Assignment</a>

The group project:<a href="https://raw.githubusercontent.com/u5656487/u5656487.github.io/master/img/BUSN2011_Group_Assignment.pdf" target="_blank">BUSN 2011 Group Assignment</a>


## BUSN 3003 Advanced Management Accounting

	git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
	cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc

重新打开终端，输入

	zsh

即可切换终端，并且发现 oh my zsh 已经帮我们配置好 zsh 了

## BUSN 3001 Accounting Theory

	open ~/.zshrc

修改 `ZSH_THEME=”robbyrussell”`，主题在 ~/.oh-my-zsh/themes 目录下。
修改为

	ZSH_THEME="kolo"

可以[参照这里](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)进行选择.

## 设置为默认shell

	chsh -s /bin/zsh

## 添加自定义命令

	open ~/.zshrc
添加显示隐藏文件的快捷命令

	alias fd='defaults write com.apple.finder AppleShowAllFiles -boolean true ; killall Finder'
	alias fh='defaults write com.apple.finder AppleShowAllFiles -boolean false ; killall Finder'

</font>