# Collegeboard-Unit4 Notes
 
4.1 while Loops: "While loops in programming allow a block of code to be executed repeatedly as long as a specified condition is true."
 Scanner scanner = new Scanner(System.in);
        System.out.print("Faktöriyelini hesaplamak istediğiniz sayıyı girin: ");
        int sayi = scanner.nextInt();

        int faktoriyel = 1;

        while (sayi > 0) {
            faktoriyel *= sayi;
            sayi--;
        }

        System.out.println("Faktöriyel: " + faktoriyel);


4.2 for Loops: "For loops provide a concise way to iterate over a range of values, making tasks like list processing or counting more efficient."
 int[] liste = {1, 2, 3, 4, 5};
        int toplam = 0;

        for (int eleman : liste) {
            toplam += eleman;
        }

        System.out.println("Toplam: " + toplam);

4.3 Developing Algorithms Using Strings: "This section focuses on creating algorithms that manipulate and process strings, which are sequences of characters."
Scanner scanner = new Scanner(System.in);
        System.out.print("Kaç satır yıldız deseni çizmek istiyorsunuz? ");
        int satirSayisi = scanner.nextInt();

        // Satırlar için döngü
        for (int i = 1; i <= satirSayisi; i++) {
            // Her satırın içindeki yıldızlar için döngü
            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }
            System.out.println(); // Her satırın sonunda bir alt satıra geç
        }
 

4.4 Nested Iteration: "Nested iteration involves using one loop inside another, enabling complex patterns or multi-dimensional data processing."
for (int i = 1; i <= 10; i++) {
            for (int j = 1; j <= 10; j++) {
                System.out.println(i + " x " + j + " = " + (i * j));
            }
        }
4.5 Informal Code Analysis: "Informal code analysis emphasizes evaluating code for readability, modularity, and overall effectiveness, rather than formal verification."
