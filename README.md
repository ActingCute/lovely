# lovely

## 博客重写计划启动 -- 2019-04-11 15:09

## 安装依赖

    npm install
    cd themes\next
    npm install

### hexo

    npm install -g hexo-cli

### pace

    cd themes/next
    git clone https://github.com/theme-next/theme-next-pace source/lib/pace

### neat 压缩

    npm install hexo-neat --save

### 七牛

    npm install hexo-qiniu-sync --save

#### 生成七牛路径

    hexo g

### pace

    cd themes\next\lib
    git clone https://github.com/theme-next/theme-next-pace pace

### 统计

    npm install hexo-leancloud-counter-security --save
    hexo lc-counter register rem486@qq.com aptx4869CONAN

    参考 https://vonsdite.cn/posts/74d5335f.html

#### 直推工具

    npm install --save hexo-deployer-git

#### 提交

    hexo clean
    hexo g -d
