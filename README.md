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

## Proje 3 - Binary Search Tree Projesi

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


```
Root 7'dir.

                7
               / \
              5   8
             / \   \
            1   6   9
           / \
          0   3
             / \
            2   4
```

- Root 7'dir.
- 5, 7'den küçük olduğu için root'un solunda bulunur.
- 1, 7'den ve 5'ten küçük olduğu için 5'in solunda bulunur.
- 8, 7'den büyük olduğu için root'un sağında bulunur.
- 3, 7'den ve 5'ten küçük, 1'den büyük olduğu için 1'in sağında bulunur.
- 6, 7'den küçük, 5'ten büyük olduğu için 5'in sağında bulunur.
- 0, hepsinden küçük olduğu için en sola yerleşir (1'in soluna).
- 9, hepsinden büyük olduğu için en sağa yerleşir (8'in sağına).
- 4, 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için 3'ün sağına yerleşir.
- 2, 7, 5 ve 3'ten küçük, 1'den büyük olduğu için 3'ün soluna yerleşir.


