# Portable-Bridge-Based-Unet-Implementation-for-Semantic-Segmentation-Coupled-with-Post-Processing
Portable Bridge-Based Unet Implementation for Semantic Segmentation Coupled with Post-Processing Techniques for Accurate Cardiovascular Segmentation


## 1. Proposed Methodology:
### 1.1	Preprocessing / Dataset Normalization
### 1.2	Dataset Splitting

<br>
Sr. No.	Portion Name	Portion Ratio	Image Count
<br>
1	Train Set	70	5155
<br>
2	Valid Set	15	1104
<br>
3	Test Set	15	1104
<br>

### 1.3	Proposed Architecture of Model
![image](https://user-images.githubusercontent.com/25412736/187079664-cbbfafb1-09fe-406a-8002-5dea0df7753e.png)
<br>

![image](https://user-images.githubusercontent.com/25412736/187079669-8fda584b-d966-4ed3-bdaa-1208f824b8a0.png)
<br>

![image](https://user-images.githubusercontent.com/25412736/187079672-fa33702f-cea1-4c70-8ef4-653c481ed494.png)
<br>
Configuration for Proposed Model
<br>

Sr. No.
	Name of Model	Total
#	Trainable
#	Non-Trainable
#
1	Stock Unet	1213953	1211649	2304
2	Proposed	2360321	2356609	3712
Difference	1,146,368	1,144,960	1408
Optimized Ratio %	51%	51%	62%


<br>
![image](https://user-images.githubusercontent.com/25412736/187079714-b12532f7-db35-49e6-8229-6496623103b3.png)

<br>
![image](https://user-images.githubusercontent.com/25412736/187079725-718b51e4-c90c-4971-a72b-3583f4aa570e.png)

<br>
