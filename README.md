# TugasPertemuan2VisualDekstop
using System;

class Program
{
    static void Main(string[] args)
    {
      
        string nama = "Akbar Azi Nurrohman";
        string kelas = "TI.23.C7";
        string prodi = "Teknik Informatika";
        string kampus = "Universitas Pelita Bangsa";
        string hobi = "Bermain Sepak Bola";

     
        Console.WriteLine("BIODATA");
        Console.WriteLine($"Halo, nama saya adalah {nama}");
        Console.WriteLine($"Dari Kelas TI.23.C9");
        Console.WriteLine($"Saya kuliah pada jurusan {prodi} di {kampus}");
        Console.WriteLine($"Saya memiliki hobi {hobi}");

       
        Console.Write("\nMasukkan angka pertama: ");
        int angka1 = int.Parse(Console.ReadLine());

        Console.Write("Masukkan angka kedua: ");
        int angka2 = int.Parse(Console.ReadLine());

        
        int tambah = angka1 + angka2;
        int kali = angka1 * angka2;
        double bagi = angka2 != 0 ? (double)angka1 / angka2 : 0; 
        int modulus = angka2 != 0 ? angka1 % angka2 : 0;

        
        Console.WriteLine("\n--- Hasil Operasi ---");
        Console.WriteLine($"Penjumlahan: {Math.Abs(tambah)}");
        Console.WriteLine($"Perkalian: {Math.Abs(kali)}");
        Console.WriteLine($"Pembagian: {Math.Abs(bagi)}");
        Console.WriteLine($"Modulus: {Math.Abs(modulus)}");

        Console.WriteLine("\nProgram selesai. Tekan Enter untuk keluar...");
        Console.ReadLine();
    }
}
