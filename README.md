# 📈 simulasi-harga-saham

Simulasi pergerakan harga saham menggunakan metode **Random Walk** dengan Python dan visualisasi grafik menggunakan Matplotlib.

---

## 📖 Deskripsi

Project ini mensimulasikan pergerakan harga saham berdasarkan:

- Return harian historis
- Drift (rata-rata return)
- Volatilitas saham

Metode yang digunakan adalah **Random Walk Simulation**, yaitu pendekatan probabilistik yang umum digunakan dalam analisis pasar saham dan keuangan.

---

## 🚀 Features

- Menghitung return harian saham
- Menghitung drift dan volatilitas
- Simulasi harga saham menggunakan Random Walk
- Visualisasi pergerakan saham
- Mendukung multi-stock simulation

---

## 🧠 Konsep yang Digunakan

### 1. Daily Return

Return harian dihitung menggunakan:

\[
Return = \frac{P_t - P_{t-1}}{P_{t-1}}
\]

---

### 2. Random Walk Simulation

Harga saham berikutnya dihitung berdasarkan:

\[
P_{t+1} = P_t \times (1 + r)
\]

dengan:

- \( P_t \) = harga saat ini
- \( r \) = perubahan acak berdasarkan distribusi normal

---

## 📦 Requirements

Install dependencies terlebih dahulu:

```bash
pip install numpy pandas matplotlib
```

---

## ▶️ Run Program

```bash
python main.py
```

---

## 📊 Example Stocks

Data saham yang digunakan dalam simulasi:

- PGAS
- SMGR
- KLBF
- BBRI

---

## 📈 Visualization

Program akan menghasilkan grafik simulasi pergerakan harga saham untuk setiap emiten berdasarkan metode Random Walk.

---

## 📁 Project Structure

```bash
.
├── main.py
├── README.md
```

---

## 🛠️ Built With

- Python
- NumPy
- Pandas
- Matplotlib

---

## 🎯 Purpose

Project ini dibuat untuk:

- Pembelajaran simulasi saham
- Analisis probabilistik pasar saham
- Implementasi Random Walk
- Visualisasi data finansial
