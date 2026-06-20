#  深圳市二手房数据清洗与房价预测系统
本项目独立完成了从原始二手房数据清洗、深度探索性数据分析（EDA）到机器学习建模预测的全流程。利用 Pandas 攻克数据清洗，通过可视化发现了面积、区域对房价的核心影响;基于此特征，利用 Scikit-learn 构建线性回归模型，成功实现了对深圳二手房价格的量化预测。
# 🔍数据分析与可视化展示
<img width="683" height="465" alt="image" src="https://github.com/user-attachments/assets/dac0f754-6851-4a37-9f82-a1fe7721e368" />
<img width="635" height="457" alt="image" src="https://github.com/user-attachments/assets/410b26c4-5c87-46c8-89d8-5a26fe67264c" />
<img width="653" height="470" alt="image" src="https://github.com/user-attachments/assets/108d8113-bb48-482a-a5c3-d101e516b98f" />
<img width="632" height="502" alt="image" src="https://github.com/user-attachments/assets/5385c9a8-6c20-4df9-ae0a-924deb710a03" />
# 📈 模型评估与预测结果
======= 🤖 线性回归模型性能报告 =======
平均绝对误差 (MAE): 186.50 万元
均方根误差 (RMSE): 325.02 万元
模型确定系数 (R² 评分): 0.8089
======= 📈 特征对总价的影响权重排行（前5名） =======
            Feature      Weight
0              AREA  597.952224
9  district_nanshan  187.254553
5            subway   49.998424
3         floor_num   37.689019
7  district_longhua   30.070487
## 🛠️ 技术栈
数据处理：Python, Pandas, NumPy
机器学习：Scikit-learn (Linear Regression)
数据可视化：Matplotlib / Seaborn
