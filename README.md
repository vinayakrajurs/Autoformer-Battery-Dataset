# Synthetic Battery Parameter Generation to Surmount Limited Data Challenges using Auto-Correlation Mechanism

We use an Auto-correlation mechanism to compose synthetic battery datasets. This procedure is very beneficial during data scarce scenarios wherein researchers have access to finite amount of data. The leading contributions of this
work include:

a) Synthetic battery dataset creation using Auto-Correlation Mechanism

b) Diverse heterogeneous data generation which is suitable for battery capacity forecasting purposes.

# Procedure to run this code- 

1. Click on code and download zip
2. Upload the file on your google drive
3. Open the file with zip extractor in the drive
4. Then click open Autoformer.ipynb file and follow the code each step
5. You can click open the file in colab and run the file only after the file is mounted in your drive
6. All changes to the Prediction Length, epochs, dataset, etc can be made in the run.py file 
7. Insertion of a new dataset must be done in the data folder as well as adding the data as a custom data in data_loader.py Line 192
8. You may make changes in the data set used and target to be run























# Citation 
@inproceedings{wu2021autoformer,
  title={Autoformer: Decomposition Transformers with {Auto-Correlation} for Long-Term Series Forecasting},
  author={Haixu Wu and Jiehui Xu and Jianmin Wang and Mingsheng Long},
  booktitle={Advances in Neural Information Processing Systems},
  year={2021}
}
