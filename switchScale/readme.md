一个三图轮换放大效果


效果图：

![三图轮换放大](./images/switch-scale.gif)


思路：
1. 只有两种情景，左边大图、右边两个小图  
               右边大图、左边两个小图
2. 通过绝对定位，改变图片的位置以及大小，使用CSS的过渡实现动画。
3. 情景一，.img-1为左边大图，.img-2为右边上边小图，.img-3为右边下边小图  
   情景二，.img-1为左边上边小图，.img-2为左边下边小图，.img-3为右边大图  
4. js只需要修改场景和对应图片类名。