### 一周一文
----

#### markdown 常用语法整理（20190327）
----

1. 标题

  ```
    # h1
    ## h2
    ### h3
    #### h4
    ##### h5
    ###### h6
  ```

  # h1
  ## h2
  ### h3
  #### h4
  ##### h5
  ###### h6
2. 单行引用

    ```
      > markdown code
      >> code
    ```
    > markdown code
    >> code
3. 多行引用

    ```
    > markdown!
      github!
      博客园!
      penCode!
    ```
    > markdown!
    github!
    博客园!
    penCode!

4. 代码
  4.1 单行代码
  ```
    行内标记 `markdown code pyrenees`
  ```
  4.2 多行代码块
  ```html
    <div>
      <div>1</div>
      <div>2</div>
      <div>3</div>
    </div>
  ```

  ```javascript
    const name = "github"
    console.log(name)
  ```

5. 链接

  [pyreneesGoat--codePen](https://codepen.io/pyreneesgoat/)
  [博客园](https://home.cnblogs.com/u/lhd404/)
  [百度](http://www.baidu.com/)

6. 图片

  ```
    ![图片...](https://upload-images.jianshu.io/upload_images/6912209-8c53b79a706bb7c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/273/format/webp)
  ```

  ###### 效果：
  ![图片...](https://upload-images.jianshu.io/upload_images/6912209-8c53b79a706bb7c2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/273/format/webp)


7. 序号
  7.1 有序

  ```
    1. one
    2. two
    3. three

  ```

  7.2 无序

  ```
    * one
    * two
    * three
  ```

  7.3 序号嵌套

  ```
    * one
      1. one-1
      2. two-1
      3. three-1
      4. four-1
    * two
      1. one-2
      2. two-2
      3. three-2
    * three
    * four
  ```

8. 任务列表

  - [ ] 吃饭
  - [ ] 睡觉
  - [ ] 打游戏
  - [x] 学习

9. 表格

  ###### 代码1

```
| a | b | c |
|:--:|:-- | --:|
|居中|左对齐|右对齐|
```
  ###### 代码2

```
 a | b | c
 :-:|:-|-:
 居中|左对齐|右对齐
```

10. 常用语义标记

|   描述    | 代码            |
|:---------:| --------------- |
|   斜体    | *斜体*          |
|   斜体    | _斜体_          |
|   加粗    | **加粗**        |
| 加粗+斜体 | ***加粗+斜体*** |
| 加粗+斜体 | **_加粗+斜体_** |
|  删除线   | ~~删除线~~      |

11. 分隔符
  ```
    ***
    ---
  ```
12. 脚注
  ```
  Markdown[^1]
  Canvas[^2]
  [^1]: Markdown 是一种文本标记语言。
  [^2]: <canvas> 标签只是图形容器，您必须使用脚本来绘制图形
  ```
13. [Makedown 编写工具](https://typora.io/)
