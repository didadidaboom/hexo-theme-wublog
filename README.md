# hexo-theme-wublog
> Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io) and [kaijun](https://github.com/Kaijun/hexo-theme-huxblog).
>
> ***中文使用手册在下面***

## [Demo](https://didadidaboom.github.io/blog/):

![](https://didadidaboom.github.io/blog/img/example.jpg)

## Usage

+ Init

  ```shell
  #way 1：
  git clone https://github.com/didadidaboom/hexo-theme-wublog.git
  cd hexo-theme-wublog
  npm install
  
  #way 2：
  git clone https://github.com/didadidaboom/hexo-theme-wublog/theme/wublog theme/wublog
  ```

  

+ modify

  modify the deploy part of `_config.yml` file under your blog project

  ```shell
  deploy:
    type: git
    repo: git@github.com:didadidaboom/blog.git
    branch: gh-pages
  ```

+ writing/server/deploy

  ```shell
  # create a new template for publishing
  hexo new post <new-post-name>
  # clean caches
  npm run clean
  # build static file
  npm run build
  # run the blog project on local server
  npm run server
  # deploy the blog project on remote server
  npm run deploy
  ```

## 使用步骤

+ 相关依赖的初始化

  ```shell
  #第一种方式(整个文件下载)：
  git clone https://github.com/didadidaboom/hexo-theme-wublog.git
  cd hexo-theme-wublog
  npm install
  
  #第二种方式（主题的下载）：
  git clone https://github.com/didadidaboom/hexo-theme-wublog/theme/wublog theme/wublog
  ```

  

+ 部署配置修改

  修改博客项目目录下的`_config.yml`文件的部署配置

  ```shell
  deploy:
    type: git
    repo: git@github.com:didadidaboom/blog.git
    branch: gh-pages
  ```

  

+ 发文章/本地和远程服务器部署

  ```shell
  # 新文章模板
  hexo new post <new-post-name>
  # 清楚部署相关缓存
  npm run clean
  # 构建博客相关静态页面
  npm run build
  # 在本地运行博客项目
  npm run server
  # 在远程服务器部署博客项目
  npm run deploy
  ```

  
