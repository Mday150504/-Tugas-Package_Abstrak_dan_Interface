# Program Simulasi Pengguna Laptop dengan Interface (Java)

Repository ini berisi source code **Program Simulasi Pengguna Laptop** yang dikembangkan menggunakan **bahasa pemrograman Java** dengan konsep **Interface dan Pemrograman Berorientasi Objek (OOP)**. Program ini mensimulasikan penggunaan beberapa merek laptop oleh pengguna.

## Deskripsi Program
Program ini dirancang untuk menerapkan konsep **interface**, **inheritance**, dan **polimorfisme** dalam Java. Setiap merek laptop direpresentasikan sebagai class tersendiri yang mengimplementasikan interface `Laptop`. Class `LaptopUser` berperan sebagai pengguna yang dapat menyalakan, mematikan, dan menggunakan laptop.

## Tujuan Pengembangan
- Memahami konsep interface pada Java
- Menerapkan prinsip OOP (Object-Oriented Programming)
- Mengimplementasikan polimorfisme
- Melatih pemodelan class dan object
- Mensimulasikan interaksi antara user dan perangkat

## Struktur File
- `Laptop.java`  
  Interface yang mendefinisikan method dasar laptop

- `LaptopUser.java`  
  Class yang merepresentasikan pengguna laptop

- `Lenovo.java`  
  Implementasi interface `Laptop` untuk merek Lenovo

- `Mackbook.java`  
  Implementasi interface `Laptop` untuk merek MacBook

- `Toshiba.java`  
  Implementasi interface `Laptop` untuk merek Toshiba

- `Main.java`  
  Class utama untuk menjalankan program simulasi

## Konsep OOP yang Digunakan
- **Interface**  
  Digunakan untuk mendefinisikan kontrak method pada laptop

- **Inheritance**  
  Class laptop mewarisi perilaku dari interface

- **Polymorphism**  
  Satu interface dapat memiliki banyak implementasi merek laptop

- **Encapsulation**  
  Atribut dan method dikelola dalam class masing-masing

## Cara Kerja Program
1. Program dijalankan melalui class `Main`.
2. User memilih atau menggunakan salah satu merek laptop.
3. Laptop dapat dinyalakan, digunakan, dan dimatikan.
4. Setiap merek laptop memiliki implementasi perilaku sendiri.

## Contoh Alur Program
- User menggunakan laptop Lenovo
- Laptop dinyalakan
- Laptop digunakan
- Laptop dimatikan

## Teknologi yang Digunakan
- Java
- Konsep OOP
- Interface Java

## Cara Menjalankan Program
1. Pastikan Java Development Kit (JDK) sudah terpasang.
2. Compile seluruh file:
   ```bash
   javac *.java
