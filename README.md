# Calorie Mahjong Calculator
<p>一个轻量级的网页应用，用于记录、计算并展示多局麻将对战中的卡路里消耗分数。支持随机因子引入，使结果更具趣味性和不可预测性。</p>

## 🧮功能介绍

- ✍️ 支持每局输入 4 位玩家的数据
- 🧑‍🤝‍🧑 玩家名称可编辑（支持中文、英文自动限制长度）
- ➕ 动态添加多局数据
- 🔄 可选开启「随机乘数」和「随机加数」模拟不可控的热量波动
- 📊 自动计算每位玩家总和分数
- 🍪 数据将自动保存在浏览器 Cookie 中（包括玩家名称、输入值、随机数、设置等）

## 🎲随机机制说明
### 随机乘数 
- 范围：[0.00, 10.00]
- 概率：
  - 增加：89.91%
  - 不变或减少：9.99%
  - 赦免：0.1%

### 随机加数 
- 范围：[0.00, 25.00]
- 概率：
  - 增加：95.96%
  - 不变或减少：4%
  - 赦免：0.04%

## 📦 使用方法
1. 打开 index.html 文件（可直接双击或直接访问 https://single0walker.github.io/CalorieMahjongCalculator/  ）
2. 输入每局每位玩家的数据
3. 点击「计算」按钮，查看带有随机因子的得分结果
4. 可通过「添加数据行」继续记录更多局
5. 可通过「清空」按钮移除所有记录和缓存

## 📝 更新日志
### 2025/06/09
- 添加随机加数机制：即使全胜也可能被惩罚
- 祝你好运 😛

### 2025/06/09
- 随机数保留两位小数
- 新增概率说明
- 调整命名规则

---

<p>A lightweight web application for recording, calculating, and displaying calorie consumption scores across multiple Mahjong rounds. Supports the introduction of random factors to make results more fun and unpredictable.</p>

## 🧮 Features

- ✍️ Input data for 4 players per round
- 🧑‍🤝‍🧑 Editable player names (auto-limit length for both Chinese and English)
- ➕ Dynamically add multiple rounds of data
- 🔄 Optional toggles for "Random Multiplier" and "Random Adder" to simulate uncontrollable calorie fluctuations
- 📊 Automatically calculates total score for each player
- 🍪 Data is automatically saved in browser cookies (including player names, input values, random numbers, settings, etc.)

## 🎲 Random Mechanism Explanation
### Random Multiplier
- Range: [0.00, 10.00]
- Probability:
  - Increase: 89.91%
  - No change or decrease: 9.99%
  - Immunity: 0.1%

### 随机加数 
- Range: [0.00, 25.00]
- Probability:
  - Increase: 95.96%
  - No change or decrease: 4%
  - Immunity: 0.04%

## 📦 How to Use
1. Open the index.html file (double-click directly or visit the website at https://single0walker.github.io/CalorieMahjongCalculator/  )
2. Enter data for each player per round
3. Click the "Calculate" button to view results with random factors
4. Use the "Add Data Row" button to record more rounds
5. Use the "Clear" button to remove all records and cached data

## 📝 Changelog
### 2025/06/09
- Added random adder mechanism: even a full win might come with penalties
- Good luck 😛

### 2025/06/09
- Random values now retain two decimal places
- Added probability explanation
- Adjusted naming rules
