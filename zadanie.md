## 1. Zero-shot

**Prompt:**  
Doradź mi, gdzie pojechać na wakacje?

**Zmiany w zapytaniu:**  
W zapytaniu nie ma żadnych dodatkowych instrukcji.

**Wynik:**  
Odpowiedź była krótka. Chatbot zapytał o cztery dodatkowe szczegóły:
datę podróży, liczbę dni, budżet oraz preferowany rodzaj wakacji.
Po uzyskaniu tych informacji zaproponował podanie 3–5 kierunków
wraz z ich plusami i minusami.


## 2. Role prompting

**Prompt:**  
Jesteś rezydentem hotelowym w dużej firmie turystycznej.
Pracujesz w niej od 10 lat. Podróżujesz od dziecka i byłeś
w 150 krajach. Doradź mi, gdzie pojechać na wakacje?

**Zmiany w zapytaniu:**  
Chatbotowi została nadana konkretna rola i doświadczenie.

**Wynik:**  
Wstęp i zakończenie odpowiedzi były bardziej rozbudowane.
Chatbot zapytał o sześć rzeczy: datę podróży, liczbę dni,
budżet, preferowany rodzaj wakacji, osoby towarzyszące oraz
preferowaną odległość podróży.

Zaproponował również przedstawienie 3–5 kierunków wraz z ich
plusami i minusami oraz możliwość uwzględnienia miasta wylotu.


## 2. Prompt chaining

**Prompt 1:**  
Podaj 5 popularnych kierunków wakacyjnych w Europie.

**Prompt 2:**  
Porównaj podane przez Ciebie kierunki pod względem cen,
pogody i rodzaju wypoczynku.

**Prompt 3:**  
Na podstawie tego porównania wybierz dwa kierunki odpowiednie
dla osoby, która chce przede wszystkim odpocząć na plaży,
ale również trochę pozwiedzać. Wyjaśnij, dlaczego spełniają
te kryteria.

**Zmiany w zapytaniu:**  
Zamiast przekazywać wszystkie instrukcje w jednym prompcie,
podzieliłam zadanie na trzy kolejne etapy. Każdy kolejny prompt
odnosi się do odpowiedzi uzyskanej wcześniej.

**Wynik:** 
Odpowiedź najbardziej rozbudowana z konkretnymi destynacjami. Chatbot podał odpowiednią ilość kierunków, trafne argumeny, a wszelkie inne dane zawarł w tabeli. 