# Binary-Search-Tree-Projesi
Proje 3 [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.  Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Binary Search Tree (İkili Ağaç Yapısı) node'lardan oluşan , her node'un 2 adet child node'a sahip olduğu veri yapısıdır. Peki nedir bu node kavramı ?

Node, bir veri yapısının en temel birimidir. Nodelar veri içerebilir ve birbirleri ile bağlantılıdır.

Bu algoritmada en üstte bulunan node'a root adı verilir.

Root değerinden küçük değere sahip olan node'lar root'un sol tarafına yerleşir.

Root değerinden büyük değere sahip olan node'lar root'un sağ tarafına yerleşir.

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları
İlk değer olan 7 root seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.

![img1](https://user-images.githubusercontent.com/32942860/185233770-e8ddfaa8-0332-4ec5-ace6-b2d5da255486.png)

1 değeri 7'den küçüktür, sola tarafa gider, 5'ten de küçüktür o yüzden 5'in sol altına yazılır.

![img2](https://user-images.githubusercontent.com/32942860/185233828-885165dd-5464-456d-a969-e3ec492c9755.png)

8 değeri 7'den büyüktür, root'un sağ tarafına yazılır.

![img3](https://user-images.githubusercontent.com/32942860/185233857-af63e11a-63bc-4e5c-9a4d-7d230ac6ef2b.png)

3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.

![img4](https://user-images.githubusercontent.com/32942860/185233895-667d380e-388e-4ffa-a01f-73c15797164b.png)

6 değeri 7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır.

![img5](https://user-images.githubusercontent.com/32942860/185233915-bded2d60-7483-45ea-9762-d94f9ced58d6.png)

0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.

![img6](https://user-images.githubusercontent.com/32942860/185233952-fac5aadd-e12d-463b-9da5-cb95b077d7aa.png)

9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır.

![img7](https://user-images.githubusercontent.com/32942860/185233986-39c9fecb-4547-4006-a92e-b57b5f34cf53.png)

4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır.

![img8](https://user-images.githubusercontent.com/32942860/185234003-18240b5b-5342-494b-8f9d-69064eb835aa.png)

2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.

![img9](https://user-images.githubusercontent.com/32942860/185234066-ff0a7760-b04c-4e51-b2c1-52bc317bfc5d.png)
