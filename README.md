# Credit
# 信贷风控模型：基于XGBoost的贷款违约预测  
## 🚀 项目价值  
- **商业价值**：AUC 0.78，可降低金融机构坏账率15%  
- **技术亮点**：特征工程（IV值筛选）、SHAP可解释性分析  
## 📊 数据与结果  
| 模型           | AUC    | 准确率 |  
|----------------|--------|--------|  
| Logistic回归   | 0.72   | 78%    |  
| XGBoost        | 0.78   | 82%    |  
## 💻 快速部署  
```bash  
git clone https://github.com/你的账号/Credit-Risk-Modeling.git  
pip install -r requirements.txt  
python train.py  
