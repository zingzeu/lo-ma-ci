# 排版样例

## 嵌入图片

将图片放到 `docs/img` 文件夹下。然后在 md 文件中:

```
![内容说明](img/test.png)
```

就会得到
 
---

![内容说明](img/test.png)
*图为某某某某...*

---

> 要注意: 路径是相对的。比如在 `docs/nested/test.md`，同一个图片则要用 `![内容说明](../img/test.png)`

## 嵌入音频

```
<audio controls src="<音频网址>">你的浏览器不支持播放音频</audio>
```
<audio controls src="http://idioms.mindong.asia/assets/audio/2ae5b3ac-0408-4028-a9a0-5b642a219a56.mp3">
你的浏览器不支持播放音频
</audio>

## 嵌入视频

一般视频网站会提供嵌入代码。直接贴入。

<iframe src="//player.bilibili.com/player.html?aid=29214945&cid=50885854&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

## 表格

可以使用 [Markdown 表格生成器](https://tool.lu/tables/)