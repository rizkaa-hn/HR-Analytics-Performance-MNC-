# HR Analytics & Performance MNC

## About the Project
Proyek ini bertujuan untuk menganalisis data karyawan dari sebuah perusahaan multinasional (2 juta records) untuk memberikan insight terkait distribusi tenaga kerja, tingkat attrition, pola kerja, serta perbandingan gaji antar departemen. Dashboard ini membantu HR dalam pengambilan keputusan strategis terkait workforce planning, employee retention, dan compensation management.

## Dataset Overview
Dataset ini berisi 2 juta data karyawan dengan 11 kolom:
1. Employee ID : Identifikasi unik yang ditetapkan untuk setiap karyawan (ex: EMP000001)
2. Full Name : Nama lengkap karyawan
3. Department : Departemen tempat karyawan bekerja (ex: IT, HR, Marketin, etc.)
4. Job Title : Jabatan atau peran dari karyawan (ex: Software Engineer, HR Manager, etc.)
5. Hire Date : Tanggal karyawan direkrut oleh perusahaan
6. Location : Lokasi geografis karyawan
7. Performance Rating : Skor evaluasi kinerja (skala 1-5)
8. Experience Years : Jumlah tahun pengalaman profesional yang dimiliki karyawan
9. Status : Stasus pekerjaan saat ini (ex: Aktif, Resign, etc.)
10. Work Mode : Cara bekerja (ex: Hybrid, Remote)
11. Salary INR : Gaji tahunan karyawan dalam Rupee India
    
## Tools
Aplikasi yang digunakan selama mengerjakan projek ini:
1. Microsoft Power BI
   
## Exploratory Data Analysis
Untuk melakukan analisis pada projek ini, saya menggunakan Microsoft Power BI untuk mengubah raw data menjadi sesuatu yang lebih menarik dan insightful. 

1. Key Statistics
   <img width="1222" height="164" alt="image" src="https://github.com/user-attachments/assets/7b9fabe6-ea69-4afc-8143-aec34918f87e" />
    Secara keseluruhan, perusahaan ini memiliki 2 juta karyawan dengan rata-rata gaji tahunan sekitar ₹896.890 dan rata-rata rating kinerja 3.00. Namun, metrik yang paling signifikan adalah tingkat attrition (tingkat turnover), yang mencapai 25%, sebuah angka yang memerlukan perhatian serius.

2. Distribusi Karyawan
   <img width="457" height="351" alt="image" src="https://github.com/user-attachments/assets/bac6b056-c8cf-489a-a53a-fcc4c8117eab" />
   
   Dari segi distribusi karyawan, mayoritas atau sekitar 70.08% karyawan berstatus Aktif. Karyawan yang Mengundurkan diri dan Dipecat (Resigned dan Terminated) masing-masing berkontribusi sekitar 19.93% dan 5% dari total populasi, yang menjadi indikator penting untuk dianalisis lebih lanjut terkait penyebab tingginya tingkat attrition.
   
   <img width="453" height="342" alt="image" src="https://github.com/user-attachments/assets/ebb07604-edbb-4842-a6da-2e14b78d7af4" />
   
   Dalam hal pola kerja, mayoritas karyawan menjalani pekerjaan secara on-site (59,96% atau 1,2 juta orang), sedangkan sisanya 40,04% (0,8 juta orang) bekerja secara remote. Proporsi ini menunjukkan bahwa meskipun kerja jarak jauh sudah cukup signifikan, perusahaan masih lebih banyak mengandalkan model kerja tatap muka. Temuan ini bisa menjadi dasar untuk evaluasi efektivitas model kerja hybrid dan perumusan kebijakan fleksibilitas kerja di masa depan.

3. Analisis Attrition
   <img width="575" height="348" alt="image" src="https://github.com/user-attachments/assets/d1e759ca-7654-4357-bb04-96deba300367" />

   Tingkat attrition ternyata paling tinggi pada beberapa jabatan spesifik. Visualisasi Attrition by Job Title menunjukkan bahwa Software Engineer dan Sales Executive adalah dua jabatan dengan jumlah attrition terbesar, mengindikasikan bahwa kedua peran ini mungkin menghadapi tantangan retensi yang lebih besar.


## Dashboard
Berikut adalah dashboard dari hasil analisis:
<img width="1121" height="702" alt="Screenshot 2025-08-27 105809" src="https://github.com/user-attachments/assets/05e5e38f-1c79-443d-a592-3168be53f81a" />


## Conclusion
Dashboard ini mengonfirmasi bahwa perusahaan memiliki tenaga kerja yang besar, dengan komposisi yang beragam dalam hal status dan mode kerja. Meskipun perusahaan berhasil mempertahankan sebagian besar karyawan (70.08% Aktif), tingkat attrition sebesar 25% adalah masalah yang tidak bisa diabaikan. Tingkat ini menunjukkan adanya masalah retensi yang perlu ditangani. Masalah ini diperkuat oleh fakta bahwa jabatan-jabatan kunci, seperti Software Engineer dan Sales Executive, menunjukkan jumlah turnover yang sangat tinggi.

## Recommendation
Berdasarkan data yang disajikan, berikut adalah tiga rekomendasi utama untuk tim HR:
- Lakukan Analisis Attrition Mendalam: Prioritaskan analisis untuk memahami alasan di balik tingginya tingkat attrition secara keseluruhan. Lakukan analisis exit interview, bandingkan kompensasi dengan standar industri, dan nilai faktor-faktor seperti beban kerja atau peluang pengembangan karier.
- Fokus pada Retensi Peran-Peran Kunci: Segera selidiki mengapa Software Engineer dan Sales Executive memiliki tingkat turnover yang tinggi. Pertimbangkan untuk meluncurkan program retensi yang ditargetkan untuk kedua peran tersebut, seperti menawarkan kenaikan gaji, bonus, atau peluang pelatihan dan pengembangan khusus.
- Optimalisasi Strategi Tenaga Kerja: Manfaatkan data distribusi karyawan untuk perencanaan strategis. Misalnya, pastikan departemen seperti IT yang memiliki banyak karyawan didukung dengan struktur manajemen dan sumber daya yang memadai untuk mencegah kelelahan dan mempertahankan kinerja yang baik.
  
## Kontributor
- Nama :  Rizka Hasna Nabila
- Email : rizkahasna94@gmail.com
- Github : @rizkaa-hn
- Linkedin : https://www.linkedin.com/in/rizkahasnanabila/ 
