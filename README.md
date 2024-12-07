<!DOCTYPE html>
<html>
<body>
  
<!-- Header dengan Divider -->
[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
<h1 style="text-align: center; font-family: Arial, sans-serif; color: #4CAF50;">dynamic-request</h1>

<!-- Badge -->
<p style="text-align: center;">
  <img src="https://img.shields.io/badge/AUTHOR-Selxyz-green.svg?style=for-the-badge&logo=github">
  <img src="https://img.shields.io/badge/AIOS-green.svg?style=for-the-badge&logo=apple">
</p>
<hr style="border: 1px solid #ddd;">

<!-- Apa Itu Aios -->
<h2 style="font-family: Arial, sans-serif;">Apa Itu <span style="color: #4CAF50;">dynamic-request</span>?</h2>
<blockquote style="font-size: 16px; font-family: Georgia, serif; color: #555;">
  dynamic-request Adalah Sebuah Module Yang Dynamics Dan Menawarkan 2 tipe request Yaitu Https Dan Http Dan Juga Sudah Di Bekali Dengan Penyusunan Data Yang Bagus Dan Teratur.</strong> yang dikembangkan oleh tim yang hebat.
</blockquote>

<!-- Tujuan -->
<h2 style="font-family: Arial, sans-serif;">🎯 Tujuan</h2>
<blockquote style="font-size: 16px; font-family: Georgia, serif; color: #555;">
  <ul>
    <li>Memudahkan Para Programmer Yang Senang Melakukan Web Scraping, Agar Lebih Luas Dalam Metode Request Yang Di Ingin Kan.</li>
  </ul>
</blockquote>
<hr style="border: 1px solid #ddd;">

<!-- Install dan Penggunaan -->
<details>
  <summary><strong>💾 Installisasi</strong></summary>

```bash
npm i dynamic-request
```

</details>
<details>
  <summary><strong>👨‍💻 Usages</strong></summary>
  
 ```javascript
const request = require('dynamic-request');

// Request menggunakan HTTPS
(async () => {
  try {
    const response = await request({
      request: 'https', // Memilih HTTPS
      method: 'GET',
      hostname: 'api.example.com',
      path: '/v1/data',
      headers: {
        'Authorization': 'Bearer your-token',
        'Accept': 'application/json',
      },
    });

    console.log('Response Data (HTTPS):', response);
  } catch (error) {
    console.error('Error (HTTPS):', error);
  }
})();

const request = require('dynamic-request');

// Request menggunakan HTTP
(async () => {
  try {
    const response = await request({
      request: 'http', // Memilih HTTP
      method: 'GET',
      hostname: 'example.com',
      path: '/',
      headers: {
        'Accept': 'text/html', // Meminta HTML
      },
    });

    console.log('Response Data (HTTP):', response);
  } catch (error) {
    console.error('Error (HTTP):', error);
  }
})();
 ```
</details>
<hr style="border: 1px solid #ddd;">
<!-- Developers --> 
<h2 style="font-family: Arial, sans-serif;">👥 Developers</h2> 
<blockquote style="font-size: 16px; font-family: Georgia, serif; color: #555;"> <p>Module ini dikembangkan oleh:</p>
<p><a href="https://wa.me/6282181938329" style="color: #4CAF50; text-decoration: none;"><strong>Selxyzz</strong></a></p> 
<p><em>Terima kasih telah menggunakan module kami!</em></p> 
</blockquote> 
<!-- Footer Divider -->

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
