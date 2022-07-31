# Merge Sort Projesi
---

**``` 1 ```** İlk olarak  dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar bölüyoruz. Tek eleman kalana kadar devam ediyoruz...
<br>

**``` 2 ```** Bölme işleminden sonra, tek elemanlı dizilerimizi birleştiriyoruz. Sıralı dizi elde edinceye kadar bu işleme devam ediyoruz...
<br>


|  |  |  |  |  |  |  |  |  |  |  |  | 
|- |- |- |- |- |- |- |- |- |- |- |- |
|  |  |  |6|21|11|8|12|22|  |  |  |
|  |  |6|21|11|  |  |8 |12|22|  |  |
|  |6| |21|11|  |  |8 |  |12|22|  |
|6|  |21|  |11|  |  |8 |  |12|  |22|
|  |  |  |  |  |  |  |  |  |  |  |  |
|  |6|21|  |11|  |  |8 |12  | |22|  |
|  |  |6|11|21|  |  |8 |12|22|  |  |
|  |  |  |6|8|11|12|21|22|  |  |  |
<br>

**``` 3 ```**

Bu fonksiyonda sürekli kendini çağırarak diziyi hep ikiye böldük. Her bölünmüş dizinin Merge işlemi için dizinin uzunluğu olan n işlem yapıldığından <b><u>Big-O gösterimi;</u><b><br>
  
$$O(n*(logn)) --> O(6*(log6)) olur!$$
