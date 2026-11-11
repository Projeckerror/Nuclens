<div align="center">
  <img src="banner.png" width="100%" alt="NucLens Security Scanner">
</div>

╔══════════════════════════════════════════════════════════════╗
║                         N U C L E N S                        ║
║                 WEBSITE SECURITY SCANNER                     ║
║                    SCAN • DETECT • REPORT                     ║
╚══════════════════════════════════════════════════════════════╝

Nuclens adalah alat pemindai website untuk membantu memeriksa dan
menemukan indikasi masalah keamanan pada website. Nuclens memiliki
konsep penggunaan yang mirip dengan Nuclei.

Dibuat oleh : Mr Panglima Jatim

──────────────────────────────────────────────────────────────
  1. PERSIAPAN DAN INSTALASI MODUL
──────────────────────────────────────────────────────────────

Jalankan perintah berikut di Kali Linux / Debian.

[ A ] Install paket sistem

sudo apt update
sudo apt install python3-pycryptodome python3-full python3-venv -y

[ B ] Masuk ke folder proyek

cd /home/kali/x3-env

[ C ] Buat virtual environment

python3 -m venv venv

[ D ] Aktifkan virtual environment

source venv/bin/activate

[ E ] Install modul Python

pip install pycryptodome
pip install rich

──────────────────────────────────────────────────────────────
  2. CARA MENJALANKAN NUCLENS
──────────────────────────────────────────────────────────────

Pastikan virtual environment sudah aktif, kemudian jalankan:

python Nuclens.py -u https://contoh.com

Ganti https://contoh.com dengan URL website yang kamu miliki
atau website yang sudah memberikan izin untuk diuji.

──────────────────────────────────────────────────────────────
  3. HASIL SCANNING
──────────────────────────────────────────────────────────────

Hasil scanning akan disimpan secara otomatis ke file:

Nuclens.txt

Periksa file tersebut di folder kerja Nuclens untuk melihat
hasil pemindaian.

──────────────────────────────────────────────────────────────
  4. DUKUNG NUCLENS
──────────────────────────────────────────────────────────────

Jika Nuclens bermanfaat:

  ★ Berikan STAR pada repository GitHub ini.
  ▶ Subscribe YouTube Panglima Jatim.
  ↗ Bagikan proyek ini kepada teman-teman.

YouTube:
https://www.youtube.com/results?search_query=Panglima+Jatim

──────────────────────────────────────────────────────────────

             DEVELOPED WITH PASSION BY
                  MR PANGLIMA JATIM

              NUCLENS — SCAN RESPONSIBLY
══════════════════════════════════════════════════════════════
