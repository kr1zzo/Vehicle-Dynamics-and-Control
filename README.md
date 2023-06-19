# Upravljanje uzdužnom i bočnom dinamikom vozila

### Projekt za Modeliranje i upravljanje dinamikom vozila

U prvom dijelu projekta izrađeni su estimatori vertikalnih sila te estimator longitudinalne brzine. Iz odziva moguće je vidjeti kako estimirane vrijednosti dobivene preko formula i korištenjem Kalmanovog filtra odgovaraju pravom vrijednostima koje se mogu vidjeti u Simulinku. Nakon estimacije izrađen je Cruise control koji se sastoji od PI regulatora kojim se regulira brzina koja prati referentnu vrijednost te sustav aktivnog skretanja kojim omogućujemo da vozilo skreće te time izbjegava prepreke. Za kraj je implementiran Traction control koji uspješno onemogućuje proklizavanje vozila.

*Fakultet elektrotehnike i računarstva, lipanj 2023.*
