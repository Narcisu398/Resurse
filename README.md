# Resurse
<!DOCTYPE html>
<html>
<head>
<title>Isoria României</title>
</head>
<body>

<h1>Isoria Românilor</h1>
<p>Hai să începem.</p>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: "Lato", sans-serif;}

/* Style the tab */
.tab {
  float: left;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
  width: 30%;
  height: 300px;
}

/* Style the buttons inside the tab */
.tab button {
  display: block;
  background-color: inherit;
  color: black;
  padding: 22px 16px;
  width: 100%;
  border: none;
  outline: none;
  text-align: left;
  cursor: pointer;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current "tab button" class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  float: left;
  padding: 0px 12px;
  border: 1px solid #ccc;
  width: 70%;
  border-left: none;
  height: 300px;
}
</style>
</head>
<body>

<h2>File verticale</h2>
<p>Faceți clic pe butoanele din meniul cu file:</p>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'Perioada dacică și influența romană (sec. I î.Hr. – sec. II d.Hr.)')" id="defaultOpen">Perioada dacică și influența romană (sec. I î.Hr. – sec. II d.Hr.)</button>
  <button class="tablinks" onclick="openCity(event, 'Evul Mediu (sec. IX – sec. XVI)')">Evul Mediu (sec. IX – sec. XVI)</button>
  <button class="tablinks" onclick="openCity(event, 'Epoca modernă și lupta pentru independență (sec. XIX)')">Epoca modernă și lupta pentru independență (sec. XIX)</button>
  <button class="tablinks" onclick="openCity(event, 'Secolul XX – Primul și al Doilea Război Mondial')">Secolul XX – Primul și al Doilea Război Mondial</button>
  <button class="tablinks" onclick="openCity(event, 'Epoca contemporană')">Epoca contemporană</button>
</div>

</div>

<div id="Perioada dacică și influența romană (sec. I î.Hr. – sec. II d.Hr.)" class="tabcontent">
  <h3>Perioada dacică și influența romană (sec. I î.Hr. – sec. II d.Hr.)</h3>
  <p>Dacii, sub conducerea lui Burebista și apoi a lui Decebal, au creat un regat puternic în zona Carpaților. După războaiele dacice (101-102 și 105-106 d.Hr.), Imperiul Roman a cucerit Dacia, transformând-o în provincie romană. Aceasta a adus infrastructură, cultură latină și o nouă organizare socială.<img src="c:\Users\utente\OneDrive\xbox\imagini\Trecerea_dunarii_1878.jpeg.jpeg" alt="" width="200" height="200"></p>
</div>

<div id="Evul Mediu (sec. IX – sec. XVI)" class="tabcontent">
  <h3>Evul Mediu (sec. IX – sec. XVI)</h3>
  <p>Formarea celor trei principate române: Țara Românească, Moldova și Transilvania. În această perioadă, conducători precum Ștefan cel Mare și Vlad Țepeș au luptat împotriva amenințărilor externe, în special a Imperiului Otoman. De asemenea, erau timpuri marcate de construcții de biserici și mănăstiri impresionante.</p> 
</div>

<div id="Epoca modernă și lupta pentru independență (sec. XIX)" class="tabcontent">
  <h3>Epoca modernă și lupta pentru independență (sec. XIX)</h3>
  <p>În secolul al XIX-lea, Principatele Române (Țara Românească și Moldova) s-au unit în 1859 sub domnia lui Alexandru Ioan Cuza, formând astfel România. În 1877, România și-a câștigat independența față de Imperiul Otoman.</p>
</div>
<div id="Secolul XX – Primul și al Doilea Război Mondial" class="tabcontent">
    <h3>Secolul XX – Primul și al Doilea Război Mondial</h3>
    <p>România a participat activ la ambele războaie. După Primul Război Mondial, prin Marea Unire de la 1 decembrie 1918, Transilvania, Basarabia și Bucovina s-au unit cu România. Totuși, Al Doilea Război Mondial a adus pierderi teritoriale și schimbări politice majore, inclusiv instaurarea regimului comunist.<img src="c:\Users\utente\OneDrive\xbox\imagini\R.jpeg" alt="" width="200" height="200"></p>
  </div>

  <div id="Epoca contemporană" class="tabcontent">
    <h3>Epoca contemporană</h3>
    <p>După Revoluția din 1989, care a dus la înlăturarea regimului comunist, România a trecut printr-o perioadă de tranziție către democrație. În 2007, România a aderat la Uniunea Europeană, consolidându-și locul în Europa modernă.</p>
  </div>

    
<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> ****
