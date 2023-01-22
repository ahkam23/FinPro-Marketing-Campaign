# Data Preprocessing

### Data cleansing :
1. Handle missing values dengan .dropna()
2. Tidak ada data duplikat
3. Outliers dibuang dengan menggunakan metode zscore, dimana data yang diambil adalah yang memiliki nilai zscore lebih kecil dari 3
### Feature Transformation:
1. Transformasi Normal untuk kolom : Income, Recency, NumWebVisitsMonth
2. Log Transformasi untuk kolom : Spendings, NumDealsPurchase, NumWebPurchase, NumCatalogPurchase, NumStorePurchase
### Feature Encoding 
Me-encode kolom Marital_status, Education, Generasi, Campaign_result, Year_customer, Kidsorteen
### Handle Class Imbalance 
1. Random oversampling
2. SMOTE


## Feature Engineering : 

### Feature Extraction
1. Menggabungkan kolom ‘MntMeatProducts’ , ‘MntFishProducts’, MntSweetProducts’, ‘MntGoldProds’, ‘MntFruits’, ‘MntWines’ menjadi Spending
2. Menggabungkan kolom kidhome dan teenhome menjadi kolom kidsorteen
3. Menggabungkan AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5 menjadi campaign_result
4. Mengganti kolom Year_Birth menjadi kolom generasi
### Feature Selection
Membuang kolom ID, Z_CostContact, Z_Revenue, MntMeatProducts’ , ‘MntFishProducts’, MntSweetProducts’, ‘MntGoldProds’, ‘MntFruits’, ‘MntWines’ , kidhome, teenhome, AcceptedCmp1, AcceptedCmp2, AcceptedCmp3, AcceptedCmp4, AcceptedCmp5, Dt_Customer

