# Klasifikasi Jenis Sampah

 klasifikasi gambar sampah ke dalam **10 kategori** menggunakan *deep learning*.

## Model yang Digunakan

| Model           | Keterangan                                                |
|-----------------|-----------------------------------------------------------|
| **MobileNetV2** | *Transfer learning* dengan bobot ImageNet                 |
| Custom CNN      | CNN sederhana (3 lapisan konvolusi) yang dilatih dari nol |

## Dataset

**12.259 gambar** sampah yang terbagi ke dalam 10 kelas:

| Kelas        | Keterangan                | Jumlah |
|--------------|---------------------------|-------:|
| `battery`    | Baterai                   |    756 |
| `biological` | Sampah organik            |    699 |
| `cardboard`  | Kardus                    |  1.411 |
| `clothes`    | Pakaian                   |  1.892 |
| `glass`      | Kaca                      |  1.736 |
| `metal`      | Logam                     |    930 |
| `paper`      | Kertas                    |  1.336 |
| `plastic`    | Plastik                   |  1.597 |
| `shoes`      | Sepatu                    |  1.449 |
| `trash`      | Sampah residu / lain-lain |    453 |

Sumber: [Garbage Classification V2 (Kaggle)](https://www.kaggle.com/datasets/sumn2u/garbage-classification-v2)

## Teknologi yang Digunakan

- Python 3
- TensorFlow / Keras
- scikit-learn
- pandas, NumPy
- Pillow
- Matplotlib
- Google Colab (GPU T4)

## Struktur Repositori

```
.
├── Klasifikasi_Jenis_Sampah.ipynb   # Notebook utama
├── Dataset_Garbage/                 # Dataset gambar (10 folder kelas)
└── README.md
```

