# SalesUserForm
VBA-based UserForm for Sales Dpt to deliver new client's data to the Data Management Dpt.

PL:
UserForm powstał w celu poprawy jakości danych klientów, które dział sprzedaży przesyła działowi Master Data. Aplikacja zawiera krótką isntrukcję dla użytkowników, którzy mogą wprowadzić dane dla nowego płatnika lub odbiorcy. Projekt został wdrożony do procesu wprowadzania nowych danych (zmodyfikowano dane wrażliwe).

UserForm ułatwia użytkownikowi prawidłowe wprowadzenie danych poprzez walidację danych. Przykładowo, kolejne możliwe opcje "Customer grp" są zależne od wyborów w poprzednich kategoriach.

UserForm przewiduje potencjalne błędy we wprowadzonych danych i nie pozwoli na ich dalsze przetworzenie. W przypadku błędu pojawia się okno z adekwatnym komunikatem.
Błędy obejmują m. in.:
- brak wymaganego pola
- nipoprawną długość NIP
- niepoprawną formę kodu pocztowego

Po prawidłowym wypełnieniu UserFormy, dane zostają przeniesione do arkusza "Cleansed_data" w formie gotowej do wprowadzenia do bazy danych (wielkie litery, zamiana kodowania).

Aplikacja została stworzona z myślą o użytkowaniu zarówno na komputerach jak i tabletach. W związku z tym okna UserFormy zostały uzależniona od rozdzielczości w celu zachowania użyteczności na mniejszych urządzeniach.

EN:
The UserForm was created in order to increase the quality of new clients' data, submitted to Master Data dept by the Sales team. The application contains a short instruction for the users who can input data for a new payer or sold-to party. The project has been successfully implemented into the process of new data input (the sensitive data have been modified).

UserForm makes it easier for the user to input correct data by data validation. For example, each new options of "Customer grp" are dependent on previous choices in the category.

The UserForm predicts potential errors of the input data and does not let the user to commit them. In case of an error, a window with a proper message pops up.
The errors contain i.a.:
- an empty mandatory field
- incorrect length of NIP number
- incorrect form of the zip code

After the UserForm gets completed, the data are moved to "Cleansed_data" spreadsheet in a form that is fit for further implementation into the database (capital letters, change in coding).

The Application has been created with PC and tablet users in mind. To make it compatible with different screen sizes, the UserForm windows are strictly dependent on the device's resolution.
