---
title: 插件功能测试：代码高亮+全站搜索验证
date: 2026-06-28 21:00:00
tags: [Hexo, 建站, 插件测试]
categories: [技术笔记]
---

# 一、测试Prism代码高亮功能
## Python示例代码
```python
# AI副业小脚本：批量打印学习记录
def study_record():
    study_list = ["Python基础", "RAG知识库实战", "Hexo个人博客搭建"]
    for item in study_list:
        print(f"今日学习内容：{item}")

if __name__ == "__main__":
    study_record()