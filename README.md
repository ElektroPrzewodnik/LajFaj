<img src="https://raw.githubusercontent.com/ElektroPrzewodnik/LajFaj/gh-pages/intro.png" alt="" />
<br />

# Specyfikacja

<ul>
<li>ESP-WROOM-02

<ul>
<li>32 bitowy mikrokontroler oparty na chipie ESP8266</li>
<li>Taktowanie: 160 MHz</li>
<li>Pamięć Flash 4 MB</li>
</ul></li>

<li>Zasilanie
<ul>
<li>Li-pol - 3,7 V</li>
<li>Gniazdo microUSB - 5 V</li>
<li>Gniazdo DC jack / uchwyty na krokodylki – od 3 V do 18 V</li>
</ul></li>

<li>Standard WiFi 802.11 b/g/n (2,4 GHz)</li>
<li>Napięcie pracy wyprowadzeń: 3,3 V</li>
<li>Ilość pinów GPIO: 12</li>
<li>Interfejsy I2C, SPI, UART</li>
<li>8 multipleksowanych wejść analogowych (0 – 1 V)</li>
<li>Wbudowany moduł ładujący lipol</li>
<li>Wbudony czytnik kart pamięci microSD / microSDHC</li>
<li>Wbudowany programator</li>
<li>Gniazdo akumulatora JST 2,0 mm</li>
<li>Przycisk reset</li>
<li>Wymiary: 103x54x13 mm</li>
</ul>

# Instrukcja instalacji
<ol>
<li>Pobierz i zainstaluj środowisko Arduino IDE ze strony: www.arduino.cc</li>
<li>Uruchom Arduino IDE, wybierz Plik -> Preferencje</li>
<li>W miejscu Dodatkowe adresy URL dla menadżera płytek podaj:
https://raw.githubusercontent.com/ElektroPrzewodnik/LajFaj/gh-pages/package_LajFaj_index.json</li>
<li>Wybierz Narzędzia -> Płytka -> Menadżer płytek</li>
<li>Zainstaluj moduł ElektroPrzewodnik ŁajFaj (prawdopodobnie na dole listy)</li>
<li>Od tej pory płytka ŁajFaj będzie już dostępna z Menu: Narzędzia -> Płytka</li>
<li>Przykładowy program znajdziesz w Plik -> Przykłady -> ElektroPrzewodnik ŁajFaj -> blink</li>
</ol>

# Dokumentacja
Sczegółowy opis dostępnych funkcji można znaleźć pod adresem:<br />
https://github.com/esp8266/Arduino#documentation
<br /><br >
Należy posługiwać się oznaczeniami pinów opisanymi na płytce tj. D0, D1, D2 itd.<br />
Przykładowa funkcja: <i>digitalWrite(D1, HIGH);</i>
