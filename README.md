# Proje 1

## Soru 1
**[22,27,16,2,18,6]** -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.

----------------

## Cevap 1
1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]


* Big-O gösterimi : O(n^2)
* 18 için Time Complexity: Average case olacaktır.

## Soru 2
**[7,3,5,8,2,9,4,15,6]** dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

-----------------

## Cevap 2
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]


# Proje 2

## Soru 1
[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.

## Cevap 1
* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

```
            [16,21,11,8,12,22]
            /                  \
        [16,21,11]         [8,12,22]
        /       \            /    \
      [16]    [21,11]     [8]  [12,22]
      /        /   \       /    /   \
    [16]     [21]  [11]  [8]  [12]  [22]
       \       |    /      \    |    /
       [16]   [11,21]      [8] [12,22]
          \     /            \    /
         [11,16,21]        [8,12,22]
                \            /
              [8,11,12,16,21,22]

```


* Big-O gösterimini yazınız. --> O(n.logn)


# Proje 3
## Soru 1
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap 1
```
Root =      7     ise;
           /  \
          5    8
         / \    \
        1   6    9
       / \  
      0   3 
         / \
        2   4

```