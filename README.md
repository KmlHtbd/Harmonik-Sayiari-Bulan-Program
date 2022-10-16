# Harmonik-Sayiari-Bulan-Program
---
Bu bir [patika.dev](www.patika.dev) projesidir.
```
import java.util.Scanner;
public class harmonik {
    public static void main(String[] args) {
        int n;

        Scanner input = new Scanner(System.in);
        System.out.print("Bir sayı giriniz:");
        n = input.nextInt();

        double i, result=0 ;
        for (i=1; i<=n ;i++){
            result += (1/i);
        }
        System.out.print("Sonuç: "+result);
    }
}
```
