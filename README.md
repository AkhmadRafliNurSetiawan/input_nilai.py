# Program Menghitung Rata-rata Nilai

# Membuat list kosong
data_nilai = []

# Perulangan input 5 nilai
for i in range(1, 6):
    nilai = float(input(f"Masukkan nilai ke-{i}: "))
    data_nilai.append(nilai)

# Menghitung total nilai
total = sum(data_nilai)

# Menghitung rata-rata
rata_rata = total / len(data_nilai)

# Menampilkan hasil
print("\n===== HASIL =====")
print("Data nilai :", data_nilai)
print("Total nilai:", total)
print("Rata-rata  :", rata_rata)
