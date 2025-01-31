## 项目名称：知识图谱管理系统

### 项目简介

知识图谱管理系统是一个基于 web 的系统，用于展示和管理知识图谱。系统主要用于展示知识图谱的增删改查，底层数据库知识图谱采用 neo4j，关系型数据库采用 sqlite。

### 主要功能

**教师端：**

- 登录、注册、退出、修改密码等功能
- 上传文件（用于知识图谱提取）
- 基于开始节点名称查询知识图谱
- 修改和删除知识图谱的节点


**学生端：**

- 登录、注册、退出、修改密码等功能
- 基于开始节点、结束节点和关系查询知识图谱


### 技术架构

- 前端：React
- 后端：Python
- 数据库：neo4j、sqlite


### 使用说明

**教师端：**

1. 登录系统
2. 上传文件
3. 基于开始节点名称查询知识图谱
4. 点击节点跳转修改页面，或点击删除按钮删除节点


**学生端：**

1. 登录系统
2. 输入开始节点、结束节点和关系来查询知识图谱


### 联系方式

**微信号：zt745324325**