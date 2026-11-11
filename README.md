<div align="center">
  <img src="banner.png" width="100%" alt="NucLens Security Scanner">
</div>

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nuclens | Website Scanner</title>
  <style>
    :root{--bg:#07111f;--panel:#101e31;--line:#173d5a;--cyan:#22d3ee;--text:#e5f3ff;--muted:#9bb2c8}
    *{box-sizing:border-box}body{margin:0;padding:28px 16px;background:radial-gradient(circle at top,#102c49 0,var(--bg) 55%);color:var(--text);font-family:Arial,Helvetica,sans-serif;line-height:1.65}
    .wrap{max-width:900px;margin:auto}.hero{text-align:center;padding:38px 22px;border:1px solid var(--line);border-radius:20px;background:linear-gradient(145deg,#10263d,#081321);box-shadow:0 0 35px #0891b233}
    .logo{display:inline-block;color:var(--cyan);font-size:clamp(34px,8vw,62px);font-weight:900;letter-spacing:4px;text-shadow:0 0 22px #06b6d4aa}.tagline{color:var(--muted);margin:8px 0 0}
    .pill{display:inline-block;margin-top:18px;padding:5px 12px;border:1px solid #0e7490;border-radius:999px;color:var(--cyan);font-size:12px;letter-spacing:1px}
    .card{margin-top:20px;padding:24px;border:1px solid var(--line);border-radius:16px;background:#0d1a2bdf}h2{margin:0 0 12px;color:var(--cyan);font-size:21px}p,li{color:var(--muted)}
    code{color:#a5f3fc;background:#06101d;border:1px solid #173d5a;border-radius:6px;padding:2px 6px}pre{position:relative;overflow-x:auto;padding:42px 18px 18px;border:1px solid #164e63;border-radius:12px;background:#030b15;color:#b9f5ff}pre code{padding:0;border:0;background:transparent;color:inherit}
    .copy{position:absolute;top:9px;right:9px;border:1px solid #155e75;border-radius:7px;padding:5px 10px;background:#0c2638;color:var(--cyan);cursor:pointer}.copy:hover{background:#164e63}
    .footer{text-align:center;padding:28px 12px 8px;color:var(--muted)}.star{color:#facc15;font-weight:bold}a{color:var(--cyan);text-decoration:none}a:hover{text-decoration:underline}.note{border-left:3px solid var(--cyan);padding-left:13px}
    @media(max-width:560px){body{padding:14px 10px}.card{padding:18px}}
  </style>
</head>
<body>
<main class="wrap">
  <header class="hero"><div class="logo">NUCLENS</div><p class="tagline">Website Security Scanner</p><span class="pill">SCAN • DETECT • REPORT</span></header>
  <section class="card"><h2>🔎 Tentang Nuclens</h2><p><strong>Nuclens</strong> adalah alat pemindai website untuk membantu memeriksa dan menemukan indikasi masalah keamanan pada website. Nuclens memiliki konsep penggunaan yang mirip dengan Nuclei dan dibuat oleh <strong>Mr Panglima Jatim</strong>.</p></section>
  <section class="card"><h2>⚙️ Instalasi Modul</h2><p>Jalankan perintah berikut pada Kali Linux atau Debian:</p>
    <pre><button class="copy" onclick="copyCode(this)">Salin</button><code>sudo apt update
sudo apt install python3-pycryptodome python3-full python3-venv -y</code></pre>
    <p>Masuk ke folder Nuclens, buat virtual environment, lalu aktifkan:</p>
    <pre><button class="copy" onclick="copyCode(this)">Salin</button><code>cd /home/kali/x3-env
python3 -m venv venv
source venv/bin/activate</code></pre>
    <p>Install modul Python yang dibutuhkan:</p>
    <pre><button class="copy" onclick="copyCode(this)">Salin</button><code>pip install pycryptodome
pip install rich</code></pre>
  </section>
  <section class="card"><h2>🚀 Cara Menjalankan</h2><p>Jalankan Nuclens dengan memasukkan URL website target:</p>
    <pre><button class="copy" onclick="copyCode(this)">Salin</button><code>python Nuclens.py -u https://contoh.com</code></pre>
    <p class="note">Ganti <code>https://contoh.com</code> dengan URL website yang kamu miliki atau yang sudah memberikan izin untuk diuji.</p>
  </section>
  <section class="card"><h2>📄 Hasil Scanning</h2><p>Hasil pemindaian akan disimpan otomatis ke file <code>Nuclens.txt</code> di folder kerja program.</p></section>
  <section class="card"><h2>⭐ Dukung Pengembangan</h2><p>Jika Nuclens bermanfaat, jangan lupa berikan <span class="star">⭐ STAR</span> pada repository ini dan dukung channel YouTube <strong>Panglima Jatim</strong>.</p><p>▶️ <a href="https://www.youtube.com/results?search_query=Panglima+Jatim" target="_blank" rel="noopener noreferrer">Cari dan subscribe Panglima Jatim di YouTube</a></p></section>
  <footer class="footer"><div>Developed by <strong>Mr Panglima Jatim</strong></div><div>NUCLENS — Scan responsibly.</div></footer>
</main>
<script>
function copyCode(button){const code=button.parentElement.querySelector('code').innerText;const done=()=>{const old=button.innerText;button.innerText='Tersalin!';setTimeout(()=>button.innerText=old,1400)};if(navigator.clipboard&&window.isSecureContext){navigator.clipboard.writeText(code).then(done)}else{const area=document.createElement('textarea');area.value=code;document.body.appendChild(area);area.select();document.execCommand('copy');area.remove();done()}}
</script>
</body>
</html>

