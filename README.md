Kod ma za zadanie wczytać dane genetyczne i kliniczne pacjentów chorujących na raka piersi.
Etapy procesu przetwarzania surowych danych, po połączeniu ramek danych zostały usunięte puste kolumny, 
w puste miejsca zostały dodane dane w zależności od typu danych w kolumnie: w numeryczne średnią wartość z danej kolumny i w tekstowych najczęściej występująca wartość. 
Dane zostały przekonwertowane do wartości numerycznych, a następnie wyskalowane. 
Następnie wykonałem badanie zależności cech do naszej kolumny decyzyjnej, te, które były wysoko zależne zostały usunięte z ramki. 
Ostatnim krokiem było stworzenie modelu lasów losowych do detekcji najważniejszych cech. 
Wybrałem 100 takich i zostawiłem tylko je w ramce. 
Po takim przekształceniu danych można je teraz podzielić na treningowe i testowe i śmiało budować model np. SVM do klasyfikacji osób chorych.
