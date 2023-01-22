# Data Preprocessing

## Data cleansing :
Handle missing values dengan .dropna()
Tidak ada data duplikat
Outliers dibuang dengan menggunakan metode zscore, dimana data yang diambil adalah yang memiliki nilai zscore lebih kecil dari 3
Feature Transformation:
Transformasi Normal untuk kolom : Income, Recency, NumWebVisitsMonth
Log Transformasi untuk kolom : Spendings, NumDealsPurchase, NumWebPurchase, NumCatalogPurchase, NumStorePurchase
Feature Encoding 
Me-encode kolom Marital_status, Education, Generasi, Campaign_result, Year_customer, Kidsorteen
Handle Class Imbalance 
Random oversampling
SMOTE


Feature Engineering : 

Feature Extraction
Menggabungkan kolom ‘MntMeatProducts’ , ‘MntFishProducts’, MntSweetProducts’, ‘MntGoldProds’, ‘MntFruits’, ‘MntWines’ menjadi Spending
Menggabungkan kolom kidhome dan teenhome menjadi kolom kidsorteen
Menggabungkan AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5 menjadi campaign_result
Mengganti kolom Year_Birth menjadi kolom generasi
Feature Selection
Membuang kolom ID, Z_CostContact, Z_Revenue, MntMeatProducts’ , ‘MntFishProducts’, MntSweetProducts’, ‘MntGoldProds’, ‘MntFruits’, ‘MntWines’ , kidhome, teenhome, AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, Dt_Customer

