<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Kitchenmate Destek</title>
  <meta name="description" content="Kitchenmate uygulaması için destek ve iletişim sayfası." />
  <link rel="icon" href="data:image/svg+xml,<svg xmlns=%27http://www.w3.org/2000/svg%27 viewBox=%270 0 100 100%27><text y=%27.9em%27 font-size=%2790%27>🍳</text></svg>">
  <style>
    :root{--bg:#f8fafc;--card:#ffffff;--fg:#0f172a;--muted:#64748b;--primary:#2563eb;--ok:#16a34a}
    *{box-sizing:border-box} html,body{margin:0;padding:0;background:var(--bg);color:var(--fg);font:16px/1.6 system-ui,-apple-system,Segoe UI,Roboto,Helvetica,Arial}
    .wrap{max-width:800px;margin:40px auto;padding:0 16px}
    .card{background:var(--card);border-radius:16px;box-shadow:0 6px 20px rgba(2,6,23,.06);padding:24px;margin-bottom:16px}
    h1{font-size:28px;margin:0 0 6px} .sub{color:var(--muted);margin:0 0 16px}
    h2{font-size:18px;margin:18px 0 8px}
    a{color:var(--primary);text-decoration:none} a:hover{text-decoration:underline}
    .pill{display:inline-block;padding:4px 10px;border-radius:999px;background:#eef2ff;color:#3730a3;font-weight:600;font-size:12px;margin-left:8px}
    ul{padding-left:18px;margin:8px 0}
    .footer{color:var(--muted);font-size:13px;text-align:center;margin:24px 0}
    .cta{display:inline-block;background:var(--primary);color:#fff;padding:10px 14px;border-radius:10px;font-weight:600}
    .ok{color:var(--ok);font-weight:700}
    code{background:#f1f5f9;border-radius:6px;padding:2px 6px}
  </style>
</head>
<body>
  <main class="wrap">
    <section class="card">
      <h1>Kitchenmate Destek <span class="pill">v1.0</span></h1>
      <p class="sub">Mutfak & kiler yönetimi, alışveriş listesi ve tarif önerileri – sorularınız için buradayız.</p>
      <p><a class="cta" href="mailto:destek@ornek-domain.com?subject=Kitchenmate%20Destek">destek@ornek-domain.com</a></p>
      <p class="sub">Lütfen e-postanıza iPhone modelinizi ve uygulama sürümünü ekleyin.</p>
    </section>

    <section class="card">
      <h2>Sıkça Sorulanlar</h2>
      <ul>
        <li><strong>Verilerim nerede saklanıyor?</strong> <span class="ok">Cihazınızda yerel olarak</span>. iCloud ya da harici sunucu yok.</li>
        <li><strong>Çoklu kullanıcı desteği var mı?</strong> Yakında eş paylaşımı ve bulut yedek planlanıyor.</li>
        <li><strong>Barkod tarama neden yok?</strong> İlk sürümde devre dışı. İlerleyen güncellemelerde geri gelecek.</li>
        <li><strong>Uyarılar çalışmıyor?</strong> Bildirim iznini verdiğinizden ve uygulamayı güncellediğinizden emin olun.</li>
      </ul>
    </section>

    <section class="card">
      <h2>Hata Bildirimi</h2>
      <p>Bir sorunla karşılaşırsanız aşağıdakileri iletin:</p>
      <ul>
        <li>Adımlar (soruna nasıl ulaştınız)</li>
        <li>Ekran görüntüsü (varsa)</li>
        <li>Cihaz & iOS sürümü (örn. iPhone 13, iOS 17.5)</li>
      </ul>
      <p>E-posta: <a href="mailto:destek@ornek-domain.com">destek@ornek-domain.com</a></p>
    </section>

    <section class="card">
      <h2>Yasal</h2>
      <p><a href="./privacy.html">Gizlilik Politikası</a> · Telif © <span id="yıl"></span> Kitchenmate</p>
    </section>

    <p class="footer">Bu sayfa GitHub Pages üzerinde barındırılmaktadır.</p>
  </main>
  <script>document.getElementById('yıl').textContent=new Date().getFullYear()</script>
</body>
</html>
