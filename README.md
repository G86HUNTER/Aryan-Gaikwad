<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>TEAM SAARTHI</title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
 <style>
 body { font-family: Arial, sans-serif; color: white; background: black; overflow-x: hidden; }
 #video-background { position: fixed; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: -1; }
 .presidents img { margin: 20px; border-radius: 10px; cursor: pointer; transition: transform 0.4s, box-shadow 0.4s; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); }
 .presidents img:hover { transform: scale(1.1); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.5); }
 #back-to-top { display: none; position: fixed; bottom: 30px; right: 30px; background: lightblue; color: black; font-size: 18px; border: none; border-radius: 50%; width: 50px; height: 50px; text-align: center; cursor: pointer; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3); z-index: 999; }
 #back-to-top:hover { background: rgb(21, 45, 165); }
 .accordion { max-width: 600px; margin: auto; }
 .accordion-button { font-size: 0.9rem; padding: 8px 12px; }
 .accordion-body { font-size: 0.85rem; padding: 8px 12px; }
 .btn-active { background-color: rgb(184, 13, 161) !important; color: white !important; border: 2px solid rgb(104, 6, 86); }
 .btn-linkedin { background-color: blue !important; color: white !important; border: 2px solid blue; }
 .btn-whatsapp { background-color: rgb(23, 157, 20) !important; color: rgb(233, 241, 233) !important; border: 2px solid green; }
 </style>
</head>
<body>
 <video autoplay muted loop id="video-background">
   <source src="C:\Users\Admin\Videos\Recording imp.mp4">
   Your browser does not support the video tag.
 </video>

 <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
   <div class="container">
     <a class="navbar-brand" href="#">
       <img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144858.png" alt="Logo" width="40" height="40" class="d-inline-block align-text-top">
       <h7>TEAM SAARTHI</h7>
     </a>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarNav">
       <ul class="navbar-nav ms-auto">
         <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
         <li class="nav-item"><a class="nav-link" href="#domain">Domains</a></li>
         <li class="nav-item"><a class="nav-link" href="#Gallery">Gallery</a></li>
         <li class="nav-item"><a class="nav-link" href="#presidents">Presidents</a></li>
         <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
       </ul>
     </div>
   </div>
 </nav>

 <header class="text-center text-white py-5 mt-5">
   <h1 class="display-3">TEAM SAARTHI !!!</h1>
   <h4>THE OFFICIAL FIRST-YEAR COUNCIL OF VIT PUNE 🎓<br>CONNECTING, SUPPORTING AND EMPOWERING FRESHERS 💡</h4>
   <p id="dynamic-message" class="lead text-info"></p>
 </header>

 <section id="domain" class="container my-5">
   <h2 class="text-center text-warning">DOMAIN</h2>
   <div class="accordion" id="domainAccordion">

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExecution">Execution</button></h2>
       <div id="collapseExecution" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles event planning and logistics.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseEsports">Esports</button></h2>
       <div id="collapseEsports" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Organizes gaming events and competitions.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseMultimedia">Multimedia</button></h2>
       <div id="collapseMultimedia" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles video editing and graphic designing.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseAesthetics">Aesthetics</button></h2>
       <div id="collapseAesthetics" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages visual and creative design aspects.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePR">PR and Branding</button></h2>
       <div id="collapsePR" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles public relations and branding strategies.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSponsorship">Sponsorship</button></h2>
       <div id="collapseSponsorship" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages sponsorship and financial deals.</div></div>
     </div>

     <!-- Continue similarly for other domains, fixing data-bs-target attributes -->
   </div>
 </section>

 <section id="Gallery" class="container text-center my-5">
   <h2><center><p><a href="C:\Users\Admin\Documents\sarthi web2.html">Click here to view our Gallery!</a></p></center></h2>
 </section>

 <section id="presidents" class="container text-center my-5">
   <h2 class="text-primary">PRESIDENTS</h2>
   <div class="row presidents">
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144654.png" class="img-fluid" width="300" height="300" alt="President Varad"></div>
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144711.png" class="img-fluid" width="300" height="300" alt="President Prathamesh"></div>
   </div>
 </section>

 <section id="contact" class="container text-center my-5">
   <h3>CONTACT US</h3>
   <p>
     <a href="https://www.instagram.com/vit_pune_saarthi/" class="btn btn-active">Instagram</a>
     <a href="https://www.linkedin.com/company/saarthi-vit-pune" class="btn btn-linkedin">LinkedIn</a>
     <a href="whatsapp" class="btn btn-whatsapp">WhatsApp</a>
   </p>
 </section>

 <button id="back-to-top" class="btn btn-light">⬆</button>

 <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

 <script>
 $(document).ready(function () {
   const hours = new Date().getHours();
   const greeting = hours < 12 ? 'Good Morning!' : hours < 18 ? 'Good Afternoon!' : 'Good Evening!';
   $('#dynamic-message').text(`${greeting} Welcome to Saarthi!`);

   $(window).scroll(function () {
     if ($(this).scrollTop() > 100) {
       $('#back-to-top').fadeIn();
     } else {
       $('#back-to-top').fadeOut();
     }
   });

   $('#back-to-top').click(function () {
     $('html, body').animate({ scrollTop: 0 }, 800);
     return false;
   });
 });
 </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>TEAM SAARTHI</title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
 <style>
 body { font-family: Arial, sans-serif; color: white; background: black; overflow-x: hidden; }
 #video-background { position: fixed; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: -1; }
 .presidents img { margin: 20px; border-radius: 10px; cursor: pointer; transition: transform 0.4s, box-shadow 0.4s; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); }
 .presidents img:hover { transform: scale(1.1); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.5); }
 #back-to-top { display: none; position: fixed; bottom: 30px; right: 30px; background: lightblue; color: black; font-size: 18px; border: none; border-radius: 50%; width: 50px; height: 50px; text-align: center; cursor: pointer; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3); z-index: 999; }
 #back-to-top:hover { background: rgb(21, 45, 165); }
 .accordion { max-width: 600px; margin: auto; }
 .accordion-button { font-size: 0.9rem; padding: 8px 12px; }
 .accordion-body { font-size: 0.85rem; padding: 8px 12px; }
 .btn-active { background-color: rgb(184, 13, 161) !important; color: white !important; border: 2px solid rgb(104, 6, 86); }
 .btn-linkedin { background-color: blue !important; color: white !important; border: 2px solid blue; }
 .btn-whatsapp { background-color: rgb(23, 157, 20) !important; color: rgb(233, 241, 233) !important; border: 2px solid green; }
 </style>
