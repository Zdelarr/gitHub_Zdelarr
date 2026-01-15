# gitHub_Zdelarr
Struktura Unity projekta
Assets/

Glavni direktorij Unity projekta.
Sadrži sav sadržaj koji se koristi u aplikaciji ili igri, uključujući C# skripte, scene, prefabe, materijale, teksture, zvukove i animacije.

Ovaj direktorij se obavezno verzionira jer sadrži izvorni sadržaj projekta.

Library/

Automatski generiran direktorij koji Unity koristi za privremene i cache podatke, uključujući uvezene assete i optimizirane verzije resursa.

Ne verzionira se jer se ponovno generira prilikom svakog otvaranja projekta.

Logs/

Sadrži log datoteke Unity Editora, uključujući zapise o greškama, upozorenjima i radu editora.

Ne verzionira se jer su logovi lokalni i privremeni.

Packages/

Sadrži konfiguraciju Unity Package Managera, uključujući popis paketa i njihove verzije.

Verzionira se jer definira koje pakete projekt koristi i mora biti isto za sve članove tima.

ProjectSettings/

Sadrži globalne postavke projekta kao što su build postavke, input sustav, grafičke postavke i konfiguracije platformi.

Verzionira se jer su te postavke ključne za ispravan rad projekta na svim razvojnim okruženjima.

UserSettings/

Sadrži lokalne korisničke postavke, poput izgleda editora i osobnih preferencija.

Ne verzionira se jer je specifičan za svakog korisnika.

.vsconfig

Konfiguracijska datoteka za Visual Studio.
Definira koje komponente i alati trebaju biti instalirani kako bi se projekt mogao ispravno razvijati.

Može se verzionirati kako bi svi developeri imali isto razvojno okruženje.

.gitignore datoteka
Čemu služi .gitignore?

Datoteka .gitignore služi za definiranje datoteka i direktorija koje Git treba ignorirati i ne dodavati u repozitorij.

Time se sprječava dodavanje privremenih, generiranih i lokalnih datoteka koje nisu potrebne za rad projekta.

Što .gitignore sprječava u Unity projektu?

Datoteka .gitignore najčešće sprječava dodavanje sljedećih direktorija i datoteka:

Library/

Logs/

UserSettings/

Temp/

.vs/ (Visual Studio datoteke)

privremene i cache datoteke

operacijski sustav specifične datoteke

Na taj način u repozitoriju ostaju samo datoteke nužne za izgradnju i razvoj projekta.




Zašto koristimo feature branch?

Feature branch omogućuje razvoj novih funkcionalnosti bez utjecaja na stabilnu main granu te olakšava paralelni rad i kontrolu promjena.

Zašto je main branch protected?

main branch je zaštićen kako bi se spriječile neprovjerene promjene i osiguralo da sav kod prođe Pull Request i review proces.

Što sam naučio kroz Pull Request i review proces?

Naučio sam kako predavati promjene na pregled, važnost jasnih commit poruka te kako review proces poboljšava kvalitetu koda.