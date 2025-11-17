# stormmachine.github.io


[welcome.html](https://github.com/user-attachments/files/23592150/welcome.html)
<h1>Welcome!</h1>
<html lang="en">
<body>
    <div class="container">
        <h1>Welcome!</h1>
        <p>This is your control panel (now static).</p>
        
        <hr>
        
        <h2>Navigation Menu</h2>
        <p>
            <a href="read_users.html">View User List & Administer</a> 
        </p>
        <p>
            <a href="register.html">Register New User</a>
        </p>
        
        <hr>
        
        <p><a href="login.html">Logout</a></p>
    </div>
</body>
</html>

[index.html](https://github.com/user-attachments/files/23592162/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>User Login</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    
    <div class="container">
        <h1>Login</h1>

        <form method="POST"> 
    </form>
           
        
        <p style="text-align: center; margin-top: 20px;">
            <a href="register.html">Don't have an account? Register here</a>
        </p>
    </div>
</body>
</html>




[read_users.html](https://github.com/user-attachments/files/23592168/read_users.html)
<table class='users-table'>
            <tr><th>ID</th><th>Name</th><th>Email</th><th>Actions</th></tr>
            
            <tr>
                <td>1</td>
                <td>John Doe (Static)</td>
                <td>john.doe@example.com</td>
                <td>
                    <a href="#">Edit</a> | 
                    <a href="#">Delete</a> 
                </td>
            </tr>
            
            <tr>
                <td>2</td>
                <td>Jane Smith (Static)</td>
                <td>jane.smith@example.com</td>
                <td>
                    <a href="#">Edit</a> | 
                    <a href="#">Delete</a>
                </td>
            </tr>
            
        </table>
        
        <p style='margin-top: 20px;'><a href='welcome.html'>Back to Control Panel</a></p>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>User Administration Panel</title>
    <link rel="stylesheet" href="style.css"> 
</head>
<body>
    <div class="container">
        <h1>Registered Users List</h1>

       
    </div>
</body>
</html>



[Uploading register.html…]()
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Formular de Înregistrare</title>
	<link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Register</h1>

    <form method="POST"> 
    </form>
        <label for="nume">Name:</label><br>
        <input type="text" id="nume" name="nume" required><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <label for="parola">password:</label><br>
        <input type="password" id="parola" name="parola" required><br><br>

        <input type="submit" value="submit">
   

</body>
</html>


[Uploading style.css…]()
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh; /* Asigură că se centrează pe toată înălțimea paginii */
}

.container {
    background: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

h1 {
    text-align: center;
    color: #007bff;
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
}

input[type="text"],
input[type="email"],
input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box; /* Include padding și border în lățimea totală */
}

input[type="submit"] {
    background-color: #007bff;
    color: white;
    padding: 10px 15px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
    width: 100%;
}

input[type="submit"]:hover {
    background-color: #0056b3;
}


/* Adaugă la finalul fișierului style.css */

.users-table {
    width: 100%;
    border-collapse: collapse; /* Înlătură spațiul dintre celule */
    margin-top: 20px;
}

.users-table th, .users-table td {
    border: 1px solid #ddd;
    padding: 10px;
    text-align: left;
}

.users-table th {
    background-color: #007bff;
    color: white;
}

.users-table tr:nth-child(even) {
    background-color: #f2f2f2;
}



[chair.page.html](https://github.com/user-attachments/files/23592535/chair.page.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Storm Machine - Chairs</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- ===== HEADER / NAVBAR ===== -->
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top py-3" id="mainNav">
      <div class="container d-flex justify-content-between align-items-center">
        <!-- Left Menu -->
        <ul class="navbar-nav d-none d-lg-flex flex-row gap-3">
          <li class="nav-item"><a class="nav-link" href="marquees.html">MARQUEES</a></li>
          <li class="nav-item"><a class="nav-link" href="discos.html">DISCOS</a></li>
          <li class="nav-item"><a class="nav-link" href="jaysbars.html">JAYS BARS</a></li>
        </ul>

        <!-- Centered Logo -->
        <a class="navbar-brand mx-auto" href="index.html">
          <img src="images/logo.png" alt="Storm Machine Logo" class="navbar-logo">
        </a>

        <!-- Right Menu -->
        <ul class="navbar-nav d-none d-lg-flex flex-row gap-3">
          <li class="nav-item"><a class="nav-link" href="equipment.html">EQUIPMENT HIRE</a></li>
          <li class="nav-item"><a class="nav-link" href="gallery.html">GALLERY</a></li>
          <li class="nav-item"><a class="nav-link" href="information.html">INFORMATION</a></li>
          <li class="nav-item"><a class="nav-link" href="contact.html">CONTACT US</a></li>
        </ul>

        <!-- Mobile Menu Button -->
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
      </div>
    </nav>
  </header>

  <!-- ===== BANNER ===== -->
  <section class="banner-section position-relative mt-5 pt-5">
    <img src="images/banner-chairs.jpg" class="w-100" alt="Chairs Banner">
    <div class="banner-overlay"></div>
    <div class="container position-absolute bottom-0 text-white p-4">
      <h1>Chairs</h1>
      <p>Fill out our contact form, or alternatively call us on <strong>01694 751380</strong></p>
      <a href="contact.html" class="btn btn-light mt-2">Get a Quote</a>
    </div>
  </section>

  <!-- ===== CHAIRS SECTION ===== -->
  <section class="chairs-section py-5">
    <div class="container">

      <!-- CHIVARI -->
      <div class="chair-item mb-5 text-center">
        <img src="https://www.scauneevenimente.ro/imagini/Scaun-Evenimente-CHIAVARI-Alb-copy.jpg" class="img-fluid" alt="CHIVARI">
        <h2 class="chair-title mt-3">CHIVARI</h2>
        <p class="chair-desc">Available in various colours with seat pads</p>
      </div>

      <!-- WOODEN CROSS BACK -->
      <div class="chair-item mb-5 text-center">
        <img src="https://www.scauneevenimente.ro/imagini/Scaun-Evenimente-PILGRIM-copy.jpg" class="img-fluid" alt="WOODEN CROSS BACK">
        <h2 class="chair-title mt-3">WOODEN CROSS BACK</h2>
        <p class="chair-desc">Great for creating a rustic natural look</p>
      </div>

      <!-- BANQUETING -->
      <div class="chair-item mb-5 text-center">
        <img src="https://s13emagst.akamaized.net/products/39502/39501736/images/res_681dbde1e4e00b0321fe51cac647e5cb.jpg" class="img-fluid" alt="BANQUETING">
        <h2 class="chair-title mt-3">BANQUETING</h2>
        <p class="chair-desc">Ideal for elegant indoor settings</p>
      </div>

     
<!-- PLASTIC -->
<div class="chair-item mb-5 text-center">
  <img src="https://eventstuff.ro/wp-content/uploads/2019/06/scaun-plastic-alb-1-scaled.jpg" class="img-fluid" alt="PLASTIC">
  <h2 class="chair-title mt-3">PLASTIC</h2>
  <p class="chair-desc">Ideal for outdoor events and shows</p>
</div>


    </div>
  </section>

 
  
 <!-- FOOTER -->
  <footer>
    <p>Give us a call on <strong>01694 751380</strong></p>
    <p>Send us an email at <a href="mailto:info@stormmachine.co.uk">info@stormmachine.co.uk</a></p>
    <p>Or fill out our <a href="contact.html">enquiry form</a> below</p>

    <hr class="my-3" style="border-color: rgba(255,255,255,0.2);">

    <p>Follow us</p>
    <p>© STORM MACHINE 2025</p>
    <p>
      <a href="marquees.html">MARQUEES</a> •
      <a href="discos.html">DISCOS</a> •
      <a href="jaysbars.html">JAY’S BARS</a> •
      <a href="equipment.html">EQUIPMENT HIRE</a> •
      <a href="gallery.html">GALLERY</a> •
      <a href="information.html">INFORMATION</a> •
      <a href="contact.html">CONTACT US</a>
    </p>
  </footer>

 
 
 
 <script>
  // Selectăm doar textul din secțiunea Chairs
  const chairTexts = document.querySelectorAll(
    '.chairs-section p, .chairs-section h2, .chairs-section h3'
  );

  function revealChairs() {
    chairTexts.forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) {
        el.classList.add('visible');
      }
    });
  }

  window.addEventListener('scroll', revealChairs);
  revealChairs(); // la încărcare
</script>


<meta name="viewport" content="width=device-width, initial-scale=1.0">


