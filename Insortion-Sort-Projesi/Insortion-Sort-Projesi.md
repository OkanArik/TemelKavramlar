 <h1>Proje 1</h1>

<h2>Örnek 1) [22,27,16,2,18,6] -> Insertion Sort</h1><br>


<li>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</li><br>
<li>Big-O gösterimini yazınız.</li><br>
<li>Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.</li><br>
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.<br>

<h3> Çözüm: </h3>

 <strong>Insortion Sort:</strong>En basit sorting algoritmalarından biridir.Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. Peki ya devamı? İkinci en küçük elemanı buluyor ve 2. sıra ile değiştiriyor. Baktın ki 2.sıradaki eleman en küçük hiç dokunma!!!. Hemen 3. sıraya geç. 4, 5 derken dizi bitti.<br><br>
<li> Adım adım insortion sorting:<br></li>
 [22,27,16,2,18,6]-->insortion sort uygulanacak array(dizi).<br>
 [2,27,16,22,18,6]<br>
 [2,6,16,22,18,27]<br>
 [2,6,16,22,18,27]<br>
 [2,6,16,18,22,27]<br>
 [2,6,16,22,18,27]<br>
 [2,6,16,22,18,27]<br><br><br>
 <li><strong>Big-O gösterimi:</strong>Big-O dediğimiz kavram input büyüklüğündeki değişime göre algoritmamızın hızının karakteristiğidir.<br></li>
 Insortion Sorting de n elamanlı array'i sıralamak için ilk olarak n defa işlem yapılır en küçük eleman bulunur.Sonra n-1 defa işlem yapılır ve bu n-2 , n-3 şeklinde 1 e kadar devam eder.<br>
 Toplam yapılan işlem sayısını elemansayına göre ifade edebilirsek Big-O'sunu bulmuş oluruz.<br>
 Burada n elemana göre işlem sayısı:<br>
 n+(n-1)+(n-2)+.....+1=(n*(n+1))/2=(n^2+n)/2 ---> sonucun değişimini n'e göre grafiğe dökecek olursak bu grafiğin karakteristiğini  n^2 belirler çünkü sonucun değişimini ençok n^2 etkilemektedir ve buna dominat(baskın) değer denir.<br>

 <strong>Big-O</strong>(n^2)<br><br>
 
<li> Dizi sıralandıktan sonra 18 sayısı average case kapsamına girer.<br><br><br></li>
 

 

<h2> Örnek 2)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.<br> </h2>
 
 0.adım:[7,3,5,8,2,9,4,15,6]<br>
 1.adım:[2,3,5,8,7,9,4,15,6]<br>
 2.adım:[2,3,5,8,7,9,4,15,6]<br>
 3.adım:[2,3,4,8,7,9,5,15,6]<br>
 4.adım:[2,3,4,5,7,9,8,15,6]<br>
 
