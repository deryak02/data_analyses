[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Aşamalar :
-Dizideki ikinci eleman başlangıç elemanı(27) olarak seçilir ve kendisinden önce gelen yani solundaki eleman ile kıyaslanır.
-Eğer birinci eleman ikinci elemandan büyükse yer değiştirirler.
-Daha küçük bir sayıysa bir sonraki elemana(16) geçilir.
-(22 ve 25)>16 olduğu için birinci sıraya alınır.
-Aynı şekilde 2 de soldaki bütün elemanlardan küçük olduğu için en başa geçer.([2,16,22,27,18,6])
-Sonrasında 18 de yerini bulur.([2,16,18,22,27,6])
-Son olarak [2,6,16,18,22,27].

Big-O gösterimini yazınız :
n + n-1 + n-2 + n-3 + n-4 + n-5 = n.(n+1) / 2 = O(n^2)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız : Average case

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız :
[7,3,5,8,2,9,4,15,6] [2,3,5,8,7,9,4,15,6] [2,3,4,8,7,9,5,15,6] [2,3,4,5,7,9,8,15,6]
