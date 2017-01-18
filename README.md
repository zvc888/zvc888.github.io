# 准备


### 环境需要 nodejs、git、hexo

### windows安装可能需要 



	git aconfig --global core.autocrlf false
	git config --system core.longpaths true

###在博客目录运行



	npm install hexo-generator-cname --save
	npm install hexo-deployer-git --save



### 配置 "_config.yml" 文件



	plugins:
        - hexo-generator-cname

	deploy:
	  type: git
	  repo:
	    github: https://github.com/zvc888/zvc888.github.io.git,master
	  message: update in {{now("YYYY-MM-DD HH:mm")}}


[http://wingjay.com/2015/12/07/%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%80%E5%A4%A9%E4%B9%8B%E5%86%85%E6%90%AD%E5%BB%BA%E4%BB%A5%E4%BD%A0%E8%87%AA%E5%B7%B1%E5%90%8D%E5%AD%97%E4%B8%BA%E5%9F%9F%E5%90%8D%E7%9A%84%E5%BE%88cool%E7%9A%84%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/](http://wingjay.com/2015/12/07/%E5%A6%82%E4%BD%95%E5%9C%A8%E4%B8%80%E5%A4%A9%E4%B9%8B%E5%86%85%E6%90%AD%E5%BB%BA%E4%BB%A5%E4%BD%A0%E8%87%AA%E5%B7%B1%E5%90%8D%E5%AD%97%E4%B8%BA%E5%9F%9F%E5%90%8D%E7%9A%84%E5%BE%88cool%E7%9A%84%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/ "参照资料")
