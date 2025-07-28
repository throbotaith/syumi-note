# syumi-note


* 勉強ノートですので正確とは限りません．途中の物もいくつかあります．
* アウトプットをしすぎて復習ができていないので,週に1日は復習日とし，新たな知見があれば反映します.
* 学びノートを追加しました．散らかりがちな各論文や本での発見を1つのページにまとめます．
# 分野別のNotebook一覧





## 強化学習 

### Reinforcement Learning : Theory and Algorithms
- 第1章：[RL_Theorybook_Chapter_1.ipynb](RL_Theorybook_Chapter_1.ipynb)
- 第1章(線形計画問題と双対)：[RL_Theorybook_Chapter_1_LP.ipynb](RL_Theorybook_Chapter_1_LP.ipynb)
- 第1章（線形計画問題の実装）：[RL_Theorybook_Chapter_1_LP_implement.ipynb](RL_Theorybook_Chapter_1_LP_implement.ipynb)
- 第2章：[RL_Theorybook_Chapter_2.ipynb](RL_Theorybook_Chapter_2.ipynb)
- 第3章：[RL_Theorybook_Chapter_3.ipynb](RL_Theorybook_Chapter_3.ipynb)
- 第4章：[RL_Theorybook_Chapter_4.ipynb](RL_Theorybook_Chapter_4.ipynb)
- 第5章：[RL_Theorybook_Chapter_5.ipynb](RL_Theorybook_Chapter_5.ipynb)
- 第11章：[RL_Theorybook_chapter_11.ipynb](RL_Theorybook_chapter_11.ipynb)
- 第12章：[RL_Theorybook_Chapter_12.ipynb](RL_Theorybook_Chapter_12.ipynb)
- 第14章（Conservative Policy Iteration）：[RL_Theorybook_Chapter_14_CPI.ipynb](RL_Theorybook_Chapter_14_CPI.ipynb)
- 第14章（Trust Region Policy Optimization(and PPO)）：[RL_Theorybook_Chapter_14_TRPO_PPO.ipynb](RL_Theorybook_Chapter_14_TRPO_PPO.ipynb)

- 
- 


### ロバストMDP（RMDP）
- RMDP理論論文の証明：[Paper_RMDP_thoery.ipynb](Paper_RMDP_thoery.ipynb)
- RMDPの基礎から方策勾配法まで（メモ）：[RMDP_foundations.ipynb](RMDP_foundations.ipynb)
- RDPにおける動的計画法のPythonコード：[Paper_RDP_implement.ipynb](Paper_RDP_implement.ipynb)
- RMDPにおける方策勾配法の大域的最適性証明：[RMDP_PG_global_optimality.ipynb](RMDP_PG_global_optimality.ipynb)
- モデル推定を行わないRMDP：[Paper_RMDP_wo_model_estimation.ipynb](Paper_RMDP_wo_model_estimation.ipynb)
- Generative modelsを用いたロバスト強化学習のサンプル複雑度： [Paper_Sample_Complexity_of_RMDP.ipynb](Paper_Sample_Complexity_of_RMDP.ipynb)
- ロバスト制約つきMDP，弱凸関数の勾配支配:[Paper_RCMDP_weak_conv_grad_dominance.ipynb](Paper_RCMDP_weak_conv_grad_dominance.ipynb)
- RectangularロバストMDPにおける方策勾配[Paper_RMDP_rectangular_PG.ipynb](Paper_RMDP_rectangular_PG.ipynb)
- 単一ループのRMP：[Paper_Single_loop_RMDP.ipynb](Paper_Single_loop_RMDP.ipynb)

### 制約付きMDP（CMDP）

- Altman本 第3章：[CMDP_Altman_Chapter_3.ipynb](CMDP_Altman_Chapter_3.ipynb)
- RCMDPのサブルーチン：[RCMDP_subrountine.ipynb](RCMDP_subrountine.ipynb)

### ロバスト制約付きMDP（RCMDP）

- EpiRC-PGS0の実装：[EpiRC-PGS.ipynb](EpiRC-PGS.ipynb)
- 
### バンディット問題
- ETCアルゴリズム：[Bandit_ETC.ipynb](Bandit_ETC.ipynb)
- インスタンス依存の下界：[Bandit_Instance-Dependent_Lower_Bounds.ipynb](Bandit_Instance-Dependent_Lower_Bounds.ipynb)
- UCBにおける上界の証明：[Bandit_UCB.ipynb](Bandit_UCB.ipynb)

