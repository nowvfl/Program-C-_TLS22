# Program-C-_TLS22

//  Program Penghitung Harga Setelah Diskon
//
//  Created by Naufal Anwar.
// Tugas TLS Pemrograman

#include <iostream>
using namespace std;

int main() {
    
    //agar user menginput harga beli barang dalam satuan dollar
    cout << "Masukkan Harga Barang = $";
    int harga_beli;
    cin >> harga_beli;
    
    //agar user menginput besar diskon
    cout << "Masukkan Besar Diskon (dalam persen) = %";
    int besar_diskon;
    cin >> besar_diskon;
    cout << "Harga awal = $" << harga_beli<< endl;

    //Perhitungan potongan harga
    double potongan_harga = harga_beli*besar_diskon/100;
    cout << "Total potongan harga = $" << potongan_harga<< endl;
    
    //Perhitungan harga akhir
    double harga_akhir = harga_beli - potongan_harga;
    cout << "Besar harga setelah diskon = $" <<harga_akhir<< endl;
    
    return 0;
}
