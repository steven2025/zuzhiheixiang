# 组织黑箱诊断教学平台：7文件静态版

## 文件结构
- index.html：主程序，包含全部前端逻辑和样式
- data/horizontal_baijiu_2025.json：白酒行业2025横向对比
- data/horizontal_robot_2025.json：机器人行业2025横向对比
- data/vertical_moutai_2023_2025.json：贵州茅台纵向对比
- data/vertical_luzhoulaojiao_2023_2025.json：泸州老窖纵向对比
- data/vertical_roborock_2023_2025.json：石头科技纵向对比
- data/vertical_ecovacs_2023_2025.json：科沃斯纵向对比

另附：
- JSON生成提示词.txt：给豆包/大模型整理年报生成JSON时使用

## 使用方法
1. 把整个文件夹上传到 GitHub Pages。
2. 先直接打开 index.html 测试。
3. 用豆包等工具读取年报，按模板替换6个 JSON 文件内容。
4. 保持文件名不变，前端会自动读取。


本次更新：
- 更新输入/输出指标体系。
- 新增“支付给职工以及为职工支付的现金”作为人力资本投入指标。
- 新增人均净利润、单位人力资本回报率、研发投入产出效率、销售费用产出率、管理费用产出率、资产产出效率。
- 拆分为两份提示词：横向分析_JSON提示词.txt、纵向分析_JSON提示词.txt。
