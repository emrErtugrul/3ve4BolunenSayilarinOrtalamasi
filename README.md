# 3ve4BolunenSayilarinOrtalamasi

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
    
        Scanner inp=new Scanner(System.in);
        
        int sayi ,a,ortalama,bolme;
        System.out.println("Lütfen Bir Sayı Giriniz");
        sayi=inp.nextInt();

        for (a=1;a<=sayi;a++){

            if(a%3==0&&a%4==0){
                bolme=sayi/12;
                ortalama=(12*(bolme*(bolme+1)/2))/bolme;
                System.out.println(ortalama);
            }
        }

    }
}
