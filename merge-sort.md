# Patika.dev Veri Yapıları ve Algoritmalar dersinde bulunan Merge Sort ödevi

#### [16,21,11,8,12,22] dizisinin Merge Sort'a göre sıralanması


|1.Adım|16|21|11|8|12|22|
|------|-|-|-|-|-|-|

|2.Adım|16|21|11|-|8|12|22|
|------|-|-|-|-|-|-|-|

|3.Adım|16|-|21|11|-|8|-|12|22|
|------|-|-|-|-|-|-|-|-|-|

|4.Adım|16|-|21|-|11|-|8|-|12|-|22|
|------|-|-|-|-|-|-|-|-|-|-|-|

|5.Adım|16|-|11|21|-|8|-|12|22|
|------|-|-|-|-|-|-|-|-|-|

|6.Adım|11|16|21|-|8|12|22|
|------|-|-|-|-|-|-|-|


|7.Adım|8|11|12|16|21|22|
|------|-|-|-|-|-|-|


#### Big-O Notation gösterimi

Her seferinde 2'ye bölünerek gittiği için. 2^x = n = logn = **O(logn)**

Her seferinde n kadar işlem yaptığı için **O(nlogn)** olur.
