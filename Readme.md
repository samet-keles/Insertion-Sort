## Proje 1
[22,27,16,2,18,6] -> Insertion Sort
* Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
1. [22,27,16,2,18,6] (n)
2. [2,27,16,22,18,6] (n-1)
3. [2,6,16,22,18,27] (n-2)
4. [2,6,16,18,22,27] (n-3)

* Big-O gösterimini yazınız.  
O(n)

* Time Complexity:
1. Average Case: Worst case ile best casein ortalamasını aldığımızda n^2 olarak buluruz.  
2. Worst case : TAM TERS VERİLMİŞ DİZİ, bu durumda dizinin her bir elemanı bir gerisindekinden küçük olacaktır. Dolayısıyla   1inci eleman için iç döngü 0 2 eleman için geriye doğru 1, 3. eleman için iki daha sonra 3 4 5 6… n kadar geriye hareket yapacaktır. Yani 0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2  
3. Best case : Tam sıralı dizi, n tane sayinin üzerinden birer defa geçer ve hiç birini geriye doğru ilerletme gereği   olmadığı için bu tek geçişle kalır. Yani n.

* Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.  
[2,6,16,18,22,27] Average case Kapsamına girer.

* [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. [7,3,5,8,2,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]

