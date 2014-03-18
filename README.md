SAMOUCZEK_HTML
==============

[Strona jsbin.com](http://jsbin.com/dirar/31/ "Enjoy")

<!DOCTYPE html>
<html> <!-- język w którym piszemy-->
<head>  <!-- głowa początek -->
  <meta charset="utf-8" />  <!-- strony kodowania -->
  <title>Samouczek html</title> <!-- tytuł po którym Google wyszukuje wyniki-->
</head> <!-- głowa koniec -->
<body bgcolor="FF9911">  <!-- ciało - tu umieszczamy wszystko co ma sie wyswietlać -->
  Podstawowymi elementami języka HTML są znaczniki. Znacznik zwykle rozpoczyna się znacznikiem otwierającym (np. < nazwa-znacznika>), a kończy znacznikiem zamykającym (np. < /nazwa-znacznika>). Atrybuty elementu są zawarte w znaczniku otwierającym (po nazwie znacznika), zawartość umieszczana jest pomiędzy znacznikiem otwierającym i zamykającym<br />
  <p align="center"><b> < nazwa-znacznika atrybut="wartość">zawartość< /nazwa-znacznika></b></p>
  <h1 id="heading1" align="center"> <font color="519548"> SAMOUCZEK HTML </font></h1> <!-- nagłówek -->
  
  Powyższy <b>nagłówek</b> można stworzyć przez znacznik <b>h1</b> (o kolorze i wypośrodkowaniu tekstu nieco później)
  
	  <h2 align="center"><font color="519548">Przez znacznik h2 uzyskujemy podtytuł może ich być do h6</font></h2>
  
    <p>Używając znacznika <b>p</b> wpisywany tekst wyświetla się <b>od nowego akapitu</b> </p> <!--paragraf czyli nowy akapit-->
      
	 <i>Znacznik <b>i</b> sprawia, że wpisywany tekst jest <b>pochylony</b></i>  <br /> 
  <br /> 
  Znacznik <b>br ze spacją i /</b> wymusza <b>koniec linii</b>  <br />
  <br />
     <b>Znacznik b sprawia, że tekst jest pogrubiony</b>  <br />
  <br />
  <b><i>Znaczniki b i i połączone ze sobą dają tekst pogrubiony i pochylony </i>  </b> <br />
  <p align="center">Wypośrodkowanie tekstu uzyskamy nadając znacznikowi atrybut align="center"</p>
  <small><b>Małe litery</b> piszemy używając znacznika <b>small</b></small> <br />  
  <br />

    Znacznik <b>ul</b> tworzy <b>liste nieuporządkowaną</b> przy czym kolejne linijki tekstu piszemy w znacznikach <b>li</b> od list item
  <ul>
	  <li>Pierwszy element listy</li>
	  <li>Drugi element listy</li>
  </ul>
  Znacznik <b>ol</b> tworzy <b>liste uporządkowaną</b>, a kolejne linijki tekstu piszemy rowniez w znaczniku <b>li</b>
  <ol>
	  <li>Pierwszy element listy</li>
	  <li>Drugi element listy</li>
	</ol>
  
W HTML można <b>zmieniać kolor tła wiersza</b> (takie zakreślanie) przez zastosowanie atrybutów takich jak <b>style = background:kolor</b> (pisząc to bez spacji) i ujmując w paragraf :<br />
  
  <p style=background:#ffffff>Białe tło</p>
  <p style=background:#000000><font color="white">Czarne tło - Biały tekst - uzyskujemy przez znacznik font atrybut color="white" - w tym przypadku</font></p>
  <p style=background:#ff0000>Czerwone tło</p>
  <p style=background:#0000ff><font color="yellow">Niebieskie tło</font></p>
  <p style=background:#00ff00>Zielone tło</p>
  <p style=background:#ffff00>Żółte tło</p>
  <br />
Oczywiście łatwiej to wszystko zrobić w CSSie, ale dobrze wiedzieć, że HTML też daje taką możliwość <br />
  <br />
  Aby utworzyć <b>link do strony</b> używamy następującej formuły:<br />
  <br />
  <b>< a href = "adres strony"> </b>nie zapomnijmy o zamknięciu znacznika <b>< /a ></b> <br />
  <br />
  Element <b> a </b> oznacza "anchor", czyli kotwica. Natomiast atrybut <b>href</b> jest skrótem od "hypertext reference", czyli odnośnik hyper tekstowy, określający dokąd prowadzi odnośnik - najczęściej adres pliku w internecie.
  <a href="http://pl.html.net/tutorials/html/"><br /><b>Tutorial, z którego korzystałam</b></a><br />
  <br />
    Odnośniki można tworzyć również do innych składnikow "ciała" strony np. do nagłówka
  <br />
  <a href="#heading1"><b>Odnośnik do nagłówka</b></a><br />
  <br />
  <p align="left"><b>Umieszczanie obrazków</b> na stronie internetowej:  <br />
  <br />
<center><img src="http://www.html4all.org/wiki/images/4/4c/HTML4ALL_logo10.jpg" width="600" height="300" style="margin-top: 10px"; title="Ucz się języka HTML"/><br />
  <br /> 
    <p align="left">Jedyne co musisz zrobić to powiedzieć przeglądarce, że chcesz umieścić obrazek (img) i gdzie obrazek jest zlokalizowany (src, skrót do "Źródła").<br />
      Istnieją trzy różne typy plików obrazków, które możesz umieścić na stronie:
<ul>
  <li align="left">GIF (Graphics Interchange Format)</li>
  <li align="left">JPG / JPEG (Joint Photographic Experts Group)</li>
  <li align="left">PNG (Portable Network Graphics)</li>
</ul>
  <p align="left">W nawiasie trójkątnym należy umieścić następujące wyrażenie: <br />
  <br />
  <b>img src="nazwa.jpg" lub "link do obrazka zamieszczonego na stronie internetowej"</b><br />
  <br />
  Wiele właciwości grafiki można ustawić za pomocą następujących atrybutów (podstawowe z nich to):
  <ul>
  <li align="left">szerokość <b>width="ilość pixeli"</b> </li>
  <li align="left">wysokość <b>height="ilość pixeli"</b></li>
  <li align="left">margines górny <b>style="margin-top:"ilość pixeli"</b>, analogicznie margines dolny - <b>margin-bottom</b>, margines lewy - <b>margin-left</b> oraz prawy - <b>margin-right</b></li>
  <li align="left">tytuł, który ukaże się po wskazaniu obrazka przez myszkę <b>title="nazwa"</b>  
  </ul> 
  </p>   
 <p align="left"> Co ciekawe <b>obrazek może być również odnośnikiem do strony internetowej.</b> Wystarczy tylko w znanej już nam formule < a href > umieścić do niego link i otrzymujemy efekt jak poniżej:</p>
<a href="http://slid.es/mtyde/dyniowe-inspiracje-kulinarne">
  <center><img src="http://cdn30.mowimyjak.smcloud.net/t/photos/t/16844/dynia-jaka-do-jedzenia-jaka-do-ozdoby_385229.jpg" title="Zobacz prezentację Dyniowe Inspiracje Kulinarne"/></a>
 
   <p align="left">Poziomą linię uzyskujemy znacznikiem <b>hr spacja /</b> właśnie tak</p>
  <hr />
  <p align="center"><small> <b>wykonała Magdalena Tyde</b></small></p>
</body>
</html>


