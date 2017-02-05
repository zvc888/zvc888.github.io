# 准备


### 环境需要 nodejs(6.9.0、4.4.4测试正常)、git、hexo（3.2.2）

### windows安装可能需要
``` 
git config --global core.autocrlf false
git config --system core.longpaths true
```

###在博客目录运行
```
npm install hexo-generator-cname --save
npm install hexo-deployer-git --save
```


### 配置 "_config.yml" 文件
```
deploy:
	type: git
	repo:
	github: https://zvc888:密码@github.com/zvc888/zvc888.github.io.git,master
	message: update in {{now("YYYY-MM-DD HH:mm")}}
```
### 生成html文件，发布

生成
``
hexo g  或者 hexo generator
``  
部署
``
hexo d  或者 hexo deploy
``

本地运行

```
hexo server 或者 hexo s
```
    


### 更换主题
[官网主题网址/](https://hexo.io/themes/ "官网主题网址")

找到想要的主题的github地址然后复制，切换进本地目录

```
git clone https://github.com/hexojs/hexo-theme-landscape.git themes/landscape
```

#### 修改_config.yml

``
theme: landscape
``

重新发布就可以了
[http://wingjay.com/2015/12/07/%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%80%E5%A4%A9%E4%B9%8B%E5%86%85%E6%90%AD%E5%BB%BA%E4%BB%A5%E4%BD%A0%E8%87%AA%E5%B7%B1%E5%90%8D%E5%AD%97%E4%B8%BA%E5%9F%9F%E5%90%8D%E7%9A%84%E5%BE%88cool%E7%9A%84%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/](http://wingjay.com/2015/12/07/%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%80%E5%A4%A9%E4%B9%8B%E5%86%85%E6%90%AD%E5%BB%BA%E4%BB%A5%E4%BD%A0%E8%87%AA%E5%B7%B1%E5%90%8D%E5%AD%97%E4%B8%BA%E5%9F%9F%E5%90%8D%E7%9A%84%E5%BE%88cool%E7%9A%84%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/ "参照资料")
