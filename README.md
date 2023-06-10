## Task 1

## Details

Flow meters are devices used to measure the volumetric or mass flow  of a fluid with ultrasound. However, these devices present serious  engineering problems that give rise to a defective meter function and  cause errors in reading the flow velocity.

In this study, we analyze a database with the characteristics of a  liquid ultrasonic flowmeter and its state (healthy or unhealthy) to know the relevant factors that cause failures in the system.

Therefore, a solution that balances accurate measurement and the necessary costs of recalibration is needed.

 

**Resources:** Dataset ([Download Excel data](https://buetedu-my.sharepoint.com/:x:/g/personal/esrdlab_cse_buet_ac_bd/ESujzf0RsblJrLs1NFF_EroB-T181j12DlbHLLCMEt94XA?e=ozORng))

## Task

1. Plot a confusion matrix.

2. Predict the health state of a flowmeter given the input variables’ any required values.


### Solution


Multiple models were tested. Among them XGBoost performer best. which is a regularizing gradient boosting framework. Confusion matrix and accuracy of the models are added.

| Model            |    Support Vector Machine    |        Logistics Regression        |             XGBoost              |
| ---------------- | :--------------------------: | :--------------------------------: | :------------------------------: |
| Confusion Matrix | ![](Task%201/assets/svm.jpg) | ![](Task%201/assets/logistics.jpg) | ![](Task%201/assets/xgboost.jpg) |
| Accuracy         |             0.54             |                0.57                |               0.83               |

