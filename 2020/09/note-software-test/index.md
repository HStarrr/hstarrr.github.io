# 笔记软件测试



<!--more-->

最近由于想换一个笔记软件，需测试笔记软件的 `Markdown` 语法是否完备，所以列举了大部分自己常用的 `Markdown` 语法，以便复制进行测试，如下：

```markdown
# 目录索引测试
[toc]

---

# 标题测试

# 这是 H1 标题

## 这是 H2 标题

### 这是 H3 标题

#### 这是 H4 标题

##### 这是 H5 标题

###### 这是 H6 标题

---

# 引用块测试

> 这是第一行引用块
> 这是第二行引用块
> 
> 这是跨行引用块
> 

---

# 列表测试

* 无序列表 1
* 无序列表 2
* 无序列表 3

1. 有序列表 1
2. 有序列表 2
3. 有序列表 3

---

# 任务列表测试

- [ ] 未完成的列表 1
- [ ] 未完成的列表 2
- [x] 已完成的列表 1
- [ ] 未完成的列表 3

---

# 代码块测试

行内代码：`<h1>Hello, World!</h1>`
代码块：主要查看高亮

HTML
{?`}{?`}{?`}html
<h1>Hello, World!</h1>
{?`}{?`}{?`}

Python
{?`}{?`}{?`}python
print("Hello, World!")
{?`}{?`}{?`}

Java
{?`}{?`}{?`}java
System.out.println("Hello, World!");
{?`}{?`}{?`}

C
{?`}{?`}{?`}c
printf("Hello, World!");
{?`}{?`}{?`}

C++
{?`}{?`}{?`}c++
std::cout << "Hello, World!";
{?`}{?`}{?`}

JavaScript
{?`}{?`}{?`}javascript
<script>console.log("Hello, World!")</script>
{?`}{?`}{?`}

Go
{?`}{?`}{?`}go
fmt.Println("Hello, World!")
{?`}{?`}{?`}

Shell
{?`}{?`}{?`}shell
echo "Hello, World!"
{?`}{?`}{?`}

---

# 表格测试

| 第一个表头  | 第二个表头 |
| ------------- | ------------- |
| 第一行第一列  | 第一行第二列  |
| 第二行第一列  | 第二行第二列  |

---

# 水平线测试

---

---

# 链接测试

这个 [链接](# "我是链接提示") 有提示。
这个 [链接](#) 没有提示。

---

# 图片测试

这个图片没有提示。
![](https://www.baidu.com/favicon.ico)
这个图片有提示。
![我是下方提示](https://www.baidu.com/favicon.ico "我是鼠标放置提示")

---

# 字体测试

我是普通字体
**我是粗体**
*我是斜体*
~~我是删除线~~

---

# Emoji 测试

我是笑脸:smile:

---

# HTML 测试

<span style="color:red">这是红色的 HTML 文本</span>
```
