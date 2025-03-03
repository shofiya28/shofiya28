class Mahasiswa:
    def __init__(self, nim, prodi, angkatan):
        self.nim = nim
        self.prodi = prodi
        self.angkatan = angkatan

    def mengikuti_pmb(self):
        print(f"Mahasiswa prodi PTI angkatan {self.angkatan} sedang mengikuti PMB.")

    def mengisi_absensi(self):
        print(f"Mahasiswa prodi {self.prodi} telah mengisi absensi kehadiran.")

    def presentasi_tugas(self):
        print(f"Mahasiswa dengan NIM {self.nim} sedang melakukan presentasi tugas.")

mahasiswa1 = Mahasiswa("A12345678", "Teknik Informatika", 2024)
mahasiswa2 = Mahasiswa("E87654321", "Sistem Informasi", 2023)

mahasiswa1.mengikuti_pmb()
mahasiswa1.mengisi_absensi()
mahasiswa2.presentasi_tugas()
