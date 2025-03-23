---
title: "Markdown 格式测试"
date: 2024-03-23
draft: false
tags: ["markdown", "测试"]
categories: ["教程"]
---

# Markdown 格式测试

这篇文章展示了各种 Markdown 格式元素在本博客上的渲染效果。

## 1. 基础文本格式

**粗体文本** 和 _斜体文本_

**_粗斜体文本_**

~~删除线文本~~

<u>下划线文本</u>

## 2. 列表

### 无序列表

- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
- 项目 3

### 有序列表

1. 第一步
2. 第二步
   1. 子步骤 2.1
   2. 子步骤 2.2
3. 第三步

### 任务列表

- [x] 已完成的任务
- [ ] 未完成的任务
- [ ] 另一个未完成的任务

## 3. 链接和图片

[Hugo 官方网站](https://gohugo.io/)

![Hugo Logo](https://d33wubrfki0l68.cloudfront.net/c38c7334cc3f23585738e40334284fddcaf03d5e/2e17c/images/hugo-logo-wide.svg)

## 4. 引用

> 这是一段引用的文字。
>
> 这是引用的第二段落。

## 5. 代码

行内代码 `print("Hello, World!")`

代码块：

```python
def greet(name):
    """
    一个简单的问候函数
    """
    print(f"Hello, {name}!")

# 调用函数
greet("World")
```

```javascript
// JavaScript代码示例
function calculateSum(a, b) {
  return a + b;
}

console.log(calculateSum(5, 10)); // 输出: 15
```

## 6. 表格

| 名称 | 年龄 | 职业     |
| ---- | ---- | -------- |
| 张三 | 25   | 工程师   |
| 李四 | 30   | 设计师   |
| 王五 | 28   | 产品经理 |

## 7. 水平分割线

---

## 8. 数学公式

行内公式: $E = mc^2$

独立公式:

$$
\frac{d}{dx}(x^n) = nx^{n-1}
$$

## 9. 脚注

这是一个有脚注的文本[^1]。

[^1]: 这是脚注的内容。

## 10. 定义列表

术语 1
: 定义 1

术语 2
: 定义 2a
: 定义 2b
