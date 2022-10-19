# Individual-FullStack-with-Python-Project

UŽDUOTIS
Sukurkite internetinę svetainę, kuri naudodami Flask arba Django. Papildomai galite naudoti bet kokius papildomus paketus ar išorinius APIs.

MINIMALŪS REIKALAVIMAI:

1. Svetainė turi leisti registraciją/prisijungimą. (3)
2. Puslapyje turi būti apsaugoti ir neapsaugoti maršrutai (angl. routes). (2)
3. Duomenų bazėje turėtų būti bent keturios Jūsų sukurtos lenteles arba naudojami keli išoriniai APIs. (3)
4. Projektas turi turėti dokumentacija ir paleidimo instrukcijas. (1)
5. Prisitaikantis dizainas (angl. "Responsive Web Design"). Galima naudoti ir "UI framework". (1)

SAVĘS ĮSIVERTINIMAS: 

1.  [+] Visiškai įgyvendintas reikalavimas. Sukurtas Account app, kuris rūpinasi registracija ir prisijungimu prie sukurto blog sprendimo.
2.  [+] Visiškai įgyvendintas reikalavimas. Neprisijungę vartotojai negali kurti post'ų, jų keisti ar matyti savo istorijos.
3.  [-] Iš dalies įgyvendintas reikalavimas. Modeliai sukuria 2 iš 4 reikalautų lentelių - account ir blogpost. Tikiuos papildomų balų už kitas įgyvendintas funkcijas.
4.  [+] Visiškai įgyvendintas reikalavimas.
5.  [+] Visiškai įgyvendintas reikalavimas. Vizualinis apipavidalinimas sukurtas naudojantis Bootstrap.
6.  Papildomos funkcijos:
    
     a. Galimybė įkelti nuotraukas į blog įrašą (static failų naudojimas);
    
     b. Pagination;
    
     c. Paieška;
    
     d. Galimybė atnaujinti slaptažodį ar prisijungimo vardą;
     
DIEGIMO PROCESAS:

1. Sukuriame virtualią aplinką (VA);
2. Į VA perkeliame atsiųstus failus;
3. Į VA diegiame reikalingus modulius iš requirements.txt (django, pillow);
4. Atliekame migracijas ir kartu sukuriame duomenų bazę (python manage.py makemigrations; python manage.py migrate);
5. Sukuriame superUser (python manage.py createsuperuser);
6. Paleidžiame serverį (python manage.py runserver);
7. Per nuorodą einame į sukurtą blog puslapių administratorių.

PROJEKTO KŪRIMAS:

1. Susikurtas DJANGO projektas;
2. Sukurtas Accout app registracijos ir prisijungimo administravimui;
3. Prijungtas Bootstrap;
4. Sukurtas Blog app;
5. Suvaldytas static files procesas;
6. Įdiegta paieškos funkcija;
7. Įdiegtas pagination.
    

