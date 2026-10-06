# Analisis Titik Panas Indonesia: El Niño 2023 vs Non-El Niño (2021–2025)
Projek Statistika dan Probabilitas – Kelompok 10, 3TI B, Politeknik Caltex Riau
 
## Dosen Pengampu
Mona Elviyenti, S.Si., M.Si.

## Anggota
- Fathur Rizky Assani (2455301068)
- Joy Agave (2455301086)
- M. Iqbal Najuan Viskhal (2455301092)
- Marcel Ariyanto (2455301104)
 
## Sumber data
NASA FIRMS – VIIRS S-NPP Collection 2, area Indonesia, 2021-01-01 s.d. 2025-12-31
(Fire Archive Download Request ID 806233). Batas provinsi: Natural Earth Admin-1.
 
## Cara menjalankan
1. Buka notebooks/01_pipeline_data.ipynb di Google Colab, upload data/raw/...xlsx, Run all.
2. Jalankan notebooks/02_analisis_deskriptif.ipynb.
 
## Alur pipeline
Ingestion → Validasi → Cleaning (type=0) → Transformasi (pulau, kelompok tahun) → Agregasi harian → Analisis

 
