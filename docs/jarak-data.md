## Menghitung Jarak antar Data tipe Numerik

<hr></hr>
1. <i>Minkowski Distance</i>

   Minkowski Distance termasuk <i>Euclidean Distance</i> dan <i>Manhattan Distance</i>, perhitungan jarak dimana nilai m adalah bilangan asli positif dan xi dan yi adalah 2 vector dalam dimensi n

   Rumus untuk <i>Minkowski Distance</i> adalah:
   $$
   d_{min}=(\sum_{i=1}^n|x_{i}-y_{i}|^m)^\frac{1}{m},m\ge1
   $$
   
   <hr></hr>
   
2. <i>Manhattan Distance</i>

   <i>Manhattan Distance</i> agak berbeda daripada <i>Minkowski Distance</i> dimana nilai m=1 sama halnya dengan <i>Minkowski Distance</i> yang sensitif terhadap oulier

   Rumus untuk <i>Manhattan Distance</i>  adalah:

   $$
   d_{man}=\sum_{i=1}^{n}|x_{i}-y_{i}|
   $$

   <hr></hr>

3. <i>Euclidean Distance</i>

   <i>Euclidean Distance</i> adalah perhitungan yang paling terkenal/banyak diketahui digunakan untuk data numerik. Ini berbeda daripada <i>Minkowski Distance</i> dimana nilai m = 2. <i>Euclidean Distance</i> berjalan baik disaat digunakan untuk datasets compact atau isolated clusters. Namun dia memiliki kelemahan yaitu jika dua vektor data tidak mempunyai atribut yang sama, mereka akan memiliki jarak yang lebih kecil dibandingan dengan pasangan data vektor yang mempuna nilai atribut yang sama

   <hr></hr>

4. <i>Average Distance</i>

   Mengenai kelemahan daripada <i>Euclidean Distance</i>, <i>Average Distance</i> adalah modifikasi daripada <i>Euclidean Distance</i> untuk memperbaiki hasil. untuk dua data x,y dalam dimensi-n, rumusnya adalah:
   $$
   d_{ave}=\left(\frac{1}{n}\sum_{i=1}^{n}(x_{i}-y_{i})^2\right)^\frac{1}{2}
   $$

   <hr></hr>

5. <i>Weighted Euclidean Distance</i>

   Jika kedudukan masing masing atribut tersedia, <i>Weighted Euclidean Distance</i> adalah modifikasi dari <i>Euclidean Distance</i>. Jarak ini mempunyai rumus:

   $$
   d_{we}=\left(\sum_{i=1}^n w_{i}(x_{i}-y_{i}\right)^2)^\frac{1}{2}
   $$
   Dimana w adalah berat yang diberikan kepada komponen ke-i

   <hr></hr>

6. <i>Chord Distance</i>

   <i>Chord Distance</i> adalah hasil modifikasi lainnya dari <i>Euclidean Distance</i> untuk mengatasi kelemahan <i>Euclidean Distance</i> lainnya. jarak ini juga bisa digunakan untuk memecahkan masalah yang disebabkan skala pengukuran juga. Jarak ini bisa di kalkulasikan dari non-normalized data. rumus jarak ini adalah:
   $$
   d_{chord}=\left(2-2 \frac{{\sum_{i=1}^n}x_{i}y_{i}}{||x||_{2}||y||_{2}}\right)^\frac{1}{2}
   $$

   <hr></hr>

7. <i>Mahalanobis Distance</i>

   <i>Mahalobis Distance</i> adalah perbedaan ke Euclidean dan Manhattan distance yaitu jarak ini terbebas dari hubungan data yang mana dua data berasal

   $$
   d_{mah}=\sqrt{(x-y)S^{-1}(x-y)^{T}}
   $$

8. <i>Cosine Measure</i>

   Persammaan Cosine kebanyakan digunakan untuk mencari kemiripan dokumen dan rumusnya adalah:
   $$
   Cosine(x,y)=\frac{\sum_{i=1}^{n}x_{i}{y_{i}}}{||x||2||y||2}
   $$

9. <i>Pearson Correlation</i>

   <i>Pearson Correlation</i> Digunakan dalam clustering ekspresi data. Ukuran kemiripan menghitung kemiripan antara bentuk dari dua pola ekspresi. Rumusnya adalah:
   $$
   Pearson(x,y)=\frac{\sum_{i=1}^n(x_{i}-\mu_{x})(y_{i}-\mu_{y})}{\sqrt{\sum_{i=1}^n(x_{i}-y_{i})^2}\sqrt{\sum_{i=1}^n(x_{i}-y_{i})^2}}
   $$

   Dimana mu x dan mu y dimaksudkan untuk x dan y. Jarak ini juga memiliki kelemahan yaitu sensitif terhadap outliers 

   <hr></hr>

