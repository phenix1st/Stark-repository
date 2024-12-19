.header {
    background-color: #0C4A60; /* Set header color */
    color: #FFFFFF; /* Optional: Set text color for better contrast */
    padding: 20px; /* Add some padding */
    height: 80px; /* Set a fixed height for the header */
    display: flex; /* Use flexbox for alignment */
    align-items: center; /* Center items vertically */
}
.nav-link {
    display: inline-block; /* Make the link behave like a block element */
    padding: 10px 20px; /* Add padding for a button-like appearance */
    border-radius: 25px; /* Make the corners rounded */
    background-color: #F1A260; /* Set the background color */
    color: #FFFFFF; /* Set text color to white for contrast */
    transition: background-color 0.3s ease, transform 0.3s ease; /* Add transition for smooth effect */
    text-decoration: none; /* Remove underline from links */
}

.nav-link:hover {
    background-color: #D89A4D; /* Darker shade for hover effect */
    transform: scale(1.05); /* Slightly scale up on hover */
<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   STARK Portfolio
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link rel="stylesheet" href="aboutchikour.css"> 
</head>
 <body class="bg-[#0C4A60] text-white font-sans">
    <header class="header"> <!-- Updated class to 'header' -->
        <div class="flex items-center mr-8">
            <div class="text-2xl font-bold text-custom-lighter">STARK</div>
        </div>
        <nav class="flex-grow flex justify-center space-x-4">
            <a href="#Home" class="nav-link">Home</a>
            <a href="#Sponsors" class="nav-link">Sponsors</a>
            <a href="#contact" class="nav-link">Contact Me</a>
        </nav>
    </header>
  <div id="Home" class="text-center py-10">
   <h2 class="text-sm uppercase tracking-widest">
    A Bit About Me
   </h2>
   <h1 class="text-5xl font-bold text-white mt-2">
    Who Am I?
   </h1>
   <div class="mt-6">
    <img src="𝐆𝐨𝐥 𝐃_ 𝐑𝐨𝐠𝐞𝐫.jpg" alt="Portrait of a person" class="rounded-full border-4 border-[#F15A24] mx-auto" height="150" src="https://storage.googleapis.com/a1aa/image/1f5kETc5jv0VKyx5cEaFzCpCIQeZUEsCeJBcp8xAId4KbJ5nA.jpg" width="150"/>
   </div>
   <p class="mt-6 max-w-2xl mx-auto text-gray-300">
    I’m Hamdi Adem Aka "STARK", a student at ESTIN Béjaïa with a drive for innovation and problem-solving. Studying computer science and engineering, I’m passionate about technology, learning, and shaping the future. Engineering isn’t just my field—it’s my mission!
   </p>
  </div>
  <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 px-6 pb-10">
   <div class="bg-white text-black rounded-lg p-6 text-center">
    <i class="fas fa-paint-brush text-4xl text-[#F15A24] mb-4">
    </i>
    <h3 class="text-xl font-semibold text-[#F15A24]">
     Video editing
    </h3>
   </div>
   <div class="bg-white text-black rounded-lg p-6 text-center">
    <i class="fas fa-desktop text-4xl text-[#F15A24] mb-4">
    </i>
    <h3 class="text-xl font-semibold text-[#F15A24]">
     Web Design
    </h3>
   </div>
  </div>
  <div id="Sponsors" class="text-center py-10">
   <h1 class="text-5xl font-bold text-white mt-2">
    Sponsors
   </h1>
   <div class="mt-6">
    <img src="images.jpeg" alt="Portrait of a person" class="rounded-full border-4 border-[#F15A24] mx-auto" height="150" src="https://storage.googleapis.com/a1aa/image/1f5kETc5jv0VKyx5cEaFzCpCIQeZUEsCeJBcp8xAId4KbJ5nA.jpg" width="150"/>
   </div>
   <p class="mt-6 max-w-2xl mx-auto text-gray-300">
    I’m Islam Slimani, an Algerian striker with a passion for scoring goals and making history. From local streets to Europe’s biggest stages, I’ve fought hard, played harder, and delivered for my teams and my country. Football isn’t just my game—it’s my heartbeat!
   </p>
   <h1 class="text-4xl font-bold text-custom-dark">Ana Chikour ta3kom Ga3!</h1>
  </div>
  <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 px-6 pb-10">
   <div class="bg-white text-black rounded-lg p-6 text-center">
    <i class="fas fa-futbol text-4xl text-[#F15A24] mb-4">
    </i>
    <h3 class="text-xl font-semibold text-[#F15A24]">
     Football
    </h3>
   </div>
   <div class="bg-white text-black rounded-lg p-6 text-center">
    <i class="fas fa-chalkboard-teacher text-4xl text-[#F15A24] mb-4">
    </i>
    <h3 class="text-xl font-semibold text-[#F15A24]">
     Coaching
    </h3>
   </div>
  </div>
  <footer id="contact" class="footer"> <!-- Updated class to 'footer' -->
    <div class="p-4 flex flex-col justify-center items-center space-y-2"> <!-- Changed to flex-col for vertical alignment -->
        <div class="flex justify-center items-center space-x-4">
            <a href="https://www.instagram.com/ha_adex_1st/" class="text-custom-lighter"><i class="fab fa-instagram"></i></a>
        </div>
        <p class="text-custom-lighter text-center">© 2024 STARK. All rights reserved.<br>Spartax | Empowering myself since 2024</p> <!-- Added copyright notice -->
    </div>
</footer>
 </body>
</html>
