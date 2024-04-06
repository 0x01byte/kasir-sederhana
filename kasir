#include <iostream>
#include <cstring>

using namespace std;

int main() {
    char lanjut, perintah;
    string nama, makanan;
    int status;
    double belanja, menu, hargamenu, diskon, jumlah, total = 0;

    do {
        cout << "===================================================|" << endl;
        cout << "              W E L C O M E   T O   W A R N A K    |" << endl;
        cout << "===================================================|" << endl;
        cout << "          DAFTAR        ||           HARGA         |" << endl;
        cout << "===================================================|" << endl;
        cout << "MENU MAKANAN :          ||                         |" << endl;
        cout << "1. BEBEK                ||                         |" << endl;
        cout << "  a. BEBEK BAKAR        ||         Rp. 50.000,-    |" << endl;
        cout << "  b. BEBEK GORENG       ||         Rp. 45.000,-    |" << endl;
        cout << "  c. BEBEK RICA RICA    ||         Rp. 60.000,-    |" << endl;
        cout << "===================================================|" << endl;
        cout << "2. AYAM                 ||                         |" << endl;
        cout << "  a. AYAM BAKAR         ||         Rp. 20.000,-    |" << endl;
        cout << "  b. AYAM GORENG        ||         Rp. 15.000,-    |" << endl;
        cout << "===================================================|" << endl;
        cout << "MENU MINUMAN :                                     |" << endl;
        cout << "1. TEH MANIS            ||         Rp.  5.000,-    |" << endl;
        cout << "2. TEH TAWAR            ||         Rp.  3.000,-    |" << endl;
        cout << "3. ES TEH               ||         Rp.  7.000,-    |" << endl;
        cout << "4. TEH HANGAT           ||         Rp.  5.000,-    |" << endl;
        cout << "===================================================|" << endl;

        cout << "\n";
        cout << "MASUKKAN NAMA ANDA : ";
        cin.ignore();
        getline(cin, nama);
        cout << "STATUS PEMBELI : " << endl;
        cout << "1. MEMBER" << "\n" << "2. BUKAN MEMBER" << endl;
        cout << "MASUKKAN STATUS (1 atau 2) : ";
        cin >> status;

        switch (status) {
            case 1:
                do {
                    cout << "===================================================|" << endl;
                    cout << "SELAMAT DATANG KEMBALI " << nama << " ANDA ADALAH MEMBER WARNAK" << endl;
                    cout << "MENU YANG DIPESAN : ";
                    cin.ignore();
                    getline(cin, makanan);
                    cout << "JUMLAH MENU YANG DIPESAN : ";
                    cin >> menu;
                    cout << "MASUKKAN HARGA MENU : ";
                    cin >> hargamenu;
                    jumlah = hargamenu * menu;
                    if (jumlah >= 200000) {
                        diskon = 25000 + 5000;
                    } else {
                        diskon = 5000;
                    }
                    belanja = jumlah - diskon;
                    cout << "===================================================|" << endl;
                    cout << "PESANAN ANDA ADALAH : " << makanan << "\n" << "TOTAL PESANAN : " << menu << endl;
                    total += belanja;
                    cout << "ADA PESANAN LAGI (Y/y) ? ";
                    cin >> perintah;
                } while (perintah == 'y' || perintah == 'Y');
                break;

            case 2:
                do {
                    cout << "===================================================|" << endl;
                    cout << "SELAMAT DATANG " << nama << endl;
                    cout << "MENU YANG DIPESAN : ";
                    cin.ignore();
                    getline(cin, makanan);
                    cout << "JUMLAH MENU YANG DIPESAN : ";
                    cin >> menu;
                    cout << "MASUKKAN HARGA MENU : ";
                    cin >> hargamenu;
                    jumlah = hargamenu * menu;
                    if (jumlah >= 200000) {
                        diskon = 25000;
                    } else {
                        diskon = 0;
                    }
                    belanja = jumlah - diskon;
                    cout << "===================================================|" << endl;
                    cout << "PESANAN ANDA ADALAH : " << makanan << "\n" << "TOTAL PESANAN : " << menu << endl;
                    total += belanja;
                    cout << "ADA PESANAN LAGI (Y/y) ? ";
                    cin >> perintah;
                } while (perintah == 'y' || perintah == 'Y');
                break;
        }

        cout << "===================================================|" << endl;
        cout << "SELAMAT ANDA MENDAPATKAN DISKON SEBESAR " << diskon << "\n\n" << "TOTAL YANG HARUS ANDA BAYAR Rp." << total << endl;
        cout << "\n\n";
        cout << "*****************************************" << endl;
        cout << "TOTAL KESELURUHAN PEMBELIAN Rp." << total << endl;
        cout << "TERIMA KASIH, SELAMAT MENIKMATI" << endl;
        cout << "*****************************************";

        cout << "\n\n\n" << "LANJUT (Y/y) ?";
        cin >> lanjut;

    } while (lanjut == 'y' || lanjut == 'Y');

    return 0;
}
