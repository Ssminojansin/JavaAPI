# JavaAPI
   double vize , Final;

        Scanner sc = new Scanner(System.in);
        System.out.println("vize notu  :");
        vize=sc.nextDouble();
        System.out.println("final notu  :");
        Final = sc.nextDouble();
         double toplam;
         toplam = (vize * 0.3) + (Final * 0.7);
         if (toplam >= 50){
             System.out.println("Tebrikler geçtiniz");
         }else{
             System.out.println("maalesef ");
         }
         System.out.println(toplam);
