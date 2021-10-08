---
layout:     post
title:      "Markdown Test"
date:       2021-10-08 12:00:00
author:     "LPZhang"
catalog: false
header-style: text
tags:
  - test
---

Ramerzhang's Blog
========
Content
-----------------
# Ramerzhang's Blog
#### Ramerzhang's Blog

欢迎使用 **{小书匠}(xiaoshujiang)编辑器**，您可以通过 `小书匠主按钮>模板` 里的模板管理来改变新建文章的内容。

> 引用

###### 超链接
[github](https://github.com/Ramer42/Ramer42.github.io)

###### 图片
![](https://github.com/Ramer42/Ramer42.github.io/blob/master/img/404-bg.jpg)

###### 视频
[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1633664414/video_to_markdown/images/youtube--kMndV7Fy-zw-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

**这是加粗**
*这是斜体*
~~这是划掉~~

- 项目1
  - 子项目1.1
  - 子项目1.2
    - 子项目1.2.1
- 项目2
- 项目3

1. First
2. Second
3. Serve the website (`localhost:4000` by default):

```java
import java.util.HashMap;
import java.util.List;

public class OomageTestUtility {
    public static boolean haveNiceHashCodeSpread(List<Oomage> oomages, int M) {
        int[] bucketList = new int[M];
        for (Oomage o : oomages) {
            int bucketNum = (o.hashCode() & 0x7FFFFFFF) % M;
            bucketList[bucketNum] = bucketList[bucketNum] + 1;
        }
        for (int k : bucketList) {
            System.out.println(k);
        }
        for (int j : bucketList) {
            if ((j < oomages.size() / 50) || (j > oomages.size() / 2.5)) {
                return false;
            }
        }
        return true;
    }
}
```
