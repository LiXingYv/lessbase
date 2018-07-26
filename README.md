# less安装
```
npm install -g less   全局安装less
```

# less编译
```
lessc styles.less styles.css
```

# less压缩编译
需要用到插件less-plugin-clean-css

**插件安装方法：**
```
npm install -g less-plugin-clean-css
```

**压缩编译方法**
lessc styles.less styles.min.css --clean-css="--s1 --advanced --compatibility=ie8"
--compatibility  设置其兼容性
--advanced 添加浏览器厂商标识

**在WebStorm里配置watcher实现编辑less文件时自动生成.map和压缩后的.css文件**
https://blog.csdn.net/lhtzbj12/article/details/54882683