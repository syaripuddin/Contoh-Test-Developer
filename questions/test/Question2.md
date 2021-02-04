Diberikan sebuah array A yang terdiri atas N integer.

"Melipat" array A berarti mengubah ukuran array A menjadi separuhnya, dimana nilai tiap elemen dihitung berdasarkan mapping berikut ini:

Sebagai contoh, semisal ada array A yang terdiri atas 6 elemen sebagai berikut:

```
  A[0] =  0
  A[1] =  5
  A[2] =  3
  A[3] =  2
  A[4] = -1
  A[5] =  6
```

Proses "melipat" akan menghasilkan output sebagai berikut:

```
  A[0] =  6      // berasal dari (A[0] + A[5]) mod 10
  A[1] =  4      // berasal dari (A[1] + A[4]) mod 10
  A[2] =  5      // berasal dari (A[2] + A[3]) mod 10
```

Jika jumlah elemen bernilai ganjil, maka hasilnya akan seperti berikut ini:

```
  A[0] =  0
  A[1] =  5
  A[2] =  3
  A[3] =  8
  A[4] = -1
  
  menjadi
  
  A[0] = -1      // berasal dari (A[0] + A[4]) mod 10
  A[1] =  3      // berasal dari (A[1] + A[3]) mod 10
  A[2] =  3      // berasal dari A[2]
```

Buatlah fungsi:

`public int solution(int[] A);`

yang, ketika diberi input array A yang terdiri atas N integer, mengembalikan sebuah bilangan yang dibentuk dari proses melipat hingga ukuran array menjadi 1.

Sebagai contoh, semisal array A terdiri atas of 6 elemen sebagai berikut:

```
  A[0] =  0
  A[1] =  5
  A[2] =  3
  A[3] =  8
  A[4] = -1
```

fungsi di atas akan menghasilkan `5`.
