
# Data Exploration Report

## CoalPrice01.csv

### Column Structure and Data Types
```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 150 entries, 0 to 149
Data columns (total 3 columns):
 #   Column  Non-Null Count  Dtype
---  ------  --------------  -----
 0   date    150 non-null    datetime64[ns]
 1   price   150 non-null    float64
 2   unit    0 non-null      float64
dtypes: datetime64[ns](1), float64(2)
memory usage: 3.6 KB

```

### Basic Statistics
|       |    price |
|:------|---------:|
| count | 150      |
| mean  |  93.2852 |
| std   |  15.9356 |
| min   |  71.1    |
| 25%   |  85.5475 |
| 50%   |  91.77   |
| 75%   |  93.7775 |
| max   | 151      |

## HeatPrice_Prediction01.csv

### Column Structure and Data Types
```
<class 'pandas.core.frame.DataFrame'>
Index: 41 entries, 2 to 42
Data columns (total 4 columns):
 #   Column          Non-Null Count  Dtype
---  ------          --------------  -----
 0   date            41 non-null     datetime64[ns]
 1   gangneung_anin  28 non-null     float64
 2   samcheok_green  28 non-null     float64
 3   goseong_high    28 non-null     float64
dtypes: datetime64[ns](1), float64(3)
memory usage: 1.6 KB

```

### Basic Statistics
|       | date                          |   gangneung_anin |   samcheok_green |   goseong_high |
|:------|:------------------------------|-----------------:|-----------------:|---------------:|
| count | 41                            |            28    |            28    |          28    |
| mean  | 2025-04-01 07:36:35.121951232 |         33872.5  |         32714.2  |       32587    |
| min   | 2023-08-01 00:00:00           |         22827    |         24879    |       27124    |
| 25%   | 2024-06-01 00:00:00           |         32503.8  |         31036    |       30912    |
| 50%   | 2025-04-01 00:00:00           |         33945    |         32252.5  |       32102.5  |
| 75%   | 2026-02-01 00:00:00           |         35889    |         34004.2  |       34476.8  |
| max   | 2026-12-01 00:00:00           |         46263    |         43635    |       40180    |
| std   | nan                           |          4246.59 |          3487.02 |        2831.71 |
