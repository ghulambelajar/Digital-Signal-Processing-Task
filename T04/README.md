# 🎧 Tugas T04 - Pengolahan Sinyal Suara

Tugas individu T04 yang bertujuan untuk menerapkan operasi dasar pada sinyal suara menggunakan Python dan pustaka Librosa.

## 📁 File Audio

Berikut adalah file audio yang digunakan dan dihasilkan dari proses transformasi:

| Nama File         | Deskripsi                                      |
|-------------------|------------------------------------------------|
| `bird_song.mp3`   | File suara asli (dikonversi ke mp3)            |
| `normalized.mp3`  | Setelah normalisasi amplitudo                  |
| `denoised.mp3`    | Setelah noise reduction (moving average)       |
| `pitch_up.mp3`    | Setelah pitch shifting (+5 semitone)           |
| `faster.mp3`      | Setelah time stretching (1.5x lebih cepat)     |

> Semua file awalnya dalam format `.wav`, namun dikonversi ke `.mp3` untuk menghindari batas ukuran GitHub.

## 🧪 Tahapan Proses

1. **Load dan visualisasi waveform**  
2. **Normalisasi amplitudo**
3. **Noise reduction** dengan filter moving average
4. **Analisis frekuensi** menggunakan spektrogram (STFT)
5. **Pitch shifting** sebanyak +5 semitone
6. **Time stretching** (percepatan 1.5x)

## 📊 Visualisasi

Visualisasi dilakukan menggunakan `matplotlib` untuk:
- Waveform sebelum dan sesudah proses
- Spektrogram hasil STFT

# 🎧 Tugas T04 - Pengolahan Sinyal Suara

Repositori ini merupakan bagian dari tugas individu T04 yang bertujuan untuk menerapkan operasi dasar pada sinyal suara menggunakan Python dan pustaka Librosa.

## 📁 File Audio

Berikut adalah file audio yang digunakan dan dihasilkan dari proses transformasi:

| Nama File         | Deskripsi                                      |
|-------------------|------------------------------------------------|
| `bird_song.mp3`   | File suara asli (dikonversi ke mp3)            |
| `normalized.mp3`  | Setelah normalisasi amplitudo                  |
| `denoised.mp3`    | Setelah noise reduction (moving average)       |
| `pitch_up.mp3`    | Setelah pitch shifting (+5 semitone)           |
| `faster.mp3`      | Setelah time stretching (1.5x lebih cepat)     |

> Semua file awalnya dalam format `.wav`, namun dikonversi ke `.mp3` untuk menghindari batas ukuran GitHub.

## 🧪 Tahapan Proses

1. **Load dan visualisasi waveform**  
2. **Normalisasi amplitudo**
3. **Noise reduction** dengan filter moving average
4. **Analisis frekuensi** menggunakan spektrogram (STFT)
5. **Pitch shifting** sebanyak +5 semitone
6. **Time stretching** (percepatan 1.5x)

## 📊 Visualisasi

Visualisasi dilakukan menggunakan `matplotlib` untuk:
- Waveform sebelum dan sesudah proses
- Spektrogram hasil STFT

![Waveform Asli](/kaggle/input/experiment-bird-song/images/waveframeAsli.png)
![Waveform Normalisasi](/kaggle/input/experiment-bird-song/images/afternormalisasi.png)
![Spectrogram](/kaggle/input/experiment-bird-song/images/spectrogram.png)


## 🔧 Tools yang Digunakan

- Python 3
- Librosa
- NumPy
- Soundfile
- Matplotlib
- Pydub (untuk konversi WAV → MP3)

## 👤 Refleksi Pribadi

Melalui tugas ini, saya jadi memahami bagaimana operasi dasar sinyal digital bekerja secara nyata. Tidak hanya memanipulasi data, tetapi juga belajar memvisualisasikannya dan mendengar langsung hasil transformasinya. Ini membuka wawasan saya terhadap aplikasi pengolahan sinyal suara dalam kehidupan sehari-hari.




## 🔧 Tools yang Digunakan

- Python 3
- Librosa
- NumPy
- Soundfile
- Matplotlib
- Pydub (untuk konversi WAV → MP3)

## 👤 Refleksi Pribadi

Melalui tugas ini, saya jadi memahami bagaimana operasi dasar sinyal digital bekerja secara nyata. Tidak hanya memanipulasi data, tetapi juga belajar memvisualisasikannya dan mendengar langsung hasil transformasinya. Ini membuka wawasan saya terhadap aplikasi pengolahan sinyal suara dalam kehidupan sehari-hari.

