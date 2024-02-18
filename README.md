### **PROBLEM STATEMENT**
Do not yet have the right strategy to offer the type of product that suits the prospective customer segment that will be recruited

### **OBJECTIVE**
Create a Clustering Model to determine product ownership based on customer demographics who are currently using FundFusion services with a Silhouette Score >0.7

### **AVAILABLE VARIABLES**
From the existing dataset, there is some data available:


---
**1. GCIF                     :** Unique Identifier Nasabah\
**2. Area                     :** Customer Location (Jakarta,Bogor,Bandung,Surabaya,Jogja,Solo)\
**3. Jalur_Pembukaan          :** Touch Points Customer opens the product --> Branches, Telemarketing, Digital Applications, Internet Banking\
**4. Vintage                  :** Duration of Becoming a Customer (Since opening an account)\
**5. Usia                     :** Customer Age\
**6. Jenis_Kelamin            :** Male (1) & Female (0)\
**7. Status_Perkawinan        :** Not Married (0), Married (1), Divorced (2), Widowed (3)\
**8. Jumlah_Anak              :** Number of Customer's Children (numeric)\
**9. Pendidikan               :** Latest Educational Status --> No Formal Education (0), Elementary School (1), Middle School (2), High School (3), Bachelor (4), Masters (5), Doctorate (6)\
**10. Produk_Tabungan         :** Product Ownership Status (Yes/1, No/0)\
**11. Produk_Deposito         :** Product Ownership Status (Yes/1, No/0)\
**12. Produk_Kartu_Kredit     :** Product Ownership Status (Yes/1, No/0)\
**13. Produk_Kredit_Rumah     :** Product Ownership Status (Yes/1, No/0)\
**14. Produk_Kredit_Kendaraan :** Product Ownership Status (Yes/1, No/0)\
**15. Produk_Kredit_Dana_Tunai:** Product Ownership Status (Yes/1, No/0)\
**16. Total_Kepemilikan_Produk:** Number of Products Owned (Sum of Products2)\
**17. Pendapatan_Tahunan      :** Average Annual Income\
**18. Total_Relationship_Balance :** Total Customer Assets in the Cutoff Month of Observation\


# **EXPERIMENT**
Point of View:
1. Grouped based on demographics to look for product ownership patterns
2. Grouped based on product ownership to look for patterns based on demographics

