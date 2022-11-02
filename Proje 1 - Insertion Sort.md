# Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.


## Cevap


### 1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
1. Aşama

[22, 27, 16, 2, 18, 6] 

2. Aşama 



3. Aşama

[16, 22, 27, 2, 18, 6] 

4. Aşama

[16, 22, 2, 27, 18, 6] 

5. Aşama

[16, 2, 22, 27, 18, 6] 

6. Aşama

[2, 16, 22, 27, 18, 6] 

7. Aşama

[2, 16, 22, 18, 27, 6] 

8. Aşama

[2, 16, 18, 22, 27, 6] 

9. Aşama

[2, 16, 18, 22, 6, 27] 

10. Aşama

[2, 16, 18, 6, 22, 27] 

11. Aşama

[2, 16, 6, 18, 22, 27] 

12. Aşama

[2, 6, 16, 18, 22, 27] 
```

### 2. Big-O gösterimini yazınız.
``` 
(n*(n+1)/2) 
= (n^2 + n)/2 
= n^2/2 + n/2

O(n^2)
``` 

### 3. Time Complexity: 
``` 
Average Case: O(n^2)
Worst Case: O(n^2)
Best Case: O(n)
``` 

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?
``` 
Average Case
``` 
-------------------------------------------------------------------------------------------------
<br>
<br>

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Cevap
```
1. Adım

[3,7,5,8,2,9,4,15,6]

2. Adım

[3,5,7,8,2,9,4,15,6]

3. Adım

[3,5,7,2,8,9,4,15,6]

4. Adım

[3,5,2,7,8,9,4,15,6]
```