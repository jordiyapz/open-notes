# Intro Desain dan Analisis Algoritma

## Tugas \#1

**1. Jelaskan pemahaman anda terkait desain dan analisis algoritma!**

"Teknik desain algoritma adalah suatu pendekatan umum untuk menyelesaikan masalah secara algoritmik yang dapat diaplikasikan kepada beberapa jenis masalah dari area komputasi yang berbeda" *(Anany Levitin, 2003)*. Oleh karena itu, desain dan analisis algoritma membahas mengenai desain suatu algoritma dengan analisa efisiensinya yang meliputi efisiensi waktu dan efisiensi ruang dalam cakupan pembelajaran ilmu komputasi. 

**2. Jelaskan apa yang dimaksud dengan algoritma yang efektif dan efisien!** 

Algoritma efektif adalah algoritma yang menghasilkan jawaban 		yang benar. Algoritma efisien adalah algoritma yang menggunakan sumber daya secara hemat. Efektifitas berbicara mengenai performa, sedangkan efisiensi berbicara mengenai sumber daya. Suatu algoritma yang efektif belum tentu efisien, Contohnya pencarian invers matriks menggunakan algoritma `Gauss Elimination`dengan efisiensi *O(n^3)* tidak seefisien algoritma `QR-decomposition` dengan efisiensi *O(n^2)* walaupun keduanya sama-sama efektif.

**3. Bagaimana cara mengukur efisiensi suatu algoritma?**

Efisiensi pada algoritma dibagi dua, yaitu efisiensi ruang dan efisiensi waktu. Efisiensi waktu suatu algoritma diukur sebagai fungsi dari ukuran *input* dengan mengitung berapa kali suatu operasi dasar dieksekusi. Seringnya operasi dasar yang dihitung adalah operasi yang cukup berpengaruh pada *running time*.
