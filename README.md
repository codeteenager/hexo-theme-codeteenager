# hexo-theme-codeteenager
一款专属程序员的扁平化主题

# 安装教程

```java
	cd yourblog
	git clone git@github.com:codeteenager/hexo-theme-codeteenager.git themes/codeteenager
```

# 启用
修改 _config.yml 中的theme一项的值为codeteenager

# 插件
1. 搜索：安装hexo-generator-search，在yourblog/_config.yml中添加如下配置代码。如果不需要搜索功能，将yourblog/themes/raytaylorism/_config.yml中menu的-id: search那一整项删除即可
```java
search:
  path: search.xml
  field: all
```
2. RSS：安装hexo-generator-feed，并按照说明配置。