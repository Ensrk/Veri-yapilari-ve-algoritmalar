# Veri-yapilari-ve-algoritmalar
# Insertion Sort Projesi-Patika.dev
[22,27,16,2,18,6] -> Insertion Sort
```
 1 - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
 2 - Big-O gösterimini yazınız.
 3 - Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 5 - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
## 1 - Insertion Sort Asamalari
```
1.aşama =[22,27,16,2,18,6]
2.aşama =[16,22,27,2,18,6]
3.aşama =[2,16,22,27,18,6]
4.aşama =[2,16,18,22,27,6]
5.aşama =[2,6,16,18,22,27]
```
## 2- Big-O gösterimini yazınız. 
worst case durumu => n+(n-1)+(n-2)....+1 =n*(n+1)/2 = (n^2+n)/2 = O(n^2)

## 3-Time Complexity: 
Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 ```
 Best Case : [2,6,16,18,22,27]
 Worst Case : [27,22,18,16,6,2]
 ```
## 4-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
```
 18 sayısı bu diziye göre average case kapsamındadır.
```

## 5 [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
```
1.aşama =[3,7,5,8,2,9,4,15,6]
2.aşama =[3,5,7,8,2,9,4,15,6]
3.aşama =[2,3,5,7,8,9,4,15,6]
4.aşama =[2,3,4,5,7,8,9,15,6]
```
