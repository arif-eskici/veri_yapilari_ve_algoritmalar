
# Insertion Sort Projesi
---

**``` 1 ```**

**[22, 27, 16, 2, 18, 6]** --> Insertion Sort ---> *n*

*Stage 1* --> **[2, 27, 16, 22, 18, 6]** ---> *(n-1)* <br>
*Stage 2* --> **[2, 6, 16, 22, 18, 27]** ---> *(n-2)* <br>
*Stage 3* --> **[2, 6, 16, 18, 22, 27]** ---> *(n-3)* = *1* <br>

**``` 2 ```**

Big-O gösterimi : 1'den n'ye kadar olan sayıların toplamıdır. Yani; <br>
 
$$ n*(n+1) / 2 = n^2 /2  +  n /2 $$

Buradan en büyük domine eden fonksiyon alınacağına göre; Big - O gösterimi: <br>

$$ O(n^2) $$ 

**``` 3 ```**

Time Complexity:
1. Average case: Aradığımız sayının ortada olması,
2. Worst case: Aradığımız sayının sonda olması,
3. Best case: Aradığımız sayının dizinin en başında olması.


**``` 4 ```**

Dizi sıralandıktan sonraki hali : **[2, 6, 16, 18, 22, 27]** olduğuna göre;<br>
<b> 18 </b> sayısı ***Average case*** kapsamına girmektedir.


**``` 5 ```**

**[7, 3, 5, 8, 2, 9, 4, 15, 6]** dizisinin ***<u>Insertion Sort</u>'a*** göre adımları:

*Stage 1* --> [2, 3, 5, 8, 7, 9, 5, 15, 6] <br>
*Stage 2* --> [2, 3, 4, 8, 7, 9, 5, 15, 6] <br>
*Stage 3* --> [2, 3, 4, 5, 7, 9, 8, 15, 6] <br>
***Stage 4*** **--> [2, 3, 4, 5, 6, 9, 8, 15, 7]** <br>
*Stage 5* --> [2, 3, 4, 5, 6, 7, 8, 15, 9] <br>
*Stage 6* --> [2, 3, 4, 5, 6, 7, 8, 9, 15] <br>

---
