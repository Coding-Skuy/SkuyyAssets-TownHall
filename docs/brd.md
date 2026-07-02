# Business Requirements Document (BRD)



## SkuyAssets Pro



**Version:** 1.0

**Status:** Draft

**Author:** CodingSkuy

**Last Updated:** July 2026



---



# 1. Executive Summary



## Project Name



**SkuyAssets Pro**



## Tagline



> **AI-Powered Asset Management for Modern Businesses**



## Project Overview



SkuyAssets Pro adalah platform manajemen aset perusahaan berbasis mobile yang dirancang untuk membantu organisasi mengelola seluruh siklus hidup aset secara digital, efisien, dan berbasis data.



Aplikasi ini mengintegrasikan teknologi **Artificial Intelligence (AI)** untuk membantu proses inventarisasi, pemantauan aset, analisis kondisi aset, prediksi pemeliharaan, hingga pembuatan laporan otomatis.



SkuyAssets Pro dibangun menggunakan pendekatan **serverless architecture** dengan **Flutter**, **Firebase**, dan **Firebase Genkit** sehingga mudah dikembangkan, scalable, dan memiliki biaya operasional yang rendah.



---



# 2. Background



Banyak organisasi masih mengelola aset menggunakan spreadsheet atau proses manual yang memiliki berbagai keterbatasan.



Permasalahan yang sering ditemui antara lain:



* Sulit mengetahui lokasi aset secara aktual.

* Audit aset membutuhkan waktu yang lama.

* Tidak adanya histori pemeliharaan yang terdokumentasi dengan baik.

* Kesulitan memonitor aset yang dipinjam.

* Tidak tersedia analisis terhadap nilai dan kondisi aset.

* Laporan harus dibuat secara manual.

* Pengambilan keputusan masih berdasarkan asumsi, bukan data.



Dengan berkembangnya teknologi cloud dan AI, perusahaan membutuhkan sistem yang mampu membantu pengelolaan aset secara lebih cerdas dan otomatis.



---



# 3. Business Problem Statement



Perusahaan memerlukan sistem yang mampu:



* Mengurangi kehilangan aset.

* Mempercepat proses audit.

* Mempermudah inventarisasi.

* Mengoptimalkan biaya pemeliharaan.

* Meningkatkan transparansi kepemilikan aset.

* Menyediakan insight berbasis AI untuk pengambilan keputusan.



---



# 4. Business Goals



SkuyAssets Pro dikembangkan untuk mencapai tujuan berikut:



### Goal 1



Digitalisasi seluruh proses manajemen aset perusahaan.



### Goal 2



Mengurangi waktu audit aset hingga lebih dari 50%.



### Goal 3



Mengurangi risiko kehilangan aset melalui pelacakan yang lebih baik.



### Goal 4



Menyediakan dashboard aset secara real-time.



### Goal 5



Membantu perusahaan melakukan maintenance secara proaktif menggunakan AI.



### Goal 6



Menyediakan laporan otomatis yang akurat dan mudah dipahami.



---



# 5. Vision



Menjadi platform **AI-First Asset Management System** yang membantu organisasi mengelola seluruh siklus hidup aset secara efisien, modern, dan berbasis data.



---



# 6. Target Users



## Primary Users



### Asset Administrator



Mengelola seluruh data aset perusahaan.



---



### Asset Officer



Melakukan inventarisasi, audit, dan pemeliharaan aset.



---



### Warehouse Staff



Mengelola aset yang berada di gudang.



---



### IT Support



Mengelola aset teknologi seperti laptop, server, printer, dan perangkat jaringan.



---



## Secondary Users



* Finance

* Operational Manager

* Branch Manager

* Internal Auditor

* General Staff (Peminjaman aset)



---



# 7. Business Scope



## In Scope (MVP)



* Authentication

* Company Management

* Department Management

* Asset Management

* Asset Category

* Asset Status

* Asset Image

* QR Code

* Barcode Scanner

* Asset Transfer

* Borrow & Return

* Maintenance History

* Dashboard

* Notification

* AI Assistant

* AI Report

* AI Insight



---



## Out of Scope



* ERP Integration

* SAP Integration

* Oracle Integration

* RFID

* IoT Sensor

* Procurement

* Accounting

* Payroll



---



# 8. Business Objectives



SkuyAssets Pro diharapkan mampu memberikan manfaat bisnis berupa:



* Peningkatan efisiensi operasional.

* Pengurangan biaya maintenance.

* Pengurangan kehilangan aset.

* Peningkatan akurasi data inventaris.

* Pengambilan keputusan yang lebih cepat.

* Transparansi kepemilikan aset.



---



# 9. Key Business Features



## Asset Inventory



Pencatatan seluruh aset perusahaan secara digital.



