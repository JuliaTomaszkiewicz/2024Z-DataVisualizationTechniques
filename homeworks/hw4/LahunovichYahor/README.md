# Noworodki pozostawione w szpitalu nie ze względów zdrowotnych
**Author:** Yahor Lahunovich  
**Date:** 2024-12-07

# Wstęp

Projekt zrealizowano w ramach inicjatywy #BI_NGO Fundacji Gajusz.

Przeglądając dane udostępnione przez fundację, zdecydowałem się skupić na temacie noworodków pozostawionych w szpitalu nie ze względów zdrowotnych w Polsce w latach 2007-2023.

# Ogólny trend w Polsce

Na początek, przyjrzałem się ogólnemu trendowi tej problematyki w całej Polsce. Chciałem sprawdzić, jaki procent wszystkich noworodków zostaje w szpitalu z powodów innych niż zdrowotne.

![Ogólny trend w Polsce](images/poland_plot.png)

Na powyższym wykresie można zauważyć, że poziom pozostawiania noworodków w szpitalach na przestrzeni lat utrzymywał się na podobnym poziomie. W latach 2017-2020 zaobserwowano jednak znaczący spadek. Ciekawe, czy istnieją konkretne przyczyny tego spadku? A może problemem są dane?

# Województwa

Następnie przyjrzałem się, w których województwach pozostawia się najwięcej noworodków. W tym celu wybrałem lata 2007, 2015 i 2023, by zobaczyć zmiany na przestrzeni czasu.

![Województwa 2007](images/poland_map1.png)

![Województwa 2015](images/poland_map2.png)

![Województwa 2023](images/poland_map3.png)

Porównując te mapy, można zauważyć, że problem częściej występuje w województwach zachodnich Polski. Dlaczego tak jest? Warto zgłębić tę kwestię.

# Wykres porównawczy

![Wykres porównawczy](images/poland_map4.png)

# Trendy w województwach

Na koniec zastosowałem metody regresji liniowej do danych, aby sprawdzić, w których województwach sytuacja się poprawia, a w których pogarsza.

![Trend 1](images/trend1.png)

![Trend 2](images/trend2.png)

Widać, że w większości województw sytuacja ulega poprawie, ale są regiony, w których problem się nasila.

# Podsumowanie

Mam nadzieję, że przygotowane przeze mnie wizualizacje pomogą w zobrazowaniu istniejącego problemu. Interesujące byłoby również przeanalizowanie podobnych danych w innych krajach europejskich w celu porównania.