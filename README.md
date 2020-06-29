# chenchenyi.github.io
在新电脑上操作，先把新电脑上环境安装好，node.js、git、hexo，ssh key 也创建和添加好。
选好博客安装的目录， git clone git@github.com:username/username.github.io.git 。
cd 到博客目录，npm install、hexo g && hexo s，安装依赖，生成和启动博客服务。正常的话，浏览器打开 localhost:4000 可以看到博客了。至此新电脑操作完毕。
以后无论在哪台电脑上，更新以及提交博客，依次执行，git pull，git add -A ，git commit -m "--"，git push origin hexo，hexo clean && hexo g && hexo d 即可.
