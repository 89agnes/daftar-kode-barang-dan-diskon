# daftar-kode-barang-dan-diskon
c++
//------//
#include <iostream>

using namespace std;

int main()
{
int pilihan;
char ulang;
do
{
cout << "## Daftar Kode Barang ##" << endl;
cout << "==============================" << endl;
cout << "1. Table" << endl;
cout << "2. Paper" << endl;
cout << "3. Envelopes " << endl;
cout << "4. Computer" << endl;
cout << "5. Book cases" << endl;
cout << endl;

cout << "Masukan kode lokasi: ";
cin >> pilihan;

switch(pilihan){
case 1:
cout << "Nama Item : Table" << endl;
cout << "Harga: 1.000.000" << endl;
cout << "diskon: 100000" << endl;
cout << "harga setelah diskon : 900.000" << endl;
break;
case 2:
cout << "Nama Item : Paper" << endl;
cout << "Harga: 50.000"<< endl;
break;
case 3:
cout << "Nama Item : Envelopes" << endl;
cout << "Harga: 15000" << endl;
cout << "diskon: 1500" << endl;
cout << "Harga setelah diskon: 13500" << endl;
break;

YAYASAN MEMAJUKAN ILMU DAN KEBUDAYAAN
UNIVERSITAS SIBER ASIA
Kampus Menara, Jl. RM. Harsono, Ragunan - Jakarta Selatan.Daerah Khusus Ibukota Jakarta
12550. Telp. (+6221) 27806189. asiacyberuni@acu.ac.id. www.unsia.ac.id

case 4:
cout << "Nama Item : Computer" << endl;
cout << "Harga: 7000000" << endl;
cout << "diskon: 1050000" << endl;
cout << "Harga setelah diskon: 5950000" << endl;
break;
case 5:
cout << "Nama Item : Book Cases" << endl;
cout << "Harga: 150000" << endl;
cout << "diskon: 7500" << endl;
cout << "Harga setelah diskon: 142500" << endl;
break;
default:
cout << "Menu tidak tersedia" << endl;
}
cout << endl;

cout << "Ingin memilih menu lain (y/t)? ";
cin >> ulang;
cout << endl;
}
while (ulang!= 't');

cout << "Terimakasih...";

cout << endl;
return
