# Uslu-Sayi-Hesaplayan-Program
Java ile kullanıcının girdiği değerler ile üslü sayı hesaplayan programı "For Döngüsü" kullanarak yapınız.

    import java.util.Scanner;

    public class Main {

    public static void main(String[] args) {

        int n, k, total = 1;
        Scanner inp = new Scanner(System.in);
        System.out.print("Üssü alınacak sayı :");
        n = inp.nextInt();
        System.out.print("Üs olacak sayı :");
        k = inp.nextInt();

        for (int i = 1; i <= k; i++) {
            total *= n;

        }
        System.out.println("Cevap :" + total);

      }
    }
    
    
    
![image](https://user-images.githubusercontent.com/107626332/180635245-f2291d9a-700b-4813-8d38-9dd946b60560.png)


    
https://app.patika.dev/ahmetfurkan
