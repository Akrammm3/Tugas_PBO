# Tugas_PBO
Fungsional Pemrograman dan OPP pada Python
def total_harga_produk(daftar_produk):
    total = sum(map(lambda p: p["harga"], daftar_produk))
    return total

produk = [
    {"nama": "Buku", "harga": 5000},
    {"nama": "Pensil", "harga": 1000},
    {"nama": "Penghapus", "harga": 2000},
]

print(total_harga_produk(produk)) # Output: 8000
