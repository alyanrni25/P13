# No 2
## Code cpp
```
#include <iostream>
using namespace std;

class Hewan {
public:
    void predator() {
        cout << "Ini adalah hewan predator" << endl;
    }

    void taring() {
        cout << "Hewan ini memiliki taring" << endl;
    }

    void cakar() {
        cout << "Hewan ini memiliki cakar" << endl;
    }
};

class Harimau : public Hewan {
public:
    void predator() {
        cout << "Hewan ini adalah Harimau" << endl;
    }
};

class Singa : public Hewan {
public:
    void predator() {
        cout << "Hewan ini adalah Singa" << endl;
    }
};

class Macan : public Hewan {
public:
    void predator() {
        cout << "Hewan ini adalah Macan" << endl;
    }
};

int main() {
    Harimau harimau;
    Singa singa;
    Macan macan;
    
    // Menampilkan informasi tentang Harimau
   // predator.info();
    harimau.predator();
    harimau.taring();
    harimau.cakar();

    // Menampilkan informasi tentang Singa
    //predator.info();
    singa.predator();
    singa.taring();
    singa.cakar();

    // Menampilkan informasi tentang Macan
    //predator.info();
    macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
```
## Capture Hasil Running
![P13 no2](https://github.com/alyanrni25/P13/assets/156888432/98250efb-e598-46f7-be13-5a61701c9656)

## Kesimpulan 
Perbedaan output antara no 1 dan 2 kode tersebut terletak pada pemanggilan fungsi predator() dari objek masing-masing kelas turunan.
Pada kode pertama, fungsi predator() dari kelas dasar Hewan yang dipanggil, sehingga output untuk setiap objek adalah "Ini adalah hewan predator".
Sedangkan pada kode kedua, fungsi Predator() yang merupakan override dari fungsi predator() pada masing-masing kelas turunan dipanggil.
Akibatnya, output yang dihasilkan adalah deskripsi spesifik untuk setiap hewan, yaitu "Hewan ini adalah Harimau", "Hewan ini adalah Singa", dan "Hewan ini adalah Macan".



