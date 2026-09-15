---
title: "Growing the efficient frontier on panel trees"
authors: "Lin William Cong, Guanhao Feng, Jingyu He, Xin He"
year: 2025
venue: Journal of Financial Economics 167
doi: 10.1016/j.jfineco.2025.104024
method: ML / test assets
slug: ptree-efficient-frontier
source_file: uploads/1-s2.0-S0304405X25000327-main_7308.pdf
status: carded-from-first14pp
---

# Growing the efficient frontier on panel trees

文章编号 104024。开放获取 CC BY。Feng / He J.：香港 RGC 与 NSFC；InnoHK。R 包 PTree。只根据 PDF 前约 14 页。

## 问题

个股不平衡面板很难直接估切点组合。常用单/双特征排序测试资产跨不到真正的均值–方差前沿，也难捕捉非线性和不对称交互。有没有一种带经济目标的树，能同时长出测试资产和可交易因子。

## 识别

方法论文，不是因果。P-Tree 按特征从上往下切截面，目标是最大化叶组合切点组合（SDF）的夏普，而不是局部预测 MSE。时间不变的树结构让每期叶子是同一套特征组合。Boosted P-Tree 长多因子；随机 P-Forest 做特征重要性和过参数对照。样本内夏普被目标函数直接最大化，不能当发现。

## 数据

美国个股月收益 1981–2020，61 个公司特征。训练/对照还切过 1981–2000 与 2001–2020。

## 主结果

样本内年化夏普：单棵树（10 个组合）约 6.37，20 棵 boosting（200 个组合）约 15.63，远高于常规排序组合和常见因子。作者称样本外夏普仍超过 3，且有显著正 alpha（过去预测未来、未来预测过去）。第一棵树相对 Fama–French 五因子，GRS 约 141.27，多数月度 alpha 大于 1%。随机森林 SDF 样本外夏普接近更大的过参数模型。常被选中的特征包括 SUE、DOLVOL、BM_IA。作者自己写样本内与样本外夏普有缺口。

## 可攻击点

- 6.37 / 15.63 是目标函数内的样本内数字，交易成本、卖空和可交易性前 14 页没有。
- 用夏普当分裂准则，测试资产被「长」出来专门为难别的模型，GRS 高是设计如此。
- 61 个特征的定义和缺失处理决定叶子，换特征集会变。
- 稀疏可解释不等于这些特征就是 SDF 的基本风险。

## 可复用设计

要新测试资产时，把经济目标（切点夏普）写进分裂准则，不要只做 CART 预测。样本内夏普和样本外夏普必须分开报。把 P-Tree 叶子加进模型比较可以，但不要写成发现了新风险因子。

证据指针：摘要（推进前沿、稀疏接近过参数夏普）；引言（1981–2020、61 特征、6.37 / 15.63、OOS 夏普>3、GRS 141.27）。

训练价值：测试资产怎么长、样本内目标函数怎么骗人。方法卡，不当定价发现。
