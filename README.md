# Insertion-Sort-Projesi-
Proje-1 
Proje1
[22,27,16,2,18,6] -> Insertion Sort
1.	Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.<br />
```
 min value =2, change 2 and 22 -> [2, | 27, 16, 22, 18, 6]
 min=6, change 27 and 6 -> [2, 6, | 16, 22, 18, 27]
 min=16, no need to change -> [2, 6, 16, | 22, 18, 27]
 min=18, change 18 and 22 -> [2, 6, 16, 18 ,22, 27]
```
2.	Big-O gösterimini yazınız.<br />
```
Step 1 = n (check)
Step 2 = n-1
Step 3 =n-2
....
Step n-1 =1
sum =n+(n-1) + (n-2) …...+1 = (n*(n-1))/2 = O(n^2)
```
3.	Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.<br />
``` 
Worst case-->O(n^2) Average case-->O(n^2) Best case-->O(n)
```

4.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.<br />
```
Dizi sıralandıktan sonra 18 sayısı dizinin ortasında olduğu için Average case kapsamına girer.
```
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.<br />
```
min value=2, change 7 and 2 -> [2, | 3, 5, 8, 7, 9, 4, 15, 6]
min value=3, no need to swap [2, 3, | 5, 8, 7, 9, 4, 15, 6]
min value =4, change 5 and 4 -> [2, 3, 4, | 8, 7, 9, 5, 15, 6]
min value =5, change 8 and 5 -> [2, 3, 4, 5, | 7, 9, 8, 15, 6]
```
