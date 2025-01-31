# data-structures

<h2>Ödev-1   </h2>

[22,27,16,2,18,6]

Adım 1: ilk eleman 22 zaten sıralı
22,27,16,2,18,6

Adım 2: (27>22 olduğu için dizi değişmez)
22,27,16,2,18,6

Adım 3: (16 hem 22'den hem de 27'den küçük olduğu için en başa gelir.)
16,22,27,2,18,6

Adım 4: (2, 27'den küçük => 2 ile 27 yer değiştirir. 2, 22'den küçük => 2 ile 22 yer değiştirir. 2, 16'dan küçük => 2 ile 16 yer değiştirir.)
2,16,22,27,18,6

Adım 5: (18, 27'den küçük => 18 ile 27 yer değiştirir. 18, 22'den küçük => 18 ile 22 yer değiştirir.)
2,16,18,22,27,6

Adım 6: (6, 27'den küçük =>6 ile 27 yer değiştirir.6, 22'den küçük => 6 ile 22 yer değiştirir.6, 18'den küçük => 6 ile 18 yer değiştirir.6, 16'dan küçük => 6 ile 16 yer değiştirir.)
2,6,16,18,22,27

Dizinin son hali = 2,6,16,18,22,27

<h4>Big (0) Notasyonu </h4>
O(n²)

<h4>Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız</h4>
ortalarda bir yerde olduğu için <b>average case (O(n))</b> kapsamına girer.

<h4>[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.</h4>
Adım 1: [7,3,5,8,2,9,4,15,6]
Adım 2: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 3: [2, 3, 5, 8, 7, 9, 4, 15, 6]
Adım 4: [2, 3, 4, 8, 7, 9, 5, 15, 6]
