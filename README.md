# HotPostShow

根据typecho的热门文章用滑动幻灯片的形式在相应页面展示出来

# 原理
通过对post的views字段进行排序输出对应的thumb字段值，用carousel.min.js达到幻灯片滑动播放。

# 使用
1. 文件夹命名为`HotPostShow` 

2. 在需要展示的地方填上 `<?php SlideShow_Plugin::outputSlideShow() ?> `即可

3. 文章需要设置`thumb` 自定义字段，这里需要填写图片地址，如不填写则出现空白的情况。

   如：自定义字段 thumb ：　http://xxxx.com/bg.png 

# 注意
确保文章有views字段，可以通过插件或主题方法实现。
