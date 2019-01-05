# C-Program-Pembalik-kata-atau-kalimat

    #include <iostream>
    #include <string.h>
    using namespace std;
    int main(void)
    {
    char str[100];
    int i,l;

    cout << "\t\t Pelita Bangsa \n\n" << endl;
    cout << "=========================================\n" << endl;
    cout << "Nama    : Rafi Alwan Setyawan \nNIM     : 311810325 \nKelas   : TI.18.D7 \n" << endl;
    cout << "=========================================\n" << endl;

    cout<< "\t     Program Pembalik Kata\n" << endl;

    cout<<"MASUKKAN KATA = ";
    cin>>str;

    l=strlen (str);
    cout<<"KATA TERBALIK = ";

    for (i=l-1;i>=0;i--){
        cout<<str[i];
    }
    return 0;
    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Program-Pembalik-kata-atau-kalimat/blob/master/C++%20Program%20Pembalik%20kata%20atau%20kalimat.png?raw=true)
