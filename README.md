# Temel Kavramlar
---
## Algoritma Nedir?
Algoritma Nedir?
Algoritma, Cebrin atası ve kurucusu olarak bilinen Harezmî tarafından 9.yüzyılda cebir alanındaki araştırmaları neticesinde ortaya çıkmıştır. Avrupalılar, Harezmî ismini telaffuz edemediklerinden dolayı algorizm (Arap sayıları kullanarak aritmetik problemler çözme kuralları) olarak kullandılar. Algorizm daha sonra "algoritma" adını aldı.

Algoritma nedir sorusunun cevabı, bir problemin çözümü için gerekli olan adımların bütününe verilen isimdir.Başka bir deyişle ,  algoritma belirli bir durumdan başlayıp belirli bir sonuçta biten problemlere çözüm getiren adımlardır.

## Bilgi bilgisayar tarafından nasıl ifade edilir ?
Şöyle düşünelim, bir insan kendini ifade etmek istediğinde native (ana) bir dil kullanıyor öyle değil mi? Bilgisayar da bilgiyi (Resim, ses, yazı vb) ifade etmek ve döngüyü sağlamak için bit (0 ve 1)' den oluşan ikili sayıları (Binary Numbers) kullanıyor.

İkili sayılarda bulunan 1 ve 0 rakamları (bit), bilgisayarın elektrik iletimi için kullandığı transistörlerin açık veya kapalı olma durumunu gösteriyor. Transistörlerde iki tane komut vardır, 0 (kapat) ve 1 (aç).

Konuyu pekiştirmek için bir örnekle açıklayalım. C#, Java gibi dillerde kullandığımız platformlar aracılığıyla yazdığımız kod ilk olarak derlenir ve makine koduna (0 ve 1'li sayılara) dönüştürülür. Bilgisayar okur ve çıktı verir.

Peki bu derleme nedir ve nasıl olur? Hemencecik anlatalım. Örneğin, bir dilde (örnek Java üzerinden olacak) yazdığınız kod Java'nın hali hazırda sahip olduğu Java Compiler ile derlenerek .class uzantılı dosyayı oluşturur. Haa dikkat, bu format prensesimiz olan sadece JVM (JAVA VİRTUAL MACHİNE)'ye özeldir. İşlemcimiz bu aşamada okuyamadığından işleyemez. JVM (JAVA VİRTUAL MACHİNE) .class uzantılı bytecode'u satır satır işleyerek makine koduna dönüştürür ve çalıştırır.

Özetle, Javada yazılan kod önce bytecode'a çevrilir, daha sonrasında üzerinde çalıştığı makinenin içerisindeki yalın dile (makine koduna) yorumlanarak çalıştırılır.

Sonuç olarak bilgisayarlar kendilerini 0 ve 1 sayıları aracılığıyla ifade eder. Bilgisayar üzerindeki her şey 1 ve 0'lardan oluşur.

Bytecode -> Java derleyicisinin Java ile yazılmış kodların makine dili yerine kendine has oluşturduğu Binary (0 ve 1) dosyasıdır.

JVM -> Java Bytecode formatına derlenmiş programların çalışmasını sağlayan bir sistemdir.

## Sayı Sistemleri
İkili sayı sisteminde sayılar 2 tabanında yazılır. Bu yüzden, ikili sayılar 0 ve 1 kullanarak ifade edilir.<br>
Sayıları ifade ederken genellikle onluk sayı sistemini kullanırız. Onluk sayı sisteminde aralığımız 0 dan 9 a kadar olmasından dolayı tek basamakta 10 farklı durumu ifade edebiliriz. İkili sistemde ise tek basamakta 2 farklı durum ifade edilir; 0 veya 1.<br>
Onluk sayı sistemindeki bir sayı ikilik sisteme, ikilik sistemdeki bir sayı ise onluk sisteme dönüştürülebilir.

## Bilgisayarda Sayısal Olmayan Verilerin Tutulması
Sayısal olmayan bir ifadenin sembol ile gösterimi yapılabilir. Mesela, 1100010010 sayısını onluk tabana çevirdiğimizde değeri 786, fakat sayı olarak değil de bir sembol olarak incelersek karşılığı W harfi olabilir. Başka bir örnek, elimizde 100101010 sembolü var ve bu sembolün karşılık geldiği değer V olabilir.<br>
Sayısal olmayan verilerin bir sembol olduğunu ve 1 ve 0'lardan oluşur.Binary olarak gördüğümüz ifade makine kodundan dolayı farklı bir nesneyi işaret edebilir.

## Bilgisayarda Verilen Tutulması
Bilgisayar, yapısından dolayı içerisinde tutulabilecek veri miktarı sınırlıdır. Bu verilerin en küçük yapı taşları bitlerdir. Bu bitleri bir hafıza gibi düşünebiliriz. Ne kadar çok bit dolar ise o kadar az veri depolama alanımız kalmaktadır. <br>
Bit: Binary Digit'in kısaltılmış halidir.Binary Digit(Bit) ikili basamak(hane) anlamındaır.<br>
Byte, sekiz adet bitin yanyana dizilmiş hali olarak düşünülebilir.Bir byte ile 2^8 yani 256 adet farklı durum ifade edilebilir.

## Recursion
Bir problemin alt problemlere bölünüp hesaplanmasına, nerde son bulacağını belirttiğimiz ifadelere recursion (Özyineleme) diyoruz.<br>


