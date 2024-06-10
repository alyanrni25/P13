# No 1
## code cpp
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
    void info() {
        cout << "Hewan ini adalah Harimau" << endl;
    }
};

class Singa : public Hewan {
public:
    void info() {
        cout << "Hewan ini adalah Singa" << endl;
    }
};

class Macan : public Hewan {
public:
    void info() {
        cout << "Hewan ini adalah Macan" << endl;
    }
};

int main() {
    Harimau harimau;
    Singa singa;
    Macan macan;
    
    // Menampilkan informasi tentang Harimau
    harimau.info();
    harimau.predator();
    harimau.taring();
    harimau.cakar();

    // Menampilkan informasi tentang Singa
    singa.info();
    singa.predator();
    singa.taring();
    singa.cakar();

    // Menampilkan informasi tentang Macan
    macan.info();
    macan.predator();
    macan.taring();
    macan.cakar();

    return 0;
}
```

### Capture Hasil Running
![p13](https://github.com/alyanrni25/P13/assets/156888432/b86269f1-2cd8-4e77-82db-c3bdd9ef0165)

