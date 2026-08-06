# 数据结构与算法学习笔记

这是我学习数据结构与算法时整理的个人笔记与 Python 代码实践仓库。学习内容主要参考开源教程 [《Hello 算法》](https://www.hello-algo.com/)。

本仓库用于记录学习过程：理解数据结构的工作原理、分析算法的时间与空间复杂度，并通过代码实现巩固所学知识。

## 学习内容

- 数据结构：数组、链表、栈、队列、哈希表、树、堆与图
- 基础算法：遍历、查找与排序
- 算法思想：分治、回溯、贪心与动态规划
- 复杂度分析：时间复杂度与空间复杂度

## 项目结构

```text
.
├── algorithms-notes.md     # 个人学习笔记与知识总结
├── codes/
│   └── python/             # Python 算法实现与练习
├── docs/                   # 《Hello 算法》课程文档与配套资源
├── pyproject.toml          # Python 项目配置
└── README.md
```

## 运行代码

项目代码使用 Python 编写。进入代码目录后，可以运行全部测试：

```bash
cd codes/python
python test_all.py
```

也可以直接运行某个章节中的单个示例：

```bash
python chapter_sorting/quick_sort.py
```

## 学习笔记

学习笔记见 [algorithms-notes.md](./algorithms-notes.md)，主要包含：

- 常用数据结构的特点与操作复杂度
- 常见算法的思路与适用场景
- 易混淆知识点和个人理解

## 说明

- 本仓库是个人学习记录，代码以理解算法思想为主要目标，并非生产环境实现。
- 笔记和代码会随着学习与复习持续补充、修正和重构。
- `docs/` 目录中的教程文档、图片和示例代码来源于《Hello 算法》项目，其版权与许可证以原项目说明为准。

## 参考资料

- [《Hello 算法》在线教程](https://www.hello-algo.com/)
- [《Hello 算法》GitHub 仓库](https://github.com/krahets/hello-algo)

## License

本仓库保留原项目的 [LICENSE](./LICENSE)。提交或使用仓库内容时，请同时遵守《Hello 算法》及其原始许可证的相关要求。
