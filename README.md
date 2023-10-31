detail:
1.	import java.util.Scanner;: Mendeklarasikan penggunaan kelas Scanner dari pustaka Java untuk membaca input dari pengguna.
2.	public class KalkulatorSederhana {: Mendefinisikan kelas KalkulatorSederhana yang berisi program kalkulator.
3.	public static void main(String[] args) {: Metode utama main yang akan dieksekusi saat program dijalankan.
4.	Scanner input = new Scanner(System.in);: Membuat objek Scanner bernama input untuk membaca input dari pengguna melalui konsol.
5.	Menampilkan pesan awal kalkulator.
6.	System.out.print("Masukkan angka pertama : ");: Menampilkan pesan untuk meminta pengguna memasukkan angka pertama.
7.	double a = input.nextInt();: Membaca angka pertama yang dimasukkan oleh pengguna dan menyimpannya dalam variabel a.
8.	System.out.print("Masukkan angka kedua : ");: Menampilkan pesan untuk meminta pengguna memasukkan angka kedua.
9.	double b = input.nextInt();: Membaca angka kedua yang dimasukkan oleh pengguna dan menyimpannya dalam variabel b.
10.	Menampilkan menu operasi matematika yang tersedia.
11.	System.out.print("Masukkan pilihan (1/2/3/4) : ");: Menampilkan pesan untuk meminta pengguna memasukkan pilihan operasi (dalam bentuk angka).
12.	int pilihan = input.nextInt();: Membaca pilihan operasi yang dimasukkan oleh pengguna dan menyimpannya dalam variabel pilihan.
13.	Menggunakan struktur switch untuk mengeksekusi operasi sesuai dengan pilihan pengguna.
    case 1 -> { ... }: Jika pilihan adalah 1, maka menjalankan penjumlahan dan menampilkan hasilnya.
    case 2 -> { ... }: Jika pilihan adalah 2, maka menjalankan pengurangan dan menampilkan hasilnya.
    case 3 -> { ... }: Jika pilihan adalah 3, maka menjalankan perkalian dan menampilkan hasilnya.
    case 4 -> { ... }: Jika pilihan adalah 4, maka menjalankan pembagian dan menampilkan hasilnya. Namun, sebelum melakukan pembagian, dilakukan pemeriksaan untuk memastikan bahwa pengguna tidak membagi oleh nol, dan jika demikian, pesan kesalahan ditampilkan.
default -> { ... }: Ini adalah kasus default yang akan dieksekusi jika pilihan tidak cocok dengan kasus lainnya. Pesan kesalahan ditampilkan.
14.	input.close();: Menutup objek Scanner setelah selesai membaca input.