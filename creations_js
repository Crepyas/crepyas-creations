//Change title of page
document.title = "MERA by CC";

//favicon
$(window).load(function () {
    $('head').append('<link href="https://i.imgur.com/FIghj8b.png"' +
      'rel="shortcut icon" type="image/x-icon" />');
  });

//Olyvian Date Calemdar
setInterval(findOlyvianDate, 60000);

function findOlyvianDate() {
var date = new Date();
var orgn = new Date("08/08/2022");
var diff = date.getTime() - orgn.getTime();
var days = Math.floor(diff / (1000 * 3600 * 24));
var dOfM = (days % 20) + 1;
var monthNum = Math.floor((days + 19) / 20) % 9;
let mnth = "Test";
    if (monthNum === 1) { mnth = "Viorna"; }
    else if (monthNum === 2) { mnth = ":&nbsp;Jasmine"; }
    else if (monthNum === 3) { mnth = ":&nbsp;:&nbsp;:&nbsp;Alata"; }
    else if (monthNum === 4) { mnth = ":&nbsp;Tri&#239;pom"; }
    else if (monthNum === 5) { mnth = "Sanguine"; }
    else if (monthNum === 6) { mnth = "Calanthe"; }
    else if (monthNum === 7) { mnth = ":&nbsp;:&nbsp;:&nbsp;:&nbsp;Alon"; }
    else if (monthNum === 8) { mnth = ":&nbsp;Ismelia"; }
    else { mnth = "Crina"; }
var year = 900 + Math.floor(days / 180);
var dtSt = dOfM.toString(6);
var dtSt = checkTime(dtSt);
var yrSt = year.toString(6);
var cent = yrSt.substring(0, 2);
var dcad = yrSt.substring(2);
var olyvDate = cent.concat("-", dcad, " ", mnth, " ", dtSt);
document.getElementById("olyvDate").innerHTML = olyvDate;
           }

function startTime() {
  const today = new Date();
  let h = today.getHours();
  let m = today.getMinutes();
  let s = today.getSeconds();
  h = checkTime(h);
  m = checkTime(m);
  s = checkTime(s);
  document.getElementById('Time').innerHTML =  h + ":&nbsp;" + m + ":&nbsp;" + s;
  h = h.toString(6);
  m = m.toString(6);
  s = s.toString(6);
  m = checkOlyvTime(m);
  s = checkOlyvTime(s);
  document.getElementById('olyvTime').innerHTML =  h + ":" + m + ":" + s;
  setTimeout(startTime, 1000);
}
function checkTime(i) {
  if (i < 10) {i = "0" + i};  // add zero in front of numbers < 10
  return i;
}
function checkOlyvTime(i) {
  // add zeroes
  if (i.length < 3) {
    i = "0" + i;
    i = checkOlyvTime(i)};
  return i;
}

