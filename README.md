<!DOCTYPE html>
<html>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Halaman Web Pantauan Perubahan Suhu Harian</title>

  <style>
    /* ====== STYLE DASAR HALAMAN ====== */
    body {
      font-family: Arial, sans-serif;
      background-color: #F2F8FF;
      margin: 20px;
      padding: 0;
    }

    h2 {
      text-align: center;
      color: #2F4F60;
    }

    h4 {
      color: #2D3E50;
    }

    /* ====== STYLE PETA (IFRAME) ====== */
    iframe {
      display: block;
      margin: 20px auto;
      border: 0;
      width: 80%;
      height: 400px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.15);
    }

    /* ====== STYLE TABEL CUACA ====== */
    table {
      width: 85%;
      margin: 20px auto;
      border-collapse: collapse;
      background-color: #ffffff;
      box-shadow: 0px 0px 12px rgba(0, 0, 0, 0.15);
      border-radius: 6px;
      overflow: hidden;
    }

    th,
    td {
      padding: 12px;
      text-align: center;
      border: 1px solid #cccccc;
    }

    th {
      background-color: #3BABBD;
      color: white;
      font-size: 16px;
    }

    tr:nth-child(even) {
      background-color: #EAF7FF;
    }

    tr:hover {
      background-color: #D8F0FF;
      transition: 0.2s;
    }

    /* ====== STYLE GARIS PEMBATAS ====== */
    hr {
      border: none;
      border-top: 2px solid #3BABBD;
      width: 90%;
      margin: 20px auto;
    }

    /* ====== STYLE FOOTER ====== */
    footer {
      text-align: center;
      margin-top: 25px;
      padding: 10px;
      font-weight: bold;
      color: #2D3E50;
    }
  </style>

</head>

<body>

  <h2>Kondisi Cuaca Daerah Tasikmalaya</h2>

  <!-- Google Maps Embed -->
  <iframe
    frameborder="0"
    src="https://www.google.com/maps?q=tasikmalaya+indonesia&z=13&output=embed"
    allowfullscreen
    loading="lazy"
    referrerpolicy="no-referrer-when-downgrade">
  </iframe>

  <hr>
  <h4>Lokasi</h4>
  <p style="text-align:center;">Daerah Ciherang, Tasikmalaya, Jawa Barat</p>

  <table>
    <tr>
      <th>No.</th>
      <th>Hari</th>
      <th>Tanggal</th>
      <th>Suhu (°C)</th>
      <th>Kelembapan (%)</th>
    </tr>
    <tr>
      <td>1.</td>
      <td>Senin</td>
      <td>1/11/2025</td>
      <td>29°C</td>
      <td>75%</td>
    </tr>
    <tr>
      <td>2.</td>
      <td>Selasa</td>
      <td>2/11/2025</td>
      <td>27.3°C</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>3.</td>
      <td>Rabu</td>
      <td>3/11/2025</td>
      <td>28.7°C</td>
      <td>75%</td>
    </tr>
    <tr>
      <td>4.</td>
      <td>Kamis</td>
      <td>4/11/2025</td>
      <td>28.4°C</td>
      <td>70%</td>
    </tr>
    <tr>
      <td>5.</td>
      <td>Jum'at</td>
      <td>5/11/2025</td>
      <td>27.8°C</td>
      <td>80%</td>
    </tr>
    <tr>
      <td>6.</td>
      <td>Sabtu</td>
      <td>6/11/2025</td>
      <td>27.1°C</td>
      <td>75%</td>
    </tr>
    <tr>
      <td>7.</td>
      <td>Minggu</td>
      <td>7/11/2025</td>
      <td>28.1°C</td>
      <td>80%</td>
    </tr>
  </table>

  <hr>

  <footer>
    <p>Dibuat Oleh &copy; Saritirta Hastuti</p>
  </footer>

</body>

</html>
