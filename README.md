<!DOCTYPE html>
<html>
<head>
  <title>ODB Türk Pro+</title>
  <meta charset="UTF-8">
  <style>
    body { font-family: Arial, sans-serif; background: linear-gradient(135deg, #ff6600, #cc0000); color: white; text-align: center; padding: 50px; }
    .card { background: rgba(0,0,0,0.4); padding: 20px; margin: 20px auto; border-radius: 15px; width: 80%; max-width: 500px; }
    h1 { color: cyan; }
    button { padding: 10px 20px; border: none; border-radius: 10px; background: lime; color: black; font-weight: bold; cursor: pointer; }
    button:hover { background: yellow; }
    .locked { opacity: 0.5; }
  </style>
</head>
<body>
  <h1>ODB Türk Pro+</h1>
  <p>Bu sürümde ücretsiz özellikler açık, bazı özellikler <b>Pro satın alındığında</b> açılır.</p>

  <div class="card">
    <h2>🚗 Arıza Kodlarını Oku</h2>
    <p>Bu özellik <b>ücretsiz</b>!</p>
  </div>

  <div class="card locked">
    <h2>🔧 Hata Kodlarını Sil</h2>
    <p>🔒 Kilitli – Pro satın alınmalı</p>
  </div>

  <div class="card locked">
    <h2>📊 Canlı Veri İzleme</h2>
    <p>🔒 Kilitli – Pro satın alınmalı</p>
  </div>

  <div class="card locked">
    <h2>🌍 Çok Dilli Destek</h2>
    <p>🔒 Kilitli – Pro satın alınmalı</p>
  </div>

  <button onclick="alert('Satın alma sayfasına yönlendiriliyorsunuz...')">Pro Satın Al</button>
</body>
</html>
