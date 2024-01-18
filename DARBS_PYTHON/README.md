Es izveidoju programmu python valodā, kas ļauj man automatizēt procesu priekš populārāko filmu un seriālu apkopošanas. Man brīvajā laikā patīk skatīties filmas un seriālus.Tāpēc izdomāju, ka es populārākas filmas un seriālus varu apkopot excel failā ar vienu klikšķi.

Sākot projektu zināju, ka es izmantošu selenium bibliotēku, jo kursa laikā man tā likās viss interesantākā. Un tā kā man patīk filmas, domāju ka ideja būtu laba. Kā arī projektā izmantoju openpyxl bibliotēku, jo man liekas, ka tas ir ļoti labs veids, kā automatizēt procesu ar excel failiem.

1.Projekta kods sākās ar to ka es aprakstu bibliotēkas, ko izmantoju un norādu kādu pārlūk programmu izmantošu.

2.Tad es norādiju, kādu mājaslapu es izmantošu un sākās webskrāpēšana.Pirmajos soļos es atvēru menu un izvēlējos populārāko filmu sadaļu.

3.Sākumā es izveidoju divus masīvus, lai es varu saglabāt filmu nosaukumus un to reitingus atsevišķi. Viss lielākās problēmas man šājā projektā sagādāja pareiza koda izmantošana, lai atrastu pareizos elementus mājaslapā. Jo daudziem elementiem ir viens klases vārds vai ID tapēc bija diezgan ilgi jāmeklē pareizā opcija, lai dabūtu pareizos elementus no mājaslapas. Es pārsvarā izmantoju XPATH funkciju, šī funkcija bija ļoti izpalīdzīga, jo kā jau minēju bija daudz elementi ar vienādiem klašu nosaukumiem. Pagāja laiks kamēr atradu pareizo veidu kā rakstīt šo XPATH. Un tad sadaliju šo filmu nosakumus un reitingus atsevšķos masīvos.

4.Kad tika saglabāti visas filmas un reitingi, tad es ķēros klāt seriāliem. Darīju to pašu ko iepriekš, atvēru menu un aizgāju uz populārākajiem seriāliem. Un ar XPATH palīdzību savācu vajadzīgos seriālu nosaukumus un reitingus, izmantojot tādu pašu tehniku kā iepriekš. 

5.Tad kods ielādē man jau sagatavotu excel failu. Šajā excel failā izveidoju tabulu, lai saglabātie dati ir lasāmāki. Izviedoju divus diezgan vienkāršus for ciklus, vienu priekš filmām un vienu priekš sereāliem. Šajos ciklos arī norādiju kurās šūnās jāiet datiem. Filmu nosaukumi un reitingi iet dažādās kolonnās un seriālu nosaukumi ar reitingiem iet dažādās kolonnās. Un beigās excel fails tiek saglabāts. 

