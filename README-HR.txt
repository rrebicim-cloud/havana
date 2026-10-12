HAVANA – objedinjena PWA nadogradnja (v3)

U paketu su sve datoteke aplikacije. Na GitHubu zamijeni postojeće datoteke ovima iz mape havana_pwa (sve u isti glavni direktorij repozitorija). Nemoj stvarati novi repozitorij ni mijenjati adresu stranice.

DODANO / UKLJUČENO
- Kategorije rashoda: STRUJA, VODA, INTERNET, ZAMP, HRT, KOMUNALNO, IMOTSKI, KNJIGOVODSTVO, ČIŠĆENJE, PLAĆA 1–5, MUZIKA, OSTALO.
- Excel-kompatibilan izvještaj (.xls) s listovima Dnevni unosi, Mjesečni pregled i Rashodi po kategorijama.
- Izvještaj za ispis / spremanje kao PDF kroz dijalog ispisa preglednika.
- Mjesečna usporedba prihoda i rashoda grafičkim trakama i godišnji pregled.
- Predlošci ponavljajućih rashoda koje korisnik ručno dodaje u odabrani mjesec (na prvi dan mjeseca, bez automatskog dupliranja istog predloška).
- Podsjetnici unutar aplikacije, označavanje dovršenih i brisanje.
- Bilješke, kontakti i fotografije ostaju dostupni.
- JSON sigurnosna kopija i vraćanje kopije uključuju prihode, rashode, kategorije, bilješke, predloške i podsjetnike.
- Stare prihode/rashode ne uvozimo; sve unose unosiš ručno.
- Podaci ostaju u localStorage istog preglednika/iste adrese; nema online baze. Service worker predmemorija osvježena je na v3.

VAŽNO
- Prije nadogradnje izvezi JSON sigurnosnu kopiju iz postojeće aplikacije. Ne briši podatke Safari/GitHub stranice.
- PIN zaključava sučelje, ali ne šifrira podatke. JSON kopija nije šifrirana.
- PDF se izrađuje preko dijaloga ispisa i opcije Spremi kao PDF.
- Podsjetnici su unutar aplikacije; web-aplikacija ne može jamčiti iOS obavijesti dok je potpuno zatvorena.
- Ovo je PWA za osobnu upotrebu, nije App Store aplikacija.

INSTALACIJA / AŽURIRANJE
1. Na računalu raspakiraj ZIP.
2. U GitHub repozitoriju otvori postojeću aplikaciju.
3. Prenesi sve datoteke iz mape havana_pwa u glavni direktorij repozitorija, uz zamjenu postojećih datoteka.
4. Potvrdi promjene (Commit changes).
5. Otvori postojeću adresu u Safariju na iPhoneu i osvježi. Ako se prikaže stara verzija, otvori adresu s dodatkom ?v=3.
6. Provjeri da se PIN i postojeći testni unosi još vide prije svakodnevne uporabe.
