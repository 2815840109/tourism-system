# 旅游信息管理系统

基于 SpringBoot + Vue 2 的旅游信息管理系统，包含景点、线路、美食、酒店预订、新闻资讯等模块。

## 技术栈

- 后端：Spring Boot 2 + MyBatis + MySQL + PageHelper
- 前端：Vue 2 + Vuex + Vue Router + Element UI + Axios
- 构建：Maven + Webpack

## 目录结构

- client/  Vue 前端
- server/  Spring Boot 后端
- tourism.sql  数据库脚本

## 快速开始

### 1. 导入数据库
mysql -uroot -p < tourism.sql

### 2. 启动后端
cd server
mvnw spring-boot:run

### 3. 启动前端
cd client
npm install
npm run serve