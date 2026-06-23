# -manager-zwrotow-info
Apliakcja zarządzająca zwrotami allegro.
Manager Zwrotów to wewnętrzne narzędzie desktopowe stworzone na potrzeby firmy TradeSport.pl. Aplikacja automatyzuje obsługę zwrotów oraz zamówień złożonych na platformie Allegro, integrując dane z systemem magazynowo-sprzedażowym Subiekt GT (InsERT) oraz platformą BaseLinker.

Zakres dostępu do Allegro REST API
Pobieranie listy zwrotów klientów (/order/customer-returns)
Pobieranie szczegółów pojedynczych zwrotów
Pobieranie zamówień (/order/checkout-forms)
Odświeżanie tokenów dostępu OAuth 2.0
Sposób użycia danych
Pobrane dane są zapisywane wyłącznie w lokalnej, szyfrowanej bazie danych na komputerze operatora. Dane nie są udostępniane osobom trzecim ani przesyłane na zewnętrzne serwery. Aplikacja działa wyłącznie w imieniu właściciela kont sprzedawcy w serwisie Allegro.