</head>
<body>
 <video autoplay muted loop id="video-background">
   <source src="C:\Users\Admin\Videos\Recording imp.mp4">
   Your browser does not support the video tag.
 </video>

 <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
   <div class="container">
     <a class="navbar-brand" href="#">
       <img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144858.png" alt="Logo" width="40" height="40" class="d-inline-block align-text-top">
       <h7>TEAM SAARTHI</h7>
     </a>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarNav">
       <ul class="navbar-nav ms-auto">
         <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
         <li class="nav-item"><a class="nav-link" href="#domain">Domains</a></li>
         <li class="nav-item"><a class="nav-link" href="#Gallery">Gallery</a></li>
         <li class="nav-item"><a class="nav-link" href="#presidents">Presidents</a></li>
         <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
       </ul>
     </div>
   </div>
 </nav>

 <header class="text-center text-white py-5 mt-5">
   <h1 class="display-3">TEAM SAARTHI !!!</h1>
   <h4>THE OFFICIAL FIRST-YEAR COUNCIL OF VIT PUNE 🎓<br>CONNECTING, SUPPORTING AND EMPOWERING FRESHERS 💡</h4>
   <p id="dynamic-message" class="lead text-info"></p>
 </header>

 <section id="domain" class="container my-5">
   <h2 class="text-center text-warning">DOMAIN</h2>
   <div class="accordion" id="domainAccordion">

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExecution">Execution</button></h2>
       <div id="collapseExecution" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles event planning and logistics.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseEsports">Esports</button></h2>
       <div id="collapseEsports" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Organizes gaming events and competitions.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseMultimedia">Multimedia</button></h2>
       <div id="collapseMultimedia" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles video editing and graphic designing.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseAesthetics">Aesthetics</button></h2>
       <div id="collapseAesthetics" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages visual and creative design aspects.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePR">PR and Branding</button></h2>
       <div id="collapsePR" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles public relations and branding strategies.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSponsorship">Sponsorship</button></h2>
       <div id="collapseSponsorship" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages sponsorship and financial deals.</div></div>
     </div>

     <!-- Continue similarly for other domains, fixing data-bs-target attributes -->
   </div>
 </section>

 <section id="Gallery" class="container text-center my-5">
   <h2><center><p><a href="C:\Users\Admin\Documents\sarthi web2.html">Click here to view our Gallery!</a></p></center></h2>
 </section>

 <section id="presidents" class="container text-center my-5">
   <h2 class="text-primary">PRESIDENTS</h2>
   <div class="row presidents">
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144654.png" class="img-fluid" width="300" height="300" alt="President Varad"></div>
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144711.png" class="img-fluid" width="300" height="300" alt="President Prathamesh"></div>
   </div>
 </section>

 <section id="contact" class="container text-center my-5">
   <h3>CONTACT US</h3>
   <p>
     <a href="https://www.instagram.com/vit_pune_saarthi/" class="btn btn-active">Instagram</a>
     <a href="https://www.linkedin.com/company/saarthi-vit-pune" class="btn btn-linkedin">LinkedIn</a>
     <a href="whatsapp" class="btn btn-whatsapp">WhatsApp</a>
   </p>
 </section>

 <button id="back-to-top" class="btn btn-light">⬆</button>

 <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

 <script>
 $(document).ready(function () {
   const hours = new Date().getHours();
   const greeting = hours < 12 ? 'Good Morning!' : hours < 18 ? 'Good Afternoon!' : 'Good Evening!';
   $('#dynamic-message').text(`${greeting} Welcome to Saarthi!`);

   $(window).scroll(function () {
     if ($(this).scrollTop() > 100) {
       $('#back-to-top').fadeIn();
     } else {
       $('#back-to-top').fadeOut();
     }
   });

   $('#back-to-top').click(function () {
     $('html, body').animate({ scrollTop: 0 }, 800);
     return false;
   });
 });
 </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>TEAM SAARTHI</title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
 <style>
 body { font-family: Arial, sans-serif; color: white; background: black; overflow-x: hidden; }
 #video-background { position: fixed; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: -1; }
 .presidents img { margin: 20px; border-radius: 10px; cursor: pointer; transition: transform 0.4s, box-shadow 0.4s; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); }
 .presidents img:hover { transform: scale(1.1); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.5); }
 #back-to-top { display: none; position: fixed; bottom: 30px; right: 30px; background: lightblue; color: black; font-size: 18px; border: none; border-radius: 50%; width: 50px; height: 50px; text-align: center; cursor: pointer; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3); z-index: 999; }
 #back-to-top:hover { background: rgb(21, 45, 165); }
 .accordion { max-width: 600px; margin: auto; }
 .accordion-button { font-size: 0.9rem; padding: 8px 12px; }
 .accordion-body { font-size: 0.85rem; padding: 8px 12px; }
 .btn-active { background-color: rgb(184, 13, 161) !important; color: white !important; border: 2px solid rgb(104, 6, 86); }
 .btn-linkedin { background-color: blue !important; color: white !important; border: 2px solid blue; }
 .btn-whatsapp { background-color: rgb(23, 157, 20) !important; color: rgb(233, 241, 233) !important; border: 2px solid green; }
 </style>
