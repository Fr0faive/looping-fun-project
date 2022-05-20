# Tentang Repo ini
Repo ini bertujuan untuk menyimpan tugas Looping

## Social Media
* [Instagram](https://www.instagram.com/fai.kryz/)
* [Facebook](https://www.facebook.com/FaikarMochT)

## KickRoom
```
#include <iostream>
using namespace std;

struct wpn_data {
    int id;
    string nama_user;
    string nama_wpn;
    string tipe_wpn;
};

int main() {
	// Sebuah program scan room game di mana penggunaan senjata Shotgun tidak diperkenankan
	cout << "=== Don't Use Shotgun Weapon ==="<<endl;
    wpn_data wpn[] {
        {
            1,
            "Andhika",
            "AK-47",
            "AssaultRifle",
        },
        {
            2,
            "Faiz",
            "P90",
            "SubMachineGun",
        },
        {
            3,
            "Grennz",
            "M1887",
            "Shotgun",
        },
        {
            4,
            "Freedy",
            "L115A1",
            "SniperRifle",
        },
        {
            5,
            "Lorenz",
            "Glock",
            "SecondaryRifle",
        }
    };
    
    for (int i=0; i<5;i++) {
        if (wpn[i].tipe_wpn == "Shotgun") {
            cout << "User " << wpn[i].nama_user << " di-kick karena telah menggunakan Shotgun";
	    break;
        }
        cout << "User " << wpn[i].nama_user << ", menggunakan " << wpn[i].nama_wpn << ", tipe " << wpn[i].tipe_wpn << endl;
    }
}
```
![image](https://user-images.githubusercontent.com/105912788/169553896-6814b208-87ee-49cb-ad21-ad65fe7ae38a.png)

## Pemilihan tiket kereta
