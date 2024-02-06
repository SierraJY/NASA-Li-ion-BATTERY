## NASA Lithium-ion Battery SoH Prediction
### latest version : 2024/02/04 by JuYeon

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/NASA_logo.svg/2449px-NASA_logo.svg.png" width=230 height=200/>

### 📌 Description
- **"Machine Learning-Based Lithium-Ion Battery Capacity Estimation Exploiting Multi-Channel Charging Profiles"** 리프로덕션
(https://ieeexplore.ieee.org/document/8731962)
- Data from **NASA PCoE**(https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
- Framework : **PyTorch**
- model type : FNN / CNN / LSTM / Bi-LSTM / Multie-head Attention
- Use **charging** datas and capacity data


### 📌 Directorys & Files
- DATA/RAW : raw data (**.mat** files)
- DATA/DataFrame : extracted charge and capacity data ( **.csv** files )
- BEST_MODEL : parameters of best models ( **.pt** files)
- PREDICT : prediction of B0005's capacity
- Train_SC_Models : training Models using voltage data only (single-channel)
- Train_MC_Models : training Models using voltage, current, temperature (multi-channel)


### 📌 Conclusion
<img src="./output1.png">
<img src="./output2.png">
