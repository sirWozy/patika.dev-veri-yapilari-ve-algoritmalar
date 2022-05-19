# Patika.dev Veri Yapıları ve Algoritmalar dersinde bulunan Insertion Sort ödevi
___
#### [22,27,16,2,18,6] dizisinin Insertion Sort'a göre sıralanması
___

|1.Adım|22|16|27|2|18|6|
|------|-|-|-|-|-|-|

|2.Adım|16|22|27|2|18|6|
|------|-|-|-|-|-|-|

|3.Adım|16|22|2|27|18|6|
|------|-|-|-|-|-|-|

|4.Adım|16|2|22|27|18|6|
|------|-|-|-|-|-|-|

|5.Adım|2|16|22|27|18|6|
|------|-|-|-|-|-|-|

|6.Adım|2|16|22|18|27|6|
|------|-|-|-|-|-|-|

|7.Adım|2|16|18|22|27|6|
|------|-|-|-|-|-|-|

|8.Adım|2|16|18|22|6|27|
|------|-|-|-|-|-|-|

|9.Adım|2|16|18|6|22|27|
|------|-|-|-|-|-|-|

|10.Adım|2|16|6|18|22|27|
|------|-|-|-|-|-|-|

|11.Adım|2|6|16|18|22|27|
|------|-|-|-|-|-|-|

#### Big-O Notation gösterimi
____

n'den 1'e kadar sayılara bakıldığı için 

n(n+1)/2 = n^2+n/2 = **O(n^2)** 'dir.

#### Time Complexity
____

##### Worst Case

En kötü senaryoda küçük sayıların en sonda olduğunu düşünürsek yine **O(n^2)**'dir.

##### Average Case

Sayının ortada olduğunu düşündüğümüzde yine **O(n^2)**'dir.

##### Best Case

Algoritma bir kere çalışır ve Best Case **O(n)**'dir.


#### Dizi Sıralandıktan sonra 18 sayısı hangi case kapsamına girer.
___

Ortada bulunduğu için **Average Case** kapsamına girer.

#### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
___

|1.Adım|7|3|5|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|

|2.Adım|3|7|5|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|

|3.Adım|3|5|7|8|2|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|

|4.Adım|3|5|7|2|8|9|4|15|6|
|------|-|-|-|-|-|-|-|-|-|
