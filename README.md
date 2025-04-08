# Patika.dev - Insertion Sort Projesi
## Proje 1 - Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort

### Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
[22, 27, 16, 2, 18, 6] (n)
[22, 27, 16, 2, 18, 6] (n-1)
[16, 22, 27, 2, 18, 6] (n-2)
[2, 16, 22, 27, 18, 6] (n-3)
[2, 16, 18, 22, 27, 6] (n-4)
[2, 6, 16, 18, 22, 27] (n-5)
```

### Big-O gösterimini yazınız.

```
Worst Case: O(n²)
Average Case: O(n²)
Best Case: O(n)
```

### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

18 sayısı, sıralanmış dizide [2, 6, 16, 18, 22, 27] ortada yer aldığı için Average case kapsamına girer.

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

```
[2,3,5,8,7,9,4,15,6] - En küçük eleman 2, ilk eleman 7 ile yer değiştirir
[2,3,5,8,7,9,4,15,6] - İkinci en küçük eleman 3 zaten doğru pozisyonda
[2,3,4,8,7,9,5,15,6] - Üçüncü en küçük eleman 4, 5 ile yer değiştirir
[2,3,4,5,7,9,8,15,6] - Dördüncü en küçük eleman 5, 8 ile yer değiştirir
```

## Proje 2 - Merge Sort

[16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
            [16,21,11,8,12,22]
                   /   \
           [16,21,11]   [8,12,22]
            /    \        /    \
        [16]   [21,11]  [8]   [12,22]
         /        /\      \      /\
      [16]     [21] [11]  [8]  [12] [22]
         \      /    /     \    \   /
         [16]  [11,21]     [8]  [12,22]
              \   /          \   /
           [11,16,21]       [8,12,22]
                  \         /
               [8,11,12,16,21,22]
```
### Big-O gösterimini yazınız.

```
O(n log n)
```

Merge Sort'un zaman karmaşıklığı her durumda (best case, average case, worst case) O(n log n)'dir. Bu karmaşıklık, diziyi ikiye bölme işleminden dolayı log n, her seviyede tüm elemanları birleştirme işleminden dolayı n faktörü ile oluşur.
