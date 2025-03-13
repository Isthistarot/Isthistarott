 <script>
         function changeLanguage() {
             const lang = document.getElementById("language").value;
 
             if (lang === "en") {
                 document.getElementById("title").innerHTML = "Discover the Magic of Tarot";
                 document.getElementById("intro-text").innerHTML = "Tarot readings, astrology charts, and more";
                 document.getElementById("instagram-button").innerHTML = "Contact me on Instagram";
                 document.getElementById("services-title").innerHTML = "Services";
                 document.getElementById("services-description").innerHTML = "Esoteric consultations and personalized readings for every question.";
                 document.getElementById("tarot-title").innerHTML = "Tarot Reading (30 minutes)";
                 document.getElementById("tarot-price").innerHTML = "150 RON";
                 document.getElementById("birth-chart-title").innerHTML = "Birth Chart / Astrology Analysis (3 questions + general reading)";
                 document.getElementById("birth-chart-price").innerHTML = "200 RON";
                 document.getElementById("general-reading-title").innerHTML = "General Reading";
                 document.getElementById("general-reading-price").innerHTML = "60 RON";
                 document.getElementById("ask-price").innerHTML = "Ask for the price of the reading type you want";
                 document.getElementById("contact-title").innerHTML = "Contact";
                 document.querySelector('button[type="submit"]').innerHTML = "Send Message";
             } else {
                 document.getElementById("title").innerHTML = "Descoperă Magia Tarotului";
                 document.getElementById("intro-text").innerHTML = "Citiri în tarot, analize astrologice și multe altele";
                 document.getElementById("instagram-button").innerHTML = "Contactează-mă pe Instagram";
                 document.getElementById("services-title").innerHTML = "Servicii";
                 document.getElementById("services-description").innerHTML = "Consultații esoterice și citiri personalizate pentru fiecare întrebare a ta.";
                 document.getElementById("tarot-title").innerHTML = "Citire Tarot (30 minute)";
                 document.getElementById("tarot-price").innerHTML = "150 RON";
                 document.getElementById("birth-chart-title").innerHTML = "Birth Chart / Analiză Astrologică (3 întrebări + citire generală)";
                 document.getElementById("birth-chart-price").innerHTML = "200 RON";
                 document.getElementById("general-reading-title").innerHTML = "Citire generală";
                 document.getElementById("general-reading-price").innerHTML = "60 RON";
                 document.getElementById("ask-price").innerHTML = "Întreabă prețul pentru tipul de citire dorit";
                 document.getElementById("contact-title").innerHTML = "Contact";
                 document.querySelector('button[type="submit"]').innerHTML = "Trimite mesajul";
             }
         }
     </script>
