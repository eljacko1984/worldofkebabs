<!DOCTYPE html>
<head>
  <title>The world of kebabs</title>
  <style>
    body {
      text-align: center;
      background-size: cover;
      background-color: white;

    }
    .tab {
  overflow: hidden;
  border: none;
  background-color: white;

}

/* Style the buttons that are used to open the tab content */
.tab button {
  background-color: inherit;
  float: center;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-family: 'Pacifico', cursive;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: white;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
  font-family: 'Pacifico', cursive;

}
.tabcontent {
  animation: fadeEffect 2s; /* Fading effect takes 2 seconds */
}

/* Go from zero to full opacity */
@keyframes fadeEffect {
  from {opacity: 0;}
  to {opacity: 1;}
}
    img {
  display:block;
  margin-left: auto;
  margin-right: auto;
  width: 20%;
  height: 60%;
  padding-bottom: 0px;
}
    a {
      color: black;
      font: bold;
      font-family: 'Pacifico', cursive;
    }
    h1 {
      color: black;
      font-family: 'Pacifico', cursive;

    }
    h3 {
      color: black;
      font-family: 'Pacifico', cursive;
      text-align: center;

    }
    p {
      color: black;
      font-family: 'Pacifico', cursive;
      text-align: left;

    }

    }

    }
    @media (max-width: 500px) {
      h1 {
        font-size: 30px;


      }


    }
  </style>
</head>
<body>

    <img src="https://images.assetsdelivery.com/compings_v2/nsit0108/nsit01082002/nsit0108200200682.jpg" alt="Kebab">
<h1>The world of Kebabs</h1>
    <!-- Tab links -->
<div class="tab">
<button class="tablinks" onclick="openTab(event, 'Home')"id="defaultOpen"><b>Home</b></button>
  <button class="tablinks" onclick="openTab(event, 'History')"><b>History</b></button>
  <button class="tablinks" onclick="openTab(event, 'National varieties')"><b>National varieties</b></button>
  <button class="tablinks" onclick="openTab(event, 'Kebab in western culture')"><b>Kebabs in western culture</b></button>
</div>

<!-- Tab content -->
<div id="Home" class="tabcontent">
<p>Kebabs are various cooked meat dishes, with their origins in Middle Eastern cuisine. Many variants are popular around the world.
<p>This website takes a brief look at the history and varities of this popular food.</p>
<p><small>The text content of this site was lovingly borrowed from the <a href="https://en.wikipedia.org/wiki/Kebab"> Wikipedia article on Kebabs</a></small></div>.
<div id="History" class="tabcontent">
  <h3>History</h3>
  <p>While the word kebab or shish kebab may sometimes be used in English as a culinary term that refers to any type of small chunks of meat cooked on a skewer, kebab is mainly associated with a diversity of meat dishes that originated in the medieval kitchens of Persia and Turkey.Though the word has ancient origins, it was popularized by Turks to refer to this range of grilled and broiled meat, which may be cooked on skewers, but also as stews, meatballs, and other forms. This cuisine has spread around the world, in parallel with Muslim influence. According to Ibn Battuta, a Moroccan traveller, kebab was served in the royal houses during the Delhi Sultanate (1206–1526 CE), and even commoners would enjoy it for breakfast with naan. Kebab dishes have been adopted and integrated with local cooking styles and innovations, from the now-ubiquitous doner kebab fast food, to the many variations of shish kebab, such as the satays of Southeast Asia.</p>

</div>

<div id="National varieties" class="tabcontent">
  <h3>National varieties</h3>
  <h4>Greece</h4>
  <p>While the history of street foods in Greece goes back to ancient times, the iconic Greek gyros and souvlaki as it is known today arose only following the Second World War. Introduced to Athens in the 1950s by immigrants from Turkey and the Middle East, gyros was originally known simply as döner kebab. It is typically served as a sandwich rolled in pita bread, or on a plate, with french fries and various salads and sauces such as tzatziki. Later in the 1960s, vendors also began selling dishes in the same style made with souvlaki, which resembles Turkish shish kebab, but is usually made with pork.</p>

<h4>India</h4>
<p>Though spit- or skewer-cooked meat dishes are noted in the Hindu text, the Mahabharata, and a Medieval Indian text, the Manasollasa, modern-day kebabs in India mostly trace their origin to the influence of Mughlai cuisine.Some varieties of kebab in India are more or less similar to kebab preparations elsewhere but with a distinctive taste, which can be credited to the use of Indian spices. Other varieties are entirely distinct versions native to India. such as Tunde ke kabab, Tikka kebab, Shami kebab, Soovar ki Saanth (pork belly kebabs from Rajasthan) and Rajpooti soolah. The prevalence of vegetarianism in much of India also means that there are many local vegetarian varieties made from Paneer or potato.</p>

<h4>Pakistan</h4>
<p>Kebabs in Pakistan trace their origin to the influence of the Mughlai cuisine.
</br>
</br>
Varieties such as sheesh, doner (known as shawarma), shammi, tikka, and other forms of roasted and grilled meats are found in Pakistan.
</br>
</br>
Pakistani cuisine has different kebabs. Meat including beef/buff, chicken, lamb and fish is used in kebabs.</p>

<h4>Turkey</h4>
<p>Kebab in Turkey encompasses not only grilled or skewered meats, but also stews and casseroles.</p>
</div>

<div id="Kebab in western culture" class="tabcontent">
  <h3>Kebabs in western culture</h3>
  <p>Kebab cuisine has spread around the world together with Muslim influence. Although non-Muslim Westerners may be increasingly familiar with some of the many other international kebab dishes, only two have become an established and widely popular part of the culture in many Western countries. In English, the word kebab commonly refers to shish kebab and, outside of North America, to döner kebab or related fast-food dishes.These dishes are also served in many other countries, where they may have different names.</p>
</div>
<script>
function openTab(evt, tabName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(tabName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
</body>
</html>
