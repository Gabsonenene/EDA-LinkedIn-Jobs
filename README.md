# Data analysis:
# LinkedIn Job Postings - 2023
### source: https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data
## Summary: The dataset contains information about LinkedIn job postings from 2023. Data files such as job_posting.csv, skills.csv, benefits.csv, companies.csv, company_industry.csv and employee_counts.csv were considered in the analysis. In the process of analyzing these files, these files were prepared and merged accordingly. A more detailed analysis of the rest of the files can be performed in the future by using the remaining files.
## Questions and hypotheses:
* __Question:__ In what currency were salaries paid?
__Conclusion:__ The currency was US dollars (USD).
* __Question:__ For which country were there the most job offers? __Conclusion:__ Most of the job offers were directed at residents of the United States (US).
* __Question:__ What were the most popular job posting websites? __Conclusion:__ The most popular site was 'click2.apply', followed by 'jobs.smartrecruiters' in second place and 'click.appcast.io' in third.
* __Hypothesis :__ In the dataset, the largest number of job offers is in the IT industry. __Conclusion:__ The largest number of offers were from the Staffing and Recruiting industry, rather than the IT industry.
* __Question:__ Was Staffing and Recruiting also the most frequently applied and viewed industry? __Conclusion:__ Staffing and Recruiting was not the most frequently applied and viewed industry. The most frequently viewed and applied offers were those from the IT industry. 
* __Hypothesis:__ Nowadays, most companies have a remote work option. __Conclusion:__ Most companies didn't have a remote work option.
* __Hypothesis:__ Employees with more experience were most likely to receive the offers. __Conclusion:__ Mostly mid-senior workers were offered jobs. Entry-level offers ranked second.
* __Hypothesis:__ In IT, most of the offers were directed at more mid-senior employees rather than entry-level ones. __Conclusion:__ Most of the IT industry's offers were directed at mid-senior employees. For mid-senior employees, the number of offers was much higher than for entry-level employees.
* __Hypothesis:__ Most companies were looking for full-time employees. __Conclusion:__ Most types of employment are full-time, followed by contract and in third place by part-time.
* __Hypothesis:__ The largest number of IT job offers was for the city of San Francisco. __Conclusion:__ The largest number of offers for the IT sector were in San Francisco.
* __Question:__ What was the distribution of offers addressed to IT employees on the US map? __Conclusion:__ The largest number of offers for IT employees were in the state of California - where San Francisco (Silicon Valley) is located.
* __Question:__ What was the correlation between the size of the company and the number of views, number of applications, number of followers and number of employees? __Conclusion:__ The number of applications correlated with the number of views (0.85), as did the number of employees correlated with the number of followers (0.81). Views, applications, employees, and followers were not affected by the size of the company.
* __Question:__ In how many companies' job postings is the salary not stated (neither min, max, or med salary)? __Conclusion:__ The majority of postings, 19,429, did not include a salary. On the other hand, 1,316 job postings included salary information.
* __Question:__ In which state does the average U.S. citizen earn the most? __Conclusion:__ Maine has the highest average salary, while Oklahoma has the lowest. In the middle of the country, the average salary is the lowest.
* __Question:__ Which company has the largest average salaries? __Conclusion:__ The largest average salaries were provided by RISC Zero, followed by The Dedham Group in second place and The Dedham Group in third place.
* __Question:__ What form of employment is the most profitable? __Conclusion:__ It was most profitable to work full-time, and the most favorable pay period was the yearly period.
* __Hypothesis:__ In the IT industry, employees have the highest maximum salaries. __Conclusion:__ In the IT industry, the maximum annual salaries were more than $1M - the highest value of $1.66M was recorded for IT, followed by an offer rate from Staffing ($1.3M), and two more also from IT ($1.1M and $1M).
* __Question:__ Which industry had the highest average salaries? __Conclusion:__ The highest average salaries were in the IT industry.


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