<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Storm Machine Entertainment - Evenimente</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    /* ==================================================== */
    /* 1. BAZĂ & FONT-URI */
    /* ==================================================== */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        padding-top: 60px; /* Spațiu pentru bara fixă */
        background-color: #fff;
        color: #333;
        line-height: 1.6;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    /* ==================================================== */
    /* 2. ANTET (HEADER) & NAVIGARE */
    /* ==================================================== */
    .header {
        background-color: #000;
        color: #fff;
        padding: 5px 0;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
    }

    .navbar {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        text-transform: uppercase;
    }

    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        padding: 0 10px;
        font-size: 13px;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #ffcc00;
    }

    .logo {
        margin: 0 30px;
        display: flex;
        align-items: center;
    }

    .logo img {
        height: 30px; 
        margin-right: 5px;
    }

    /* ==================================================== */
    /* 3. HERO SECTION */
    /* ==================================================== */
    .hero {
        position: relative;
        height: 500px; 
        background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        justify-content: center;
        padding-bottom: 50px;
    }

    .hero-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.3);
    }

    .hero-text {
        z-index: 1;
        color: #fff;
        text-align: center;
        text-transform: uppercase;
    }

    .hero-text h1 {
        font-size: 28px;
        margin: 0;
        font-weight: 600;
    }

    .hero-text p {
        font-size: 18px;
        margin-top: 5px;
        font-weight: 300;
    }

    /* ==================================================== */
    /* 4. INTRO & CONȚINUT */
    /* ==================================================== */
    .intro-section {
        text-align: center;
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }

    .intro-section p {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 15px;
    }

    /* ==================================================== */
    /* 5. GRID SERVICII (Cele 6 boxuri) */
    /* ==================================================== */
    .services-grid {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .service-box {
        position: relative;
        height: 250px;
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        align-items: flex-start;
        padding: 20px;
        cursor: pointer;
        transition: transform 0.3s;
    }

    .service-box:hover {
        transform: scale(1.02);
    }

    .service-box-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .service-content {
        z-index: 1;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .service-content h3 {
        font-size: 20px;
        margin: 0;
        font-weight: 600;
    }

    .arrow-icon {
        font-size: 24px;
    }

    /* Stiluri specifice pentru background-urile boxurilor */
    #box-quote { background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg'); }
    #box-marquees { background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg'); }
    #box-discos { background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg'); }
    #box-bars { background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400'); }
    #box-equipment { background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg'); }
    #box-gallery { background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg'); }

    /* ==================================================== */
    /* 6. TESTIMONIALE */
    /* ==================================================== */
    .testimonials {
        text-align: center;
        padding: 60px 20px;
        background-color: #f7f7f7;
    }

    .testimonials h2 {
        color: #0d83d1;
        font-weight: 600;
    }

    .testimonial-grid {
        max-width: 800px;
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        text-align: left;
        border-bottom: 1px solid #ddd;
        padding-bottom: 30px;
    }

    .testimonial-item {
        flex-basis: 45%;
        padding: 0 20px;
    }

    .testimonial-item h4 {
        font-weight: bold;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .testimonial-item p {
        font-size: 14px;
        line-height: 1.5;
    }

    .view-more-btn {
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        background-color: #0d83d1;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    .view-more-btn:hover {
        background-color: #0a6bb8;
    }

    /* ==================================================== */
    /* 7. FOOTER (SUBSOL) */
    /* ==================================================== */
    .footer {
        background-color: #333;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    .footer-content {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .footer-info, .footer-links, .footer-social {
        flex-basis: 30%;
        text-align: left;
    }

    .footer-links {
        flex-basis: 35%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-height: 100px;
    }

    .footer-info p, .footer-links a, .footer-social a {
        font-size: 13px;
        margin: 5px 0;
        display: block;
    }

    .footer-social {
        text-align: right;
    }

    .footer-social i {
        font-size: 20px;
        margin-left: 10px;
    }

    /* ==================================================== */
    /* 8. MODALE (POP-UP) */
    /* ==================================================== */
    .modal-content {
        display: none; /* Ascuns implicit */
        position: fixed;
        z-index: 2000;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        max-width: 600px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        border: 1px solid #ddd;
        border-radius: 5px;
    }

    .modal-active {
        display: block;
    }

    #gallery-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    #gallery-content img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* ==================================================== */
    /* MEDIA QUERIES (CSM) - Stilizare pentru Telefoane Mobile */
    /* ==================================================== */
    @media (max-width: 768px) {
        
        body {
            padding-top: 100px;
        }

        /* Navigare */
        .navbar {
            flex-direction: column;
            text-align: center;
        }
        
        .nav-links {
            width: 100%;
            margin: 5px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-links a {
            padding: 5px 8px;
            font-size: 12px;
        }

        .logo {
            margin: 10px 0;
        }

        /* Hero Section */
        .hero {
            height: 300px;
        }

        .hero-text h1 {
            font-size: 18px;
        }

        .hero-text p {
            font-size: 14px;
        }

        /* Grid-ul de Servicii (Cele 6 Boxuri) */
        .services-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .service-box {
            height: 150px;
        }

        /* Testimoniale */
        .testimonial-grid {
            flex-direction: column;
            border-bottom: none;
        }
        
        .testimonial-item {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        /* Footer */
        .footer-content {
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .footer-info, .footer-links, .footer-social {
            flex-basis: 100%;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .footer-links {
            max-height: none;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .footer-links a {
            padding: 5px 10px;
        }
        
        .footer-social i {
            margin: 0 5px;
        }
    }
</style>



<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            // Închide toate modalele deschise (pentru siguranță)
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            
            // Activează modalul dorit
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        document.getElementById(modalId).classList.remove('modal-active');
    }

    // Închide modalul dacă utilizatorul face click în afara ferestrei modale
    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            // Verifică dacă click-ul s-a întâmplat pe fundalul modalului
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>


<head>
    <title>Titlul Paginii</title>

    <link rel="stylesheet" href="style.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>


<div id="bar-modal" class="modal-content">
    <h2>Lista de Băuturi (Jay's Bar)</h2>
    <div id="bar-content">
        <h3>Alcohol</h3>
        <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
        <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
        <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
        <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
        <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
        <hr>
        <h3>Non-alcoholic</h3>
        <p><strong>Water:</strong> Still and mineral.</p>
        <p><strong>Juices:</strong> Natural and carbonated.</p>
        <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
        <hr>
        <h3>Additional recommendations</h3>
        <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
    </div>
    <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="quote-modal" class="modal-content">
    <h2>Solicită o Ofertă</h2>
    <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
    <form>
        <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
        <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
    </form>
    <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="gallery-modal" class="modal-content">
    <h2>Galerie Foto</h2>
    <div id="gallery-content">
        <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
    </div>
    <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        const modal = document.getElementById(modalId);
        if (modal) {
            modal.classList.remove('modal-active');
        }
    }

    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>




[contactuspage.html](https://github.com/user-attachments/files/23592536/contactuspage.html)
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Storm Machine Entertainment - Contact Us</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* CSS general și reset */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* ---------------------------------------------------- */
        /* Antet (Header) - Preluat de pe pagina principală */
        .header {
            background-color: #000;
            color: #fff;
            padding: 10px 0;
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            text-transform: uppercase;
        }

        .nav-links a {
            padding: 0 15px;
            font-size: 14px;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            height: 40px; 
            margin-right: 10px;
        }
        
        /* ---------------------------------------------------- */
        /* Bara de Navigare Secundară (Sub Hero) */
        .secondary-nav {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
        }
        
        .secondary-nav-links {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 0 20px;
            font-size: 14px;
            text-transform: uppercase;
        }
        
        /* ---------------------------------------------------- */
        /* Secțiunea de Formular */
        .contact-container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .contact-header {
            padding-bottom: 20px;
            border-bottom: 1px solid #ddd;
            margin-bottom: 30px;
        }

        .contact-header h1 {
            font-size: 36px;
            margin: 0 0 10px 0;
            color: #333;
        }

        .contact-header p {
            font-size: 16px;
            line-height: 1.5;
        }

        /* Stiluri pentru Formular */
        .contact-form {
            background-color: #fff;
            padding: 0;
        }
        
        .form-group h3 {
            font-size: 18px;
            margin-top: 25px;
            margin-bottom: 15px;
            padding-bottom: 5px;
            border-bottom: 1px solid #ddd;
        }

        .form-row {
            display: flex;
            gap: 20px;
            margin-bottom: 15px;
        }

        .form-field, .full-width {
            flex-grow: 1;
        }

        label {
            display: block;
            font-size: 14px;
            color: #555;
            margin-bottom: 5px;
        }

        input[type="text"], 
        input[type="email"], 
        input[type="tel"],
        select, 
        textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            box-sizing: border-box; /* Include padding și border în lățimea totală */
            font-size: 14px;
        }

        select {
            height: 38px; /* Ajustează înălțimea select-ului cu input-urile */
        }

        textarea {
            resize: vertical;
            min-height: 100px;
        }
        
        /* Câmpuri de cerințe (Checkbox-uri/Radio-uri) */
        .requirements-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr); /* 4 coloane ca în poză */
            gap: 10px;
            margin-top: 15px;
            padding: 15px 0;
            border-top: 1px solid #ddd;
            border-bottom: 1px solid #ddd;
        }

        .requirement-column label {
            display: flex;
            align-items: center;
            margin-bottom: 5px;
            font-size: 14px;
        }

        .requirement-column input[type="checkbox"] {
            width: auto;
            margin-right: 8px;
        }

        /* Butonul de Trimitere */
        .submit-button-container {
            text-align: center;
            margin-top: 30px;
        }

        .submit-button {
            padding: 12px 30px;
            background-color: #0d83d1; /* Culoarea albastră din design */
            color: #fff;
            border: none;
            text-transform: uppercase;
            font-size: 16px;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .submit-button:hover {
            background-color: #0a6bb8;
        }
        
        /* ---------------------------------------------------- */
        /* Subsol (Footer) - Preluat de pe pagina principală */
        .footer {
            background-color: #333;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .footer-info, .footer-links, .footer-social {
            flex-basis: 30%;
            text-align: left;
        }

        .footer-info p, .footer-links a, .footer-social a {
            font-size: 13px;
            margin: 5px 0;
            display: block;
        }

        .footer-social {
            text-align: right;
        }

        .footer-social i {
            font-size: 20px;
            margin-left: 10px;
        }
        
        .copyright {
            margin-top: 20px;
            font-size: 12px;
            text-align: center;
        }
        
        /* ---------------------------------------------------- */
        /* MEDIA QUERIES (Responsivitate) */
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
                text-align: center;
            }
            
            .nav-links {
                margin: 10px 0;
                display: flex;
                flex-wrap: wrap; 
                justify-content: center;
            }

            .secondary-nav-links {
                gap: 10px;
                flex-wrap: wrap;
                justify-content: center;
                padding: 10px 5px;
            }

            .form-row {
                flex-direction: column; /* Stivuiește rândurile pe verticală pe mobil */
                gap: 0;
            }
            
            .form-field, .full-width {
                margin-bottom: 15px; /* Adaugă spațiu între câmpurile stivuite */
            }

            .requirements-grid {
                grid-template-columns: 1fr 1fr; /* Trece la 2 coloane pe mobil */
            }
            
            /* Footer */
            .footer-content {
                flex-direction: column;
                align-items: center;
            }
            
            .footer-info, .footer-links, .footer-social {
                flex-basis: 100%;
                text-align: center;
                margin-bottom: 15px;
            }
        }

    </style>
</head>
<body>

    <header class="header">
        <div class="navbar">
            <div class="nav-links">
                <a href="index.html">MARQUEES</a>
                <a href="index.html">DISCOS</a>
                <a href="index.html">JAYS BARS</a>
                <a href="index.html">EQUIPMENT HIRE</a>
            </div>
            <div class="logo">
                <img src="https://i.imgur.com/5wQ2pXF.png" alt="Storm Machine Logo" style="height: 30px;"> 
                <span>stormmachine</span>
            </div>
            <div class="nav-links">
                <a href="index.html">GALLERY</a>
                <a href="index.html">INFORMATION</a>
                <a href="index.html">CONTACT US</a>
                <a href="#"><i class="fas fa-info-circle"></i></a>
            </div>
        </div>
    </header>

    <nav class="secondary-nav">
        <div class="secondary-nav-links">
            <a href="#">MARQUEES</a>
            <a href="#">DISCOS</a>
            <a href="#">JAYS BARS</a>
            <a href="#">EQUIPMENT HIRE</a>
            <a href="#">GALLERY</a>
            <a href="#">INFORMATION</a>
            <a href="#">CONTACT US</a>
            <a href="#"><i class="fas fa-info-circle"></i></a>
        </div>
    </nav>
    
    <main class="contact-container">
        
        <div class="contact-header">
            <h1>Contact Us</h1>
            <p>Give us a call on <span>01694 751380</span>, send us an email at <span>info@stormmachine.co.uk</span> <br> Or fill out our enquiry form below</p>
        </div>

        <form action="/submit-form" method="POST" class="contact-form">
            
            <div class="form-group">
                <h3>Your Details</h3>
                <div class="form-row">
                    <div class="form-field">
                        <label for="title">Title</label>
                        <select id="title" name="title">
                            <option value="">Select</option>
                            <option value="mr">Mr</option>
                            <option value="ms">Ms</option>
                            <option value="mrs">Mrs</option>
                            <option value="miss">Miss</option>
                        </select>
                    </div>
                    <div class="form-field">
                        <label for="first-name">First Name*</label>
                        <input type="text" id="first-name" name="firstName" required>
                    </div>
                    <div class="form-field">
                        <label for="surname">Surname*</label>
                        <input type="text" id="surname" name="surname" required>
                    </div>
                </div>
                
                <div class="form-row">
                    <div class="form-field">
                        <label for="telephone">Telephone</label>
                        <input type="tel" id="telephone" name="telephone">
                    </div>
                    <div class="form-field">
                        <label for="email">E-mail*</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-field">
                        </div>
                </div>
            </div>

            <div class="form-group">
                <h3>Your Postal Address</h3>
                <div class="form-row">
                    <div class="form-field">
                        <label for="address">Address</label>
                        <input type="text" id="address" name="address">
                    </div>
                    <div class="form-field">
                        <label for="address2">Address 2</label>
                        <input type="text" id="address2" name="address2">
                    </div>
                    <div class="form-field">
                        <label for="town-city">Town / City</label>
                        <input type="text" id="town-city" name="townCity">
                    </div>
                </div>
                
                <div class="form-row">
                    <div class="form-field">
                        <label for="county">County</label>
                        <input type="text" id="county" name="county">
                    </div>
                    <div class="form-field">
                        <label for="postcode">Postcode</label>
                        <input type="text" id="postcode" name="postcode">
                    </div>
                    <div class="form-field">
                        </div>
                </div>
            </div>

            <div class="form-group">
                <h3>Event Details</h3>
                <div class="form-row">
                    <div class="form-field">
                        <label for="date-of-event">Date of Event?</label>
                        <input type="text" id="date-of-event" name="dateOfEvent" placeholder="DD/MM/YYYY"> 
                    </div>
                    <div class="form-field">
                        <label for="no-of-guests">No. of Guests?</label>
                        <input type="text" id="no-of-guests" name="numberOfGuests">
                    </div>
                    <div class="form-field">
                        <label for="event-location">Event Location?</label>
                        <input type="text" id="event-location" name="eventLocation">
                    </div>
                </div>
                
                <div class="form-row">
                    <div class="form-field">
                        <label for="ground-surface">Ground Surface?</label>
                        <select id="ground-surface" name="groundSurface">
                            <option value="">Select</option>
                            <option value="grass">Grass</option>
                            <option value="concrete">Concrete</option>
                            <option value="mixed">Mixed</option>
                        </select>
                    </div>
                    <div class="form-field">
                        <label for="event-type">Event Type?</label>
                        <select id="event-type" name="eventType">
                            <option value="">Select</option>
                            <option value="wedding">Wedding</option>
                            <option value="corporate">Corporate</option>
                            <option value="party">Party</option>
                        </select>
                    </div>
                    <div class="form-field">
                        <label for="style-of-event">Style of Event?</label>
                        <select id="style-of-event" name="styleOfEvent">
                            <option value="">Select</option>
                            <option value="formal">Formal</option>
                            <option value="casual">Casual</option>
                        </select>
                    </div>
                </div>
            </div>

            <div class="form-group">
                <h3>Event Requirements</h3>
                <div class="requirements-grid">
                    
                    <div class="requirement-column">
                        <label><input type="checkbox" name="req_tables"> Tables?</label>
                        <label><input type="checkbox" name="req_chairs"> Chairs?</label>
                        <label><input type="checkbox" name="req_reception"> Reception Area?</label>
                    </div>
                    
                    <div class="requirement-column">
                        <label><input type="checkbox" name="req_dance_floor"> Dance Floor?</label>
                        <label><input type="checkbox" name="req_bar_facilities"> Bar Facilities?</label>
                        <label><input type="checkbox" name="req_walkway"> Walkway Entrance?</label>
                    </div>
                    
                    <div class="requirement-column">
                        <label><input type="checkbox" name="req_lining"> Lining?</label>
                        <label><input type="checkbox" name="req_heating"> Heating?</label>
                        <label><input type="checkbox" name="req_catering_tent"> Catering Tent?</label>
                    </div>
                    
                    <div class="requirement-column">
                        <label><input type="checkbox" name="req_lighting"> Lighting?</label>
                        <label><input type="checkbox" name="req_generator"> Generator?</label>
                        <label><input type="checkbox" name="req_staging"> Staging?</label>
                    </div>
                    
                </div>
            </div>

            <div class="form-group">
                <h3>Further Details</h3>
                <div class="full-width">
                    <label for="other-comments">Other comments</label>
                    <textarea id="other-comments" name="otherComments"></textarea>
                </div>
                
                <div class="full-width" style="margin-top: 15px;">
                    <label for="how-did-you-find-us">How did you find us?</label>
                    <input type="text" id="how-did-you-find-us" name="howDidYouFindUs">
                </div>
            </div>

            <div class="submit-button-container">
                <button type="submit" class="submit-button">Submit Contact Form</button>
            </div>
        </form>
    </main>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-info">
                <p><strong>CONTACT US</strong></p>
                <p>CALL US: 01694 751380</p>
            </div>
            <div class="footer-links">
                <p>MARQUEES</p>
                <p>DISCOS</p>
                <p>JAYS BARS</p>
            </div>
             <div class="footer-links" style="flex-basis: 15%;">
                <p>EQUIPMENT HIRE</p>
                <p>INFORMATION</p>
                <p>CONTACT US</p>
            </div>
            <div class="footer-social">
                <p>Follow us</p>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
        <div class="copyright">
            <p>© STORM MACHINE 2025</p>
        </div>
    </footer>
</body>
</html>



<a href="contact.html">CONTACT US</a>

<meta name="viewport" content="width=device-width, initial-scale=1.0">



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Storm Machine Entertainment - Evenimente</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    /* ==================================================== */
    /* 1. BAZĂ & FONT-URI */
    /* ==================================================== */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        padding-top: 60px; /* Spațiu pentru bara fixă */
        background-color: #fff;
        color: #333;
        line-height: 1.6;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    /* ==================================================== */
    /* 2. ANTET (HEADER) & NAVIGARE */
    /* ==================================================== */
    .header {
        background-color: #000;
        color: #fff;
        padding: 5px 0;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
    }

    .navbar {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        text-transform: uppercase;
    }

    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        padding: 0 10px;
        font-size: 13px;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #ffcc00;
    }

    .logo {
        margin: 0 30px;
        display: flex;
        align-items: center;
    }

    .logo img {
        height: 30px; 
        margin-right: 5px;
    }

    /* ==================================================== */
    /* 3. HERO SECTION */
    /* ==================================================== */
    .hero {
        position: relative;
        height: 500px; 
        background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        justify-content: center;
        padding-bottom: 50px;
    }

    .hero-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.3);
    }

    .hero-text {
        z-index: 1;
        color: #fff;
        text-align: center;
        text-transform: uppercase;
    }

    .hero-text h1 {
        font-size: 28px;
        margin: 0;
        font-weight: 600;
    }

    .hero-text p {
        font-size: 18px;
        margin-top: 5px;
        font-weight: 300;
    }

    /* ==================================================== */
    /* 4. INTRO & CONȚINUT */
    /* ==================================================== */
    .intro-section {
        text-align: center;
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }

    .intro-section p {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 15px;
    }

    /* ==================================================== */
    /* 5. GRID SERVICII (Cele 6 boxuri) */
    /* ==================================================== */
    .services-grid {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .service-box {
        position: relative;
        height: 250px;
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        align-items: flex-start;
        padding: 20px;
        cursor: pointer;
        transition: transform 0.3s;
    }

    .service-box:hover {
        transform: scale(1.02);
    }

    .service-box-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .service-content {
        z-index: 1;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .service-content h3 {
        font-size: 20px;
        margin: 0;
        font-weight: 600;
    }

    .arrow-icon {
        font-size: 24px;
    }

    /* Stiluri specifice pentru background-urile boxurilor */
    #box-quote { background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg'); }
    #box-marquees { background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg'); }
    #box-discos { background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg'); }
    #box-bars { background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400'); }
    #box-equipment { background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg'); }
    #box-gallery { background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg'); }

    /* ==================================================== */
    /* 6. TESTIMONIALE */
    /* ==================================================== */
    .testimonials {
        text-align: center;
        padding: 60px 20px;
        background-color: #f7f7f7;
    }

    .testimonials h2 {
        color: #0d83d1;
        font-weight: 600;
    }

    .testimonial-grid {
        max-width: 800px;
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        text-align: left;
        border-bottom: 1px solid #ddd;
        padding-bottom: 30px;
    }

    .testimonial-item {
        flex-basis: 45%;
        padding: 0 20px;
    }

    .testimonial-item h4 {
        font-weight: bold;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .testimonial-item p {
        font-size: 14px;
        line-height: 1.5;
    }

    .view-more-btn {
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        background-color: #0d83d1;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    .view-more-btn:hover {
        background-color: #0a6bb8;
    }

    /* ==================================================== */
    /* 7. FOOTER (SUBSOL) */
    /* ==================================================== */
    .footer {
        background-color: #333;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    .footer-content {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .footer-info, .footer-links, .footer-social {
        flex-basis: 30%;
        text-align: left;
    }

    .footer-links {
        flex-basis: 35%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-height: 100px;
    }

    .footer-info p, .footer-links a, .footer-social a {
        font-size: 13px;
        margin: 5px 0;
        display: block;
    }

    .footer-social {
        text-align: right;
    }

    .footer-social i {
        font-size: 20px;
        margin-left: 10px;
    }

    /* ==================================================== */
    /* 8. MODALE (POP-UP) */
    /* ==================================================== */
    .modal-content {
        display: none; /* Ascuns implicit */
        position: fixed;
        z-index: 2000;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        max-width: 600px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        border: 1px solid #ddd;
        border-radius: 5px;
    }

    .modal-active {
        display: block;
    }

    #gallery-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    #gallery-content img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* ==================================================== */
    /* MEDIA QUERIES (CSM) - Stilizare pentru Telefoane Mobile */
    /* ==================================================== */
    @media (max-width: 768px) {
        
        body {
            padding-top: 100px;
        }

        /* Navigare */
        .navbar {
            flex-direction: column;
            text-align: center;
        }
        
        .nav-links {
            width: 100%;
            margin: 5px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-links a {
            padding: 5px 8px;
            font-size: 12px;
        }

        .logo {
            margin: 10px 0;
        }

        /* Hero Section */
        .hero {
            height: 300px;
        }

        .hero-text h1 {
            font-size: 18px;
        }

        .hero-text p {
            font-size: 14px;
        }

        /* Grid-ul de Servicii (Cele 6 Boxuri) */
        .services-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .service-box {
            height: 150px;
        }

        /* Testimoniale */
        .testimonial-grid {
            flex-direction: column;
            border-bottom: none;
        }
        
        .testimonial-item {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        /* Footer */
        .footer-content {
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .footer-info, .footer-links, .footer-social {
            flex-basis: 100%;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .footer-links {
            max-height: none;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .footer-links a {
            padding: 5px 10px;
        }
        
        .footer-social i {
            margin: 0 5px;
        }
    }
</style>


<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            // Închide toate modalele deschise (pentru siguranță)
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            
            // Activează modalul dorit
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        document.getElementById(modalId).classList.remove('modal-active');
    }

    // Închide modalul dacă utilizatorul face click în afara ferestrei modale
    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            // Verifică dacă click-ul s-a întâmplat pe fundalul modalului
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>


<head>
    <title>Titlul Paginii</title>

    <link rel="stylesheet" href="style.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>


<div id="bar-modal" class="modal-content">
    <h2>Lista de Băuturi (Jay's Bar)</h2>
    <div id="bar-content">
        <h3>Alcohol</h3>
        <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
        <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
        <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
        <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
        <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
        <hr>
        <h3>Non-alcoholic</h3>
        <p><strong>Water:</strong> Still and mineral.</p>
        <p><strong>Juices:</strong> Natural and carbonated.</p>
        <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
        <hr>
        <h3>Additional recommendations</h3>
        <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
    </div>
    <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="quote-modal" class="modal-content">
    <h2>Solicită o Ofertă</h2>
    <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
    <form>
        <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
        <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
    </form>
    <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="gallery-modal" class="modal-content">
    <h2>Galerie Foto</h2>
    <div id="gallery-content">
        <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
    </div>
    <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        const modal = document.getElementById(modalId);
        if (modal) {
            modal.classList.remove('modal-active');
        }
    }

    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>

<script src="script.js"></script>
<script src="script.js"></script>


[homepage.html](https://github.com/user-attachments/files/23592537/homepage.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jay’s Bars</title>
  <style>
    /* ===== BARA DE SUS ===== */
    header nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #333;
      padding: 10px 20px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    header nav ul li {
      margin: 0 15px;
    }
    header nav ul li.logo {
      margin: 0 40px;
    }
    header nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    header nav ul li a:hover {
      color: #ffcc00;
    }
    header nav ul li img {
      height: 50px;
    }

    /* ===== BODY ===== */
    body {
      margin: 0;
      padding-top: 80px; /* spațiu pentru bara fixă */
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    /* ===== BANNER ===== */
    .banner {
      position: relative;
      text-align: center;
      color: white;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .banner .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.4);
    }
    .banner .text {
      position: absolute;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
    }
    .btn-quote {
      background-color: #fff;
      color: #333;
      padding: 10px 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 10px;
      display: inline-block;
    }
    .btn-quote:hover {
      background-color: #ffcc00;
      color: #333;
    }

    /* ===== CONȚINUT ===== */
    .content {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    
  <!-- ===== HEADER ===== -->
  <header>
    <nav>
      <ul>
        <li><a href="marquees.html">MARQUEES</a></li>
        <li><a href="discos.html">DISCOS</a></li>
        <li><a href="jaysbars.html">JAY’S BARS</a></li>
        <li><a href="equipment.html">EQUIPMENT HIRE</a></li>
        <li class="logo"><a href="index.html"><img src="images/stormmachine-logo.png" alt="Storm Machine Logo"></a></li>
        <li><a href="gallery.html">GALLERY</a></li>
        <li><a href="information.html">INFORMATION</a></li>
        <li><a href="contact.html">CONTACT US</a></li>
      </ul>
    </nav>
  </header>

  <!-- ===== BANNER ===== -->
  <section class="banner">
    <img src="images/banner-jaysbars.jpg" alt="Jay's Bars Banner">
    <div class="overlay"></div>
    <div class="text">
      <h1>Jay’s Bars</h1>
      <a href="contact.html" class="btn-quote">Get a Quote</a>
    </div>
  </section>

  <!-- ===== CONȚINUT ===== -->
  <div class="content">
    <h2>Weddings, Corporate Events & Parties</h2>
    <p>Storm Machine Entertainment are Shropshire's finest and experienced party organisers and entertainment providers.</p>
    <p>Marquee, Discos, Bars and Equipment Hire for whatever your occasion may be.</p>
    <p>Whether you are planning your wedding, birthday or corporate event, or need a marquee, bar, disco or fireworks, Storm Machine Entertainment will go that extra mile for you.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
  </div>

 




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marquees</title>
  <style>
    /* ===== BARA DE SUS ===== */
    header nav ul {
      list-style: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #333;
      padding: 10px 20px;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
    }
    header nav ul li {
      margin: 0 15px;
    }
    header nav ul li.logo {
      margin: 0 40px;
    }
    header nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    header nav ul li a:hover {
      color: #ffcc00;
    }
    header nav ul li img {
      height: 50px;
    }

    /* ===== BODY ===== */
    body {
      margin: 0;
      padding-top: 80px; /* spațiu pentru bara fixă */
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }
    .banner {
      position: relative;
      text-align: center;
      color: white;
    }
    .banner img {
      width: 100%;
      height: auto;
    }
    .banner .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0,0,0,0.4);
    }
    .banner .text {
      position: absolute;
      bottom: 20px;
      left: 50%;
      transform: translateX(-50%);
    }
    .btn-quote {
      background-color: #fff;
      color: #333;
      padding: 10px 20px;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
      margin-top: 10px;
      display: inline-block;
    }
    .btn-quote:hover {
      background-color: #ffcc00;
      color: #333;
    }

    /* ===== CONȚINUT ===== */
    .content {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    /* ===== FOOTER ===== */
    footer {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    footer a {
      color: #ffcc00;
      text-decoration: none;
      margin: 0 10px;
    }
  </style>
</head>
<body>

  

  

 

  










<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Storm Machine Entertainment - Evenimente</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Reset de bază și Font-uri */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }

        /* Antet (Header) */
        .header {
            background-color: #000;
            color: #fff;
            padding: 10px 0;
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }

        .nav-links a {
            padding: 0 15px;
            font-size: 14px;
            text-transform: uppercase;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            height: 40px; /* Ajustați dimensiunea logo-ului */
            margin-right: 10px;
        }

        /* Hero Section (Imaginea mare de sus) */
        .hero {
            position: relative;
            height: 500px; /* Înălțime fixă */
            background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
            background-size: cover;
            background-position: center;
            display: flex;
            align-items: flex-end;
            justify-content: center;
            text-align: center;
            padding-bottom: 50px;
        }

        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.3); /* Suprapunere semi-transparentă */
        }

        .hero-text {
            z-index: 1;
            color: #fff;
            text-transform: uppercase;
        }

        .hero-text h1 {
            font-size: 28px;
            margin: 0;
            font-weight: 400;
        }

        .hero-text p {
            font-size: 18px;
            margin-top: 5px;
            font-weight: 300;
        }

        /* Secțiunea Intro */
        .intro-section {
            text-align: center;
            padding: 40px 20px;
            max-width: 800px;
            margin: 0 auto;
        }

        .intro-section p {
            font-size: 16px;
            line-height: 1.6;
        }

        /* Grid-ul de Servicii (Cele 6 poze) */
        .services-grid {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .service-box {
            position: relative;
            height: 250px; /* Înălțime uniformă pentru cutii */
            background-size: cover;
            background-position: center;
            color: #fff;
            display: flex;
            align-items: flex-start; /* Aliniere text sus */
            padding: 20px;
            cursor: pointer;
            transition: transform 0.3s;
        }

        .service-box:hover {
            transform: scale(1.02);
        }

        .service-box-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.4); /* Suprapunere pentru citirea textului */
        }

        .service-content {
            z-index: 1;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .service-content h3 {
            font-size: 20px;
            margin: 0;
            font-weight: 600;
        }

        .arrow-icon {
            font-size: 24px;
            /* Culoarea implicită este albă, ca în imagine */
        }

        /* Stiluri specifice pentru fiecare box */
        #box-quote {
            background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg');
        }

        #box-marquees {
            background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg');
        }

        #box-discos {
            background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg');
        }

        #box-bars {
            background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400');
        }

        #box-equipment {
            background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg');
        }

        #box-gallery {
            background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg');
        }

        /* Secțiunea Testimoniale */
        .testimonials {
            text-align: center;
            padding: 60px 20px;
            background-color: #f7f7f7;
        }

        .testimonials h2 {
            color: #0d83d1; /* Culoarea albastră din imagine */
            font-weight: 600;
        }

        .testimonial-grid {
            max-width: 800px;
            margin: 20px auto;
            display: flex;
            justify-content: space-around;
            text-align: left;
            border-bottom: 1px solid #ddd; /* Linia despărțitoare */
            padding-bottom: 30px;
        }

        .testimonial-item {
            flex-basis: 45%;
            padding: 0 20px;
        }

        .testimonial-item h4 {
            font-weight: bold;
            font-size: 16px;
            margin-bottom: 10px;
        }

        .testimonial-item p {
            font-size: 14px;
            line-height: 1.5;
        }

        .view-more-btn {
            display: inline-block;
            margin-top: 30px;
            padding: 10px 20px;
            background-color: #0d83d1;
            color: #fff;
            text-transform: uppercase;
            font-size: 14px;
            font-weight: bold;
            transition: background-color 0.3s;
        }

        .view-more-btn:hover {
            background-color: #0a6bb8;
        }

        /* Footer (Subsol) */
        .footer {
            background-color: #333;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .footer-info, .footer-links, .footer-social {
            flex-basis: 30%;
            text-align: left;
        }

        .footer-info p, .footer-links a, .footer-social a {
            font-size: 13px;
            margin: 5px 0;
            display: block;
        }

        .footer-social {
            text-align: right;
        }

        .footer-social i {
            font-size: 20px;
            margin-left: 10px;
        }

        /* Pop-up-uri/Casete Modale (Simplificate, folosesc doar un element vizibil) */
        .modal-content {
            display: none; /* Ascuns implicit */
            position: fixed;
            z-index: 10;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
            width: 80%;
            max-width: 600px;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border: 1px solid #ddd;
        }

        /* Caseta de Bar */
        #bar-content {
            max-height: 400px;
            overflow-y: auto;
        }

        /* Casetă simplificată pentru galerie */
        #gallery-content {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
        }

        #gallery-content img {
            width: 100%;
            height: auto;
            display: block;
        }

        /* Afișează conținutul modal când este activ */
        .modal-active {
            display: block;
        }
    </style>
