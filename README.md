# makrdown-tool
cosx的markdown工具, 公众号一键部署


# 需要完成的功能

- [ ] 公式的转化: 从`` `$ `` `` $` `` 到 `$`
- [ ] 链接的转化: 从`![]()` 变成脚注下方注明
- [ ] CSS优化: 大标题等内容的CSS优化
- [ ] 图片: 微信编辑器不允许直接复制图片 需要想办法从第三方上传图片
- [ ] 公式: 需要转化成图片插入
- [ ] 清理YAML: YAML需要转化成标题等内容
- [ ] 作者信息: 需要抓过来作者信息进行更新

# 可能的解决方案

## 秀米

* 处理方式: 把文章内容复制进秀米, 手动调整样式, 再粘贴到微信
* 优点: 可以直接把图片, 公式复制过去
* 缺点: 每次样式都需要调整, 链接需要手动转化, 代码可能错行
* 资源: [秀米](https://xiumi.us/)

## 浏览器扩展

- 处理方式: md文件复制进编辑器, 使用扩展工具一键转化  
- 优点: 方便迅速  
- 缺点: 图片公式无法直接上传, 需要写JS扩展程序  
- 资源: [markdown-here](https://github.com/adam-p/markdown-here)  

## 本地(travis)生成

- 处理方式: md文件生成HTML, 复制进编辑器  
- 优点: 可以用吃饭的工具搞定   
- 缺点: 用起来可能没那么方便, 图片公式依旧无法上传  
- 资源: [wx-article-starter](https://github.com/wizicer/wx-article-starter)
 

 
