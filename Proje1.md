# Proje 1

**[22,27,16,2,18,6]** -> Insertion Sort
### 1.  Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

* 1 - [16,22,27,2,18,6]
* 2 - [2,16,22,27,18,6]
* 3 - [2,16,18,22,27,6]
* 4 - [2,6,16,18,22,27]


### 2.  Big-O gösterimini yazınız.

* n + n-1 + n-2 + n-3 ... + 1 
* n.(n+1) / 2
* **n^2** + n / 2
* O(n^2)

### 3. Time Complexity:
###### Average case: Aradığımız sayının ortada olması,
###### Worst case: Aradığımız sayının sonda olması 
###### Best case: Aradığımız sayının dizinin en başında olması.

```
[2,6,16,18,22,27]

Average case: 16,18
Worst case: 27
Best case: 2
```

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

```
18 sayısı Average case kapsamına girer.
```

### 5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre "ilk 4 adımını" yazınız.

* 1 - [3,7,5,8,2,9,4,15,6]
* 2 - [3,5,7,8,2,9,4,15,6]
* 3 - [2,3,5,7,8,9,4,15,6]
* 4 - [2,3,4,5,7,8,9,15,6]

***Devamı***

* Final aşaması - [2,3,4,5,6,7,8,9,15]