## Selection Sort Projesi

### Proje 1

 - Soru1: [22,27,16,2,18,6] -> Insertion Sort 
    - Soru1_A: Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
    - Soru1_B: Big-O gösterimini yazınız.
    - Soru1_C: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden     hangisinin kapsamına girer? Yazınız
        - Average case: Aradığımız sayının ortada olması
        - Worst case: Aradığımız sayının sonda olması
        - Best case: Aradığımız sayının dizinin en başında olması.
- Soru2: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

> Soru1 Cevap:
- Soru1_A:
    - 1.Adım  [22||27,16,2,18,6] -> [22,27||16,2,18,6]
    - 2.Adım  [22,27||16,2,18,6] -> [16,22,27||2,18,6]
    - 3.Adım  [22,27,16||2,18,6] -> [2,16,22,27||18,6]
    - 4.Adım  [2,16,22,27||18,6] -> [2,16,18,22,27||6]
    - 5.Adım  [2,16,18,22,27||6] -> [2,6,16,18,22,27]
- Soru1_B: O(n^2)
- Soru1_C: Average case

> Soru2 Cevap:
- 1.Adım -> [2,3,5,8,7,9,4,15,6] 0.index ve 4.index yer değiştirdi.(7 - 2 sayısı yer değiştirdi.)
- 2.Adım -> [2,3,5,8,7,9,4,15,6] 1.index yerinde kalacak.(min = 2 bulundu.)
- 3.Adım -> [2,3,4,8,7,9,5,15,6] 2.index ve 6.index yer değiştirdi.(5 - 4 sayıları yer değiştirdi.)
- 4.Adım -> [2,3,5,6,7,9,4,15,8] 3.index ile 8.index yer değiştirdi.(8 - 6 sayıları yer değiştirdi.)