$(window).load(function(){
  $("#buttonOver").on("myOwnEvent", function(event){
    $('#buttonOver').fadeTo('slow', 0.4);
    $('#buttonOver').css('z-index', -20);
    $('#menu').fadeTo('slow', 1); });
  $(document).ready(function(){
    $("#buttonOver").trigger("myOwnEvent"); });
  //Show Lore, Hide Meta
  $("#lore").click(function(){
    $("#loreDesc").show();
    $('#lore').css("background-color","#0004");
    $("#metaDesc").hide();
    $('#meta').css("background-color","#0008"); });
  //Show Meta, Hide Lore
  $("#meta").click(function(){
    $("#metaDesc").show();
    $('#meta').css("background-color","#0004");
    $("#loreDesc").hide();
    $('#lore').css("background-color","#0008"); });

  
  $("#abtBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#About").show(); });
  $("#mapBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Map").show(); });
  $("#parBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Pairings").show(); });
  $("#olyvBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Olyvians").show(); });
  $("#dimeBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Dimensionals").show(); });
  $("#ntrlBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Naturals").show(); });
  $("#engmBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Enigmas").show(); });
  $("#termBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Terminated").show(); });
  $("#mackBtn").click(function(){
    $(".inform").hide();
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $("#infoBox").show();
    $("#Elicia").show(); });
  //close DescScreen
  $("#exit").click(function(){
    $("#descScreen").hide();
    $(".chars").css("opacity","1");
    $("#back").css("opacity","1");
    $('#name').html('');
    $('#loreDesc').html('');
    $('#metaDesc').html(''); });
  //open DescScreen
  $(".chars button").click(function(){
    $("#descScreen").show();
    $(".chars").css("opacity","0");
    $("#back").css("opacity","0");
  });
  //Close Char Indexer
  $("#infoBox span").click(function(){ $("#infoBox").hide(); });
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
//BELOW IS CHARACTER DESCRIPTIONS
  $('#SI00').click(function(title) { $('#name').html('Benny');
    $("#iMage").attr("src","https://i.imgur.com/QXuRhjt.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>Benny is the Guardian of the region of Farside. \
    A boy of many forms, she is susceptible to transformation effects, a \
    blessing and a curse for her. They have certain forms they can transform into \
    freely, but he is locked in a catgirl for the time being.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Benjamin Țepeș Crepyas</p>\
	<p>Species: Guardian</p>\
	<p>Gender: Female</p><p>Pronouns: All/Any</p><p>Age: 21</p>\
	<p>Height: 5\'1\" / 1.55m</p><p>Weight: 119lbs / 54.0kg</p>\
	<p>Eye Color: Emerald</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG00').click(function(title) {  $('#name').html('Bill');
    $("#iMage").attr("src","https://i.imgur.com/diHHs7Q.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Bill Tapec Crepyas</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 50</p>\
	<p>Height: 6\'0\" / 1.83m</p><p>Weight: 224lbs / 101.6kg</p>\
	<p>Eye Color: Aegean Blue</p><p>Hair Color: Brown</p>\
	<p>Relationship: Married, Separated</p>');  });
  $('#OG01').click(function(title) {  $('#name').html('Elizabeth');
    $("#iMage").attr("src","https://i.imgur.com/RPnTkML.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Elizabeth Alice Crepyas</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 27</p>\
	<p>Height: 5\'4\" / 1.63m</p><p>Weight: 137lbs / 62.1kg</p>\
	<p>Eye Color: Crimson</p><p>Hair Color: Jet Black</p>\
	<p>Relationship: Single</p>');  });	
  $('#OG02').click(function(title) {  $('#name').html('Scarlett');
    $("#iMage").attr("src","https://i.imgur.com/I5Qx6an.png");
	$('#descScreen').css("background-color","#d708");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Scarlett Hackett</p>\
	<p>Species: Noxa Somnian</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 18</p>\
	<p>Height: 4\'10\" / 1.47m</p><p>Weight: 78lbs / 35.4kg</p>\
	<p>Eye Color: Jade Green</p><p>Hair Color: Pumpkin</p>\
	<p>Relationship: Single</p>');  });
  $('#OG03').click(function(title) {  $('#name').html('Sunset');
    $("#iMage").attr("src","https://i.imgur.com/dZ7WxLn.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Sunset Michelle Eaves</p>\
	<p>Species: Plush Doll</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 45</p>\
	<p>Height: 1\'4\" / 0.41m</p><p>Weight: 3lb \ 1.4kg</p>\
	<p>Eye Color: Golden</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG04').click(function(title) {  $('#name').html('Ten');
    $("#iMage").attr("src","https://i.imgur.com/WzfIyq0.png");
	$('#descScreen').css("background-color","#00808088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Ten</p>\
	<p>Species: Nihilander</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 24</p>\
	<p>Height: 1\'0\" / 0.30m</p><p>Weight: 9lbs / 4.1kg</p>\
	<p>Eye Color: Dark Cyan</p><p>Hair Color: Charcoal</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG05').click(function(title) {  $('#name').html('Jay');
    $("#iMage").attr("src","https://i.imgur.com/EvL2TUX.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Jay Booker</p>\
	<p>Species: Guardian</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 36</p>\
	<p>Height: 5\'7\" / 1.70m</p><p>Weight: 163lbs / 73.9kg</p>\
	<p>Eye Color: Brown</p><p>Hair Color: Dark Auburn</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0A').click(function(title) {  $('#name').html('Astor');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#0008");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Astor</p>\
	<p>Species: Celestial</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 6\'4\" / 1.93m</p><p>Weight: 172lbs / 78.0kg</p>\
	<p>Eye Color: White</p><p>Hair Color: Fire Orange</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0B').click(function(title) {  $('#name').html('Lana');
    $("#iMage").attr("src","https://i.imgur.com/B4ZuunJ.png");
	$('#descScreen').css("background-color","#00f8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Lana Brooke Waters</p>\
	<p>Species: Lamia</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 19</p>\
	<p>Height: 5\'8\" / 1.73m</p><p>Weight: 122lbs / 55.3kg</p>\
	<p>Eye Color: Ocean Blue</p><p>Hair Color: Ocean Blue</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0C').click(function(title) {  $('#name').html('Promise');
    $("#iMage").attr("src","https://i.imgur.com/dUvw30B.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Promise Elise Scordato</p>\
	<p>Species: Ghost</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 247</p>\
	<p>Height: 4\'10\" / 1.47m</p><p>Weight: N/A</p>\
	<p>Eye Color: Green</p><p>Hair Color: Gray</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG0E').click(function(title) {  $('#name').html('Pyra');
    $("#iMage").attr("src","https://i.imgur.com/VDeAric.png");
	$('#descScreen').css("background-color","#ffa4a488");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Pyra</p>\
	<p>Species: Vampire</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 86</p>\
	<p>Height: 5\'1\" / 1.55m</p><p>Weight: 103lbs / 46.7kg</p>\
	<p>Eye Color: Magenta</p><p>Hair Color: Pink</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0H').click(function(title) {  $('#name').html('Ellys');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00800088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Ellys</p>\
	<p>Species: Diesa Somnian</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 32</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0I').click(function(title) {  $('#name').html('Lillian');
    $("#iMage").attr("src","https://i.imgur.com/8rYJE0H.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Lillian Marie Wicke</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 48</p>\
	<p>Height: 5\'7\" / 1.70m</p><p>Weight: 154lbs / 69.9kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Black/White</p>\
	<p>Relationship: Single</p>');  });
  $('#OG0J').click(function(title) {  $('#name').html('Arachnophobia');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00800088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Phobi Anne Eaves</p>\
	<p>Species: Diesa Somnian</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 24</p>\
	<p>Height: 5\'0\" / 1.52m</p><p>Weight: 116lbs / 52.6kg</p>\
	<p>Eye Color: Emerald Green</p><p>Hair Color: Platinum Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG10').click(function(title) {  $('#name').html('Tic-Toc');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00800088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Bookie Archimedes Gears</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 33</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG11').click(function(title) {  $('#name').html('Corrine');
    $("#iMage").attr("src","https://i.imgur.com/l2XNC4I.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Corrine Renée Pepper</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 19</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Cyan</p><p>Hair Color: Black</p>\
	<p>Relationship: Single</p>');  });
  $('#OG12').click(function(title) {  $('#name').html('Lazarus');
    $("#iMage").attr("src","https://i.imgur.com/CJSCID0.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Lazarus Lane</p>\
	<p>Species: Celestial</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Yellow</p><p>Hair Color: Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG13').click(function(title) {  $('#name').html('Maurus');
    $("#iMage").attr("src","https://i.imgur.com/bMSLrNZ.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Maurus</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 62</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });
  $('#OG14').click(function(title) {  $('#name').html('Wail');
    $("#iMage").attr("src","https://i.imgur.com/9r9Zqxy.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Evan Brytchel</p>\
	<p>Species: Diesa Somnian</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 34</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Gold</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG15').click(function(title) {  $('#name').html('Amaryllis');
    $("#iMage").attr("src","https://i.imgur.com/DzEFWgW.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Amaryllis Willow Eaves</p>\
	<p>Species: Diesa Somnian</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 31</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Emerald Green/Grey</p><p>Hair Color: Platinum Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG1A').click(function(title) {  $('#name').html('Mia');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#ffa4a488");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Mia Cross</p>\
	<p>Species: Plush</p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });
  $('#OG1B').click(function(title) {  $('#name').html('Grant');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00808088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Granite Stone</p>\
	<p>Species: Stoneheart</p>\
	<p>Gender: Non-Binary</p><p>Pronoun: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });
  $('#OG1C').click(function(title) {  $('#name').html('Jenny');
    $("#iMage").attr("src","https://i.imgur.com/704jADi.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Jem Stone</p>\
	<p>Species: Stoneheart</p>\
	<p>Gender:Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: Purple</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG1E').click(function(title) {  $('#name').html('Storm');
    $("#iMage").attr("src","https://i.imgur.com/6HpyfiN.png");
	$('#descScreen').css("background-color","#eee8");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Storm</p>\
	<p>Species: Celestial</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blue-Grey</p><p>Hair Color: White</p>\
	<p>Relationship: Single</p>');  });
  $('#OG1F').click(function(title) {  $('#name').html('Toxin');
    $("#iMage").attr("src","https://i.imgur.com/DmnzBql.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Toxin Thomas</p>\
	<p>Species: Nihilander</p>\
	<p>Gender: Hermephrodite</p><p>Pronouns: She/Her</p><p>Age: 18</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Sea Green</p><p>Hair Color: Crimson</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG1G').click(function(title) {  $('#name').html('Mute');
    $("#iMage").attr("src","https://i.imgur.com/md6w8jh.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Maxime Winfield</p>\
	<p>Species: Diesa Somnian</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 27</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Snow White</p>\
	<p>Relationship: Single</p>');  });
  $('#OG1H').click(function(title) {  $('#name').html('Alissa');
    $("#iMage").attr("src","https://i.imgur.com/F3VOYon.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Alissa Caramel Harper</p>\
	<p>Species: Custard Foodfolk</p>\
	<p>Gender: Non-Binary</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Milk Chocolate</p><p>Hair Color: Dutch Vanilla</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG1I').click(function(title) {  $('#name').html('Alice');
    $("#iMage").attr("src","https://i.imgur.com/bL57pGR.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Alice Cecelia Harper</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 43</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amber</p><p>Hair Color: Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG1J').click(function(title) {  $('#name').html('Felicity');
    $("#iMage").attr("src","https://i.imgur.com/2RYYWBQ.png");
	$('#descScreen').css("background-color","#d708");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Felicity</p>\
	<p>Species: Nihilander</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 28</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Hazel</p><p>Hair Color: Harvest Gold</p>\
	<p>Relationship: Single</p>');  });
  $('#OG20').click(function(title) {  $('#name').html('Sunny');
    $("#iMage").attr("src","https://i.imgur.com/A2V3Whj.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Sunny Couture</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 22</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Gold</p>\
	<p>Relationship: Single</p>');  });
  $('#OG21').click(function(title) {  $('#name').html('Tsuretsu');
    $("#iMage").attr("src","https://i.imgur.com/Afu8Y6z.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Tsuretsu Nagi</p>\
	<p>Species: Lamia</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 37</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Gold</p><p>Hair Color: Willow Green</p>\
	<p>Relationship: Dating</p>');  });
  $('#OG22').click(function(title) {  $('#name').html('Wulfric');
    $("#iMage").attr("src","https://i.imgur.com/7hXqohG.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Wulfric Geoht</p>\
	<p>Species: Draconian</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 36</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Lavender</p>\
	<p>Relationship: Single</p>');  });
  $('#OG23').click(function(title) {  $('#name').html('Hara');
    $("#iMage").attr("src","https://i.imgur.com/IVMO6AM.png");
	$('#descScreen').css("background-color","#ffa4a488");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Hara</p>\
	<p>Species: Floran</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her/p><p>Age: 23</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Salmon Pink</p><p>Hair Color: Salmon Pink</p>\
	<p>Relationship: Single</p>');  });
  $('#OG24').click(function(title) {  $('#name').html('Rita');
    $("#iMage").attr("src","https://i.imgur.com/Qa8a4NH.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Rita Quijada</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 23</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Baja Blast Blue</p><p>Hair Color: Taco Bell Purple</p>\
	<p>Relationship: Single</p>');  });
  $('#OG25').click(function(title) {  $('#name').html('Dreithyr');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00800088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Dreithyr Tyraan</p>\
	<p>Species: Hydra</p>\
	<p>Gender: Male</p><p>Pronouns: They/Them (Plural)</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Widowed</p>');  });
  $('#OG2A').click(function(title) {  $('#name').html('Liesl');
    $("#iMage").attr("src","https://i.imgur.com/wgjYjgW.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Liesl Adelais Tyraan</p>\
	<p>Species: Dragonborn</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 19</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Scarlet</p><p>Hair Color: Light Brown</p>\
	<p>Relationship: Single</p>');  });
  $('#OG2B').click(function(title) {  $('#name').html('Charles');
    $("#iMage").attr("src","https://i.imgur.com/us1oYOl.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Charles Alder Pepper</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 49</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Red</p>\
	<p>Relationship: Married</p>');  });
  $('#OG2C').click(function(title) {  $('#name').html('Holly');
    $("#iMage").attr("src","https://i.imgur.com/yHJZb3G.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Holland Shelley</p>\
	<p>Species: Nihilander</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 31</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG2D').click(function(title) {  $('#name').html('Douglas');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#0008");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Douglas Grayson</p>\
	<p>Species: Nihilander</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 44</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: White</p><p>Hair Color: Bluish-White</p>\
	<p>Relationship: Single</p>');  });
  $('#OG2E').click(function(title) {  $('#name').html('Osmund');
    $("#iMage").attr("src","https://i.imgur.com/NAhEhcR.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Osmund Bradley</p>\
	<p>Species: Skeleton</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 281</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: N/A</p><p>Hair Color: N/A</p>\
	<p>Relationship: Single</p>');  });
  $('#OG2F').click(function(title) {  $('#name').html('Agora');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#0008");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Agora</p>\
	<p>Species: Elf</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 45</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });
  $('#OG2G').click(function(title) {  $('#name').html('Mont&#233;s');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#d708");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p> </p>\
	<p>Species: Leonin</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 24</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });
  $('#OG2H').click(function(title) {  $('#name').html('Aden');
    $("#iMage").attr("src","https://i.imgur.com/hYG0NHd.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Aden</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 30</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amethyst</p><p>Hair Color: Dirty Blonde</p>\
	<p>Relationship: Single</p>');  });
  $('#OG2I').click(function(title) {  $('#name').html('Avery');
    $("#iMage").attr("src","https://i.imgur.com/jXLp0E0.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Avery</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 29</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 144lbs / 00.0kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Sheep Wool White</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG2J').click(function(title) {  $('#name').html('Roosevelt');
    $("#iMage").attr("src","https://i.imgur.com/MZLxZ7t.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Roosvelt Madison Cleveland</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 37</p>\
	<p>Height: 5\'2\" / 1.57m</p><p>Weight: 144lbs / 65.3kg</p>\
	<p>Eye Color: Crimson</p><p>Hair Color: Crimson/White Dots</p>\
	<p>Relationship: Married</p>');  });     
  $('#OG30').click(function(title) {  $('#name').html('Bandai');
    $("#iMage").attr("src","https://i.imgur.com/6Xuwou6.png");
	$('#descScreen').css("background-color","#00f8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Bandai Oliver</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 27</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Denim Blue</p><p>Hair Color: Leather Black</p>\
	<p>Relationship: Dating</p>');  });     
  $('#OG31').click(function(title) {  $('#name').html('Adelaide');
    $("#iMage").attr("src","https://i.imgur.com/HM15ev8.png");
	$('#descScreen').css("background-color","#00f8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Adelaide Wicke</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 20</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Bright Dark Blue</p><p>Hair Color: Dark Cherry Red</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG32').click(function(title) {  $('#name').html('Im');
    $("#iMage").attr("src","https://i.imgur.com/B9Cep9g.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Im Daiki</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 43</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Cherry Red</p><p>Hair Color: Grey</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG33').click(function(title) {  $('#name').html('Cyan');
    $("#iMage").attr("src","https://i.imgur.com/7iPeHjX.png");
	$('#descScreen').css("background-color","#00808088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Aphroditus</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 19</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Vibrant Rainbows</p><p>Hair Color: Night Black</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG34').click(function(title) {  $('#name').html('Penelope');
    $("#iMage").attr("src","https://i.imgur.com/DdeVdR4.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Penelope Giroux</p>\
	<p>Species: Inkira Scylles</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 38</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Purple</p><p>Hair Color: Yellow</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG35').click(function(title) {  $('#name').html('Chardonnay');
    $("#iMage").attr("src","https://i.imgur.com/m1eNa1C.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Chardonnay</p>\
	<p>Species: Infernal</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Cyan/Lavender</p><p>Hair Color: Charcoal</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG3A').click(function(title) {  $('#name').html('Cosette');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#ffa4a488");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Cosette</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>\
	<p>Relationship: Single</p>');  });     
  $('#OG3B').click(function(title) {  $('#name').html('Amber');
    $("#iMage").attr("src","https://i.imgur.com/0tHW8Kd.png");
	$('#descScreen').css("background-color","#d708");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Amber</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 25</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amber</p><p>Hair Color: Amber</p>\
	<p>Relationship: Married</p>');  });     
  $('#OG3C').click(function(title) {  $('#name').html('Arael');
    $("#iMage").attr("src","https://i.imgur.com/a6tsH6p.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Arael</p>\
	<p>Species: Infernal</p>\
	<p>Gender: Non-Binary</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blood Red</p><p>Hair Color: Dirty White</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG3D').click(function(title) {  $('#name').html('Akari');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#ff08");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Akari</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 12</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Scarlett</p><p>Hair Color: Scarlett</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG3E').click(function(title) {  $('#name').html('Karmen');
    $("#iMage").attr("src","https://i.imgur.com/YND1hai.png");
	$('#descScreen').css("background-color","#00f8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Kylie Bell</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Cyan</p><p>Hair Color: Royal Blue</p>\
	<p>Relationship: Single</p>');  });     
  $('#OG3F').click(function(title) {  $('#name').html('Mera');
    $("#iMage").attr("src","https://i.imgur.com/89pwkN9.png");
	$('#descScreen').css("background-color","#00f8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Mera Crepyas</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 47</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Brown</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });     
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  
//   Media-Based - Enigmas
  $('#MD00').click(function(title) {  $('#name').html('Bulba');
    $("#iMage").attr("src","https://i.imgur.com/g4pABMM.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Bulba Pikk</p>\
	<p>Species: Bulbmin</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 23</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Varies</p><p>Hair Color: Varies</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD01').click(function(title) {  $('#name').html('Miyako');
    $("#iMage").attr("src","https://i.imgur.com/bh8jSAs.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Miyako Himura</p>\
	<p>Species: Octoling</p>\
	<p>Gender: Non-Binary</p><p>Pronouns: She/Her</p><p>Age: 33</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Pale Brown</p><p>Hair Color: Rust Red</p>\
	<p>Relationship: Married</p>');  });     
  $('#MD02').click(function(title) {  $('#name').html('Shigatsu');
    $("#iMage").attr("src","https://i.imgur.com/WQoHOyp.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Shigatsu</p>\
	<p>Species: Yoshi</p>\
	<p>Gender: Non-Binary</p><p>Pronouns: She/Her</p><p>Age: 36</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Black</p><p>Hair Color: Black/Red</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD03').click(function(title) {  $('#name').html('Darkling [F]');
    $("#iMage").attr("src","https://i.imgur.com/k6c2XzD.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Darkling</p>\
	<p>Species: Darkling</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amber</p><p>Hair Color: Imperial Purple</p>\
	<p>Relationship: Dating</p>');  });     
  $('#MD04').click(function(title) {  $('#name').html('Darkling [M]');
    $("#iMage").attr("src","https://i.imgur.com/4lCMtFq.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Darkling</p>\
	<p>Species: Darkling</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amber</p><p>Hair Color: Imperial Purple</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD05').click(function(title) {  $('#name').html('Tiko');
    $("#iMage").attr("src","https://i.imgur.com/sKxgl3U.png");
	$('#descScreen').css("background-color","#ff08");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Tiko</p>\
	<p>Species: Mawile</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: </p>\
	<p>Height: 4\'0\" / 1.22m</p><p>Weight: 104.3lbs / 47.3kg</p>\
	<p>Eye Color: Ruby Red</p><p>Hair Color: Black</p>\
	<p>Relationship: Dating</p>');  });     
  $('#MD0A').click(function(title) {  $('#name').html('Anima');
    $("#iMage").attr("src","https://i.imgur.com/woa0rLE.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Anima</p>\
	<p>Species: Shedinja</p>\
	<p>Gender: Unknown</p><p>Pronouns: Any</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Grey</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0B').click(function(title) {  $('#name').html('Blake');
    $("#iMage").attr("src","https://i.imgur.com/9QVqE1x.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Blake</p>\
	<p>Species: Umbreon</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Black</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0C').click(function(title) {  $('#name').html('Cassidy');
    $("#iMage").attr("src","https://i.imgur.com/MXUA6bp.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Cassidy</p>\
	<p>Species: Gardevoir</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Green</p>\
	<p>Relationship: Dating</p>');  });     
  $('#MD0D').click(function(title) {  $('#name').html('Marshall');
    $("#iMage").attr("src","https://i.imgur.com/wQgeE4G.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Marshall</p>\
	<p>Species: Rattata</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Deep Blue</p><p>Hair Color: Moss Green</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0E').click(function(title) {  $('#name').html('Chimera');
    $("#iMage").attr("src","https://i.imgur.com/IEL8CCZ.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Chimera/"Hime"</p>\
	<p>Species: </p>\
	<p>Gender: Any</p><p>Pronouns: They/Them</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Yellow</p><p>Hair Color: Bone White</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0F').click(function(title) {  $('#name').html('Kagura');
    $("#iMage").attr("src","https://i.imgur.com/1sVGFHi.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Kagura</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 18</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Amber</p><p>Hair Color: Black</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0G').click(function(title) {  $('#name').html('Shem');
    $("#iMage").attr("src","https://i.imgur.com/O23I9BY.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Shem Guy</p>\
	<p>Species: Shy Guy</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: ???</p><p>Hair Color: ???</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0H').click(function(title) {  $('#name').html('Phina');
    $("#iMage").attr("src","https://i.imgur.com/hBX6ayT.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Phina</p>\
	<p>Species: Phanto</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Black</p><p>Hair Color: White</p>\
	<p>Relationship: Dating</p>');  });     
  $('#MD0I').click(function(title) {  $('#name').html('Emii');
    $("#iMage").attr("src","https://i.imgur.com/TB4OdtF.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Emii</p>\
	<p>Species: Half-Yoshi</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 18</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Green</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD0J').click(function(title) {  $('#name').html('Gianna');
    $("#iMage").attr("src","https://i.imgur.com/uptCLlw.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Gianna</p>\
	<p>Species: Goomba</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 29</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Hazel</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD10').click(function(title) {  $('#name').html('Jai');
    $("#iMage").attr("src","https://i.imgur.com/0gtqwgV.png");
	$('#descScreen').css("background-color","#eee8");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Jai</p>\
	<p>Species: Duplighost</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: White</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD11').click(function(title) {  $('#name').html('Lyndon');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#80008088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Lyndon</p>\
	<p>Species: Lava Piranha</p>\
	<p>Gender: None</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: N/A</p><p>Body Color: Purple</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD12').click(function(title) {  $('#name').html('Dusky');
    $("#iMage").attr("src","https://i.imgur.com/tgqNtUl.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Dusky</p>\
	<p>Species: Duskull</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Black</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD13').click(function(title) {  $('#name').html('Mortimer');
    $("#iMage").attr("src","https://i.imgur.com/Ifc42yJ.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Mortimer</p>\
	<p>Species: Gengar</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red</p><p>Hair Color: Purple</p>\
	<p>Relationship: Single</p>');  });     
  $('#MD14').click(function(title) {  $('#name').html('Valkyrie');
    $("#iMage").attr("src","https://i.imgur.com/EdPu2CV.png");
	$('#descScreen').css("background-color","#00808088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Valkyrie Rikimaru</p>\
	<p>Species: Inkling</p>\
	<p>Gender: Any</p><p>Pronouns: She/Her</p><p>Age: 23</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red/Green</p><p>Hair Color: Parakeet Blue</p>\
	<p>Relationship: Single</p>');  });
  $('#MD15').click(function(title) {  $('#name').html('William');
    $("#iMage").attr("src","https://i.imgur.com/SOH1Jmm.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>William Orsen</p>\
	<p>Species: Human</p>\
	<p>Gender: Male</p><p>Pronouns: He/Him</p><p>Age: 20</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Brown</p><p>Hair Color: Brown</p>\
	<p>Relationship: Single</p>');  });
$('#MD1A').click(function(title) {  $('#name').html('Enn&#233;a');
    $("#iMage").attr("src","https://i.imgur.com/AEzobv9.png");
	$('#descScreen').css("background-color","#6668");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Enn&#233;a</p>\
	<p>Species: CPU Goddess</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Red/Blue</p><p>Hair Color: White</p>\
	<p>Relationship: Single</p>');  });
  $('#MD1B').click(function(title) {  $('#name').html('Aoringo');
    $("#iMage").attr("src","https://i.imgur.com/cujhakk.jpg");
	$('#descScreen').css("background-color","#00800088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Aoringo</p>\
	<p>Species: Yoshi</p>\
	<p>Gender: Non-Binary</p><p>Pronouns: He/Him</p><p>Age: ???</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Black</p><p>Yoshi Color: Purple</p>\
	<p>Relationship: Single</p>');  });
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  
//   Terminated
  $('#PM00').click(function(title) {  $('#name').html('Olyvia');
    $("#iMage").attr("src","https://i.imgur.com/b0SO0LS.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Olivia</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>');  });
  $('#PM0D').click(function(title) {  $('#name').html('Layla');
    $("#iMage").attr("src","https://i.imgur.com/UAUOkiM.jpg");
	$('#descScreen').css("background-color","#eee8");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Layla</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>');  });
  $('#PM0E').click(function(title) {  $('#name').html('Zuzu');
    $("#iMage").attr("src","https://i.imgur.com/EebFyDR.jpg");
	$('#descScreen').css("background-color","#80008088");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Zuzu</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>');  });
  $('#PM0F').click(function(title) {  $('#name').html('Mindy');
    $("#iMage").attr("src","https://i.imgur.com/BgvKPLO.png");
	$('#descScreen').css("background-color","#7418");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Mindy</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>');  });
  $('#PM0G').click(function(title) {  $('#name').html('Poison');
    $("#iMage").attr("src","https://i.imgur.com/gA9FQng.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Poison Thomas</p>\
	<p>Species: </p>\
	<p>Gender: </p><p>Pronouns: </p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: </p><p>Hair Color: </p>');  });
  $('#PM0H').click(function(title) {  $('#name').html('Shantae');
    $("#iMage").attr("src","https://i.imgur.com/MAiNMJB.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&copy; Shantae belongs to WayFoward.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Shantae</p>\
	<p>Species: Half-Genie</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: </p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Blue</p><p>Hair Color: Purple</p>');  });
  $('#PM0I').click(function(title) {  $('#name').html('Maeve');
    $("#iMage").attr("src","https://i.imgur.com/EsnBiAv.png");
	$('#descScreen').css("background-color","#f008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Maeve Wendy Carver</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 22</p>\
	<p>Height: 5\'5\" / 1.65m</p><p>Weight: 136lbs / 61.7kg</p>\
	<p>Eye Color: Dark Amber</p><p>Hair Color: Dark Brown</p>');  });
  $('#PM0J').click(function(title) {  $('#name').html('Elicia [Fox]');
    $("#iMage").attr("src","https://i.imgur.com/JwlsZfJ.png");
	$('#descScreen').css("background-color","#0008");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Elicia [Fox]</p>\
	<p>Species: Kitsune</p>\
	<p>Gender: Futanari</p><p>Pronouns: She/Her</p><p>Age: 27</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 00.0kg</p>\
	<p>Eye Color: N/A</p><p>Hair Color: N/A</p>');  });
  $('#PM10').click(function(title) {  $('#name').html('Ebony');
    $("#iMage").attr("src","https://i.imgur.com/nSW3htY.jpg");
	$('#descScreen').css("background-color","#0008");
    $('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Ebony Bones</p>\
	<p>Species: Genie</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 20</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Pale Purple</p><p>Hair Color: Pale Purple</p>');  });
  $('#PM11').click(function(title) {  $('#name').html('Benni');
    $("#iMage").attr("src","https://i.imgur.com/3gCemUc.png");
	$('#descScreen').css("background-color","#80008088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Benni Mack</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 26</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 0.0kg</p>\
	<p>Eye Color: Emerald Green</p><p>Hair Color: Amethyst Purple</p>');  });
  $('#PM12').click(function(title) {  $('#name').html('Kelly');
    $("#iMage").attr("src","https://i.imgur.com/ZSNLSIO.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Kelly Memoire</p>\
	<p>Species: Human</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her</p><p>Age: 21</p>\
	<p>Height: 5\'8\" / 1.73m</p><p>Weight: 137lbs / 62.1kg</p>\
	<p>Eye Color: Light Green</p><p>Hair Color: Light Green</p>');  });
  $('#PM14').click(function(title) {  $('#name').html('Candice');
    $("#iMage").attr("src","https://i.imgur.com/K8uFgDS.png");
	$('#descScreen').css("background-color","#00800088");
	$('#loreDesc').html('<p>&nbsp;This is a test paragraph. Text-Align.</p>');
    $('#metaDesc').html('<p>Full Name:</p><p>Candice</p>\
	<p>Species: Inkling</p>\
	<p>Gender: Female</p><p>Pronouns: She/Her </p><p>Age: ??</p>\
	<p>Height: 0\'0\" / 0.00m</p><p>Weight: 0lbs / 00.0kg</p>\
	<p>Eye Color: Light Slate</p><p>Hair Color: Green-Cyan</p>');  });
});
//~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
//   Elicia's
