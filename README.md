# Pravna-informatika
Pokretanje programa nije neophodno. Rezultujući csv fajlovi i obučeni modeli su prisutni, a takođe, postoje output-i za svaku ćeliju u .ipynb fajlovima, koji govore šta se desilo prilikom izvršavanja određene ćelije.

Uputstvo za korišćenje:
 - Prvo ispokretati redom ćelije u fajlu Izdvajanje rečenica.ipynb. Ovime se dobija csv fajl u kome su presude razbijene na rečenice koji se dalje koristi.
 - Zatim je moguće redom pokretati ćelije u Obucavanje i klasterizacija.ipynb fajlu sve do klasterizacije. Ovde se obučava model koji klasifikuje rečenice na argumentativne (1) i ne-argumentativne (0). 
 - Nakon toga, mogu se pokrenuti ćelije u fajlu Spajanje rečenica sa argumentima.ipynb. U ovom fajlu se rečenice koje sadrže argumente (lable = 1) dele na osnovu zareza i dobija se csv fajl. (prethodno je rađeno spajanje rečenica jednog fajla, međutim to je odbačeno, ali fajl nije preimenovan). Takođe, kopija ovog fajla postoji za deljenje rečenica iz drugog skupa po zarezima  da bi se sačuvao ouput 
 - Na kraju je moguće pokrenuti redom ćelije unutar Obucavanje i klasterizacija.ipynb fajla, u delu klasterizacije. Ovime se pokreće model koji klasteruje delove rečenica u klastere koji predstavljaju potencijalne delove argumenta.

