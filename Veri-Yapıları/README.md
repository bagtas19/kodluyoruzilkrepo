# Veri yapıları odev 

## Proje 1

Verilen dizi: [22, 27, 16, 2, 18, 6]

* [22, 27, 16, 2, 18, 6]
* [22, 27, 16, 2, 18, 6]
* [16, 22, 27, 2, 18, 6]
* [2, 16, 22, 27, 18, 6]
* [2, 16, 18, 22, 27, 6]
* [2, 6, 16, 18, 22, 27]

Big-O Gösterimi:

Insertion Sort'un en kötü durumdaki (worst-case) time complexity'si O(n^2)

Average Case: Dizinin ortasında olması durumu için 

O(n) (lineer) time complexity kapsamına girer.
Worst Case: Dizinin sonunda olması durumu için 

O(n) (lineer) time complexity kapsamına girer.
Best Case: Dizinin başında olması durumu için 

O(1) (sabit) time complexity kapsamına girer.
Selection Sort Aşamaları:

Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

* [2, 3, 5, 8, 7, 9, 4, 15, 6]
* [2, 3, 5, 8, 7, 9, 4, 15, 6]
* [2, 3, 4, 8, 7, 9, 5, 15, 6]
* [2, 3, 4, 5, 7, 9, 8, 15, 6]

---

## Proje 2

Verilen dizi: [16, 21, 11, 8, 12, 22]

* Adım: [16, 21, 11, 8, 12, 22]
* Sol: [16, 21, 11], Sağ: [8, 12, 22]
* Adım: [16, 21, 11, 8, 12, 22]
* Sol: [16], Sağ: [21, 11]
* Adım: [16, 11, 21, 8, 12, 22]
* Sol: [11], Sağ: [21]
* Birleştirme: [11, 21]
* Adım: [11, 16, 21, 8, 12, 22]
* Sol: [11, 16, 21], Sağ: [8, 12, 22]
* Adım: [11, 16, 21, 8, 12, 22]
* Sol: [11, 16, 21], Sağ: [8, 12, 22]
* Adım: [11, 16, 21, 8, 12, 22]
* Sol: [11, 16, 21, 8], Sağ: [12, 22]
* Adım: [11, 16, 8, 21, 12, 22]
* Sol: [11, 8, 16], Sağ: [12, 22]
* Birleştirme: [8, 11, 16, 21]
* Adım: [8, 11, 12, 16, 21, 22]

Merge Sort'un time complexity'si O(nlogn)

---

## Proje 3

Verilen dizi: [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

        7
       / \
      5   8
     /|   |\
    1 3   6 9
   /|   \
  0 4    2
