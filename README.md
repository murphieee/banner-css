# banner-css
## 简介
仅使用CSS完成banner点击切换图片
## 知识点
1. input(checkbox) 与 label的共用，实现图片切换与点击区域的绑定. <br>
**注意：input在html的位置，方便~选择器选择图片。**
2. 定位：position：absolute; 脱离文档流，需要父级relative;
3. rgba 与 opcity的区别： opacity会使所有子元素透明。
4. ~选择器，选择兄弟元素； nth-child()的应用。
5. vertical-align： inline-block的对齐方式
6. 设置背景渐变：```background: linear-gradient(to right, rgba(0,0,0,0.8), transparent);```
7. ```display: inline-block; display: block;```
8. 垂直居中:
    - 直接设定top；
    - `postion: absolute;`
        `top: 50%;`
        `margin-top: -height/2;`

