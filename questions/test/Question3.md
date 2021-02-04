Diberikan sebuah array A berisi N integer.

Pada array A, beberapa elemen dikatakan "berdekatan" bilamana elemen-elemen tersebut memiliki nilai yang sama dan muncul secara berurutan.

Sebagai contoh, pada array A berikut:
```
  A[0] =  2
  A[1] = -4
  A[2] = -4
  A[3] = -4
  A[4] =  9
```
elemen dengan indeks `1`, `2` dan `3` merupakan elemen-elemen yang "berdekatan".

Tulislah sebuah function:

`public int solution(int[] A);`

yang, ketika diberi input array A yang terdiri atas N integer, mengembalikan sebuah bilangan yang "berdekatan" dengan jumlah elemen paling banyak.

Sebagai contoh:
```
  A[0] = -2
  A[1] = -2
  A[2] =  9
  A[3] =  9
  A[4] =  9
  A[5] =  7
```
fungsi di atas akan mengembalikan `9`, dimana bilangan tersebut muncul secara berdekatan paling banyak, yaitu pada indeks `2`, `3`, dan `4`.

Bilamana terdapat lebih dari 1 kandidat bilangan, kembalikan bilangan yang muncul pertama kali.

Sebagai contoh, ketika fungsi diatas dijalankan dengan input array seperti ini:

```
  A[0] = -2
  A[1] = -2
  A[2] = -2
  A[3] =  9
  A[4] =  9
  A[5] =  9
  A[6] = -2
  A[7] =  7
  A[8] =  9
```

output yang dihasilkan adalah `-2`.