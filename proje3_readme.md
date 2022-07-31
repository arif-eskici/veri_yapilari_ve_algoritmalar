# Binary Search Tree Projesi
---

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin --> Binary Search Tree aşamaları: <br>

**``` Açıklama : ```** Binary Search Tree yönteminde dizinin elemanları ağaca sırayla eklenir. İlk eleman 7 root yani düğüm olur.<br> 7'den büyük sayılar düğümün sağına, küçük sayılar düğümün soluna eklenir.
<br>

**``` 1 ```** **"5"** sayısı 7'den küçük olduğundan 7'nin soluna eklenir.<br>

|     |  |  |
|-    |- |- |
|     |  | 7|  
|     | /|  | 
|**5**|  |  |
<br>

**``` 2 ```** **"1"** sayısı 7 ve 5'ten küçük olduğundan 7'nin ve 5'in soluna eklenir.<br>

|     |  |  |  |  |
|--   |--|- |- |- |
|     |  |  |  | 7|  
|     |  |  | /|  | 
|     |  | 5|  |  |  
|     | /|  |  |  | 
|**1**|  |  |  |  |
<br>

**``` 3 ```** **"8"** sayısı 7'den büyük olduğundan 7'nin sağına eklenir.<br>

|  |  |  |  |  |  |     |
|--|--|- |- |- |- |-    |
|  |  |  |  | 7|  |     |  
|  |  |  | /|  |\ |     | 
|  |  | 5|  |  |  |**8**| 
|  | /|  |  |  |  |     | 
| 1|  |  |  |  |  |     |
<br>

**``` 4 ```**  **"3"** sayısı 7'den ve 5'ten küçük  olduğundan 5'in soluna; 1'den büyük olduğundan 1'in sağına eklenir.<br>

|  |  |     |  |  |  |  |
|--|--|-    |- |- |- |- |
|  |  |     |  | 7|  |  |  
|  |  |     | /|  |\ |  | 
|  |  | 5   |  |  |  |8 | 
|  | /|     |  |  |  |  | 
| 1|  |     |  |  |  |  |
|  |\ |     |  |  |  |  |
|  |  |**3**|  |  |  |  |
<br>

**``` 5 ```**  **"6"** sayısı 7'den küçük olduğundan 7'nin soluna; 5'ten büyük olduğundan 5'in  sağına eklenir.<br>

|  |  |  |  |     |  |  |
|--|--|- |- |-    |- |- |
|  |  |  |  | 7   |  |  |  
|  |  |  | /|     |\ |  | 
|  |  | 5|  |     |  |8 | 
|  | /|  |\ |     |  |  | 
| 1|  |  |  |**6**|  |  |
|  |\ |  |  |     |  |  |
|  |  | 3|  |     |  |  |
<br>

**``` 6 ```**   **"0"** sayısı 7'den, 5'ten ve 1'den küçük olduğundan 1'in soluna eklenir.<br>

|     |  |  |  |  |  |  |  |  |
|--   |--|- |- |- |- |- |- |- |
|     |  |  |  |  |  | 7|  |  |  
|     |  |  |  |  | /|  |\ |  | 
|     |  |  |  | 5|  |  |  |8 | 
|     |  |  | /|  |\ |  |  |  |
|     |  | 1|  |  |  |6 |  |  |
|     | /|  |\ |  |  |  |  |  |
|**0**|  |  |  | 3|  |  |  |  |
<br>

**``` 7 ```**  **"9"** sayısı 7'den ve 8'den büyük olduğundan 8'in sağına eklenir.<br>

|  |  |  |  |  |  |  |  |  |  |     |
|--|--|- |- |- |- |- |- |- |- |-    |
|  |  |  |  |  |  | 7|  |  |  |     |  
|  |  |  |  |  | /|  |\ |  |  |     | 
|  |  |  |  | 5|  |  |  |8 |  |     | 
|  |  |  | /|  |\ |  |  |  |\ |     | 
|  |  | 1|  |  |  |6 |  |  |  |**9**|
|  | /|  |\ |  |  |  |  |  |  |     |
| 0|  |  |  | 3|  |  |  |  |  |     |
<br>

**``` 8 ```**  **"4"** sayısı 7'den ve 5'ten küçük olduğundan 5'in soluna; 1'den ve 3'ten büyük olduğundan 3'ün sağına eklenir.<br>

|  |  |  |  |  |  |     |  |  |  |  |
|--|--|- |- |- |- |-    |- |- |- |- |
|  |  |  |  |  |  | 7   |  |  |  |  |  
|  |  |  |  |  | /|     |\ |  |  |  | 
|  |  |  |  | 5|  |     |  |8 |  |  | 
|  |  |  | /|  |\ |     |  |  |\ |  |
|  |  | 1|  |  |  |6    |  |  |  | 9|
|  | /|  |\ |  |  |     |  |  |  |  |
| 0|  |  |  | 3|  |     |  |  |  |  |
|  |  |  |  |  |\ |     |  |  |  |  |
|  |  |  |  |  |  |**4**|  |  |  |  |
<br>

**``` 9 ```**  **"2"** sayısı 7'den ve 5'ten küçük olduğundan 5'in soluna; 1'den büyük olduğundan 1'in sağına;<br> 3'ten küçük olduğundan 3'ün soluna eklenir.<br>

|  |  |     |  |  |  |  |  |  |  |  |
|--|--|-    |- |- |- |- |- |- |- |- |
|  |  |     |  |  |  | 7|  |  |  |  |  
|  |  |     |  |  | /|  |\ |  |  |  | 
|  |  |     |  | 5|  |  |  |8 |  |  | 
|  |  |     | /|  |\ |  |  |  |\ |  | 
|  |  | 1   |  |  |  |6 |  |  |  | 9|
|  | /|     |\ |  |  |  |  |  |  |  |
| 0|  |     |  | 3|  |  |  |  |  |  |
|  |  |     | /|  |\ |  |  |  |  |  |
|  |  |**2**|  |  |  |4 |  |  |  |  |