</head>
<body>
 <video autoplay muted loop id="video-background">
   <source src="C:\Users\Admin\Videos\Recording imp.mp4">
   Your browser does not support the video tag.
 </video>

 <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
   <div class="container">
     <a class="navbar-brand" href="#">
       <img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144858.png" alt="Logo" width="40" height="40" class="d-inline-block align-text-top">
       <h7>TEAM SAARTHI</h7>
     </a>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarNav">
       <ul class="navbar-nav ms-auto">
         <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
         <li class="nav-item"><a class="nav-link" href="#domain">Domains</a></li>
         <li class="nav-item"><a class="nav-link" href="#Gallery">Gallery</a></li>
         <li class="nav-item"><a class="nav-link" href="#presidents">Presidents</a></li>
         <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
       </ul>
     </div>
   </div>
 </nav>

 <header class="text-center text-white py-5 mt-5">
   <h1 class="display-3">TEAM SAARTHI !!!</h1>
   <h4>THE OFFICIAL FIRST-YEAR COUNCIL OF VIT PUNE 🎓<br>CONNECTING, SUPPORTING AND EMPOWERING FRESHERS 💡</h4>
   <p id="dynamic-message" class="lead text-info"></p>
 </header>

 <section id="domain" class="container my-5">
   <h2 class="text-center text-warning">DOMAIN</h2>
   <div class="accordion" id="domainAccordion">

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExecution">Execution</button></h2>
       <div id="collapseExecution" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles event planning and logistics.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseEsports">Esports</button></h2>
       <div id="collapseEsports" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Organizes gaming events and competitions.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseMultimedia">Multimedia</button></h2>
       <div id="collapseMultimedia" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles video editing and graphic designing.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseAesthetics">Aesthetics</button></h2>
       <div id="collapseAesthetics" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages visual and creative design aspects.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePR">PR and Branding</button></h2>
       <div id="collapsePR" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles public relations and branding strategies.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSponsorship">Sponsorship</button></h2>
       <div id="collapseSponsorship" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages sponsorship and financial deals.</div></div>
     </div>

     <!-- Continue similarly for other domains, fixing data-bs-target attributes -->
   </div>
 </section>

 <section id="Gallery" class="container text-center my-5">
   <h2><center><p><a href="C:\Users\Admin\Documents\sarthi web2.html">Click here to view our Gallery!</a></p></center></h2>
 </section>

 <section id="presidents" class="container text-center my-5">
   <h2 class="text-primary">PRESIDENTS</h2>
   <div class="row presidents">
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144654.png" class="img-fluid" width="300" height="300" alt="President Varad"></div>
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144711.png" class="img-fluid" width="300" height="300" alt="President Prathamesh"></div>
   </div>
 </section>

 <section id="contact" class="container text-center my-5">
   <h3>CONTACT US</h3>
   <p>
     <a href="https://www.instagram.com/vit_pune_saarthi/" class="btn btn-active">Instagram</a>
     <a href="https://www.linkedin.com/company/saarthi-vit-pune" class="btn btn-linkedin">LinkedIn</a>
     <a href="whatsapp" class="btn btn-whatsapp">WhatsApp</a>
   </p>
 </section>

 <button id="back-to-top" class="btn btn-light">⬆</button>

 <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

 <script>
 $(document).ready(function () {
   const hours = new Date().getHours();
   const greeting = hours < 12 ? 'Good Morning!' : hours < 18 ? 'Good Afternoon!' : 'Good Evening!';
   $('#dynamic-message').text(`${greeting} Welcome to Saarthi!`);

   $(window).scroll(function () {
     if ($(this).scrollTop() > 100) {
       $('#back-to-top').fadeIn();
     } else {
       $('#back-to-top').fadeOut();
     }
   });

   $('#back-to-top').click(function () {
     $('html, body').animate({ scrollTop: 0 }, 800);
     return false;
   });
 });
 </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1">
 <title>TEAM SAARTHI</title>
 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
 <style>
 body { font-family: Arial, sans-serif; color: white; background: black; overflow-x: hidden; }
 #video-background { position: fixed; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: -1; }
 .presidents img { margin: 20px; border-radius: 10px; cursor: pointer; transition: transform 0.4s, box-shadow 0.4s; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3); }
 .presidents img:hover { transform: scale(1.1); box-shadow: 0 8px 30px rgba(0, 0, 0, 0.5); }
 #back-to-top { display: none; position: fixed; bottom: 30px; right: 30px; background: lightblue; color: black; font-size: 18px; border: none; border-radius: 50%; width: 50px; height: 50px; text-align: center; cursor: pointer; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3); z-index: 999; }
 #back-to-top:hover { background: rgb(21, 45, 165); }
 .accordion { max-width: 600px; margin: auto; }
 .accordion-button { font-size: 0.9rem; padding: 8px 12px; }
 .accordion-body { font-size: 0.85rem; padding: 8px 12px; }
 .btn-active { background-color: rgb(184, 13, 161) !important; color: white !important; border: 2px solid rgb(104, 6, 86); }
 .btn-linkedin { background-color: blue !important; color: white !important; border: 2px solid blue; }
 .btn-whatsapp { background-color: rgb(23, 157, 20) !important; color: rgb(233, 241, 233) !important; border: 2px solid green; }
 </style>
