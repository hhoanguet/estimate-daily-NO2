# Estimates of daily ground-level NO2 concentrations in Vietnam based on Random Forest model integrated K-means
## Data details
station.csv: Dữ liệu thô do giảng viên cung cấp

dataset.csv: Dữ liệu thô sau khi đã được trích xuất đặc trưng.

newdata.csv: Dữ liệu chứa 50 936 cặp (lat, lon) và các đặc trưng đã được trích xuất trên phạm vi toàn quốc do nhóm tự thu thập.

out.csv: Dữ liệu dự đoán lượng phân bố NO2 ứng với 50 936 cặp (lat, lon) trên phạm vi toàn quốc. 

## Installation
You can run this project yourself in **Google Colab** notebooks with free GPU:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eQj_3BWunj335IZT7Iydlh6_u3ueY1EZ?usp=sharing)

To see how we extract the dataset.csv, click [here](extract_features.ipynb)

