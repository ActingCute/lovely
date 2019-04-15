# lovely

## 博客重写计划启动 -- 2019-04-11 15:09

## 安装依赖

    npm install
    cd themes\next
    npm install

### hexo

    npm install -g hexo-cli

#### 直推工具

    npm install --save hexo-deployer-git

#### 提交方案

## 先将源文件/静态文件提交git

    hexo g -d

## 部署到网站

### 修改deploy

     hexo clean
     hexo generate --deploy