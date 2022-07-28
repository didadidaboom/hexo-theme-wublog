# hexo-theme-wublog
> Ported Theme of [Hux Blog](https://github.com/Huxpro/huxpro.github.io) and [kaijun](https://github.com/Kaijun/hexo-theme-huxblog).

## [Demo](https://didadidaboom.github.io/blog/):

![](https://didadidaboom.github.io/blog/img/example.jpg)

## Usage

+ Init

  ```shell
  #第一种方式：
  git clone https://github.com/didadidaboom/hexo-theme-wublog.git
  cd hexo-theme-wublog
  npm install
  
  #第二种方式：
  git clone https://github.com/didadidaboom/hexo-theme-wublog/theme/wublog theme/wublog
  ```

  

+ modify

  modify the deploy part of `_config.yml` file under your blog

  ```
  deploy:
    type: git
    repo: git@github.com:didadidaboom/blog.git
    branch: gh-pages
  ```

+ writting/server/deploy

  ```shell
  # write post
  hexo new post <new-post-name>
  # clean 
  npm run clean
  # build static file
  npm run build
  # run blog on local
  npm run server
  # deply blog to remote server
  npm run deploy
  ```
