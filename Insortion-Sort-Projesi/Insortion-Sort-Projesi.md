 <h1>Proje 1</h1>

<h2>Örnek 1)[22,27,16,2,18,6] -> Insertion Sort<br></h1>

1)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2)Big-O gösterimini yazınız.
3)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

 Çözüm:

 Insortion Sort:En basit sorting algoritmalarından biridir.Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Peki ya devamı? İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktın ki 2.sıradaki eleman en küçük hiç dokunma!!!. Hemen 3. sıraya geç. 4, 5 derken dizi bitti.
 Adım adım insortion sorting:
 [22,27,16,2,18,6]-->insortion sort uygulanacak array(dizi).
 [2,27,16,22,18,6]
 [2,6,16,22,18,27]
 [2,6,16,18,22,27]
  
 Big-O gösterimi:Big-O dediğimiz kavram input büyüklüğüdeki değişime göre algoritmamızın hızının karakteristiğidir.
 Insortion Sorting de n elamanlı array'i sıralamak için ilk olarak n defa işlem yapılır en küçük eleman bulunur.Sonra n-1 defa işlem yapılır ve bu n-2 , n-3 şeklinde 1 e kadar devam eder.
 Toplam yapılan işlem sayısını elemansayına göre ifade edebilirsek Big-O'sunu bulmuş oluruz.
 Burada n elemana göre işlem sayısı:
 n+(n-1)+(n-2)+.....+1 dir buda (n*(n+1))/2 ye eşittir.
 (n*(n+1))/2=(n^2+n)/2 burada n eleman sayısındaki değişimin işlem sayısı üzerindeki etkisinin grafiği çizecek olsak bizim için bunun karakteristiğini asıl etkileyecek olan n^2 dir ve buna dominat(baskın) değer denir.
 Bundan dolayı insortion sort 'ın Big-O(n^2)'dir.
 
 Dizi sıralandıktan sonra 18 syısı average case kapsamına girer.
 

 

 Örnek 2)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
 0.adım:[7,3,5,8,2,9,4,15,6]
 1.adım:[2,3,5,8,7,9,4,15,6]
 2.adım:[2,3,5,8,7,9,4,15,6]
 3.adım:[2,3,4,8,7,9,5,15,6]
 4.adım:[2,3,4,5,7,9,8,15,6]
 