### 強化学習と関連論文
- モデルフリーRLの復習：[RL_Model_Free.ipynb](RL_Model_Free.ipynb)
- sim2real：[RL_sim2real.ipynb](RL_sim2real.ipynb)
- 確率的方策勾配法：[RL_Stochastic_Policy_Gradient.ipynb](RL_Stochastic_Policy_Gradient.ipynb)
- 方策勾配法の理論：[RL_Theory of Policy Gradient.ipynb](RL_Theory of Policy Gradient.ipynb)
- 有限MDP理論（Puterman）：[MDP_Puterman_Infinite_Horizon.ipynb](MDP_Puterman_Infinite_Horizon.ipynb)
- Q学習の収束性証明：[RL_Q_Learning_proof_convergence.ipynb](RL_Q_Learning_proof_convergence.ipynb)
- シミュレーション補題に関する考察：[Paper_Simulation_Lemma.ipynb](Paper_Simulation_Lemma.ipynb)
- Simplex法によるMDP解法：[Paper_Simplex_MDP.ipynb](Paper_Simplex_MDP.ipynb)
- モーメンタムはSGDを改善させる：[Paper_Momentum_improves_SGD.ipynb](Paper_Momentum_improves_SGD.ipynb)
- 価値関数ポリトープ：[Paper_Geometory_of_Value_Function.ipynb](Paper_Geometory_of_Value_Function.ipynb)
- ロバスト価値関数ポリトープ[Paper_Geometory_of_Robust_Value_Function.ipynb](Paper_Geometory_of_Robust_Value_Function.ipynb)
- 熱方程式と方策勾配[Paper_Molification_of_PG.ipynb](Paper_Molification_of_PG.ipynb)
- 隠れ凸性の研究[Paper_hidden_convexity.ipynb](Paper_hidden_convexity.ipynb)
---

## 分布ロバスト最適化（DRO）
- DRO理論本 第1,2章(導入、不確実性集合)：[DRO_Chapter_2_uncertainty_sets.ipynb](DRO_Chapter_2_uncertainty_sets.ipynb)
- DRO理論本 第3章(不確実性集合のトポロジー性質)：[DRO_Chapter_3_topology_of_uncertainty_sets.ipynb](DRO_Chapter_3_topology_of_uncertainty_sets.ipynb)
- DRO理論本 第4章(DROと双対問題)：[DRO_Chapter4_dual_theory_in_DRO.ipynb](DRO_Chapter4_dual_theory_in_DRO.ipynb)
- DRO理論本 第5章(最悪ケースDROと双対問題)：[DRO_Chapter_5_dual_theory_in_Risk_DRO.ipynb](DRO_Chapter_5_dual_theory_in_Risk_DRO.ipynb)
- DRO理論本 第6章(Nature’s Subproblemの解析解)：[DRO_Chapter_6_analytical_solutions_of_subproblem.ipynb](DRO_Chapter_6_analytical_solutions_of_subproblem.ipynb)
- DRO理論本 第8章(ロバスト化による正則化)：[DRO_Chapter_8_regularization_by_robustification.ipynb](DRO_Chapter_8_regularization_by_robustification.ipynb)

---

## 凸最適化と非線形最適化

### First-order Methods in Optimization（Beck）
- 第3章（Subgradient）：[Beck_gradient_Chapter_3_subgradient.ipynb](Beck_gradient_Chapter_3_subgradient.ipynb)
- 第4章（L-smooth & Strong Convex）：[Beck_gradient_Chapter_4_L-smooth_strong_convex.ipynb](Beck_gradient_Chapter_4_L-smooth_strong_convex.ipynb)