---



## Asset Tracking



Melacak lokasi dan status aset.



---



## QR Code & Barcode



Identifikasi aset menggunakan QR Code maupun Barcode.



---



## Borrowing Management



Mengelola proses peminjaman dan pengembalian aset.



---



## Asset Maintenance



Mencatat histori servis dan jadwal maintenance.



---



## Dashboard



Menampilkan statistik kondisi aset secara real-time.



---



## Reporting



Menyediakan laporan aset secara otomatis.



---



## AI Assistant



Asisten berbasis AI yang mampu menjawab pertanyaan mengenai data aset menggunakan bahasa alami.



Contoh:



> "Berapa laptop yang belum pernah maintenance selama satu tahun?"



---



## AI Insights



Memberikan analisis seperti:



* Aset yang jarang digunakan.

* Aset dengan biaya maintenance tinggi.

* Risiko kehilangan aset.

* Prediksi penggantian aset.



---



## AI Report Generator



Menghasilkan ringkasan laporan hanya melalui prompt.



Contoh:



> "Buatkan laporan aset bulan ini."



---



# 10. Business Benefits



## Untuk Perusahaan



* Mengurangi pekerjaan administratif.

* Mempercepat audit.

* Meningkatkan akurasi data.

* Menurunkan biaya operasional.



---



## Untuk Manajemen



* Dashboard real-time.

* Insight berbasis AI.

* Pengambilan keputusan yang lebih baik.



---



## Untuk Staff



* Pencarian aset lebih cepat.

* Scan QR lebih mudah.

* Riwayat aset terdokumentasi.



---



# 11. Success Metrics



| KPI                           | Target         |

| ----------------------------- | -------------- |

| Seluruh aset memiliki QR Code | 100%           |

| Waktu pencarian aset          | < 30 detik     |

| Waktu audit                   | Berkurang >50% |

| AI Response Time              | < 5 detik      |

| Dashboard Loading             | < 2 detik      |

| Asset Data Accuracy           | >98%           |



---



# 12. Risks



| Risiko                                   | Mitigasi                                                                   |

| ---------------------------------------- | -------------------------------------------------------------------------- |

| Data aset tidak lengkap                  | Validasi saat input                                                        |

| Pengguna enggan beralih dari spreadsheet | Antarmuka sederhana dan pelatihan singkat                                  |

| Biaya layanan AI meningkat               | Batasi penggunaan AI dengan kuota dan caching                              |

| Kualitas jawaban AI tidak konsisten      | Gunakan prompt yang terstruktur dan validasi data sebelum dikirim ke model |



---



# 13. Assumptions



* Seluruh pengguna memiliki perangkat mobile Android atau iOS.

* Perusahaan memiliki akses internet untuk sinkronisasi data.

* Firebase digunakan sebagai backend utama.

* AI menggunakan Firebase Genkit dengan model Gemini.

* Seluruh aset memiliki identitas unik (QR Code atau Barcode).



---



# 14. Constraints



* MVP hanya mendukung mobile.

* Integrasi dengan ERP belum tersedia.

* RFID belum menjadi bagian dari ruang lingkup.

* AI hanya digunakan sebagai pendukung keputusan, bukan pengganti keputusan bisnis.



---



# 15. High-Level Technology



| Layer           | Technology               |

| --------------- | ------------------------ |

| Mobile          | Flutter                  |

| Authentication  | Firebase Authentication  |

| Database        | Cloud Firestore          |

| Storage         | Firebase Storage         |

| Notification    | Firebase Cloud Messaging |

| AI Framework    | Firebase Genkit          |

| AI Model        | Gemini                   |

| Analytics       | Firebase Analytics       |

| Crash Reporting | Firebase Crashlytics     |



---



# 16. Future Business Roadmap



### Version 1 (MVP)



* Asset Management

* QR Code

* Dashboard

* Borrowing

* Maintenance

* AI Assistant



---



### Version 2



* Offline Mode

* Approval Workflow

* Multi Company

* Asset Booking

* AI Report



---



### Version 3



* Predictive Maintenance

* AI Vision

* OCR Asset Recognition

* Procurement Recommendation



---



### Version 4



* ERP Integration

* RFID

* IoT Monitoring

* Advanced Business Intelligence



---



# 17. Conclusion



SkuyAssets Pro bertujuan menjadi solusi **AI-First Asset Management System** yang menggabungkan kemudahan penggunaan aplikasi mobile dengan kekuatan cloud dan Artificial Intelligence. Melalui digitalisasi proses inventaris, pelacakan, pemeliharaan, dan analisis aset, aplikasi ini diharapkan membantu organisasi meningkatkan efisiensi operasional, transparansi, serta kualitas pengambilan keputusan.



---
