# Predict Hospital Missions

![Hospital_Readmissions_Tableau](https://github.com/user-attachments/assets/e201ff21-b135-4c0f-8cc1-5da6d64c988e)

## Business Problem

Rumah sakit menghadapi tantangan signifikan dengan tingkat readmission pasien yang tinggi, mencapai 40,15% dari total kunjungan. Angka ini mengindikasikan adanya potensi masalah dalam kualitas perawatan, manajemen pasca perawatan, dan penanganan kondisi medis spesifik. Beberapa spesialisasi medis, seperti Praktik Umum/Keluarga dan Emergency/Trauma, menunjukkan tingkat readmission yang lebih tinggi, melebihi 49%. Selain itu, diagnosis tertentu seperti diabetes, gangguan pernapasan, dan gangguan peredaran darah memiliki risiko readmission yang lebih tinggi. Tingkat readmission yang tinggi ini tidak hanya meningkatkan biaya perawatan kesehatan tetapi juga mengindikasikan potensi penanganan medis yang tidak optimal, yang berdampak pada kepuasan pasien dan efisiensi sumber daya rumah sakit.

## Key Performance Indicators (KPI)

Untuk mengatasi masalah ini, KPI utama yang ditetapkan adalah menurunkan tingkat readmission keseluruhan dari 40,15% menjadi di bawah 30%. KPI ini diukur dengan persentase pasien yang kembali dirawat dalam 30 hari setelah pemulangan. Selain itu, target spesifik ditetapkan untuk menurunkan tingkat readmission di setiap spesialisasi medis di bawah 40%, dengan fokus khusus pada Praktik Umum/Keluarga dan Emergency/Trauma. Untuk diagnosis berisiko tinggi, target ditetapkan untuk menurunkan tingkat readmission diabetes dari 53,63% menjadi di bawah 45%, gangguan pernapasan dari 49,08% menjadi di bawah 40%, dan gangguan peredaran darah dari 47,93% menjadi di bawah 40%. KPI pendukung meliputi optimasi rata-rata waktu rawat inap dari 4 hari, peningkatan jumlah prosedur medis per pasien, peningkatan efektivitas pengobatan, peningkatan follow-up pasien, edukasi pasien tentang manajemen kondisi medis, dan peningkatan kualitas rencana pemulihan.

## PREDICT HOSPITAL READMISSIONS

Visualisasi ini menyajikan ringkasan dari prediksi readmission rumah sakit, yang mencakup total kunjungan, jumlah readmission, dan non-readmission, serta waktu rata-rata rawat inap. Dari total 29.224 kunjungan, 11.754 pasien mengalami readmission, sementara 13.246 tidak. Waktu rata-rata rawat inap tercatat 14 menit, angka yang sangat rendah dan tidak realistis, sehingga perlu diverifikasi lebih lanjut.

Selanjutnya, visualisasi ini menampilkan distribusi pasien berdasarkan usia, di mana kelompok usia 65-75 tahun memiliki jumlah pasien tertinggi. Hal ini diikuti oleh visualisasi yang menunjukkan tingkat readmission berdasarkan spesialisasi medis, di mana spesialisasi "Lainnya" memiliki tingkat readmission tertinggi, yaitu 60.10%. Spesialisasi "Internal Medicine" juga memiliki tingkat readmission yang signifikan, yaitu 14.25%.

Selain itu, visualisasi ini menyajikan dampak diagnosis terhadap readmission, di mana diagnosis "Circulatory" memiliki jumlah readmission tertinggi, yaitu 7.824. Diagnosis "Other" juga memiliki jumlah readmission yang tinggi, yaitu 6.002. Diagnosis "Respiratory" dan "Diabetes" juga memiliki jumlah readmission yang cukup besar.

Terakhir, visualisasi ini menampilkan waktu rata-rata rawat inap dalam bentuk line chart yang menurun drastis yang sekali lagi menunjukkan bahwa angka 14 menit mungkin tidak akurat. Penurunan yang tajam ini mengindikasikan adanya potensi masalah dalam pengumpulan atau interpretasi data.

Secara keseluruhan, visualisasi ini memberikan gambaran yang jelas tentang faktor-faktor yang mempengaruhi readmission rumah sakit, seperti usia, spesialisasi medis, dan diagnosis. Namun, terdapat beberapa inkonsistensi dalam data, terutama pada waktu rata-rata rawat inap, yang perlu diperbaiki untuk mendapatkan analisis yang lebih akurat dan dapat diandalkan.

## Kesimpulan

Dari visualisasi ini kita dapat mengidentifikasi beberapa pencapaian dan area yang memerlukan perbaikan.  Visualisasi ini berhasil menyajikan data readmission rumah sakit secara komprehensif mencakup jumlah kunjungan, readmission, dan non-readmission, serta distribusi usia pasien. Data ini memberikan gambaran awal tentang skala masalah readmission di rumah sakit.  Visualisasi juga menyoroti spesialisasi medis dan diagnosis yang paling berkontribusi terhadap readmission, yang memungkinkan rumah sakit untuk memfokuskan upaya perbaikan mereka.  Selain itu, visualisasi ini berhasil mengidentifikasi inkonsistensi data, seperti waktu rata-rata rawat inap yang tidak realistis, yang menunjukkan perlunya perbaikan dalam pengumpulan dan interpretasi data.  Pencapaian ini memberikan dasar yang kuat untuk pengembangan strategi intervensi yang efektif guna mengurangi tingkat readmission dan meningkatkan kualitas perawatan pasien.

## Dependensi

* Data dari Kaggle
* Excel
* Jupyter Notebook dan VS Code
* BiqQuery
* Tableau

## Kontribusi

Proyek ini bersifat open-source dan saya mendorong kontribusi dari komunitas. Jika memiliki ide atau perbaikan lalu jangan ragu untuk fork repositori dan kirim pull request.
