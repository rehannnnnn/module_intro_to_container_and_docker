Jelaskan apa yang dimaksud dengan container pada docker ! Container adalah standar unit perangkat lunak yang mengemas kode dan semua depedenciesnya sehingga aplikasi tersebut berjalan cepat dan handal dari satu lingkungan komputing ke lungkingan komputing lainnya.

Jelaskan apa perbedaan antara konsep container dengan virtual machine ! container merupakan virtualisasi OS yang dapat membungkus suatu aplikasi beserta depedency dan environmentnya. setiap container memiliki proses yang terisolir sehingga tidak mengganggu host OS ataupun container lainnya. Sedangkan VM adalah sebuah emulasi dari sebuah sistem komputer, secara sederhanan vm membuat kita membagi resources hardware dari satu hardware fisik menjadi beberapa sistem komputer

Apa yang dimaksud dengan docker file ? dokcerfile adalah sebuah dokumen yang mengangdung commands yang dapat digunakan pengguna pada command line untuk membuat gambar

Apa yang dimaksud dengan docker registery ? registery adalah tempat utuk hosting atau menyimpan gambar yang kita miliki sehingga dapat diakses banyak orang

Jelaskan bagaimana cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung ! Dengan cara membuat setup di satu docker-compose.yml yang nantinya akan mengelompokkan container sehingga dapat terhubung dan dijalankan secara bersamaan