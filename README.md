# INSERTION-SORT-PROJES-Patika.dev

Patika.dev ve Kodluyoruz marmara üniversitesi yazılıma başlangıç eğitiminin ilk projesi

[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

CEVAP=

AŞAMA: ilk aşamada örüntüye ait en küçük sayının hangisi olduğunun tespitini yaparız. En küçük sayıyı bulunca bu sayıyı en baştaki sayıyla yer değiştiriyoruz. En küçük sayının 2 olduğunu belirledik ve en baştaki 22 sayısıyla yer değiştiriyoruz. Yani; [2,27,16,22,18,6]şeklinde oluyor.
2.AŞAMA: Bu aşamada örüntüye ait en küçük 2.sayının hangisi olduğunun tespitini yapıyoruz. Bu sayının 6 olduğunu tespit ediyoruz ve örüntüde ikinci sırada bulunan yani 27 sayısıyla yer değiştiriyoruz. Yani; [2,6,16,22,18,27] şeklinde oluyor.

3.AŞAMA: Bu aşamada örüntüye ait en küçük üçüncü sayının hangisi olduğunu tespitini yaparız. Bu sayının 16 olduğunu tespit ediyoruz fakat zaten bu sayı halihazırda üçüncü sırada olduğu için herhangi bir işlem yapmıyoruz. Yani, [2,6,16,22,18,27] şeklinde oluyor.

4.AŞAMA: Bu aşamada örüntüye ait en küçük dördüncü sayının hangisi olduğunun tespitini yapıyoruz. Bu sayının 18 olduğunu tespit ediyoruz. Örüntüde dördnüncü sırada bulunan 22 sayısıyla örüntüdeki 18 sayısının yerlerini değiştiriyoruz. Yani; [2,6,16,18,22,27] şeklinde oluyor.

5.AŞAMA: Bu aşamada örüntüye ait en küçük beşinci sayının hangisi olduğunun tespitini yaparız. Bu sayının 22 olduğunu tespit ediyoruz. Bu sayı halihazırda doğru yerde olduğu için herhangi bir işlem yapmıyoruz. Yani, [2,6,16,18,22,27] şeklinde oluyor.

6.AŞAMA: Bu aşamada en son sayı olarak 27 kaldı herhangi bir işlem yapmayız. [2,6,16,18,22,27] şeklinde insertion sort tamamlanır.

2.Big-O gösterimini yazınız.

CEVAP= O(n2) ' dir. ( YAZIYLA; EN KARE )

3.Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

CEVAP= WORST CASE [27,22,18,16,6,2] BEST CASE [2,6,16,18,22,27]

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

CEVAP= Dizi sıralandıktan sonra 18 sayısı başta ve sonda değil de ortada olduğu için bu yüzden "average case" kapsamına girmektedir.

5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

CEVAP= 1.AŞAMA: En küçük sayının 2 olduğunu belirliyoruz. En baştaki 7 sayısıyla yer değiştiriyoruz. Yani; [2,3,5,8,7,9,4,15,6] şeklinde olur.

2.AŞAMA: En küçük ikinci sayının 3 olduğunu belirliyoruz ancak 3 sayısının doğru yerde olmasından ötürü herhangi bir değiştirme işlemi yapmıyoruz. Yani, [2,3,4,8,7,9,5,15,6] şeklinde olur.

3.AŞAMA: Bu aşamada 4 ile 5 yer değiştiriyor. Yani; [2,3,4,8,7,9,5,15,6] şeklinde olur.

4.AŞAMA: Bu aşamada en küçük 4.sayı 5 olduğu için 5 ile 8'i yer değiştiriyoruz. Yani; [2,3,4,5,7,9,8,15,6] şeklinde 4.aşama tamamlanır.