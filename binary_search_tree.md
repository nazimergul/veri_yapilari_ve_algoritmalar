# Project 3
```python
# Author : NAZIM ERGUL
# Date & Time : 16.03.2023 23:17
# Description : Veri Yapıları ve Algoritmalar - Binary Search Tree Projesi
```
## Binary Search Tree

- Array = [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
#### Question = Yukarıda verilen dizinin Binary-Search-Tree aşamalarını yazınız.
#### Answer = Root 7' dir solunda 5 ve sağında 8 vardır. Ağaç yapısı aşağıdaki gibidir.
```
          7
       /    \ 
      5      8
     / \      \
    1   6      9
   / \
  4   3
      /   
     0
      \
       2
```
#### Açıklama : Verilen dizideki sıralama diziye eklenen elemanların ekleme sırası olarak kabul edilmiştir bu sebep ile 7 den başlanmış ve sırasıyla ağaç yapısı kurulmuştur. 
#### Ağaç yapına bakıldığında sonradan eklenen sayılar dengesiz dağıldığı için worst case sayılabilir. 