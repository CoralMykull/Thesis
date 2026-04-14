# Fusing Context and Metrics: A Comparative Analysis of Gradient Boosting Machines and Transformer-Based Hybrid Architectures for Imbalanced Defect Prediction on the PROMISE '19 Dataset

This research addresses the critical challenge of predicting software bug severity within the imbalanced PROMISE '19 dataset by comparing traditional Gradient Boosting Machines (GBMs) against an advanced Hybrid RoBERTa architecture. By fusing 19 numerical code metrics with unstructured textual bug reports, the study identifies a significant trade-off between overall accuracy and practical utility; while the Hybrid RoBERTa model achieved a high overall accuracy of 66.00%, it failed to identify critical defects with a recall of only 13.00%. Conversely, the LightGBM ensemble—leveraging explicit class weighting—proved to be the superior tool for risk-sensitive triaging, achieving a 61.79% recall for severe bugs. Ultimately, the findings demonstrate that for imbalanced software engineering data, the choice of a robust imbalance-mitigation strategy is more consequential for catching high-risk vulnerabilities than the complexity of the model architecture itself.

<br>

Manual on how to run the Models:<br>
Step 1: Download and Extract the Zip File<br>
Step 2: Extract the promise19_dataset.zip in the same folder as EDA and ML Models.ipynb and Roberta DL Model.ipynb<br>
Step 3: Run the Ipynb Code from top to bottom.<br>

