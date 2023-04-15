Readme --Farhan

Tugas praktikum PBM A 14 april 2023

Untuk mengerjkan tugas praktikum minggu ini saya menggunakan
bantuan FirebaseAuth

Berikut merupakan tahapan pengerjaannya:

Step 1:
Bukan pubspec.yaml pada folder project

lalu tambahkan depencies:
firebase_core: ^1.20.0
firebase_auth: ^3.5.0

Step 2:
Buka firebase.com
lalu get started->create project-select account ke default lalu create project

Lalu masuk ke menu Build(pojok kiri) pilih 'Authentication' -> get started
-->email & password di enable--> save

Ke menu Project Overview --> connect android dengan klik icon android(karena saya pakai android)
Lalu isikan Package Name dengan com.example.tugaspbm(diambil dari folder project>android>app>build.gradle)
setelah itu tekan register App--> langkah berikutnya unduh google services json lalu pindah ke folder
project>andorid>app

Lalu ikuti tahap yang ada sesuaikan dengan yang diarahkan jika line tertentu belum ada copy dan paste(bukan mendaur ulang dengan yang baru)
Kalau sudah selesai Continue to Console
Step 3:
Di tahap ini kita fokus ngodingnya, sebelum itu buat dile dan folder di folder project>andorid>lib

yaitu 

>lib
	auth.dart
	main.dart
	widget_tree.dart
	>pages
		home_page.dart
		login_register_page.dart
