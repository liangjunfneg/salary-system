# salary-system
# 工资管理系统 (Salary Management System)

## 项目概述
这是一个基于React+TypeScript(前端)和Spring Boot(后端)的工资管理系统，采用MySQL作为数据库。系统实现了员工信息管理、工资计算与发放、奖惩记录、部门管理等核心功能，支持管理员和普通员工两种角色。
管理账号：admin 密码：123456，普通员工：lisi 密码：123456
附：完整版的软件工程代码开发文档，包含详细的需求分析、概要设计详细设计等和详细的软件测试部分，包括功能测试（黑白盒）和性能测试等，性能部分使用JMeter进行。bro比较忙，其余不完善部分后面有需要再好好完善。
## 功能特性
### 1. 员工管理
- 员工基本信息维护（姓名、性别、身份证号等）
- 部门分配与职位管理
- 员工入职/离职/调动记录
- 基本工资设置与调整

### 2. 工资管理
- 月度工资计算与发放
- 工资组成项配置（基本工资、绩效工资、奖金等）
- 个税、社保、公积金自动计算
- 工资条生成与查询

### 3. 部门管理
- 部门信息维护
- 部门主管设置
- 部门人员统计

### 4. 奖惩管理
- 员工奖惩记录
- 奖惩金额自动关联工资计算
- 奖惩审批流程

## 技术栈

### 前端技术
- React 18 + TypeScript
- Ant Design 组件库
- Axios HTTP客户端
- React Router 路由管理

### 后端技术
- Spring Boot 3.x
- MyBatis 数据库访问
- MySQL 9.0
- JWT 认证

### 开发工具
- Node.js 16+
- Maven 3.8+
- JDK17

## 数据库设计
系统包含以下主要数据表：

| 表名 | 描述 |
|------|------|
| `department` | 部门信息 |
| `employee` | 员工基本信息 |
| `salary` | 工资记录 |
| `salary_config` | 薪资计算配置 |
| `reward_punishment` | 奖惩记录 |
| `user` | 系统用户 |

## 安装与运行

### 前端运行
```bash
cd d:\web系统开发\react\salary
npm install
npm start

项目截图：
<img width="1078" alt="屏幕截图 2025-05-28 121109" src="https://github.com/user-attachments/assets/2dbee606-ab75-4815-acbe-3b411dc6a7b5" />
<img width="1076" alt="屏幕截图 2025-05-28 104830" src="https://github.com/user-attachments/assets/5b462e54-e1ad-40b4-a8e1-96d1442b516a" />
<img width="1078" alt="屏幕截图 2025-05-28 121109" src="https://github.com/user-attachments/assets/fecba899-2c98-483c-9a77-abac7568a27a" />
<img width="1078" alt="屏幕截图 2025-05-28 121109" src="https://github.com/user-attachments/assets/5abc84e0-21de-485d-833a-c0f5df3f0709" />
<img width="1077" alt="屏幕截图 2025-05-28 121015" src="https://github.com/user-attachments/assets/1cfe0861-9a3f-462e-b7aa-66a2ca62b177" />
<img width="1078" alt="屏幕截图 2025-05-28 121005" src="https://github.com/user-attachments/assets/5c9d734c-9ff1-4725-9f25-01b99c200b20" />
<img width="1078" alt="屏幕截图 2025-05-28 121005" src="https://github.com/user-attachments/assets/96c17fce-63fe-45b1-9005-571c6be80a8b" />

前台：
<img width="1078" alt="屏幕截图 2025-05-28 104737" src="https://github.com/user-attachments/assets/7371e37b-ee9e-4c56-8668-6e123b65958a" />





