# vue-mall学习笔记

## 01---项目开发-github托管项目

- 推送远程仓库的两种方式
- 方式一
  - 登录github官网，创建一个空仓库；
  - 通过git clone将仓库克隆到本地；
  - vue-cli3生成的项目通过git命令提交到远程仓库；
    - git add .
    - git commit -m ‘说明’;
    - git push

- 方式二：(推荐)
  - 登录github官网，创建一个空仓库；
  - vue-cli3生成项目；
  - 通过两个git命令将项目推送到远程仓库；
    - git remote add origin https://github.com/yongshenstrong/name.git;
    - git push -u origin master;

## 02---项目开发-划分目录结构

- 划分目录结构
- 