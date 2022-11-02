# Proje 2

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.

## Cevap

## 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

``` 
Aşama 1 

[16, 21, 11]           [8, 12, 22]          Array ikiye bölünür.
      /                      \
[16]  [21, 11]          [8]  [12, 22]       Arrayler kendi içinde bir kez daha ikiye bölünür.
    /   \                   /   \
[16]    [11, 21]        [8]     [12, 22]    İkili arrayler kendi içinde sıralanır.
    \   /                   \   /
    [11, 16, 21]         [8, 12, 22]        İkili arrayler birleştirilir. (En küçük elemana göre)
        \                      /
        [8, 11, 12, 16, 21, 22]             Tüm arrayler birleştirilir.
```

## Big-O gösterimini yazınız.

n sayıda element için: O(nlogn)

