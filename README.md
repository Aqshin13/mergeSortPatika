# Proje 2


[Patika](www.patika.dev)

### [16,21,11,8,12,22] -> Merge Sort

1 Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2 Big-O gösterimini yazınız.

## 1

```
[16,21,11,8,12,22]

1 [16,21,11] and [8,12,22]

2 [16,21] and [11] ---- [8,12] and [22]

3 [16] [21]  [11] ----  [8] [12] [22]

4 16 ve 21 karşılaştırılır [16,21] oluyor. Sonra [16,21] 11 ile karşılaştırılır ve [11,16,21] oluyor. [8] [12] [22] icin de ayni islemler yapiliyor.
Sonuc [8,12,22] oluyor.

5 [11,26,21] ve [8] [12] [22] karşılaştırılır. Sonuc [8,11,12,22,26] oluyor
 
```


## 2
```
Big-O: 

So we can say that the big o of merge sort is the total cost of splitting plus the total cost of merging or logn + nlogn.
Now in big o we only consider the largest exponent, and because n * logn is larger than log n the big o is nlogn.

```

