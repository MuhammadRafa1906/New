<!DOCTYPE html>
<html lang="id">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
  
  <style>
    /* Global Reset */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f3f5;
      color: #333;
    }

    /* Navbar Container */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
      background-color: #007acc;
      color: #fff;
    }

    /* Logo */
    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }

    /* Navigation Links */
    .nav-links {
      display: flex;
      list-style: none;
    }
    .nav-links li {
      margin-left: 20px;
    }
    .nav-links a {
      color: #fff;
      text-decoration: none;
      font-size: 1em;
      padding: 5px 10px;
      transition: background-color 0.3s ease;
    }
    .nav-links a:hover {
      background-color: #005b99;
      border-radius: 4px;
    }

    /* Mobile Menu Toggle Button */
    .menu-toggle {
      display: none;
      font-size: 1.5em;
      cursor: pointer;
    }

    /* Responsive Styling */
    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        width: 100%;
        text-align: center;
        background-color: #007acc;
      }
      .nav-links li {
        margin: 10px 0;
      }
      .menu-toggle {
        display: block;
      }
    }

    /* Show Menu on Mobile when Active */
    .nav-links.active {
      display: flex;
    }

    /* Main Content and iframe Styles */
    main {
      padding: 20px;
      max-width: 800px;
      margin: 20px auto;
    }
    .about-content {
      display: none; /* Hidden by default */
    }
    .about-content iframe {
      width: 100%;
      height: 600px;
      border: none;
    }
  </style>
</head>
<body>
  
  <!-- Navbar Section -->
  <nav>
    <div class="logo">@mhmmdrafaa._</div>
    <ul class="nav-links">
      <li><a href="menu.html">Home</a></li>
      <li><a href="Projek Baru.html" onclick="showAbout()">Isi Cerita</a></li>
      <li><a href="about.html">About</a></li>
      <li><a href="test.html">Contact</a></li>
    </ul>
    <div class="menu-toggle" onclick="toggleMenu()">☰</div>
  </nav>
  
  <
    
    <!-- About Section with Embedded Projek Baru.html -->
    <section id="about-section" class="about-content">
      <h2>About Us</h2>
      <iframe src="Projek Baru.html" title="About Content"></iframe>
    </section>
  </main>
  <!-- Home Section with Embedded menu.html -->
  <section id="about-section" class="about-content">
    <h2>Home</h2>
    <iframe src="menu.html" title="Home Content"></iframe>
  </section>
</main>

  

  <script>
    // Toggle Mobile Menu
    function toggleMenu() {
      const navLinks = document.querySelector('.nav-links');
      navLinks.classList.toggle('active');
    }

    // Show About Section with Projek Baru.html
    function showAbout() {
      document.getElementById('about-section').style.display = 'block';
      window.scrollTo(0, document.getElementById('about-section').offsetTop);
    }
  </script>
