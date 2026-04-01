# 输出文件清单

---

## Q1: 数据获取与整理

### 数据文件
- `../data_clean/returns.csv` - 5只股票和沪深300的日对数收益率
- `../data_clean/prices.csv` - 5只股票和沪深300的日收盘价

### 统计结果
- `Q1_data/descriptive_statistics.csv` - 描述性统计（均值、标准差、偏度、峰度）
- `Q1_data/jarque_bera_test.csv` - Jarque-Bera正态性检验

### 图表
- `Q1_data/returns_timeseries_faceted.png` - 分面收益率时序图
- `Q1_data/returns_timeseries_overlay.png` - 叠加收益率对比图
- `Q1_data/CSI300_returns_timeseries.png` - 沪深300收益率时序图

---

## Q2: 全样本Beta系数估计

- `Q2_beta/full_sample_beta.csv` - CAPM回归结果（Alpha、Beta、R²）
- `Q2_beta/residual_diagnostics.csv` - 残差诊断（Ljung-Box、White检验）

---

## Q3: 分年度Beta系数估计

- `Q3_yearly_beta/yearly_beta.csv` - 分年度Beta（长格式）
- `Q3_yearly_beta/yearly_beta_pivot.csv` - 分年度Beta（宽格式）
- `Q3_yearly_beta/yearly_beta.png` - 分年度Beta折线图

---

## Q4: 滚动Beta系数估计

- `Q4_rolling_beta/rolling_beta.csv` - 60日滚动Beta时序
- `Q4_rolling_beta/rolling_beta_stats.csv` - 滚动Beta统计特征
- `Q4_rolling_beta/rolling_beta.png` - 滚动Beta时序图
- `Q4_rolling_beta/rolling_beta_faceted.png` - 滚动Beta分面图

---

## Q5: 相关性分析

- `Q5_correlation/correlation_matrix.csv` - 相关系数矩阵
- `Q5_correlation/rolling_correlation.csv` - 滚动相关系数
- `Q5_correlation/correlation_heatmap.png` - 相关系数热力图
- `Q5_correlation/rolling_correlation.png` - 滚动相关系数时序图

---

## Q6: 等权重投资组合分析

- `Q6_portfolio/portfolio_performance.csv` - 组合绩效指标
- `Q6_portfolio/nav_data.csv` - 净值数据
- `Q6_portfolio/portfolio_nav.png` - 组合净值曲线

---

## Q7: 有效前沿分析（选做）

- `Q7_efficient_frontier/efficient_frontier_portfolios.csv` - 有效前沿组合
- `Q7_efficient_frontier/efficient_frontier.png` - 有效前沿曲线图

---

## 目录结构

```
output/
├── README.md
├── Q1_data/                    # 问题1输出
├── Q2_beta/                    # 问题2输出
├── Q3_yearly_beta/             # 问题3输出
├── Q4_rolling_beta/             # 问题4输出
├── Q5_correlation/             # 问题5输出
├── Q6_portfolio/               # 问题6输出
└── Q7_efficient_frontier/     # 问题7输出
```