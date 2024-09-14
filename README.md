# Program-CPP_TLS24

Satria Bilawa Yudianta (Gauss)

#include <iostream>
using namespace std;

int main() {
    // Deklarasi variabel
    float num1, num2, hasilKali, hasilBagi;

    // Input angka pertama
    cout << "Masukkan angka pertama: ";
    cin >> num1;

    // Input angka kedua
    cout << "Masukkan angka kedua: ";
    cin >> num2;

    // Perkalian
    hasilKali = num1 * num2;

    // Pembagian
    if (num2 != 0) {
        hasilBagi = num1 / num2;
    } else {
        cout << "Pembagian dengan 0 tidak diperbolehkan." << endl;
        return 1;
    }

    // Output hasil
    cout << "Hasil perkalian: " << hasilKali << endl;
    cout << "Hasil pembagian: " << hasilBagi << endl;

    return 0;
}
