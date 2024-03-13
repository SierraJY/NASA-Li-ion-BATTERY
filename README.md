## NASA Lithium-ion Battery SoH Prediction
### latest version : 2024/02/14 by JuYeon

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/NASA_logo.svg/2449px-NASA_logo.svg.png" width=230 height=200/>

### 📌 Description
- **"Machine Learning-Based Lithium-Ion Battery Capacity Estimation Exploiting Multi-Channel Charging Profiles"** 리프로덕션
(https://ieeexplore.ieee.org/document/8731962)
- Data from **NASA PCoE**(https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
- Framework : **PyTorch**
- model type : FNN / CNN / LSTM / Bi-LSTM / Multie-head Attention + LSTM /
- Use **charging** datas and capacity data


### 📌 Directorys & Files
- DATA/RAW : raw data (**.mat** files)
- DATA/DataFrame : extracted charge and capacity data ( **.csv** files )
- BEST_MODEL : parameters of best models ( **.pt** files)
- PREDICT : prediction of B0005's capacity
- Train_SCModels : training Models using B0006/B0007/B0018's voltage data only & Predict B0005's capacity (single-channel)
- Train_MCModels : training Models using B0006/B0007/B0018's voltage, current, temperature & Predict B0005's capacity (multi-channel)
- Train_Other_MCModels : Predict Other Cells (EX: train B0005/B0007/B0018 & Predict B0006)



### 📌 Conclusion
<img src="./output_1C.png">
<img src="./output_MC.png">