</body>

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kita Sama tapi Berbeda</title>
  
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      color: #000000;
      background-color: #f5f5f5;
    }
    header {
      background: url('background.jpg') no-repeat center center/cover;
      padding: 60px;
      text-align: center;
      color: rgb(0, 0, 0);
    }
    header h1 {
      font-size: 2.5em;
      margin: 0;
    }
    main {
      padding: 20px;
      max-width: 800px;
      margin: 20px auto;
      background: #f5f5f5;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    main p {
      line-height: 1.6;
      margin: 1em 0;
    }
    .quote {
      font-style: italic;
      color: #555;
      margin: 20px 0;
      padding-left: 20px;
      border-left: 3px solid #333;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>


  <header>
    <h1>Kita Sama tapi Berbeda</h1>
    <p>By: Muhammad Rafa</p>
  </header>
  
  <main>
    <p>Argasa Bumantara,  pria tinggi kelahiran tahun sembilan delapan itu terduduk menunduk sambil merenung, akhir - akhir ini entah mengapa kekasihnya mulai berubah, selalu saja ada pertengkaran diantara mereka. Alasannya sama, perihal keyakinan yang berbeda. </p>
    <p>Banyak sudah halang rintang yang mereka lalui, namun satu yang tak dapat mereka hindari. Dinding besar yang semesta ciptakan selalu bisa memberi celah, agar mereka yang terjebak dalam masalah, bisa keluar melalui celah itu.</p>
    <p>Terkadang kita berfikir bahwa cinta akan menyatukan kita dari perbedaan. Cinta memang membuat kita tersenyum, tetapi cinta jugalah yang dapat melukai hati kita.</p>
    <p>Tepat 5 tahun silam, Arga mengenal sosok perempuan yang bernama Maura Anandya. Wanita protestan yang sangat cantik dan jelia, diawal Argsa mengenalnya ia sudah merasa tertarik dengannya.</p>
    <p>Hari berganti hari, bulan berganti bulan, tak terasa genap 6 bulan Arga sudah mengenal Maura, dan tepat pada bulan juli Arga menjadikan Maura sebagai kekasihnya, walau mereka berbeda agama, Arga yang Islam dan Maura yang Protestan. Tetapi mereka tak mempermasalahkan perbedaan kenyakinan tersebut. Mereka berfikir bahwa suatu perbedaan akan disatukan dalam satu ikatan cinta.
    </p>
    <p>Tak terasa sudah 4 tahun berlalu. Ada banyak waktu yang telah kita lewati bersama, kebersamaan yang awal kita pikir tidak akan terpisahkan oleh maut sekalipun. </p>
    <p>Namun apa Boleh dikata manusia boleh merencanakan tetapi sang pencipta kehidupan lah yang menentukan. Tepat pada tanggal 4 Maret, mungkin malam itu adalah malam yang menjadi saksi bisu hubungan mereka berdua, karena.. 
    </p>
    <p>Malam itu kekasihnya berkata "Arga, aku rasa cinta itu tidak dapat menyatukan semua perbedaan yang ada diantara kita"
      "Lalu, hal apa yang ingin kamu satukan dari perbedaan itu? " Arga menjawab sambil kebingungan
      "Hal yang ingin aku satukan adalah tentang kenyakinan diantara kita, ada baiknya kita menjadi satu keyakinan, dan satu kepercayaan. Agar kita dapat terikat dalam ikatan suci"</p>
    <p>Setelah itu Maura mengakhiri pembicaraannya. Pipiku serasa habis ditampar oleh kenyataan, mulutku yang terbungkam, dan kakiku yang seketika kaku    </p>
    <p>"Maura, begitu mudahnya kamu menyuruhku untuk berpaling dari Tuhan dan keyakinanku untuk berpindah kepada Tuhan dan keyakinanmu. Bukankah kita dari awal sudah berkomitmen untuk tidak menggadaikan Tuhan dan keyakinan kita untuk hal apapun? " Arga menjawab dengan sedikit emosi
    </p>
    <p>"Iyaa arga, aku ngerti... . Tapi kita mau sampai kapan tetap menjalin hubungan tetapi kita beda agama, bukannya kamu tau kalo mama tak pernah merestui hubungan kita kalau kita masih beda Agama? "
    </p>
    <p>Dimalam itu Arga merasa sangat dilema. Karena Arga harus memilih dua keputusan yang sama berat dan tidak dapat diambil saat itu juga. 
    </p>
    <p>Air mata tak mampu lagi Arga tahan. Perlahan air mata pun jatuh hingga membasahi pipi, seakan tak bisa berpikir,dan mulut seakan diam dan membungkam.</p>
    <p>Kaki rasanya, tak ingin lagi untuk berjalan. "Apakah ini akhir dari kisah kita? ",  " Haruskah cinta kita berakhir dengan cara ini? "," Dan Haruskah aku memilih entah cinta atau agama?". Tanya Arga dalam kebingungan.</p>
    <p>" Tuhan, apa yang sedang engkau rencanakan dibalik semua ini? "    </p>
    <p>Arga berdoa didalam kebingungan dan berkata "Aku mencintaimu ya Allah, dan tak sedikit pun didalam benakku untuk melupakanmu. Tetapi dia perempuan yang ku impikan selama ini, dia yang selalu ku mimpikan kelak untuk menjadi Ibu dari anak-anakku. "
    </p>
    <p>Disisi lain  Maura yang sedang dilanda kebingungan, merenung, dan berpikir "Dosa apa ya Tuhan yang telah aku perbuat, sehingga aku merasakan sakit yang sedalam ini? "
    </p>
    <p>Malam itu ada banyak pertanyaan yang berkecamuk didalam benak mereka berdua. 
    </p>
    <p>Dalam diam sesaat Arga menemukan satu jawaban yang harus dipilih satu diantara dua pilihan itu, dan saat itu Arga memutuskan untuk memilih Tuhan dan keyakinnanku. Arga sadar bahwa cinta yang abadi Hanyalah Cinta dari dia sang pencipta. 
    </p>
    <p>Arga memutuskan untuk tidak memberitahu secara langsung keputusan ini kepada Maura, kemudian Araga menyampaikan kepada melalui sepucuk surat. 
    </p>
    <p class="quote">"Untuk Maura</p>

      <p class="quote">Saat tinta hitamku menari di atas kertas putih ini, saat itu pula hatiku terasa begitu hancur dan perih. Butiran air mata ini tanpa permisi membasahi pipiku begitu saja, jiwaku seakan enggan mengucapkan namamu. Kau hadir seperti pelukis, yang melukiskan berbagai warna pada kanvas hidupku.
      
      Ketika sorot mata kita bertatapan untuk pertama kalinya, kurasakan debaran-debaran cinta yang indah. Namun kini semuanya tak terasa, seolah membeku di relung hatiku yang terdalam... </p>
      
      <p class="quote">Maura, aku memang sangat mencintaimu, tapi aku lebih mencintai Tuhanku. Jalan untuk sebuah cinta bisa dipilih, tapi tidak untuk keyakinan, Tuhanku bukan pilihan. 
      "</p>
    <p>Setahun berlalu, Arga dan Maura pada akhirnya menjalani hidup dengan pilihannya mamasing-masing. Satu hal yang membuat kita mengerti akan rencana Tuhan adalah " Kita memang hidup ditengah keberagaman Agama, dan budaya. Namun satu yang pasti, perbedaan memang menyatukan kita, tetapi tidak dalam hal agama, dan kepercayaan. Jangan pernah sekali-kali menggadaikan agama-mu Tuhanmu demi cintamu, karena cinta yang tulus dan Abadi hanya datang dari Tuhan Yang Maha Esa. "</p>
    <p>Cinta itu lebih pada kerelaan untuk melepaskan, dan satu prinsip dalam hidup yang harus kita pegang, jangan pernah gadaikan Tuhan demi cinta. Biarlah kesakralan cinta itu nampak dengan begitu natural tanpa harus dibuat-buat.</p>
    
    <!-- Lanjutkan bagian konten lainnya -->
  </main>
  
  <footer>
    <p>Cinta itu lebih pada kerelaan untuk melepaskan.</p>
    <footer style="text-align: center; padding: 10px; color: #777;">
      <p>&copy; 2024 Rafa Website</p>
    </footer>
  </footer>

  
</body>
</html>