### 非線形最適化の基礎(福島先生の本(*一般的な定理のまとめのみ))
- Chapter 1 + 可視化：[Non_Linear_optimization_chapter1_and_visualization.ipynb](Non_Linear_optimization_chapter1_and_visualization.ipynb)
- Chapter 2_part1(超平面、分離超平面、支持超平面、凸集合、陰関数定理など)：[Non_Linear_optimization_chapter2_part1.ipynb](Non_Linear_optimization_chapter2_part1.ipynb)
- Chapter 2_part2(凸関数、共役関数、劣勾配など)：[Non_Linear_optimization_chapter2_part2.ipynb](Non_Linear_optimization_chapter2_part2.ipynb)
- Chapter 3(最適解)：[Non_Linear_optimization_chapter3_part1.ipynb](Non_Linear_optimization_chapter3_part1.ipynb)
- Chapter 3(最適性条件(制約想定とKKT条件))：[Non_Linear_optimization_chapter3_part2.ipynb](Non_Linear_optimization_chapter3_part2.ipynb)
- Chapter 4(Boyd本の双対理論)[Non_Linear_optimization_chapter4_part1.ipynb](Non_Linear_optimization_chapter4_part1.ipynb)
---

## 確率的最適化
- 確率的勾配降下法：[Stochastic_Optimization_SGD.ipynb](Stochastic_Optimization_SGD.ipynb)
- 弱凸関数の確率的モデルベース最小化：[Paper_weak_convex_proj_grad.ipynb](Paper_weak_convex_proj_grad.ipynb)
- 鏡像降下法：[Stochastic_Optimization_SMD.ipynb](Stochastic_Optimization_SMD.ipynb)
- 最急降下法の実装[Implement_SGD.ipynb](Implement_SGD.ipynb)

## 確率論と確率過程
- 確率論演習問題解答：[Bandit_book_Probability_Answer.ipynb](Bandit_book_Probability_Answer.ipynb)

---
## 機械学習のための数理解析
- 確率不等式大全:[Math_Probability_Inequalities.ipynb](Math_Probability_Inequalities.ipynb)
- 一様収束と汎化解析(途中)：[Math_Uniform_Convergence.ipynb](Math_Uniform_Convergence.ipynb)
- 被覆とVC理論：[Math_VC_theory.ipynb](Math_VC_theory.ipynb)
- 被覆数とパッキング数(途中):[Math_Convering_Estimation.ipynb](Math_Convering_Estimation.ipynb)
- ラデマッハ複雑度と集中不等式：[Math_Rademacher_Complexity.ipynb](Math_Rademacher_Complexity.ipynb)

---

## その他
- 拡散モデルの理論：[Theory_of_diffusion_model.ipynb](Theory_of_diffusion_model.ipynb)
- RL用ユーティリティ：[RL_utils.ipynb](RL_utils.ipynb)
- 確率的二分探索：[Paper_PBA.ipynb](Paper_PBA.ipynb)
- エピグラフ形式の定式化[Non_Linear_optimization_epigraph_formulation.ipynb](Non_Linear_optimization_epigraph_formulation.ipynb)
---

## 大規模モデル
- LoRAの理論解析：[LLM_LoRA_theory.ipynb](LLM_LoRA_theory.ipynb)

---


## 日付順のNotebook一覧

