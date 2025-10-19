<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Poling Unit Honda Mitra Jaya</title>
  <style>
    :root{--bg:#f4f6f8;--card:#ffffff;--accent:#0b6efd;--muted:#6b7280}
    body{font-family:Inter,system-ui,Segoe UI,Roboto,"Helvetica Neue",Arial;margin:0;background:var(--bg);color:#111}
    .wrap{max-width:720px;margin:40px auto;padding:20px}
    .card{background:var(--card);border-radius:12px;box-shadow:0 6px 18px rgba(16,24,40,0.06);padding:20px}
    h1{margin:0 0 8px;font-size:20px}
    p.lead{margin:0 0 18px;color:var(--muted)}
    form{display:grid;grid-template-columns:1fr 1fr;gap:12px}
    label{display:block;font-size:13px;color:var(--muted);margin-bottom:6px}
    input,select,textarea{width:100%;padding:10px;border:1px solid #e6e9ef;border-radius:8px;font-size:14px}
    textarea{resize:vertical;grid-column:1 / -1}
    .full{grid-column:1 / -1}
    .actions{display:flex;gap:8px;justify-content:flex-end;align-items:center;margin-top:10px}
    button{background:var(--accent);color:#fff;padding:10px 14px;border-radius:8px;border:0;cursor:pointer}
    .small{background:transparent;color:var(--accent);border:1px solid #d7defc}
    .note{font-size:13px;color:var(--muted);margin-top:8px}
    @media (max-width:640px){form{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <div class="wrap">
    <div class="card">
      <h1>Poling Unit Honda Mitra Jaya</h1>
      <p class="lead">Isi formulir di bawah — data akan dikirim ke admin melalui WhatsApp.</p>

      <!-- CONFIG: ganti nomor admin di sini (format internasional tanpa + dan tanpa spasi) -->
      <script>const ADMIN_WHATSAPP_NUMBER = '6281224917946'; // contoh: 62812... untuk Indonesia
      </script>

      <form id="bookingForm">
        <div>
          <label for="name">Pemohon</label>
          <input id="name" name="name" type="text" required placeholder="Nama pemohon" />
        </div>

        <div>
          <label for="stnk">Nama STNK</label>
          <input id="stnk" name="stnk" type="text" required placeholder="Nama STNK yang diinginkan" />
        </div>

        <div>
          <label for="motor">Unit / Tipe Motor</label>
          <input id="motor" name="motor" type="text" required placeholder="Contoh: Beat CBS ISS" />
        </div>

        <div>
          <label for="warna">Warna</label>
          <input id="warna" name="warna" type="text" required placeholder="Warna Unit" />
        </div>

        <div>
          <label for="otr">Harga On The Road</label>
          <input id="otr" name="otr" type="text" required placeholder="Contoh :32.000.000" />
        </div>

        <div>
          <label for="dppo">DP PO</label>
          <input id="dppo" name="dppo" type="text" required placeholder="Contoh :2.000.000" />
        </div>


        <div>
          <label for="angsuran">Angsuran</label>
          <input id="angsuran" name="angsuran" type="text" required placeholder="Contoh :1.200.000" />
        </div>

        <div>
          <label for="tenor">Tenor</label>
          <input id="tenor" name="tenor" type="text" required placeholder="Contoh:33" />
        </div>

        <div>
          <label for="phone">Nomor HP Pemohon</label>
          <input id="phone" name="phone" type="tel" required placeholder="08xx..." />
        </div>
        <div>
          <label for="phonep">Nomor HP Penjamin</label>
          <input id="phonep" name="phonep" type="tel" required placeholder="Contoh : No ibu, ayah, istri" />
        </div>

        <div>
          <label for="pekerjaan">Pekerjaan</label>
          <input id="pekerjaan" name="pekerjaan" type="text" required placeholder="Contoh: Kayawan swasta (nama perusahaan)" />
        </div>

        <div>
          <label for="leasing">Leasing</label>
          <input id="leasing" name="leasing" type="text" required placeholder="Contoh : FIF" />
        </div>

        <div class="full">
          <label for="notes">Catatan</label>
          <textarea id="notes" name="notes" rows="4" placeholder="Contoh : Jadwal Survei"></textarea>
        </div>

        <div class="full actions">
          <button type="submit">Kirim via WhatsApp ke Admin</button>
          <button type="button" class="small" id="clearBtn">Kosongkan</button>
        </div>
      </form>

      <p class="note">Catatan: untuk mengirim pesan otomatis, browser akan membuka WhatsApp Web (atau aplikasi WhatsApp jika di ponsel).</p>
    </div>
  </div>

  <script>
    // helper: ambil elemen
    const form = document.getElementById('bookingForm');
    const clearBtn = document.getElementById('clearBtn');

    function buildMessage(data){
      return `Poling Unit Honda Mitra Jaya\n` +
             `Nama      : ${data.name}\n` +
             `Nama STNK : ${data.stnk}\n` +
             `Unit / Tipe Motor : ${data.motor}\n` +
             `Warna     : ${data.warna}\n` +
             `OTR       : Rp. ${data.otr}\n` +
             `DP PO     : Rp.${data.dppo}\n` +
             `Angsuran  : Rp.${data.angsuran}\n` +
             `Tenor     : ${data.tenor}x\n` +
             `Nomor HP Pemohon  : ${data.phone}\n` +
             `Nomor HP Penjamin  : ${data.phonep}\n` +
             `Pekerjaan : ${data.pekerjaan}\n` +
             `Leasing   : ${data.leasing}\n` +
             `Catatan   : ${data.notes || '-'}\n` +
             `\nMohon konfirmasi dan jadwalkan survei.`;
    }

    form.addEventListener('submit', function(e){
      e.preventDefault();
      const formData = new FormData(form);
      const data = Object.fromEntries(formData.entries());

      // basic validation
      if(!ADMIN_WHATSAPP_NUMBER || ADMIN_WHATSAPP_NUMBER.length < 6){
        alert('Nomor admin WhatsApp belum dikonfigurasi. Buka file dan isi ADMIN_WHATSAPP_NUMBER.');
        return;
      }

      const message = buildMessage(data);
      const encoded = encodeURIComponent(message);
      // gunakan wa.me untuk web compatibility
      const url = `https://wa.me/${ADMIN_WHATSAPP_NUMBER}?text=${encoded}`;

      // buka WhatsApp Web / aplikasi
      window.open(url, '_blank');

      // opsional: beri notifikasi kecil
      alert('Form terisi — WhatsApp admin akan terbuka untuk mengirim pesan.');
    });

    clearBtn.addEventListener('click', ()=>{form.reset();});
  </script>
</body>
</html>
