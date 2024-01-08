

```bash
# https://npmmirror.com
$ npm install -g cnpm --registry=https://registry.npmmirror.com    
$ vue init webpack my_webpack

# 进入项目，安装并运行
$ cd my-my_webpack
$ npm install
$ npm run dev

# Vue 项目打包，会生成 dist 就是目标产物。
$ npm run build
```







```html
<!DOCTYPE html><html><head><meta charset=utf-8><meta name=viewport content="width=device-width,initial-scale=1"><title>my_webpack</title><link href=/static/css/app.30790115300ab27614ce176899523b62.css rel=stylesheet></head><body><div id=app></div><script type=text/javascript src=/static/js/manifest.2ae2e69a05c33dfc65f8.js></script><script type=text/javascript src=/static/js/vendor.5757ca66c9a222917873.js></script><script type=text/javascript src=/static/js/app.b22ce679862c47a75225.js></script></body></html>

==> 绝对路径 修改为 相对路径 -> 去掉 /  -> https://www.runoob.com/vue2/vue-install.html 文末

<!DOCTYPE html><html><head><meta charset=utf-8><meta name=viewport content="width=device-width,initial-scale=1"><title>my_webpack</title><link href=static/css/app.30790115300ab27614ce176899523b62.css rel=stylesheet></head><body><div id=app></div><script type=text/javascript src=static/js/manifest.2ae2e69a05c33dfc65f8.js></script><script type=text/javascript src=static/js/vendor.5757ca66c9a222917873.js></script><script type=text/javascript src=static/js/app.b22ce679862c47a75225.js></script></body></html>
```



修改 `index.html` 之后双击即可运行看到效果
