### 页面添加水印

### 三种实现方式
- div (sy-div.html)
- canvas (sy-canvas.html)  这种实现方式增加了元素监听，用户无法通过F12删除/修改元素 
- svg (sy-svg.html)

### 上面三种方式中canvas，还有缺陷。如果用户禁用JavaScript，就可以直接删掉元素。业内还有一种暗水印的实现方式，通过修改图片的像素点，后面有需要再深入
### 以上参考自 https://segmentfault.com/a/1190000038365780?utm_source=weekly&utm_medium=email&utm_campaign=SegmentFault%20%E7%B2%BE%E9%80%89%E6%AF%8F%E5%91%A8%E7%B2%BE%E9%80%89%E4%B8%A8%E5%89%8D%E7%AB%AF%E8%A3%85%E9%80%BC%E6%8A%80%E5%B7%A7%20108%20%E5%BC%8F%E4%B8%A8%E4%BD%A0%E5%8F%AF%E8%83%BD%E4%B8%8D%E7%9F%A5%E9%81%93%E7%9A%849%E6%9D%A1%20Webpack%20%E4%BC%98%E5%8C%96%E7%AD%96%E7%95%A5


### 图片添加水印
- canvas (sy-img.html) 原理很简单，直接在canvas调用 strokeText 或者 fillText