# Przetwarzanie-jezyka-naturalnego

Zadanie:
Przeprowadź  analizę  recenzji  napisanych  przez  pracowników  czołowych  firm technologicznych w USA i dotyczących ich pracodawców. Dane do analizy zawarte są w pliku employee-reviews.csv.
Program musi zawierać następujące elementy:1.Zmianę sposobu zapisu daty wkolumnie dates i ograniczenie się jedynie do roku, wktórym  recenzja  została  napisana.Jeśli  zmiana  spowoduje  wystąpienie  braków wdanych powinny one zostać usunięte(1 punkt).
2.Obliczenie, ile recenzji ma każda firma z osobna i pokazanie wyniku na wykresie (słupkowym lub kołowym)(1 punkt).
3.Wizualizacjęśredniej ocen (overall-rating)dla każdej firmy w latach (wykres liniowy)(1 punkt).
4.Określenie, ile recenzji zostało napisanych przez obecnych (Current  Employee)  a  ile przez byłychpracowników (Former Employee)oraz wizualizacjęuzyskanego wyniku na wykresie kołowym(dla każdej firmy z osobna)(1 punkt).
5.Identyfikacjęnajpopularniejszychsłówkluczowychw  komentarzach prosi cons. Należy ograniczyć się do 20 najpopularniejszych słów.(2punkty).
6.Stworzenie  chmury 20 najpopularniejszych słów  dla  każdej  z  firm  (osobno  dla komentarzy prosi cons)(2 punkty).
UWAGA: Program musi zawierać komentarze objaśniające kod.Wskazówki1.Aby zidentyfikować najpopularniejsze słowa kluczowe z tekstu komentarzy należy usunąć najpierw tzw. przerywniki (stopwords), czyli słowa, które nie niosą ze sobą znaczenia, ale są konieczne do stworzenia zdania (a, and, the, will, itp.).Można do tego wykorzystać klasę stopwordsz modułu nltk.Z tekstu powinny być również usunięte znaki interpunkcyjne. Słowa powinny zostać poddane lematyzacji, czyli sprowadzone do swojej formy podstawowej (słownikowej)przy użyciu klasy WordNetLemmatizerzmodułu nltk.2.Stworzenie chmury słów jest możliwe z wykorzystaniem klasy WordCloudz modułu nltk
