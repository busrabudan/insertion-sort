<h3>Insertion Sort</h3>

[22,27,16,2,18,6] Bu diziyi insertion sort algoritması ile sıralama işlemi yapacağım.
Öncelikle verilen dizideki en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyoruz.

1. Adım : [22,27,16,2,18,6] -> [*2*,27,16,*22*,18,6]
Son hali: [2,27,16,22,18,6]
2. Adım : [2,27,16,22,18,6] -> [2,*6*,16,22,18,*27*]
Son hali: [2,6,16,22,18,27]
3. Adım : [2,6,16,22,18,27] -> [2,6,*16*,22,18,27]
Son hali: [2,6,16,22,18,27]
4. Adım : [2,6,16,22,18,27] -> [2,6,16,*18*,*22*,27]
Son hali: [2,6,16,18,22,27]

____________________________________________________________________________________________________

Big O notation O(n^2)

____________________________________________________________________________________________________

Time Complexity insertion sıralamasından sonra 18 ortada
olduğu için Average Case'dir.

____________________________________________________________________________________________________

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,16,6]
[2,3,4,8,7,9,5,16,6]
[2,3,4,5,7,9,8,16,6]
