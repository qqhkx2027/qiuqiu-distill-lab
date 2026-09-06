# QiuQiu 蒸馏基座（Distill Hub）

把“一个人的思维方式、一本书的方法、一篇文章的结构”，蒸馏成 AI 能反复调用的 Skill。

一个基座仓库，统一管理所有已蒸馏对象；新对象按 template 复制新增即可。

---

## 这个仓库是什么

很多人都在做“蒸馏”：把散落的知识打包成 AI 能直接加载的模块。
这个仓库是秋秋的个人蒸馏基座：

- 一个对象（名人 / 书 / 文章）一个目录，统一放 distilled/
- 一个空白模板 template/ ，复制即用
- 一套方法说明 docs/methods.md
- 一组实验案例 experiments/ （用 5 种方法蒸馏同一篇文章的对比）

## 已蒸馏

| 对象 | 类型 | 位置 | 说明 |
| --- | --- | --- | --- |
| Dan Koe《How to fix your entire life in 1 day》 | 文章 + 作者方法 | distilled/dan-koe/ | 一天内重启生活：身份循环 → 24 小时协议 → 六项输出 |

## 怎么开始蒸馏一个新人/书/文章

1. 复制模板：
   cp -r template/ distilled/你的名字/
2. 打开 distilled/你的名字/SKILL.md ，按注释替换成真实内容
3. 把原材料放到 source.md 或 references/
4. 按 docs/methods.md 选 1-2 种方法做蒸馏
5. 更新本 README 的“已蒸馏”表格，提交

## 蒸馏方法一览（快速）

| 方法 | 适合 | 产物 |
| --- | --- | --- |
| CLAUDE.md 极简法 | 给 AI 行为守则 | 几条规则 |
| 人物心智蒸馏（女娲式） | 借鉴某人思维方式 | 五层认知 |
| 课程化蒸馏（仓颉式） | 体系化学习 | 6-8 模块课 |
| book-to-skill 式 | 省 token 随时查 | 核心索引+章节 |
| 综合成 Skill（默认） | 直接落地 | SKILL.md + references |

详细对比和示例见 docs/methods.md、experiments/ 。

## 模板

- template/ —— 空白模板（含 SKILL.md 骨架与说明）

## 合规与边界

- 只用公开资料做“方法提炼”，不全文复制原文。
- 名人心智蒸馏不等于“数字分身”，不冒充本人权威，不替代心理治疗。
- 反蒸馏方法仅作理解，不鼓励规避公司合规义务。

## Other

旧仓库 qiuqiu-dankoe-thinking-skill 已并入本仓库（distilled/dan-koe/），
原仓库仍在线，README 会放迁移说明。

