# ÖDEV : 
# Üslü Sayı Hesaplama :
* Java ile kullanıcının girdiği değerler üslü sayı hesaplayan programı "For Döngüsü" kullanarak yazınız.

```
package DongulerPratik;

import java.util.Scanner;
public class UsluSayiHesaplama {
    public static void main(String[] args) {
        int n,k,total=1;
        Scanner inp = new Scanner(System.in);
        System.out.print("Üssü Alınacak Sayıyı Giriniz : ");
        n=inp.nextInt();
        System.out.print("Üs Olacak Sayı Giriniz : ");
        k=inp.nextInt();
        for (int i=1;i<=k;i++){
            total*=n;
        }
        System.out.print(total);
    }
}
``` 
# Patika Profilim :
<a href='https://academy.patika.dev/profile'><u>Patika Profilim</u></a>