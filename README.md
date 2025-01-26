# Gra Miejska
Aplikacja internetowa �Gra Miejska� wykonana na PHP Frameworku Laravel, posiada odseparowany front i back-end, gdzie komunikacja idzie poprzez POST API.

# Uruchomienie
Aplikacja jest skonteneryzowana. Do uruchomienia przejdz do sciezki aplikacji w terminalu Dockera i wpisz:
```
docker compose up -d
```

# Dzialanie
 Aplikacja raz dziennie o tej samej godzinie losowo wybiera kazdemu uzytkownikowi jedno ze zdjec wykonanych przez administratora. Uzytkownik z pomoca zdjecia pr�buje odgadnac gdzie zostalo wykonane, potwierdzajac sw�j wyb�r klikajac miejsce na mapie geograficznej. Bazujac na odleglosci od celu, czasu uzytego na podjecie wyboru oraz trudnosci zdjecia przyznawane sa punkty. Uzytkownicy konkuruja ze soba iloscia punkt�w na tablicy wynik�w.
Zalozenia:

a) Uzytkownik moze:
- Zarejestrowac oraz zalogowac sie w systemie - poprzez baze danych, Google lub Facebooka.
- Zmienic swoje zdjecie profilowe.
- Raz dziennie o wyznaczonej godzinie otrzymac losowe zdjecie z systemu, jego zadaniem jest odgadniecie gdzie zdjecie zostalo wykonane wskazujac miejsce na mapie.
- Bazujac na wykonanym wyborze otrzymac punkty.
- Zobaczyc tablice wynik�w innych zalogowanych uzytkownik�w wraz z podium.

b) Administrator moze:
- Dodawac nowe zdjecia do bazy zdjec.
- Edytowac opis oraz koordynaty kazdego z dodanych zdjec.
- Zmienic wartosc o kt�rej godzinie zagadka sie resetuje.
- Zmienic wartosc dopuszczalnego maksymalnego dystansu na mapie aby otrzymac jakiekolwiek punkty.
- Zmienic wartosc z ilu dni tablica wynik�w zlicza punkty.
- Zobaczyc statystyki klikniec pod kazda zagadka, takie jak srednia liczba uzyskanych punkt�w, sredni czas wykonania wyboru oraz srednia odleglosc od celu.
- Zobaczyc ilu uzytkownik�w odpowiedzialo na ile zagadek.
- Zarzadzac uzytkownikami.
