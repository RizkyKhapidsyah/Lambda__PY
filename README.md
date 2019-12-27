# Lambda__PY
Bahan Ajar Fundamental Pemrograman Python: Membuat Anonymous Function Dengan Lambda.<br><br>
<img src="https://github.com/RizkyKhapidsyah/Lambda__PY/blob/master/Result/Capture.PNG"><br><br>
# Lihat <a href="https://github.com/RizkyKhapidsyah/Lambda__PY/blob/master/Lambda__PY.py">Source Code.</a><br><br>

# Membuat Fungsi Tanpa Nama / Anonymous Function di Python (Lambda Function).

Dalam Python, kita dapat membuat suatu fungsi sederhana yang mengembalikan nilai, yang pendefinisiannya menggunakan operator lambda. Fungsi ini sering disebut lambda function atau fungsi tanpa nama (anonymous function). Perlu kamu ketahui juga, lambda disini bukanlah sebuah perintah atau statemen namun merupakan sebuah ekspresi.

Bentuk umum:

    lambda args : ekspresi

Bentuk umum lambda adalah kata kunci lambda, dan args adalah argumen yang akan dilewatkan ke dalam fungsi. Persis seperti daftar argumen dalam tanda kurung () di def, yang merupakan parameter formal sebagai arumennya. Argumen (args) bisa lebih dari satu, dan diikuti oleh ekspresi setelah tanda titik dua (:). Contoh kode sederhana ini akan mendefinisikan fungsi tanpa nama yang akan melakukan operasi pembagian antara variabel a dan b.

Bisa kita lihat. Di atas kita menggunakan variabel "bagi" sebagai referensi dari objek lambda yang juga sebagai fungsi (function). Kemudian dikuti dengan dua argumen atau (parameter formal) yang akan dilewatkan ke dalam variabel "bagi" (function), dan diikuti ekspresi dimana a / b.

Perlu Kamu ketahui juga bahwa kode yang didefinisikan menggunakan operator lambda harus berupa ekspresi. Itu artinya, statemen yang bukan merupkan ekpresi tidak dapat digunakan di lambda function seperti: (for, while, if, dsb). Untuk lebih mudah dipahami. Berikut ini merupakan contoh kode yang menunjukan penggunaan lambda function.

Code:

      #######################################
       # Nama file:lambda_function.py
       #######################################

      from __future__ import print_function
       def panggil(func):
       return func

      def hello():
       return "Selamat Deadline @ "

      def main():
       # mendefinisikan list
       li_nama = ["Padli","eKo","Ferri","adI","rosyiD","yOga", "Dian"]

      print("List Mula-Mula: ")
       print(panggil(hello()), li_nama)

      print()

      # mengurutkan elemen tanpa mempedulikan huruf kapital/kecil
       li_nama.sort(key=lambda n: n.lower())

      print("Setelah diurutkan: ")
       print(panggil(hello()), li_nama)

      if __name__ == "__main__":
       main()

Output:
List Mula-Mula:

> Selamat Deadline @  ['Padli', 'eKo', 'Ferri', 'adI', 'rosyiD', 'yOga', 'Dian']

Setelah diurutkan:

> Selamat Deadline @  ['adI', 'Dian', 'eKo', 'Ferri', 'Padli', 'rosyiD', 'yOga']

-----
Referensi Artikel: <a href="https://www.codepolitan.com">CodePolitan</a>. Thanks to <a href="https://www.codepolitan.com">CodePolitan.</a><br>
Referensi Soure Code: <a href="https://www.youtube.com/user/faqihzamukhlish"> Kelas Terbuka </a> dan <a href="https://github.com/kelasterbuka"> Kelas Terbuka (Repository)</a>. Created by <a href="https://github.com/faqihza">Faqihza Mukhlish.</a> Thanks To: <a href="https://www.youtube.com/channel/UCRGHjysoCemh4y7tCJQs30w/about">Faqihza Mukhlish.</a><br>

-----
All Source Code is Modified.