</head>
<body>

    <header class="header">
        <div class="navbar">
            <div class="nav-links">
                <a href="#">MARQUEES</a>
                <a href="#">DISCOS</a>
                <a href="#">JAYS BARS</a>
                <a href="#">EQUIPMENT HIRE</a>
            </div>
            <div class="logo">
                <img src="https://i.imgur.com/5wQ2pXF.png" alt="Storm Machine Logo" style="height: 30px;"> 
                <span>stormmachine</span>
            </div>
            <div class="nav-links">
                <a href="#">GALLERY</a>
                <a href="#">INFORMATION</a>
                <a href="#">CONTACT US</a>
                <a href="#"><i class="fas fa-info-circle"></i></a>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-text">
            <h1>Marquee, Discos, Bars and Equipment Hire for</h1>
            <p>Weddings, Corporate Events & Parties</p>
        </div>
    </section>

    <section class="services-grid">
        <a href="#quote-modal" class="service-box" id="box-quote" onclick="showModal('quote-modal', 'https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg')">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Get a quote</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>

        <a href="https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg" target="_blank" class="service-box" id="box-marquees">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Marquees</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>

        <a href="https://s13emagst.akamaized.net/products/40549/40548579/images/res_028df301e8046e9d36a507c61e5ee480.jpg" target="_blank" class="service-box" id="box-discos">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Discos</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>

        <a href="#bar-modal" class="service-box" id="box-bars" onclick="showModal('bar-modal', null)">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Jay's Bars</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>

        <a href="https://www.stressaudio.pro/wp-content/uploads/2017/11/SONORIZARI-EVENIMENTE-SI-CONFERINTE.jpg" target="_blank" class="service-box" id="box-equipment">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Equipment Hire</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>

        <a href="#gallery-modal" class="service-box" id="box-gallery" onclick="showModal('gallery-modal', null)">
            <div class="service-box-overlay"></div>
            <div class="service-content">
                <h3>Gallery</h3>
                <i class="fas fa-arrow-right arrow-icon"></i>
            </div>
        </a>
    </section>

    <div id="bar-modal" class="modal-content">
        <h2>Lista de Băuturi (Jay's Bar)</h2>
        <div id="bar-content">
            <h3>Alcohol</h3>
            <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
            <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
            <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
            <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
            <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
            <hr>
            <h3>Non-alcoholic</h3>
            <p><strong>Water:</strong> Still and mineral.</p>
            <p><strong>Juices:</strong> Natural and carbonated.</p>
            <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
            <hr>
            <h3>Additional recommendations</h3>
            <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
        </div>
        <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
    </div>

    <div id="quote-modal" class="modal-content">
        <h2>Solicită o Ofertă</h2>
        <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
        <form>
            <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
            <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
            <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
            <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
        </form>
        <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
    </div>

    <div id="gallery-modal" class="modal-content">
        <h2>Galerie Foto</h2>
        <div id="gallery-content">
            <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
        </div>
        <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
    </div>


    <section class="intro-section">
        <p>
            Whether you are planning your wedding, birthday or corporate event, or need a 
            marquee, disco, bar or equipment hire, Storm Machine Entertainment can provide
            the perfect solution for you.
        </p>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt
            ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
            ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur
            sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim
            id est laborum.
        </p>
    </section>

    <section class="testimonials">
        <h2>Testimonials</h2>
        <p>What our clients said</p>
        <div class="testimonial-grid">
            <div class="testimonial-item">
                <h4>Thank you for everything!</h4>
                <p>We had the most amazing time and you and your team really pulled out all the stops for us!</p>
                <p>Sincere thanks and we will certainly be recommending you to all of our friends.</p>
            </div>
            <div class="testimonial-item">
                <h4>Thank you for everything!</h4>
                <p>We had the most amazing time and you and your team really pulled out all the stops for us!</p>
                <p>Sincere thanks and we will certainly be recommending you to all of our friends.</p>
            </div>
        </div>
        <a href="#" class="view-more-btn">View More &rarr;</a>
    </section>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-info">
                <p><strong>CONTACT US</strong></p>
                <p>CALL US: 0722 123 456</p>
            </div>
            <div class="footer-links">
                <a href="#">MARQUEES</a>
                <a href="#">DISCOS</a>
                <a href="#">JAYS BARS</a>
                <a href="#">EQUIPMENT HIRE</a>
                <a href="#">INFORMATION</a>
            </div>
            <div class="footer-social">
                <p>Follow us</p>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script>
        function showModal(modalId, redirectUrl) {
            const modal = document.getElementById(modalId);
            
            // Dacă este o casetă de tip link, se redirecționează (de ex., Marquees, Equipment Hire, Discos)
            // Dar pentru cererea ta specifică, "Get a quote", "Jay's Bar" și "Gallery" deschid un modal
            
            if (modal) {
                // Închide toate modalele deschise
                document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
                
                // Activează modalul dorit
                modal.classList.add('modal-active');
            } else if (redirectUrl) {
                // Dacă nu este un modal, redirecționează pur și simplu (pentru celelalte, deși am setat link-uri direct în HTML)
                window.open(redirectUrl, '_blank');
            }
        }

        function closeModal(modalId) {
            document.getElementById(modalId).classList.remove('modal-active');
        }

        // Închide modalul la click în afara lui (opțional)
        window.onclick = function(event) {
            document.querySelectorAll('.modal-content').forEach(modal => {
                if (event.target == modal) {
                    modal.classList.remove('modal-active');
                }
            });
        }
    </script>

</body>
</html>

<meta name="viewport" content="width=device-width, initial-scale=1.0">



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Storm Machine Entertainment - Evenimente</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    /* ==================================================== */
    /* 1. BAZĂ & FONT-URI */
    /* ==================================================== */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        padding-top: 60px; /* Spațiu pentru bara fixă */
        background-color: #fff;
        color: #333;
        line-height: 1.6;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    /* ==================================================== */
    /* 2. ANTET (HEADER) & NAVIGARE */
    /* ==================================================== */
    .header {
        background-color: #000;
        color: #fff;
        padding: 5px 0;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
    }

    .navbar {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        text-transform: uppercase;
    }

    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        padding: 0 10px;
        font-size: 13px;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #ffcc00;
    }

    .logo {
        margin: 0 30px;
        display: flex;
        align-items: center;
    }

    .logo img {
        height: 30px; 
        margin-right: 5px;
    }

    /* ==================================================== */
    /* 3. HERO SECTION */
    /* ==================================================== */
    .hero {
        position: relative;
        height: 500px; 
        background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        justify-content: center;
        padding-bottom: 50px;
    }

    .hero-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.3);
    }

    .hero-text {
        z-index: 1;
        color: #fff;
        text-align: center;
        text-transform: uppercase;
    }

    .hero-text h1 {
        font-size: 28px;
        margin: 0;
        font-weight: 600;
    }

    .hero-text p {
        font-size: 18px;
        margin-top: 5px;
        font-weight: 300;
    }

    /* ==================================================== */
    /* 4. INTRO & CONȚINUT */
    /* ==================================================== */
    .intro-section {
        text-align: center;
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }

    .intro-section p {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 15px;
    }

    /* ==================================================== */
    /* 5. GRID SERVICII (Cele 6 boxuri) */
    /* ==================================================== */
    .services-grid {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .service-box {
        position: relative;
        height: 250px;
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        align-items: flex-start;
        padding: 20px;
        cursor: pointer;
        transition: transform 0.3s;
    }

    .service-box:hover {
        transform: scale(1.02);
    }

    .service-box-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .service-content {
        z-index: 1;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .service-content h3 {
        font-size: 20px;
        margin: 0;
        font-weight: 600;
    }

    .arrow-icon {
        font-size: 24px;
    }

    /* Stiluri specifice pentru background-urile boxurilor */
    #box-quote { background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg'); }
    #box-marquees { background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg'); }
    #box-discos { background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg'); }
    #box-bars { background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400'); }
    #box-equipment { background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg'); }
    #box-gallery { background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg'); }

    /* ==================================================== */
    /* 6. TESTIMONIALE */
    /* ==================================================== */
    .testimonials {
        text-align: center;
        padding: 60px 20px;
        background-color: #f7f7f7;
    }

    .testimonials h2 {
        color: #0d83d1;
        font-weight: 600;
    }

    .testimonial-grid {
        max-width: 800px;
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        text-align: left;
        border-bottom: 1px solid #ddd;
        padding-bottom: 30px;
    }

    .testimonial-item {
        flex-basis: 45%;
        padding: 0 20px;
    }

    .testimonial-item h4 {
        font-weight: bold;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .testimonial-item p {
        font-size: 14px;
        line-height: 1.5;
    }

    .view-more-btn {
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        background-color: #0d83d1;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    .view-more-btn:hover {
        background-color: #0a6bb8;
    }

    /* ==================================================== */
    /* 7. FOOTER (SUBSOL) */
    /* ==================================================== */
    .footer {
        background-color: #333;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    .footer-content {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .footer-info, .footer-links, .footer-social {
        flex-basis: 30%;
        text-align: left;
    }

    .footer-links {
        flex-basis: 35%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-height: 100px;
    }

    .footer-info p, .footer-links a, .footer-social a {
        font-size: 13px;
        margin: 5px 0;
        display: block;
    }

    .footer-social {
        text-align: right;
    }

    .footer-social i {
        font-size: 20px;
        margin-left: 10px;
    }

    /* ==================================================== */
    /* 8. MODALE (POP-UP) */
    /* ==================================================== */
    .modal-content {
        display: none; /* Ascuns implicit */
        position: fixed;
        z-index: 2000;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        max-width: 600px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        border: 1px solid #ddd;
        border-radius: 5px;
    }

    .modal-active {
        display: block;
    }

    #gallery-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    #gallery-content img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* ==================================================== */
    /* MEDIA QUERIES (CSM) - Stilizare pentru Telefoane Mobile */
    /* ==================================================== */
    @media (max-width: 768px) {
        
        body {
            padding-top: 100px;
        }

        /* Navigare */
        .navbar {
            flex-direction: column;
            text-align: center;
        }
        
        .nav-links {
            width: 100%;
            margin: 5px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-links a {
            padding: 5px 8px;
            font-size: 12px;
        }

        .logo {
            margin: 10px 0;
        }

        /* Hero Section */
        .hero {
            height: 300px;
        }

        .hero-text h1 {
            font-size: 18px;
        }

        .hero-text p {
            font-size: 14px;
        }

        /* Grid-ul de Servicii (Cele 6 Boxuri) */
        .services-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .service-box {
            height: 150px;
        }

        /* Testimoniale */
        .testimonial-grid {
            flex-direction: column;
            border-bottom: none;
        }
        
        .testimonial-item {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        /* Footer */
        .footer-content {
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .footer-info, .footer-links, .footer-social {
            flex-basis: 100%;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .footer-links {
            max-height: none;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .footer-links a {
            padding: 5px 10px;
        }
        
        .footer-social i {
            margin: 0 5px;
        }
    }
</style>


<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            // Închide toate modalele deschise (pentru siguranță)
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            
            // Activează modalul dorit
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        document.getElementById(modalId).classList.remove('modal-active');
    }

    // Închide modalul dacă utilizatorul face click în afara ferestrei modale
    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            // Verifică dacă click-ul s-a întâmplat pe fundalul modalului
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>



<<head>
    <title>Titlul Paginii</title>

    <link rel="stylesheet" href="style.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>


<div id="bar-modal" class="modal-content">
    <h2>Lista de Băuturi (Jay's Bar)</h2>
    <div id="bar-content">
        <h3>Alcohol</h3>
        <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
        <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
        <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
        <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
        <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
        <hr>
        <h3>Non-alcoholic</h3>
        <p><strong>Water:</strong> Still and mineral.</p>
        <p><strong>Juices:</strong> Natural and carbonated.</p>
        <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
        <hr>
        <h3>Additional recommendations</h3>
        <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
    </div>
    <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="quote-modal" class="modal-content">
    <h2>Solicită o Ofertă</h2>
    <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
    <form>
        <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
        <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
    </form>
    <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="gallery-modal" class="modal-content">
    <h2>Galerie Foto</h2>
    <div id="gallery-content">
        <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
    </div>
    <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        const modal = document.getElementById(modalId);
        if (modal) {
            modal.classList.remove('modal-active');
        }
    }

    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>


[marqueespage.html](https://github.com/user-attachments/files/23592538/marqueespage.html)
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Storm Machine Entertainment - Marquees</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* CSS general și reset (Preluat din pagina principală) */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #333;
        }

        a {
            text-decoration: none;
            color: inherit;
        }
        
        /* ---------------------------------------------------- */
        /* Antet (Header) - Preluat de pe pagina principală */
        .header {
            background-color: #000;
            color: #fff;
            padding: 10px 0;
        }

        .navbar {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            text-transform: uppercase;
        }

        .nav-links a {
            padding: 0 15px;
            font-size: 14px;
        }

        .logo {
            display: flex;
            align-items: center;
        }

        .logo img {
            height: 40px; 
            margin-right: 10px;
        }
        
        /* ---------------------------------------------------- */
        /* HERO Section (Imaginea mare de sus - Marquees) */
        .marquee-hero {
            position: relative;
            height: 400px; /* Ajustat pentru a se potrivi cu imaginea */
            background-image: url('https://www.calinstan.com/wp-content/uploads/2022/06/restaurant-rotonda-casa-timis-3.jpg');
            background-size: cover;
            background-position: center;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
        }

        .marquee-hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background-color: rgba(0, 0, 0, 0.4); /* Suprapunere semi-transparentă */
        }

        .marquee-hero h1 {
            z-index: 1;
            font-size: 50px;
            margin-bottom: 0;
            text-transform: uppercase;
            font-weight: 800;
        }

        /* Navigare suplimentară (sub hero image) - preluată din imaginea principală */
        .secondary-nav {
            background-color: #333; /* Culoarea barei de navigație de sub imagine */
            color: #fff;
            padding: 10px 0;
        }
        
        .secondary-nav-links {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            gap: 40px;
            padding: 0 20px;
            font-size: 14px;
            text-transform: uppercase;
        }
        
        /* ---------------------------------------------------- */
        /* Secțiunea de text introductiv (sub hero) */
        .intro-text-section {
            text-align: center;
            padding: 50px 20px;
            max-width: 900px;
            margin: 0 auto;
        }

        .intro-text-section h2 {
            font-size: 24px;
            font-weight: bold;
            line-height: 1.4;
            color: #333;
            margin-bottom: 20px;
        }

        .intro-text-section p {
            font-size: 15px;
            line-height: 1.6;
            color: #555;
        }
        
        /* ---------------------------------------------------- */
        /* Secțiunea de Imagini și Descriere */
        .details-grid {
            max-width: 1200px;
            margin: 0 auto 50px auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            text-align: center;
        }

        .detail-item img {
            width: 100%;
            height: 200px; /* Înălțime fixă pentru a le uniformiza */
            object-fit: cover;
            display: block;
        }

        .detail-item p {
            margin-top: 10px;
            font-size: 14px;
            line-height: 1.5;
        }
        
        /* ---------------------------------------------------- */
        /* Secțiunea "Get a Quote" */
        .quote-section {
            background-color: #f7f7f7;
            text-align: center;
            padding: 40px 20px;
            border-top: 1px solid #ddd;
        }

        .quote-section h3 {
            font-size: 28px;
            color: #0d83d1; /* Albastru similar cu imaginea */
            margin-bottom: 10px;
            text-transform: uppercase;
        }

        .quote-section p {
            font-size: 15px;
            color: #333;
        }

        .quote-section span {
            font-weight: bold;
        }
        
        /* ---------------------------------------------------- */
        /* Subsol (Footer) - Preluat de pe pagina principală */
        .footer {
            background-color: #333;
            color: #fff;
            padding: 30px 20px;
            text-align: center;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
        }

        .footer-info, .footer-links, .footer-social {
            flex-basis: 30%;
            text-align: left;
        }

        .footer-info p, .footer-links a, .footer-social a {
            font-size: 13px;
            margin: 5px 0;
            display: block;
        }

        .footer-social {
            text-align: right;
        }

        .footer-social i {
            font-size: 20px;
            margin-left: 10px;
        }
        
        .copyright {
            margin-top: 20px;
            font-size: 12px;
            text-align: center;
        }

    </style>
</head>
<body>

    <header class="header">
        <div class="navbar">
            <div class="nav-links">
                <a href="index.html">MARQUEES</a>
                <a href="index.html">DISCOS</a>
                <a href="index.html">JAYS BARS</a>
                <a href="index.html">EQUIPMENT HIRE</a>
            </div>
            <div class="logo">
                <img src="https://i.imgur.com/5wQ2pXF.png" alt="Storm Machine Logo" style="height: 30px;"> 
                <span>stormmachine</span>
            </div>
            <div class="nav-links">
                <a href="index.html">GALLERY</a>
                <a href="index.html">INFORMATION</a>
                <a href="index.html">CONTACT US</a>
                <a href="#"><i class="fas fa-info-circle"></i></a>
            </div>
        </div>
    </header>

    <nav class="secondary-nav">
        <div class="secondary-nav-links">
            <a href="#">MARQUEES</a>
            <a href="#">DISCOS</a>
            <a href="#">JAYS BARS</a>
            <a href="#">EQUIPMENT HIRE</a>
            <a href="#">GALLERY</a>
            <a href="#">INFORMATION</a>
            <a href="#">CONTACT US</a>
            <a href="#">CONTACT US</a>
            <a href="#"><i class="fas fa-info-circle"></i></a>
        </div>
    </nav>
    
    <section class="marquee-hero">
        <div class="marquee-hero-overlay"></div>
        <h1 style="margin-bottom: 50px;">Marquees</h1>
    </section>

    <section class="intro-text-section">
        <h2>Whatever your occasion may be, be it a wedding, a party, an exhibition, hospitality or corporate event we have a marquee to suit you.</h2>
        <p>Our clearspan marquees are either 9m or 12m wide by 3m bays which allows for a variety of sizes depending on your event.</p>
    </section>

    <section class="details-grid">
        <div class="detail-item">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQ4RtSbUOts0VG-nniOHPbuNfFdheykjccgA&s" alt="Imagine Marquee 1">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
        </div>
        <div class="detail-item">
            <img src="https://b3342515.smushcdn.com/3342515/wp-content/uploads/2023/10/ZII_2615-2.jpg?lossy=2&strip=1&webp=1" alt="Imagine Marquee 2">
            <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        </div>
        <div class="detail-item">
            <img src="https://regnumevents.ro/wp-content/uploads/2022/11/salon-evenimente-corporate-nunti-botez-bucuresti-1200px.jpg" alt="Imagine Marquee 3">
            <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        </div>
    </section>
    
    <section class="quote-section">
        <h3>Get a Quote</h3>
        <p>Fill out our <span>contact form</span>, or alternatively call us on <span>01694 751380</span></p>
    </section>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-info">
                <p><strong>CONTACT US</strong></p>
                <p>CALL US: 01694 751380</p>
            </div>
            <div class="footer-links">
                <p>MARQUEES</p>
                <p>DISCOS</p>
                <p>JAYS BARS</p>
            </div>
             <div class="footer-links" style="flex-basis: 15%;">
                <p>EQUIPMENT HIRE</p>
                <p>INFORMATION</p>
                <p>CONTACT US</p>
            </div>
            <div class="footer-social">
                <p>Follow us</p>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
        <div class="copyright">
            <p>© STORM MACHINE 2025</p>
        </div>
    </footer>
</body>
</html>




<a href="https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg" target="_blank" class="service-box" id="box-marquees">




<a href="marquees.html" class="service-box" id="box-marquees">
    <div class="service-box-overlay"></div>
    <div class="service-content">
        <h3>Marquees</h3>
        <i class="fas fa-arrow-right arrow-icon"></i>
    </div>
</a>


<meta name="viewport" content="width=device-width, initial-scale=1.0">



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Storm Machine Entertainment - Evenimente</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    /* ==================================================== */
    /* 1. BAZĂ & FONT-URI */
    /* ==================================================== */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        padding-top: 60px; /* Spațiu pentru bara fixă */
        background-color: #fff;
        color: #333;
        line-height: 1.6;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    /* ==================================================== */
    /* 2. ANTET (HEADER) & NAVIGARE */
    /* ==================================================== */
    .header {
        background-color: #000;
        color: #fff;
        padding: 5px 0;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
    }

    .navbar {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        text-transform: uppercase;
    }

    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        padding: 0 10px;
        font-size: 13px;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #ffcc00;
    }

    .logo {
        margin: 0 30px;
        display: flex;
        align-items: center;
    }

    .logo img {
        height: 30px; 
        margin-right: 5px;
    }

    /* ==================================================== */
    /* 3. HERO SECTION */
    /* ==================================================== */
    .hero {
        position: relative;
        height: 500px; 
        background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        justify-content: center;
        padding-bottom: 50px;
    }

    .hero-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.3);
    }

    .hero-text {
        z-index: 1;
        color: #fff;
        text-align: center;
        text-transform: uppercase;
    }

    .hero-text h1 {
        font-size: 28px;
        margin: 0;
        font-weight: 600;
    }

    .hero-text p {
        font-size: 18px;
        margin-top: 5px;
        font-weight: 300;
    }

    /* ==================================================== */
    /* 4. INTRO & CONȚINUT */
    /* ==================================================== */
    .intro-section {
        text-align: center;
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }

    .intro-section p {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 15px;
    }

    /* ==================================================== */
    /* 5. GRID SERVICII (Cele 6 boxuri) */
    /* ==================================================== */
    .services-grid {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .service-box {
        position: relative;
        height: 250px;
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        align-items: flex-start;
        padding: 20px;
        cursor: pointer;
        transition: transform 0.3s;
    }

    .service-box:hover {
        transform: scale(1.02);
    }

    .service-box-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .service-content {
        z-index: 1;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .service-content h3 {
        font-size: 20px;
        margin: 0;
        font-weight: 600;
    }

    .arrow-icon {
        font-size: 24px;
    }

    /* Stiluri specifice pentru background-urile boxurilor */
    #box-quote { background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg'); }
    #box-marquees { background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg'); }
    #box-discos { background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg'); }
    #box-bars { background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400'); }
    #box-equipment { background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg'); }
    #box-gallery { background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg'); }

    /* ==================================================== */
    /* 6. TESTIMONIALE */
    /* ==================================================== */
    .testimonials {
        text-align: center;
        padding: 60px 20px;
        background-color: #f7f7f7;
    }

    .testimonials h2 {
        color: #0d83d1;
        font-weight: 600;
    }

    .testimonial-grid {
        max-width: 800px;
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        text-align: left;
        border-bottom: 1px solid #ddd;
        padding-bottom: 30px;
    }

    .testimonial-item {
        flex-basis: 45%;
        padding: 0 20px;
    }

    .testimonial-item h4 {
        font-weight: bold;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .testimonial-item p {
        font-size: 14px;
        line-height: 1.5;
    }

    .view-more-btn {
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        background-color: #0d83d1;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    .view-more-btn:hover {
        background-color: #0a6bb8;
    }

    /* ==================================================== */
    /* 7. FOOTER (SUBSOL) */
    /* ==================================================== */
    .footer {
        background-color: #333;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    .footer-content {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .footer-info, .footer-links, .footer-social {
        flex-basis: 30%;
        text-align: left;
    }

    .footer-links {
        flex-basis: 35%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-height: 100px;
    }

    .footer-info p, .footer-links a, .footer-social a {
        font-size: 13px;
        margin: 5px 0;
        display: block;
    }

    .footer-social {
        text-align: right;
    }

    .footer-social i {
        font-size: 20px;
        margin-left: 10px;
    }

    /* ==================================================== */
    /* 8. MODALE (POP-UP) */
    /* ==================================================== */
    .modal-content {
        display: none; /* Ascuns implicit */
        position: fixed;
        z-index: 2000;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        max-width: 600px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        border: 1px solid #ddd;
        border-radius: 5px;
    }

    .modal-active {
        display: block;
    }

    #gallery-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    #gallery-content img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* ==================================================== */
    /* MEDIA QUERIES (CSM) - Stilizare pentru Telefoane Mobile */
    /* ==================================================== */
    @media (max-width: 768px) {
        
        body {
            padding-top: 100px;
        }

        /* Navigare */
        .navbar {
            flex-direction: column;
            text-align: center;
        }
        
        .nav-links {
            width: 100%;
            margin: 5px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-links a {
            padding: 5px 8px;
            font-size: 12px;
        }

        .logo {
            margin: 10px 0;
        }

        /* Hero Section */
        .hero {
            height: 300px;
        }

        .hero-text h1 {
            font-size: 18px;
        }

        .hero-text p {
            font-size: 14px;
        }

        /* Grid-ul de Servicii (Cele 6 Boxuri) */
        .services-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .service-box {
            height: 150px;
        }

        /* Testimoniale */
        .testimonial-grid {
            flex-direction: column;
            border-bottom: none;
        }
        
        .testimonial-item {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        /* Footer */
        .footer-content {
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .footer-info, .footer-links, .footer-social {
            flex-basis: 100%;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .footer-links {
            max-height: none;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .footer-links a {
            padding: 5px 10px;
        }
        
        .footer-social i {
            margin: 0 5px;
        }
    }
</style>



<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            // Închide toate modalele deschise (pentru siguranță)
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            
            // Activează modalul dorit
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        document.getElementById(modalId).classList.remove('modal-active');
    }

    // Închide modalul dacă utilizatorul face click în afara ferestrei modale
    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            // Verifică dacă click-ul s-a întâmplat pe fundalul modalului
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>



<head>
    <title>Titlul Paginii</title>

    <link rel="stylesheet" href="style.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>



<div id="bar-modal" class="modal-content">
    <h2>Lista de Băuturi (Jay's Bar)</h2>
    <div id="bar-content">
        <h3>Alcohol</h3>
        <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
        <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
        <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
        <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
        <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
        <hr>
        <h3>Non-alcoholic</h3>
        <p><strong>Water:</strong> Still and mineral.</p>
        <p><strong>Juices:</strong> Natural and carbonated.</p>
        <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
        <hr>
        <h3>Additional recommendations</h3>
        <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
    </div>
    <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="quote-modal" class="modal-content">
    <h2>Solicită o Ofertă</h2>
    <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
    <form>
        <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
        <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
    </form>
    <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="gallery-modal" class="modal-content">
    <h2>Galerie Foto</h2>
    <div id="gallery-content">
        <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
    </div>
    <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        const modal = document.getElementById(modalId);
        if (modal) {
            modal.classList.remove('modal-active');
        }
    }

    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>


<script src="script.js"></script>




[testimonialspage.html](https://github.com/user-attachments/files/23592539/testimonialspage.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Testimonials | Storm Machine UK Ltd</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f8f9fa;
      margin: 0;
      padding: 0;
    }

    /* Header */
    header {
      background-color: #fff;
      border-bottom: 1px solid #ddd;
      text-align: center;
      padding: 1rem 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      gap: 1.5rem;
    }

    nav a {
      color: #000;
      font-weight: 500;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #007bff;
    }

    nav img {
      height: 70px;
    }

    /* Main */
    main {
      max-width: 1100px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h1 {
      text-align: center;
      margin-bottom: 1rem;
      font-size: 2.2rem;
      font-weight: 700;
      color: #333;
    }

    p.text-center {
      color: #555;
    }

    .testimonial {
      background: #fff;
      border-radius: 8px;
      padding: 2rem;
      margin: 1.5rem 0;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }

    .testimonial h3 {
      font-style: italic;
      color: #0d6efd;
      font-size: 1.4rem;
      margin-bottom: 1rem;
    }

    .testimonial p {
      font-size: 1rem;
      line-height: 1.6;
      color: #333;
    }

    .testimonial .author {
      text-align: right;
      font-weight: 600;
      margin-top: 1rem;
      color: #555;
    }

    /* Footer */
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 3rem;
    }

    footer p {
      margin: 0.5rem 0;
    }

    footer a {
      color: #f39c12;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    footer a:hover {
      color: #fff;
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <!-- HEADER -->
  <header>
    <nav>
      <ul>
        <li><a href="marquees.html">MARQUEES</a></li>
        <li><a href="discos.html">DISCOS</a></li>
        <li><a href="jaysbars.html">JAY’S BARS</a></li>
        <li><a href="equipment.html">EQUIPMENT HIRE</a></li>
        <li><img src="images/stormmachine-logo.png" alt="Storm Machine Logo"></li>
        <li><a href="gallery.html">GALLERY</a></li>
        <li><a href="information.html">INFORMATION</a></li>
        <li><a href="contact.html">CONTACT US</a></li>
      </ul>
    </nav>
  </header>

  <!-- MAIN CONTENT -->
  <main>
    <h1>Testimonials</h1>
    <p class="text-center">Fill out our contact form, or alternatively call us on <strong>01694 751380</strong></p>

    <div class="text-center my-4">
      <a href="contact.html" class="btn btn-primary">Get a Quote</a>
    </div>

    <div class="testimonial">
      <h3>“A perfect day”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">Sam & Louise</div>
    </div>

    <div class="testimonial">
      <h3>“The marquee looked magnificent”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">Peter & Hazel</div>
    </div>

    <div class="testimonial">
      <h3>“Thank you for your service”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">William & Hannah</div>
    </div>

    <div class="testimonial">
      <h3>“Superb job!”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">Ben & Holly</div>
    </div>

    <div class="testimonial">
      <h3>“The facilities were top class”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">Oscar & Charlotte</div>
    </div>

    <div class="testimonial">
      <h3>“A perfect day”</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua...</p>
      <div class="author">Sian & Abigail</div>
    </div>
  </main>

  <!-- FOOTER -->
  <footer>
    <p>Give us a call on <strong>01694 751380</strong></p>
    <p>Send us an email at <a href="mailto:info@stormmachine.co.uk">info@stormmachine.co.uk</a></p>
    <p>Or fill out our <a href="contact.html">enquiry form</a> below</p>

    <hr class="my-3" style="border-color: rgba(255,255,255,0.2);">

    <p>Follow us</p>
    <p>© STORM MACHINE 2025</p>
    <p>
      <a href="marquees.html">MARQUEES</a> •
      <a href="discos.html">DISCOS</a> •
      <a href="jaysbars.html">JAY’S BARS</a> •
      <a href="equipment.html">EQUIPMENT HIRE</a> •
      <a href="gallery.html">GALLERY</a> •
      <a href="information.html">INFORMATION</a> •
      <a href="contact.html">CONTACT US</a>
    </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>






<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Testimonials - Storm Machine Entertainment</title>

  <!-- Bootstrap 5 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Fișierul tău CSS -->
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- ===== HEADER ===== -->
  <header>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
      <div class="container">
        <a class="navbar-brand" href="index.html">Storm Machine</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item"><a class="nav-link" href="marquees.html">Marquees</a></li>
            <li class="nav-item"><a class="nav-link" href="discos.html">Discos</a></li>
            <li class="nav-item"><a class="nav-link" href="jaysbars.html">Jay’s Bars</a></li>
            <li class="nav-item"><a class="nav-link" href="equipment.html">Equipment Hire</a></li>
            <li class="nav-item"><a class="nav-link active" href="testimonials.html">Testimonials</a></li>
            <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
          </ul>
        </div>
      </div>
    </nav>
  </header>

 
  
  <script>
  const texts = document.querySelectorAll(
    '.testimonial-text, .testimonial-author, .testimonials-section p, .testimonials-section h2, .testimonials-section h3'
  );

  function revealText() {
    texts.forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) {
        el.classList.add('visible');
      }
    });
  }

  window.addEventListener('scroll', revealText);
  revealText(); // rulează și la încărcare
</script>





<script>
  // Selectăm doar textul existent în secțiunea Testimonials
  const testimonialTexts = document.querySelectorAll(
    '.testimonials-section p, .testimonials-section h2, .testimonials-section h3, .testimonials-section h5'
  );

  function revealTestimonials() {
    testimonialTexts.forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight - 100) {
        el.classList.add('visible');
      }
    });
  }

  window.addEventListener('scroll', revealTestimonials);
  revealTestimonials(); // și la încărcare
</script>


<meta name="viewport" content="width=device-width, initial-scale=1.0">



<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Storm Machine Entertainment - Evenimente</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<style>
    /* ==================================================== */
    /* 1. BAZĂ & FONT-URI */
    /* ==================================================== */
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        padding-top: 60px; /* Spațiu pentru bara fixă */
        background-color: #fff;
        color: #333;
        line-height: 1.6;
    }

    a {
        text-decoration: none;
        color: inherit;
    }

    /* ==================================================== */
    /* 2. ANTET (HEADER) & NAVIGARE */
    /* ==================================================== */
    .header {
        background-color: #000;
        color: #fff;
        padding: 5px 0;
        position: fixed;
        top: 0;
        width: 100%;
        z-index: 1000;
    }

    .navbar {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        text-transform: uppercase;
    }

    .nav-links {
        display: flex;
        align-items: center;
    }

    .nav-links a {
        padding: 0 10px;
        font-size: 13px;
        font-weight: bold;
        transition: color 0.3s;
    }

    .nav-links a:hover {
        color: #ffcc00;
    }

    .logo {
        margin: 0 30px;
        display: flex;
        align-items: center;
    }

    .logo img {
        height: 30px; 
        margin-right: 5px;
    }

    /* ==================================================== */
    /* 3. HERO SECTION */
    /* ==================================================== */
    .hero {
        position: relative;
        height: 500px; 
        background-image: url('https://www.mesteresti.ro/uploads/4400/cort-profesional-evenimente-extra-ambrus_5-m_12-m_2%2C8-m_Alb_Party_Da_Da_60-m%C2%B2_peste-50_Otel.jpeg');
        background-size: cover;
        background-position: center;
        display: flex;
        align-items: flex-end;
        justify-content: center;
        padding-bottom: 50px;
    }

    .hero-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.3);
    }

    .hero-text {
        z-index: 1;
        color: #fff;
        text-align: center;
        text-transform: uppercase;
    }

    .hero-text h1 {
        font-size: 28px;
        margin: 0;
        font-weight: 600;
    }

    .hero-text p {
        font-size: 18px;
        margin-top: 5px;
        font-weight: 300;
    }

    /* ==================================================== */
    /* 4. INTRO & CONȚINUT */
    /* ==================================================== */
    .intro-section {
        text-align: center;
        padding: 40px 20px;
        max-width: 800px;
        margin: 0 auto;
    }

    .intro-section p {
        font-size: 16px;
        line-height: 1.6;
        margin-bottom: 15px;
    }

    /* ==================================================== */
    /* 5. GRID SERVICII (Cele 6 boxuri) */
    /* ==================================================== */
    .services-grid {
        max-width: 1200px;
        margin: 20px auto;
        padding: 0 20px;
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 20px;
    }

    .service-box {
        position: relative;
        height: 250px;
        background-size: cover;
        background-position: center;
        color: #fff;
        display: flex;
        align-items: flex-start;
        padding: 20px;
        cursor: pointer;
        transition: transform 0.3s;
    }

    .service-box:hover {
        transform: scale(1.02);
    }

    .service-box-overlay {
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        background-color: rgba(0, 0, 0, 0.4);
    }

    .service-content {
        z-index: 1;
        width: 100%;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .service-content h3 {
        font-size: 20px;
        margin: 0;
        font-weight: 600;
    }

    .arrow-icon {
        font-size: 24px;
    }

    /* Stiluri specifice pentru background-urile boxurilor */
    #box-quote { background-image: url('https://eventstuff.ro/wp-content/uploads/2021/07/interior-cort-nunt-transparent.jpg'); }
    #box-marquees { background-image: url('https://www.aristocrat-events.ro/wp-content/uploads/2024/08/image01-1024x768.jpeg'); }
    #box-discos { background-image: url('https://eventstuff.ro/wp-content/uploads/2020/06/23.-corturi-pagoda-transparente-pt-nunta.jpeg'); }
    #box-bars { background-image: url('https://platform.vegas.eater.com/wp-content/uploads/sites/24/chorus/uploads/chorus_asset/file/25878196/Partage_Le_Club__SabinOrr_005_HiRes.jpg?quality=90&strip=all&crop=16.666666666667%2C0%2C66.666666666667%2C100&w=2400'); }
    #box-equipment { background-image: url('https://avantgarde.ro/wp-content/uploads/2024/04/81A_0368.jpg'); }
    #box-gallery { background-image: url('https://thepalm.ro/wp-content/uploads/2023/05/The-Palm-40.jpg'); }

    /* ==================================================== */
    /* 6. TESTIMONIALE */
    /* ==================================================== */
    .testimonials {
        text-align: center;
        padding: 60px 20px;
        background-color: #f7f7f7;
    }

    .testimonials h2 {
        color: #0d83d1;
        font-weight: 600;
    }

    .testimonial-grid {
        max-width: 800px;
        margin: 20px auto;
        display: flex;
        justify-content: space-around;
        text-align: left;
        border-bottom: 1px solid #ddd;
        padding-bottom: 30px;
    }

    .testimonial-item {
        flex-basis: 45%;
        padding: 0 20px;
    }

    .testimonial-item h4 {
        font-weight: bold;
        font-size: 16px;
        margin-bottom: 10px;
    }

    .testimonial-item p {
        font-size: 14px;
        line-height: 1.5;
    }

    .view-more-btn {
        display: inline-block;
        margin-top: 30px;
        padding: 10px 20px;
        background-color: #0d83d1;
        color: #fff;
        text-transform: uppercase;
        font-size: 14px;
        font-weight: bold;
        transition: background-color 0.3s;
    }

    .view-more-btn:hover {
        background-color: #0a6bb8;
    }

    /* ==================================================== */
    /* 7. FOOTER (SUBSOL) */
    /* ==================================================== */
    .footer {
        background-color: #333;
        color: #fff;
        padding: 30px 20px;
        text-align: center;
    }

    .footer-content {
        max-width: 1200px;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }

    .footer-info, .footer-links, .footer-social {
        flex-basis: 30%;
        text-align: left;
    }

    .footer-links {
        flex-basis: 35%;
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        max-height: 100px;
    }

    .footer-info p, .footer-links a, .footer-social a {
        font-size: 13px;
        margin: 5px 0;
        display: block;
    }

    .footer-social {
        text-align: right;
    }

    .footer-social i {
        font-size: 20px;
        margin-left: 10px;
    }

    /* ==================================================== */
    /* 8. MODALE (POP-UP) */
    /* ==================================================== */
    .modal-content {
        display: none; /* Ascuns implicit */
        position: fixed;
        z-index: 2000;
        left: 50%;
        top: 50%;
        transform: translate(-50%, -50%);
        width: 90%;
        max-width: 600px;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
        border: 1px solid #ddd;
        border-radius: 5px;
    }

    .modal-active {
        display: block;
    }

    #gallery-content {
        display: grid;
        grid-template-columns: 1fr 1fr;
        gap: 10px;
    }

    #gallery-content img {
        width: 100%;
        height: auto;
        display: block;
    }

    /* ==================================================== */
    /* MEDIA QUERIES (CSM) - Stilizare pentru Telefoane Mobile */
    /* ==================================================== */
    @media (max-width: 768px) {
        
        body {
            padding-top: 100px;
        }

        /* Navigare */
        .navbar {
            flex-direction: column;
            text-align: center;
        }
        
        .nav-links {
            width: 100%;
            margin: 5px 0;
            justify-content: center;
            flex-wrap: wrap;
        }

        .nav-links a {
            padding: 5px 8px;
            font-size: 12px;
        }

        .logo {
            margin: 10px 0;
        }

        /* Hero Section */
        .hero {
            height: 300px;
        }

        .hero-text h1 {
            font-size: 18px;
        }

        .hero-text p {
            font-size: 14px;
        }

        /* Grid-ul de Servicii (Cele 6 Boxuri) */
        .services-grid {
            grid-template-columns: 1fr;
            gap: 15px;
        }

        .service-box {
            height: 150px;
        }

        /* Testimoniale */
        .testimonial-grid {
            flex-direction: column;
            border-bottom: none;
        }
        
        .testimonial-item {
            flex-basis: 100%;
            margin-bottom: 20px;
        }

        /* Footer */
        .footer-content {
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        
        .footer-info, .footer-links, .footer-social {
            flex-basis: 100%;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .footer-links {
            max-height: none;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        
        .footer-links a {
            padding: 5px 10px;
        }
        
        .footer-social i {
            margin: 0 5px;
        }
    }
</style>


<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            // Închide toate modalele deschise (pentru siguranță)
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            
            // Activează modalul dorit
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        document.getElementById(modalId).classList.remove('modal-active');
    }

    // Închide modalul dacă utilizatorul face click în afara ferestrei modale
    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            // Verifică dacă click-ul s-a întâmplat pe fundalul modalului
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>

<head>
    <title>Titlul Paginii</title>

    <link rel="stylesheet" href="style.css">

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
</head>




<div id="bar-modal" class="modal-content">
    <h2>Lista de Băuturi (Jay's Bar)</h2>
    <div id="bar-content">
        <h3>Alcohol</h3>
        <p><strong>Wine:</strong> White, red and rosé, depending on the preferences of the guests and the season.</p>
        <p><strong>Champagne or sparkling wine:</strong> Mandatory at the beginning of the event.</p>
        <p><strong>Spirits:</strong> Vodka, whiskey, gin, rum, tequila. Liqueur, whiskey cream.</p>
        <p><strong>Low-alcohol drinks:</strong> Beer. Optional, cider.</p>
        <p><strong>Cocktails:</strong> Bitter-based, such as Campari or Aperol.</p>
        <hr>
        <h3>Non-alcoholic</h3>
        <p><strong>Water:</strong> Still and mineral.</p>
        <p><strong>Juices:</strong> Natural and carbonated.</p>
        <p><strong>Optional:</strong> Coffee (in larger quantities, about 300 coffees for a wedding of 200 people).</p>
        <hr>
        <h3>Additional recommendations</h3>
        <p>Adjust the list and quantities according to the number of guests and their preferences (if the majority are men or women). Also consider the season: in summer, rosé and white wines are more popular, and in winter, both white and red wine are preferred, along with spirits.</p>
    </div>
    <button onclick="closeModal('bar-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="quote-modal" class="modal-content">
    <h2>Solicită o Ofertă</h2>
    <p>Completați formularul de mai jos pentru a primi o ofertă personalizată.</p>
    <form>
        <input type="text" placeholder="Nume și Prenume" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <input type="email" placeholder="Adresa de email" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"><br>
        <textarea placeholder="Detalii eveniment (data, locație, număr de invitați)" style="width: 100%; padding: 10px; margin-bottom: 10px; border: 1px solid #ccc;"></textarea><br>
        <button type="submit" style="padding: 10px 20px; background-color: #0d83d1; color: white; border: none; cursor: pointer;">Trimite Solicitarea</button>
    </form>
    <button onclick="closeModal('quote-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<div id="gallery-modal" class="modal-content">
    <h2>Galerie Foto</h2>
    <div id="gallery-content">
        <img src="https://www.studiofotobucuresti.ro/wp-content/uploads/2021/09/Cabina-lux-foto-pentru-evenimente.jpg" alt="Cabina Foto">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQkFk4hyyWug_KgmPWBCa8Tc3T5lVOXolWHFg&s" alt="Decor Eveniment">
    </div>
    <button onclick="closeModal('gallery-modal')" style="margin-top: 20px; padding: 10px; cursor: pointer;">Închide</button>
</div>

<script>
    function showModal(modalId) {
        const modal = document.getElementById(modalId);
        
        if (modal) {
            document.querySelectorAll('.modal-content').forEach(m => m.classList.remove('modal-active'));
            modal.classList.add('modal-active');
        }
    }

    function closeModal(modalId) {
        const modal = document.getElementById(modalId);
        if (modal) {
            modal.classList.remove('modal-active');
        }
    }

    window.onclick = function(event) {
        document.querySelectorAll('.modal-content').forEach(modal => {
            if (event.target == modal) { 
                modal.classList.remove('modal-active');
            }
        });
    }
</script>


<script src="script.js"></script>
<script src="script.js"></script>