1. 11/20：Beck本第3章、劣勾配の基礎
2. 11/21：Beck本第3章、劣勾配の計算からKKT条件まで
3. 11/22：Beck本第4章、L-smooth前半
4. 12/05：RMDPのPIアルゴリズムの実装
5. 12/25：On the Theory of Policy Gradient Methods,直接パラメータ化のSample Complexity導出
6. 01/98：Occupancy Measureを解析したいの章
7. 01/27：RMDPの基礎1
8. 02/06　基礎2
9. 02/09：非凸ミニマックス問題
10. 02/11：モデルフリー強化学習備忘録
11. 02/16：sim2real paper
12. 03/03：SPGにおけるN-PG-IGTの証明(1)
13. 03/04：SPGにおけるN-PG-IGTの証明(完)
14. 03/05：SPGとN-PG-IGTを組み合わたアルゴリズム素案の作成
15. 03/08：分布ロバスト最適化の不確実性集合についてのまとめ(DRO2章)
16. 03/09：アルゴリズム素案の証明スケッチ
17. 03/11：手法の疑問をまとめた。
18. 03/16：DRO3章1
19. 03/18：DRO3章2
20. 03/19：強化学習理論本14章,保守的方策反復
21. 03/22：凸解析の基礎
22. 03/26：凸解析の基礎2
23. 03/27：確率不等式１．マルコフの不等式
24. 03/28：サポート型不確実性集合
25. 03/29：$\phi$-ダイバージェンス不確実集合
26. 03/30：凸解析の基礎3(凸関数の性質)
27. 03/31：不確実性集合のトポロジー的性質
28. 04/01：分布ロバスト最適化における双対理論(DRO4章)1
29. 04/02：パフォーマンス差とシミュレーション差
30. 04/03：PAC学習
31. 04/04：強化学習理論本14章TRPO
32. 04/05：モーメンタムはSGDを改善させる1
33. 04/06：モーメンタムはSGDを改善させる完、分布ロバスト最適化における双対理論(DRO4章)2
34. 04/07：確率不等式(サブガウシアン、ベルンシュタインの不等式)
35. 04/08：RMDPにおける方策勾配法の大域的最適性証明
36. 04/09：sim2real paper2
37. 04/10：価値関数のポリトープ1
38. 04/11：価値関数のポリトープ完
39. 04/12：分布ロバスト最適化における双対理論(DRO4章)3
40. 04/13：Q学習の収束性
41. 04/14：凸解析の基礎3(KKT条件)
42. 04/15：モデル推定を行わないRMDP1
43. 04/16：ロバスト価値関数のポリトープ1
44. 04/17：一様収束と汎化1
45. 04/18：強化学習理論本第1章　[RL_Theorybook_Chapter_1.ipynb](RL_Theorybook_Chapter_1.ipynb)
46. 04/19：強化学習理論本第1章(途中)　[RL_Theorybook_Chapter_4.ipynb](RL_Theorybook_Chapter_4.ipynb)
47. 04/20：sim2real paper3
48. 04/21：ETCアルゴリズム[Bandit_ETC.ipynb](Bandit_ETC.ipynb)
49. 04/22：凸関数の基礎4(双対問題)
50. 04/23：モデル推定を行わないRMDP2[Paper_RMDP_wo_model_estimation.ipynb](Paper_RMDP_wo_model_estimation.ipynb)
51. 04/24：最悪ケースリスク問題における双対理論(DRO5章)1[DRO_Chapter_5_dual_theory_in_Risk_DRO.ipynb](DRO_Chapter_5_dual_theory_in_Risk_DRO.ipynb)
52. 04/25：最悪ケースリスク問題における双対理論(DRO5章)2
53. 04/26：凸解析の基礎3(局所解と大域的最適解)[Non_Linear_optimization_chapter3_part1.ipynb](Non_Linear_optimization_chapter3_part1.ipynb)
54. 04/27：凸解析の基礎3接錐と法線錐を用いた最適解の必要条件[Non_Linear_optimization_chapter3_part1.ipynb](Non_Linear_optimization_chapter3_part1.ipynb)
55. 04/28：凸解析の基礎3最適性条件1
56. 04/29：凸解析の基礎3最適性条件2[Non_Linear_optimization_chapter3_part2.ipynb](Non_Linear_optimization_chapter3_part2.ipynb)
57. 04/30：Nature’s Subproblemの解析解[DRO_Chapter_6_analytical_solutions_of_subproblem.ipynb](DRO_Chapter_6_analytical_solutions_of_subproblem.ipynb)
58. 05/01：凸解析の基礎3最適性条件3
59. 05/02：Generative modelsを用いたロバスト強化学習のサンプル複雑度： [Paper_Sample_Complexity_of_RMDP.ipynb](Paper_Sample_Complexity_of_RMDP.ipynb)
60. 05/03：ユニオンバウンドを用いた証明(Generative modelsを用いたロバスト強化学習のサンプル複雑度)：[Paper_Sample_Complexity_of_RMDP.ipynb](Paper_Sample_Complexity_of_RMDP.ipynb)
61. 05/04：ロバスト化による正則化(DRO8章)：[DRO_Chapter_8_regularization_by_robustification.ipynb](DRO_Chapter_8_regularization_by_robustification.ipynb)
62. 05/05：バンディット問題，インスタンス依存の下界：[Bandit_Instance-Dependent_Lower_Bounds.ipynb](Bandit_Instance-Dependent_Lower_Bounds.ipynb)
63. 05/06：バンディット問題，UCBの上界の証明：[Bandit_UCB.ipynb](Bandit_UCB.ipynb)
64. 05/07：確率的最適化，確率的勾配降下法(SGD)：[Stochastic_Optimization_SGD.ipynb](Stochastic_Optimization_SGD.ipynb)
65. 05/08：被覆とVC理論：[Math_VC_theory.ipynb](Math_VC_theory.ipynb)
66. 05/09：確率的最適化，近接勾配法とSGDの収束レート：[Stochastic_Optimization_SGD.ipynb](Stochastic_Optimization_SGD.ipynb)
67. 05/10：確率的最適化，鏡像降下法：[Stochastic_Optimization_SGD.ipynb](Stochastic_Optimization_SGD.ipynb)
68. 05/11：バンディット問題，ミニマックスリグレット(ちょっと時間なかったので後日改修)：[Bandit_minimux.ipynb](Bandit_minimux.ipynb)
69. 05/12：モデル推定を行わないRMDP，制約付きDRO双対形式導出など[Paper_RMDP_wo_model_estimation.ipynb](Paper_RMDP_wo_model_estimation.ipynb)
70. 05/13：弱凸関数の確率的モデルベース最小化
71. 05/14：弱凸関数の確率的モデルベース最小化，確率的射影勾配法の収束性証明：[Paper_weak_convex_proj_grad.ipynb](Paper_weak_convex_proj_grad.ipynb)
72. 05/15：ロバスト目的関数は弱凸であることの証明：[RMDP_PG_global_optimality.ipynb](RMDP_PG_global_optimality.ipynb)
73. 05/16：確率的二分探索
74. 05/17：確率的二分探索，命題4.2の証明：[Paper_PBA.ipynb](Paper_PBA.ipynb)
75. 05/18：確率的最適化，鏡像降下法：[Stochastic_Optimization_SMD.ipynb](Stochastic_Optimization_SMD.ipynb)
76. 05/19：RL理論本第5章，オッカムのカミソリバウンド：[RL_Theorybook_Chapter_5.ipynb](RL_Theorybook_Chapter_5.ipynb)
77. 05/20：sim2real paper3
78. 05/21：RL理論本第5章，Linear realizability：[RL_Theorybook_Chapter_5.ipynb](RL_Theorybook_Chapter_5.ipynb)
79. 05/22：ロバスト制約つきMDP，弱凸関数の勾配支配:[Paper_RCMDP_weak_conv_grad_dominance.ipynb](Paper_RCMDP_weak_conv_grad_dominance.ipynb)
80. 05/23：Beck本第3章（Subgradient）：[Beck_gradient_Chapter_3_subgradient.ipynb](Beck_gradient_Chapter_3_subgradient.ipynb)
81. 05/24：制約付きロバストMDP：
82. 05/25：RectangularロバストMDPにおける方策勾配[Paper_RMDP_rectangular_PG.ipynb](Paper_RMDP_rectangular_PG.ipynb)
83. 05/26：制約付きロバストMDP2:
84. 05/27：確率的最適化，近接勾配法とSGDの収束レート2：[Stochastic_Optimization_SGD.ipynb](Stochastic_Optimization_SGD.ipynb)
85. 05/28：EpiRC-PGSの実装：[EpiRC-PGS.ipynb](EpiRC-PGS.ipynb)
86. 05/29：EpiRC-PGSの実装（完成）：[EpiRC-PGS.ipynb](EpiRC-PGS.ipynb)
87. 05/30：最急降下法の実装(途中)：[Implement_SGD.ipynb](Implement_SGD.ipynb)
88. 05/31：復習日
89. 06/01：単一ループのRMP1：[Paper_Single_loop_RMDP.ipynb](Paper_Single_loop_RMDP.ipynb)
90. 06/02：単一ループのRMP2：[Paper_Single_loop_RMDP.ipynb](Paper_Single_loop_RMDP.ipynb)
91. 06/03：問題解決の方法途中：[Math_IMO_part1.ipynb](Math_IMO_part1.ipynb)
92. 06/04：LoRAの理論解析：[LLM_LoRA_theory.ipynb](LLM_LoRA_theory.ipynb)
93. 06/05：制約付きロバストMDP3
94. 06/06：被覆数とパッキング数(途中):[Math_Convering_Estimation.ipynb](Math_Convering_Estimation.ipynb)
95. 06/07：被覆数とパッキング数(途中):[Math_Convering_Estimation.ipynb](Math_Convering_Estimation.ipynb)
96. 06/08：復習日
97. 06/09：凸解析の基礎3制約想定1[Non_Linear_optimization_chapter3_part2.ipynb](Non_Linear_optimization_chapter3_part2.ipynb)
98. 06/10：凸解析の基礎3鞍点定理[Non_Linear_optimization_chapter3_part2.ipynb](Non_Linear_optimization_chapter3_part2.ipynb)
99. 06/11：凸解析の基礎4双対理論[Non_Linear_optimization_chapter4_part1.ipynb](Non_Linear_optimization_chapter4_part1.ipynb)
100. 06/12：ラデマッハ複雑度と集中不等式：[Math_Rademacher_Complexity.ipynb](Math_Rademacher_Complexity.ipynb)
101. 06/13：復習日
102. 06/14：第1章(線形計画と双対)1：[RL_Theorybook_Chapter_1_LP.ipynb](RL_Theorybook_Chapter_1_LP.ipynb)
103. 06/15：第1章(線形計画と双対)2：[RL_Theorybook_Chapter_1_LP.ipynb](RL_Theorybook_Chapter_1_LP.ipynb)
104. 06/16：第1章(線形計画と双対)3：[RL_Theorybook_Chapter_1_LP.ipynb](RL_Theorybook_Chapter_1_LP.ipynb)
105. 06/17：確率論演習問題解答2.1：[Bandit_book_Probability_Answer.ipynb](Bandit_book_Probability_Answer.ipynb)
106. 06/18：確率的二分探索の実装(code is comming soon...)
107. 06/19：確率収束
108. 06/20：復習日
109. 06/21：解析の基礎4双対理論[Non_Linear_optimization_chapter4_part1.ipynb](Non_Linear_optimization_chapter4_part1.ipynb)
110. 06/22：最急降下法の実装(途中)：[Implement_SGD.ipynb](Implement_SGD.ipynb)
111. 06/23：ロバスト制約つきMDP，弱凸関数の勾配支配:[Paper_RCMDP_weak_conv_grad_dominance.ipynb](Paper_RCMDP_weak_conv_grad_dominance.ipynb)
112. 06/24：
113. 06/25：強化学習の基礎理論復習：
114. 06/26：強化学習の基礎理論復習：
115. 06/27：強化学習の基礎理論復習：
116. 06/28：強化学習の基礎理論復習：
117. 06/29： ロバスト制約つきMDP2，弱凸関数の勾配支配:[Paper_RCMDP_weak_conv_grad_dominance.ipynb](Paper_RCMDP_weak_conv_grad_dominance.ipynb)
118. 06/30：エピグラフ形式の定式化[Non_Linear_optimization_epigraph_formulation.ipynb](Non_Linear_optimization_epigraph_formulation.ipynb)
119. 07/02：ExogenousBlockMDPとLocal access 1
120. 07/02：ExogenousBlockMDPとLocal access 2
121. 07/04：DROのイントロ修正，読みやすくなったと思う[DRO_Chapter_2_uncertainty_sets.ipynb](DRO_Chapter_2_uncertainty_sets.ipynb)
122. 07/05：凸解析，アフィン集合と超平面の部分修正[Non_Linear_optimization_chapter2_part1.ipynb](Non_Linear_optimization_chapter2_part1.ipynb)
123. 07/06：復習
124. 07/13：熱方程式と方策勾配[Paper_Molification_of_PG.ipynb](Paper_Molification_of_PG.ipynb)
125. 07/14：確率論演習問題解答2.2：[Bandit_book_Probability_Answer.ipynb](Bandit_book_Probability_Answer.ipynb)
126. 07/17：予定：PBA外側ループ証明，Hidden convexityの研究
127. 07/23：隠れ凸性の研究[Paper_hidden_convexity.ipynb](Paper_hidden_convexity.ipynb)
128. 07/24：ニューラルネットワークの解析
129. 07/26：復習日