</head>
<body>
 <video autoplay muted loop id="video-background">
   <source src="C:\Users\Admin\Videos\Recording imp.mp4">
   Your browser does not support the video tag.
 </video>

 <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
   <div class="container">
     <a class="navbar-brand" href="#">
       <img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144858.png" alt="Logo" width="40" height="40" class="d-inline-block align-text-top">
       <h7>TEAM SAARTHI</h7>
     </a>
     <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
       <span class="navbar-toggler-icon"></span>
     </button>
     <div class="collapse navbar-collapse" id="navbarNav">
       <ul class="navbar-nav ms-auto">
         <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
         <li class="nav-item"><a class="nav-link" href="#domain">Domains</a></li>
         <li class="nav-item"><a class="nav-link" href="#Gallery">Gallery</a></li>
         <li class="nav-item"><a class="nav-link" href="#presidents">Presidents</a></li>
         <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
       </ul>
     </div>
   </div>
 </nav>

 <header class="text-center text-white py-5 mt-5">
   <h1 class="display-3">TEAM SAARTHI !!!</h1>
   <h4>THE OFFICIAL FIRST-YEAR COUNCIL OF VIT PUNE 🎓<br>CONNECTING, SUPPORTING AND EMPOWERING FRESHERS 💡</h4>
   <p id="dynamic-message" class="lead text-info"></p>
 </header>

 <section id="domain" class="container my-5">
   <h2 class="text-center text-warning">DOMAIN</h2>
   <div class="accordion" id="domainAccordion">

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExecution">Execution</button></h2>
       <div id="collapseExecution" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles event planning and logistics.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseEsports">Esports</button></h2>
       <div id="collapseEsports" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Organizes gaming events and competitions.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseMultimedia">Multimedia</button></h2>
       <div id="collapseMultimedia" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles video editing and graphic designing.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseAesthetics">Aesthetics</button></h2>
       <div id="collapseAesthetics" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages visual and creative design aspects.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePR">PR and Branding</button></h2>
       <div id="collapsePR" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Handles public relations and branding strategies.</div></div>
     </div>

     <div class="accordion-item">
       <h2 class="accordion-header"><button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSponsorship">Sponsorship</button></h2>
       <div id="collapseSponsorship" class="accordion-collapse collapse" data-bs-parent="#domainAccordion"><div class="accordion-body">Manages sponsorship and financial deals.</div></div>
     </div>

     <!-- Continue similarly for other domains, fixing data-bs-target attributes -->
   </div>
 </section>

 <section id="Gallery" class="container text-center my-5">
   <h2><center><p><a href="C:\Users\Admin\Documents\sarthi web2.html">Click here to view our Gallery!</a></p></center></h2>
 </section>

 <section id="presidents" class="container text-center my-5">
   <h2 class="text-primary">PRESIDENTS</h2>
   <div class="row presidents">
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144654.png" class="img-fluid" width="300" height="300" alt="President Varad"></div>
     <div class="col-md-6"><img src="C:\Users\HP\OneDrive\Pictures\Screenshots\Screenshot 2025-02-11 144711.png" class="img-fluid" width="300" height="300" alt="President Prathamesh"></div>
   </div>
 </section>

 <section id="contact" class="container text-center my-5">
   <h3>CONTACT US</h3>
   <p>
     <a href="https://www.instagram.com/vit_pune_saarthi/" class="btn btn-active">Instagram</a>
     <a href="https://www.linkedin.com/company/saarthi-vit-pune" class="btn btn-linkedin">LinkedIn</a>
     <a href="whatsapp" class="btn btn-whatsapp">WhatsApp</a>
   </p>
 </section>

 <button id="back-to-top" class="btn btn-light">⬆</button>

 <script src="https://code.jquery.com/jquery-3.6.4.min.js"></script>
 <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

 <script>
 $(document).ready(function () {
   const hours = new Date().getHours();
   const greeting = hours < 12 ? 'Good Morning!' : hours < 18 ? 'Good Afternoon!' : 'Good Evening!';
   $('#dynamic-message').text(`${greeting} Welcome to Saarthi!`);

   $(window).scroll(function () {
     if ($(this).scrollTop() > 100) {
       $('#back-to-top').fadeIn();
     } else {
       $('#back-to-top').fadeOut();
     }
   });

   $('#back-to-top').click(function () {
     $('html, body').animate({ scrollTop: 0 }, 800);
     return false;
   });
 });
 </script>
</body>
</html>
