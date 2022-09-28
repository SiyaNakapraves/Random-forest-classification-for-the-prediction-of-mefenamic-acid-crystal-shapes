# Random forest classification for the prediction of mefenamic acid crystal shapes
The Python scripts are used for building random forest classification models for the prediction of mefenamic acid crystal shapes. 

- "RF_2-class prediction_balance_CV" is the code for the model used for the 2-class prediction of which the training dataset contains balance observations between 2 classes. The model is evaluated by cross-validation method.

- "RF_2-class prediction_imbalance_CV" is the code for the model used for the 2-class prediction of which the training dataset contains imbalance observations between 2 classes. The model is evaluated by cross-validation method.

- "RF_3-class prediction_imbalance_CV" is the code for the model used for the 3-class prediction of which the training dataset contains imbalance observations amoung 3 classes. The model is evaluated by cross-validation method.

- "RF_2-class prediction_external solvent_2-butanol" is the code for the model used for the 2-class prediction. This model excludes the samples crystallised from 2-butanol from the training dataset and uses those samples as the external test set.
