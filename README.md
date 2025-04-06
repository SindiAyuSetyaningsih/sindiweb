<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Branding</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
            scroll-behavior: smooth;
        }
        body {
            background-color: #f4f4f4;
        }
        header {
            position: fixed;
            width: 100%;
            background: rgba(0, 0, 0, 0.7);
            padding: 15px;
            text-align: center;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }
        .cover {
            width: 100%;
            height: 100vh;
            background: url('https://www.paradisecanvasprints.com/wp-content/uploads/2022/09/wildhorse-landscape-nature-canvas-print-wall-art.jpg') no-repeat center center/cover;
            display: flex;
            align-items: center;
            justify-content: space-around;
            color: black;
            text-align: left;
            padding: 50px;
            position: relative;
        }
        .cover::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.8);
        }
        .cover-content {
            position: relative;
            max-width: 500px;
            z-index: 1;
        }
        .cover h1 {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
        }
        .cover p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .cover button {
            padding: 12px 24px;
            font-size: 16px;
            background: #ff6f61;
            border: none;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }
        .cover button:hover {
            background: #e65c50;
        }
        section {
            padding: 100px 20px;
            text-align: center;
        }
        .profil {
            background-color: #f0f0f0;
        }
        body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f1fdfc;
    }

    .profile-container {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 40px;
    }

    .profile-image {
      flex: 1;
      min-width: 300px;
      max-width: 500px;
      padding: 20px;
    }

    .profile-image img {
      width: 100%;
      border-radius: 12px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .profile-text {
      flex: 1;
      min-width: 300px;
      padding: 20px 40px;
    }

    .profile-text h2 {
      color: #d44f28;
      font-size: 28px;
      margin-bottom: 15px;
    }

    .profile-text p {
      font-size: 16px;
      color: #333;
      line-height: 1.6;
    }

    .profile-text em {
      font-style: italic;
      color: #666;
    }

    .btn-profile {
      display: inline-block;
      margin-top: 20px;
      background-color: #f15a40;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
    }

    .btn-profile:hover {
      background-color: #c44426;
    }
    .box-tentang {
  background-color: white; /* warna kotaknya */
  padding: 30px;
  margin: 30px auto;
  width: 80%;
  max-width: 800px;
  border-radius: 15px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
}
.box-tentang h2 {
  margin-bottom: 20px;
}
.box-tentang p {
  line-height: 1.6;
}

        .karya {
            background-color: #c2c2c2;
            .karya {
    text-align: center;
    padding: 40px 20px;
}
h2 {
  margin-bottom: 30px; /* atur sesuai kebutuhan */
}
.judul-karya {
  margin-bottom: 30px;
}

.grid-karya {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    max-width: 1200px;
    margin: auto;
}

.item {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding-bottom: 10px;
}

.item img {
    width: 100%;
    height: auto;
    border-bottom: 3px solid #eee;
}

.item p {
    font-size: 16px;
    font-weight: bold;
    margin-top: 10px;
}
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    text-align: center;
    margin: 0;
    padding: 0;
}
        }
        .aktivitas {
            background-color: #969696;
        }
        .aktivitas {
    text-align: center;
    padding: 40px 20px;
}
        .aktivitas h2 {
            margin-bottom: 30px; /* Tambahkan jarak bawah */
            font-size: 24px;
            text-align: center;
        }

.grid-aktivitas {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    max-width: 1200px;
    margin: auto;
}

.item {
    background: #fff;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
}

.item h3 {
    font-size: 18px;
    margin-bottom: 10px;
}

