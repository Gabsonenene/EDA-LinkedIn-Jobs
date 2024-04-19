# Analiza danych: 
## LinkedIn Job Postings - 2023
### źródło: https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data
## Opis: Zbiór danych dotyczy informacji na temat ofert pracy pochodzących z portalu LinkedIn z 2023 roku. Podczas analizy głównie wzięto pod uwagę pliki job_posting.csv, skills.csv, benefits.csv, companies.csv, company_industreis.csv oraz employee_counts.csv. W trakcie analizy pliki te zostały odpowiednio przygotowane oraz połączone. Pozostałe pliki mogą posłużyć w przyszłości do dalszych, bardziej szczegółowych analiz.
## Postawione pytania oraz hipotezy:
* __Pytanie:__ W jakiej walucie były podane stawki?
__Wniosek:__ Dla wszystkich podanych kwot walutą były dolary amerykańskie (USD).
* __Pytanie:__ Dla jakiego kraju było najwięcej ofert pracy? __Wniosek:__ Większość ofert pracy była skierowana do mieszkańców Stanów Zjednoczonych (US).
* __Pytanie:__ Jakie były najbardziej popularne strony, na których zamieszczono oferty pracy? __Wniosek:__ Najbardziej popularną stroną było 'click2.apply', na drugim miejscu 'jobs.smartrecruiters', a na trzecin 'click.appcast.io'".
* __Hipoteza:__ W zbiorze danych najwięcej ogłoszeń dotyczy branży IT. __Wniosek:__ Najwięcej ogłoszeń było z branży Staffing and Recruiting, a nie z branży IT.
* __Pytanie:__ Czy Staffing and Recruiting było także najczęściej aplikowaną i wyświetlaną branżą? __Wniosek:__ Staffing and Recruiting nie było najczęściej aplikowaną i wyświetlaną branżą. Na pierwszym miejscu znalazły się ogłoszenia z branży IT.
* __Hipoteza:__ W obecnych czasach większość firm posiada opcję pracy zdalnej. __Wniosek:__ Większość firm nie posiadała opcji pracy zdalnej.
* __Hipoteza:__ Większość ofert była skierowana do bardziej doświadczonych pracowników. __Wniosek:__ Najwięcej ofert skierowanych było do średniozaawansowanych pracowników. Na drugim miejscu znalazły się oferty skierowane dla początkujących pracowników.
* __Hipoteza:__ W IT większość ofert była skierowana do bardziej zaawansowanych pracowników niż początkujących. __Wniosek:__ W branży IT większość ofert skierowana była do średniozaawansowanych pracowników. Występowała spora różnica między ilością ofert dla średniozaawansowanych pracowników, a dla początkujących pracowników.
* __Hipoteza:__ Większość firm szukała pracowników na pełen etat. __Wniosek:__ Większość rodzajów zatrudnienia to oferty na pełen etat (full-time), później oferty pracy na kontrakt (Contract), a na trzecim miejscu oferty na część etatu (Part-time).
* __Hipoteza:__ Najwięcej ogłoszeń IT było dla miasta San Francisco. __Wniosek:__ Najwięcej ogłoszeń dla sektora IT znajdowało się w San Fransico.
* __Pytanie:__ Jak na mapie US rozkładały się oferty skierowane do pracowników IT? __Wniosek:__ Najwięcej ofert dla pracowników IT znajdwało się w stanie California - w którym leży San Francisco (Dolina Krzemowa).
* __Pytanie:__ Jaka była korelacja między wielkością firmy a ilością wyświetleń, aplikacji, liczbą followersów i liczbą pracowników? __Wniosek:__ Występiła korelacja między ilością aplikacji i wyświetleń (0.85) oraz między liczbą pracowników i liczbą obserwatorów. Rozmiar firmy nie miał znaczącego wpływu na ilość wyświetleń, aplikacji lub liczby pracowników i followersów.
* __Pytanie:__ Jak wiele firm nie podało 'widełek' w swoich ogłoszeniach (ani min, ani max, ani med salary)? __Wniosek:__ Aż 19 429 firm nie podało widełek, czyli większa część ogłoszeń. Natomiast 13116 ogłoszeń zawierało co najmniej jedną informację o wysokości stawki.
* __Pytanie:__ W którym stanie średnio zarabia się najwięcej? __Wniosek:__ Najwyższe średnie zarobki są dla stanu Maine, natomiast najniższe dla stanu Oklahoma.Najniższe średnie zarobki występują w środkowej części kraju. 
* __Pytanie:__ W której firmie były największe średnie stawki? __Wniosek:__ Największe średnie stawki oferowała firma RISC Zero, na drugim miejscu The Dedham Group i na trzecim firma The Dedham Group.
* __Pytanie:__ Jaka forma zatrudnienia jest najbardziej opłacalna? __Wniosek:__ Najbardziej opłacalną formą zatrudnienia było full-time, a najbardziej korzystynie prezentowała się stawka roczna.
* __Hipoteza:__ W branży IT pracownicy mają najwyższe maksymalne wartości stawek. __Wniosek:__ W branży IT maksymalne stawki roczne stanowiły nawet ponad 1M dolarów - dla IT odnotowano najwyższą wartość równą 1.66 M. Na drugim miejscu była stawka oferty ze Staffing (1.3M), a dwie następne także z IT (1.1 M i 1M).
* __Pytanie:__ Która branża miała najwyższe średnie zarobki? __Wniosek:__ Najwyższe średnie zarobki były w branży IT.
