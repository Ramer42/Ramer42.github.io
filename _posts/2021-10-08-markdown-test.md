---
layout:     post
title: Markdown Test
date:       2021-10-08 12:00:00
author:     "LPZhang"
catalog: false
header-style: text
tags: 
  - test
---

Ramerzhang's Blog
======
Content
---------
# Ramerzhang's Blog
#### Ramerzhang's Blog

欢迎使用 **{小书匠}(xiaoshujiang)编辑器**，您可以通过 `小书匠主按钮>模板` 里的模板管理来改变新建文章的内容。

> 引用

###### 超链接
[github](https://github.com/Ramer42/Ramer42.github.io)

###### 图片
![](https://github.com/Ramer42/Ramer42.github.io/blob/master/img/404-bg.jpg?raw=true)

###### 动图
![](https://github.com/Ramer42/Ramer42.github.io/blob/master/img/shishi.gif?raw=true)

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
public class OomageTestUtility {
    public static boolean haveNiceHashCodeSpread(List<Oomage> oomages, int M) {
        int[] bucketList = new int[M];
        for (Oomage o : oomages) {
            int bucketNum = (o.hashCode() & 0x7FFFFFFF) % M;
            bucketList[bucketNum] = bucketList[bucketNum] + 1;
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

From the `hashCode` of `ComplexOomage`, we can calculate the hashcode given length of list $N$ and each argument $s$ from the function below:

$${s_1} \times {256^{N - 1}} + {s_2} \times {256^{N - 2}} + {s_3} \times {256^{N - 3}} +  \ldots  \ldots  + {s_{N - 1}} \times {256^0}$$

<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=34341360&auto=0&height=66"></iframe>

<audio id="audio" controls="" preload="none">
      <source id="mp3" src="http://music.163.com/song/media/outer/url?id=1382359170.mp3"></audio>

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<video src="https://apd-05d336a1b4772da1e283799cf0c551fa.v.smtcdns.com/vhot2.qqvideo.tc.qq.com/A2MpZpoZp960E9gqArnh3G34Wi_9zUANpgm3UGU29zgM/uwMROfz2r5zEIaQXGdGnC2dfJ6norVr71SyOzMWdO4L-7R5f/o09294fum1s.p701.1.mp4?sdtfrom=v1104&guid=a4106cc96ce1444bd03862a74a82d1b6&vkey=7A77CC2285DCB33DDA884E80CDE79957D9548DE12C9CCE43F39EEB0C01B140E1771ECDA0177F9476DB13D06EDA7B0049E9109BFBAEA1828B3D9E706BBC58BBAFCE7F334627C48533FF03B35EEF0026DD89E21E82C4212743C8B4D4A564E6DAB58B308B8956A6F375E161343E37297896B11B8C7D315AE83FC4ED6DDE0D54357F" width="800px" height="600px" controls="controls"></video>
