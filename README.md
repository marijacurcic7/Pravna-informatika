# Pravna-informatika
Pokretanje programa nije neophodno. Rezultujući csv fajlovi su prisutni, a takođe, postoje output-i za svaku ćeliju u .ipynb fajlovima, koji govore šta se desilo prilikom izvršavanja određene ćelije.

Uputstvo za korišćenje:
 - Prvo ispokretati redom ćelije u fajlu Izdvajanje rečenica.ipynb. Ovime se dobija csv fajl u kome su presude razbijene na rečenice koji se dalje koristi.
 - Zatim je moguće redom pokretati ćelije u Obucavanje.ipynb fajlu gde se obučava model koji klasifikuje rečenice na argumentativne (1) i ne-argumentativne (0).
 - Nakon toga, može se pokrenuti ćelije u fajlu Spajanje recenica sa argumentima.ipynb. U ovom fajlu se rečenice koje sadrže argumente spajaju u celinu na osnovu naziva fajla iz kog su prethodno izdvojene i dobija se csv fajl.
 - Na kraju je moguće pokrenuti redom ćelije unutar Klasterovanje.ipynb fajla. Ovime se pokreće model koji klasteruje reči i-ili n-grame u smislene klastere koji predstavljaju delove argumenta.
