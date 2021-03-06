<!DOCTYPE html>
<html lang="hu">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0,user-scalable=yes">
    <title>Felfutó sportunkról - Az e-sportról</title>
    <link id="home" rel="stylesheet" href="home.css">
    <link rel="stylesheet" media="print" href="print.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <script>
        function swapStyleSheet(sheet)
        {
          document.getElementById('home').setAttribute('href',sheet);
        }
        </script>
</head>

<body>
    <div class="homebg">
        <div class="topnav" id="myTopnav">
            <nav>
                <a class="active" href="index.html">Kezdőlap</a>
                <a href="cs.html">Counter-Strike</a>
                <a href="lol.html">League Of Legends</a>
                <a href="urlap.html">Űrlap</a>
                <a href="javascript:void(0);" class="icon" onclick="myFunction()">
                    <i class="fa fa-bars fa-lg"></i>
                </a>
            </nav>
        </div>

        <script>
            function myFunction() {
                var x = document.getElementById("myTopnav");
                if (x.className === "topnav") {
                    x.className += " responsive";
                } else {
                    x.className = "topnav";
                }
            }
        </script>
        <h1>Kezdőlap</h1>
        <p>Könnyen olvasható mód</p>
        <button id="be" onclick="swapStyleSheet('visuallyimpaired.css')">Be</button>
        <button id="ki" onclick="swapStyleSheet('home.css')">Ki</button>
        <table>
            <caption>
                <h2>E-sport játékok</h2>
                <details>
                    <summary>
                        <h3>Részletek</h3>
                    </summary>
                    A két tárgyalt e-sport játék, és a hozzájuk hasonló e-sport játékok rövid bemutatója.
                </details>
            </caption>
            <tr>
                <th colspan="2">
                    <p><a href="#hasonloLoL" class="atugrolink">Intro átugrása</a></p>
                    <p>Az elektronikus sport (röviden e-sport) résztvevői professzionális módon, versenyszerűen
                        foglalkoznak az egyes videojátékokkal, ebből fakadóan a játékos megjelölés mellett
                        e-sportolóknak is nevezik őket.</p>
                    <p>Valószínűleg a Wii játékkonzoltól ered a sport elnevezés, mert a mai e-sportot jelölő játékokban
                        nincs szinte semmi fizikai munka, nem a testi fizikummal kell teljesítenie az embernek.</p>
                    <p>Az e- az „elektronikus” szó rövidítése. Magyarországon kb. 2005-2006 óta van a köztudatban a
                        kifejezés, de csak a 2010-es évek utánra nőtte ki magát akkorára, hogy többen is elismerik e szó
                        valódi értelmét.</p>
                    <p>Ahogy a rendes sportban, itt is vannak „sportolók”, akik pár éve már rendes bejelentett
                        munkahelynek veszik ezt a tevékenységet, és fizetéssel járó bejegyzett munkahely hiányában
                        „gamer ház”-akban laknak.</p>
                    <p>Ez azt jelenti, hogy egy csapat játékosai összeköltöznek egy házba, ahol a támogatók és saját
                        maguk megépítik a felkészüléshez szükséges helyet. Itt egy normális házról van szó, ami
                        tartalmazza a kellő mennyiségű és teljesítményű számítógépet.</p>
                    <p>2017-ben az e-sport-közösség összesen mintegy 385 millió embert jelentett világszerte.</p>
                </th>
            </tr>
            <tr>
                <th scope="col"><img id="img1"
                        src="https://freepngimg.com/thumb/league_of_legends/27974-5-league-of-legends-logo-transparent-background.png"
                        alt="League of Legends logó"></th>
                <th scope="col"><img id="img2" src="https://1000logos.net/wp-content/uploads/2017/12/CSGO-Logo.png"
                        alt="CS:GO Logó"></th>
            </tr>
            <tr>
                <td>
                    <section>
                        <h3 id="hasonloLoL">Hasonló játékok: LoL</h3>
                        <p>Míg ez a kettő játék személyes kedvenceim közé tartozik, természetesen még nagyon sok
                            potenciális választás áll a játékosok előtt.</p>
                        <p>A League of Legendshez például nagyon hasonló a <em>Dota2</em>, mely nagy valószínűséggel
                            inspirálta a
                            League Of Legends készítőit, hiszen ugyan az a műfaja a két játéknak. Ezért sokszor vitába
                            is szállnak, hogy melyik a jobb, vagy az "eredeti".</p>
                        <p>Ezek mellett ugyanebben a műfajban (<a
                                href="https://en.wikipedia.org/wiki/Multiplayer_online_battle_arena"
                                target="_blank">MOBA</a>) a <em>Heroes Of The Storm</em> is nagy sikernek örvend.</p>
                        <p>A Blizzard világhírű játékfejlesztő cég, és annak ellenére is, hogy a<em>HoTS</em> nem a
                            legsikeresebb fejlesztésük, nagyot tarolt az elhivatott játékosok körében.</p>
                        <aside>
                            <p>Persze nem csak a hatalmas játékfejlesztők töltik be az egész ipart, a Hi-Rez, relatíve
                                kisebb studiótól a <em>Smite</em> és a <em>Paladins</em> is komoly hírnevre tettek szert.
                            </p>
                        </aside>
                    </section>
                </td>
                <td>
                    <section>
                        <h3 id="hasonloCS">Hasonló játékok: CS</h3>
                        <p>Természetesen aki a CS:GO-t preferálja, sem kell, hogy messzire menjen, ha alternatív játékot
                            keres.</p>
                        <p>Az egyre bővülő listában megtalálható például az egy időben rendkívül elterjedt
                            <em>Overwatch</em>.
                        </p>
                        <p>A CS által jól ismert realizmusból fel kell áldoznia a felhasználónak, ellenben cserébe
                            rendkívüli vizuális élmény kárpótolja, a választható egyedi karakterek mellett.</p>
                        <p>Megemlítésre méltó a <em>Valorant</em> is, mely alig egy éve jelent meg, ráadásul a Riot Games
                            studiótol, mely a League of Legends készítéséért ismert leginkább.</p>
                        <p>A <em>Valorant</em> az <em>Overwatch</em>-hoz hasonlóan rendkívülen vizuális élménnyel szolgál,
                            és ez a játék
                            sem szégyenkezhet a kiváló és egyedi karakterválasztási lehetősegből.</p>
                    </section>
                </td>
            </tr>
        </table>
        <footer><a href="#myTopnav" class="atugrolink">Ugrás az oldal tetejére</a></footer>
    </div>
</body>