.item img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.btn-baca {
    margin-top: 10px;
    padding: 8px 12px;
    background: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.btn-baca:hover {
    background: #0056b3;
}

.deskripsi {
    display: none;
    margin-top: 10px;
    font-size: 14px;
    color: #555;
}

        .media-sosial {
            background-color: #5e5e5e;
        }
        body {
            font-family: Arial, sans-serif;
            background-color: #ddd;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        .media-sosial {
            padding: 50px;
        }
        .media-sosial h2 {
            margin-bottom: 40px;
            font-size: 24px;
            text-align: center;
        }
        .container {
            display: flex;
            justify-content: center;
            gap: 40px;
        }
        .circle {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        .circle:hover {
            transform: scale(1.1);
        }
        .circle a {
            display: block;
            width: 100%;
            height: 100%;
        }
        .circle img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        .profil img {
            width: 200px;
            height: auto;
            border-radius: 50%;
            display: block;
            margin: 20px auto;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#profil">Profil</a></li>
                <li><a href="#karya">Karya</a></li>
                <li><a href="#aktivitas">Aktivitas</a></li>
                <li><a href="#visi-misi">Visi Misi</a></li> <!-- Ini bagian baru -->
                <li><a href="#media-sosial">Media Sosial</a></li>
            </ul>
        </nav>
    </header>

    <div class="cover">
        <div class="cover-content">
            <h1>𝐇𝐢 𝐢'𝐦 𝐒𝐢𝐧𝐝𝐢 𝐀𝐲𝐮 𝐒𝐞𝐭𝐲𝐚𝐧𝐢𝐧𝐠𝐬𝐢𝐡!</h1>
            <p> Welcome! 
                on this website introduces my personality and the activities that I always do in my daily life.</p>
            <button onclick="document.getElementById('profil').scrollIntoView({behavior: 'smooth'});">Lihat Disini</button>
        </div>
    </div>

    <section id="profil" class="profil">
        <h2>Profil Saya</h2>
        <div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: px; margin-top: 15px;">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVSzI_irobTOy9kQcQlO-ZCbslDg7M48WdRw&s" alt="Foto Profil">
        </div>
        
    
        <div class="box-tentang">
            <h2>Tentang Saya</h2>
            <p>
                Halo! Nama saya Sindi Ayu Setyaningsih, seorang mahasiswi di Universitas Pendidikan Indonesia. 
                Saat ini saya sedang menempuh pendidikan dengan penuh semangat dan rasa ingin tahu yang tinggi. 
                Saya percaya bahwa proses belajar bukan hanya terjadi di dalam kelas, tapi juga melalui pengalaman, hobi, dan interaksi sehari-hari.
        
                Saya memiliki berbagai hobi yang menjadi warna dalam hidup saya. 
                Mulai dari berolahraga, berkuda, hingga menjelajah tempat-tempat baru. 
                Dunia kreatif selalu menarik perhatian saya, 
                karena dari sanalah saya bisa mengekspresikan diri dan melihat dunia dari sudut pandang yang berbeda.
        
                Saya juga suka mencoba hal-hal baru, karena menurut saya, 
                tantangan adalah bagian dari proses tumbuh dan berkembang. 
                Baik itu dalam hal akademik, organisasi, maupun kegiatan sosial, 
                saya selalu berusaha untuk memberikan yang terbaik dan belajar dari setiap pengalaman.
              <!-- lanjutkan isi deskripsinya di sini -->
            </p>
          </div>          
    </section>
    

    <section id="karya" class="karya">
        <h2 class="judul-karya">Karya Saya</h2>
        <div class="grid-karya">
            <div class="item">
                <img src="https://images.pexels.com/photos/358457/pexels-photo-358457.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500" alt="Karya 1">
                <p>Foto ini diabadikan di sebuah alam terbuka yang dikelilingi pepohonan serta air terjun yang indah.</p>
            </div>
            <div class="item">
                <img src="https://d1hjkbq40fs2x4.cloudfront.net/2023-02-28/files/canon-lenses-landscape-nature-photography_2271-22.jpg" alt="Karya 2">
                <p>Alam tidak hanya sebuah pemandangan tetapi mahkluk hidup disekitar kita bisa selalu kita abadikan momen tersebut.</p>
            </div>
            <div class="item">
                <img src="https://st.depositphotos.com/5987780/55099/i/450/depositphotos_550995238-stock-photo-beautiful-ukrainian-nature-small-branches.jpg" alt="Karya 3">
                <p>Setetes air hujan yang membasahi tanaman sekitar sangat bermanfaat bagi mahkluk hidup di lingkungan.</p>
            </div>
            <div class="item">
                <img src="https://img.freepik.com/free-photo/top-view-beautifully-colored-autumn-leaves_23-2148769159.jpg" alt="Karya 4">
                <p>Terciptanya warna bertujuan agar hidup lebih memiliki tujuan yang sangat ceria serta mempunyai cerita di setiap masing-masing individu.</p>
            </div>
        </div>
    </section>
    <script>
        function toggleDeskripsi(button) {
            var deskripsi = button.nextElementSibling; // Ambil elemen <p> setelah tombol
            if (deskripsi.style.display === "block") {
                deskripsi.style.display = "none";
                button.textContent = "Klik Baca Selengkapnya";
            } else {
                deskripsi.style.display = "block";
                button.textContent = "Sembunyikan Deskripsi";
            }
        }
    </script>
    
    <section id="aktivitas" class="aktivitas">
        <h2>Aktivitas Saya</h2>
        <div class="grid-aktivitas">
            <div class="item">
                <h3>Berkuda</h3>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVSzI_irobTOy9kQcQlO-ZCbslDg7M48WdRw&s" alt="Aktivitas 1">
                <button class="btn-baca" onclick="toggleDeskripsi(this)">Klik Baca Selengkapnya</button>
                <p class="deskripsi">Berkuda merupakan aktivitas yang memberikan banyak manfaat, 
                    baik secara fisik maupun mental. Dari sisi fisik, berkuda melatih keseimbangan, 
                    koordinasi, serta kekuatan otot inti dan kaki. Sementara itu, secara mental, 
                    berkuda dapat meningkatkan konsentrasi, rasa percaya diri, serta memberikan efek relaksasi
                    yang membantu mengurangi stres. Interaksi dengan kuda juga membangun empati dan ikatan emosional, 
                    sehingga berkuda tidak hanya menjadi olahraga, tetapi juga terapi yang menyenangkan dan menenangkan.</p>
            </div>
            <div class="item">
                <h3>GYM</h3>
                <img src="https://ae01.alicdn.com/kf/Sc69b18505a024815aa0e300198ca6dffd.jpg_640x640q90.jpg" alt="Aktivitas 2">
                <button class="btn-baca" onclick="toggleDeskripsi(this)">Klik Baca Selengkapnya</button>
                <p class="deskripsi" style="display: none;">Gym memiliki banyak manfaat bagi kesehatan fisik dan mental. 
                    Secara fisik, rutin berolahraga di gym dapat meningkatkan kekuatan otot, 
                    daya tahan tubuh, fleksibilitas, serta membantu menjaga berat badan ideal. 
                    Dari sisi mental, aktivitas di gym mampu mengurangi stres, meningkatkan mood, 
                    serta memperbaiki kualitas tidur. Selain itu, gym juga bisa menjadi sarana bersosialisasi 
                    dan membangun disiplin diri melalui rutinitas latihan yang teratur.</p>

            </div>
            <div class="item">
                <h3>Running</h3>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRVvSBAoPcxp1fDCDTS1i_0eIrSDvqWw8SdVg&s" alt="Aktivitas 3">
                <button class="btn-baca" onclick="toggleDeskripsi(this)">Klik Baca Selengkapnya</button>
                <p class="deskripsi">Lari bermanfaat untuk meningkatkan kesehatan jantung, 
                    membakar kalori, dan memperkuat otot serta stamina. Secara mental, 
                    lari membantu meredakan stres, memperbaiki mood, dan meningkatkan fokus.
                    Dari sisi mental, lari dapat mengurangi stres, memperbaiki suasana hati, 
                    dan membantu mengatasi gejala kecemasan atau depresi berkat pelepasan hormon endorfin. 
                    Selain itu, lari juga bisa menjadi waktu refleksi diri dan sarana untuk meningkatkan kedisiplinan.</p>
            </div>
            <div class="item">
                <h3>Memasak</h3>
                <img src="https://hips.hearstapps.com/hmg-prod/images/heart-healthy-food-1580231690.jpg?crop=0.668xw:1.00xh;0.0849xw,0&resize=640:*" alt="Aktivitas 4">
                <button class="btn-baca" onclick="toggleDeskripsi(this)">Klik Baca Selengkapnya</button>
                <p class="deskripsi">Memasak bermanfaat untuk melatih kreativitas, meningkatkan keterampilan motorik halus, 
                    dan membantu pola makan sehat. Secara mental, memasak bisa menjadi aktivitas yang menenangkan dan meningkatkan rasa percaya diri.</p>
            </div>
        </div>
    </section>
    <section id="visi-misi" style="background-color: #fff; padding: 80px 20px;">
        <div style="max-width: 900px; margin: auto; text-align: center;">
          <h2 style="color: #d44f28; margin-bottom: 40px;">Visi & Misi</h2>
      
          <!-- Kotak Visi -->
          <div style="background-color: #444; color: white; padding: 30px; border-radius: 10px; margin-bottom: 30px;">
            <h3 style="margin-bottom: 15px;">Visi</h3>
            <p style="margin: 0; line-height: 1.6;">
              Menjadi pribadi yang inspiratif dan berdampak positif dalam bidang pendidikan dan kreativitas, 
              dengan semangat belajar yang tinggi dan kontribusi nyata bagi masyarakat.
            </p>
          </div>
      
          <!-- Kotak Misi -->
          <div style="background-color: #444; color: white; padding: 30px; border-radius: 10px;">
            <h3 style="margin-bottom: 15px;">Misi</h3>
            <ul style="text-align: left; max-width: 700px; margin: auto; line-height: 1.8;">
              <li>Mengembangkan potensi diri melalui pendidikan, pengalaman, dan kegiatan positif.</li>
              <li>Meningkatkan kreativitas dalam berkarya dan berorganisasi.</li>
              <li>Menjadi pribadi yang terbuka terhadap pembelajaran dan perubahan.</li>
              <li>Menginspirasi dan memberikan dampak positif bagi lingkungan sekitar.</li>
            </ul>
          </div>
        </div>
      </section>
        

    <section id="media-sosial" class="media-sosial">
        <h2>Media Sosial</h2>
        <div class="container">
            <div class="circle">
                <a href="https://www.instagram.com/sindi.ayyst?igsh=MXNxdnN3ZmsxbTB2NA==" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/174/174855.png" alt="Instagram">
                </a>
            </div>
            <div class="circle">
                <a href="https://www.facebook.com" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/124/124010.png" alt="Facebook">
                </a>
            </div>
            <div class="circle">
                <a href="https://www.tiktok.com/@sindiayyts?_t=ZS-8vGqZnZrjgD&_r=1" target="_blank">
                    <img src="https://cdn-icons-png.flaticon.com/512/3046/3046126.png" alt="TikTok">
                </a>
            </div>
        </div>
    </section>

    <footer>
        <p>Kontak: sindi.ayu.setyaningsih@gmail.com | Telepon: +62 8977751488</p>
        <p>Ikuti saya di:</p>
        <p>
            <a href="#" style="color: white; text-decoration: none;">Instagram</a> | 
            <a href="#" style="color: white; text-decoration: none;">Facebook</a> | 
            <a href="#" style="color: white; text-decoration: none;">TikTok</a>
        </p>
    </footer>
</body>
</html>
