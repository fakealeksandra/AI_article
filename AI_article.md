# AI w służbie kodu – jak sztuczna inteligencja zmienia cykl życia oprogramowania

## Wstęp

Sztuczna inteligencja staje się jednym z najważniejszych czynników wpływających na rozwój współczesnego oprogramowania. Integracja AI z systemami kontroli wersji oraz platformami DevOps, takimi jak GitHub i GitLab, pozwala automatyzować wiele zadań wykonywanych wcześniej wyłącznie przez programistów. Narzędzia wykorzystujące modele językowe wspierają tworzenie kodu, testowanie aplikacji, wykrywanie podatności oraz zarządzanie procesem wytwarzania oprogramowania.

Celem artykułu jest przedstawienie wpływu AI na rozwój nowoczesnych procesów programistycznych oraz analiza korzyści i wyzwań związanych z wykorzystaniem tych technologii.

---

## 1. Agentic AI i inteligentna orkiestracja

Agentic AI oznacza nową generację systemów sztucznej inteligencji zdolnych do samodzielnego wykonywania złożonych zadań. W środowisku DevSecOps agenty AI mogą analizować zgłoszenia błędów, proponować zmiany w kodzie oraz tworzyć Pull Requesty lub Merge Requesty.

Najważniejsze zastosowania Agentic AI:

- automatyczna analiza zgłoszeń (Issues),
- generowanie propozycji zmian w kodzie,
- wykonywanie wstępnego code review,
- identyfikacja podatności bezpieczeństwa,
- automatyczne przygotowywanie poprawek.

Dzięki temu zespoły programistyczne mogą ograniczyć czas poświęcany na rutynowe czynności i skupić się na bardziej wymagających zadaniach.

---

## 2. Ekosystem AI na platformie GitHub

GitHub rozwija rozbudowany zestaw narzędzi wykorzystujących sztuczną inteligencję.

### GitHub Copilot

GitHub Copilot działa jako wirtualny partner programisty. Analizuje aktualny kontekst kodu i proponuje całe funkcje, klasy lub fragmenty implementacji.

Korzyści:

- szybsze pisanie kodu,
- automatyczne generowanie testów,
- wsparcie przy nauce nowych technologii,
- redukcja powtarzalnych czynności.

### GitHub Spark

GitHub Spark umożliwia tworzenie aplikacji wykorzystujących modele AI oraz szybkie budowanie prototypów nowych rozwiązań.

### GitHub Models

GitHub Models pozwala zarządzać modelami językowymi i testować różne prompty bezpośrednio w ekosystemie GitHub.

Według danych GitHub znacząca część nowego kodu powstającego przy aktywnym Copilocie jest generowana przez AI, szczególnie w językach takich jak Python.

---

## 3. Wpływ AI na produktywność programistów

Wykorzystanie narzędzi AI zwiększa efektywność zarówno pojedynczych programistów, jak i całych zespołów.

Najważniejsze korzyści:

- krótszy czas implementacji funkcjonalności,
- szybsze wdrażanie nowych członków zespołu,
- automatyczne generowanie dokumentacji,
- wsparcie w analizie błędów,
- tworzenie przypadków testowych.

AI znajduje zastosowanie również w testowaniu oprogramowania. Narzędzia generatywne pomagają tworzyć scenariusze testowe, analizować logi oraz identyfikować potencjalne przyczyny awarii systemów.

Należy jednak pamiętać, że wygenerowany kod powinien być zawsze weryfikowany przez człowieka, ponieważ AI może popełniać błędy logiczne lub generować nieoptymalne rozwiązania.

---
## 3.1 AI w automatyzacji testów oprogramowania

Coraz większą rolę sztuczna inteligencja odgrywa również w procesie testowania aplikacji. Narzędzia oparte na modelach językowych są wykorzystywane do generowania przypadków testowych, analizy logów oraz wspierania diagnostyki błędów.

W środowiskach Continuous Integration i Continuous Delivery (CI/CD) AI może pomagać w:

- generowaniu testów jednostkowych na podstawie kodu źródłowego,
- tworzeniu scenariuszy testów API,
- analizie wyników nieudanych testów,
- wykrywaniu niestabilnych testów (flaky tests),
- sugerowaniu potencjalnych przyczyn awarii.

Przykładowo, podczas testowania interfejsów REST API modele AI mogą analizować specyfikacje OpenAPI i automatycznie generować zestawy przypadków testowych obejmujących zarówno scenariusze pozytywne, jak i negatywne.

W przyszłości możliwe będzie wykorzystanie Agentic AI do samodzielnego uruchamiania testów regresyjnych, analizy wyników oraz tworzenia zgłoszeń błędów bez bezpośredniego udziału człowieka. Takie podejście może znacząco skrócić czas potrzebny na weryfikację jakości oprogramowania.
Pierwsze rozwiązania wykorzystujące Agentic AI są już dostępne na rynku. Przykładowo GitHub Copilot Coding Agent potrafi realizować zadania programistyczne, uruchamiać testy oraz przygotowywać propozycje zmian w formie Pull Requestów. Z kolei GitLab Duo Agent Platform rozwija koncepcję współpracujących agentów AI wspierających proces wytwarzania oprogramowania, w tym testowanie i analizę wyników. Można oczekiwać, że w kolejnych latach narzędzia te będą oferowały coraz większy poziom autonomii, obejmując pełne wykonywanie testów regresyjnych oraz automatyczne tworzenie zgłoszeń błędów.

---

## 4. Transformacja bezpieczeństwa kodu dzięki AI

Bezpieczeństwo aplikacji jest jednym z obszarów, w których sztuczna inteligencja przynosi największe korzyści.

Nowoczesne rozwiązania wykorzystują AI do:

- wykrywania podatności w kodzie źródłowym,
- analizy zależności zewnętrznych,
- oceny ryzyka bezpieczeństwa,
- generowania propozycji poprawek,
- wspierania procesów DevSecOps.

Coraz częściej spotykane są narzędzia automatycznie przygotowujące Pull Request zawierający poprawkę wykrytej podatności. Pozwala to znacząco skrócić czas potrzebny na usunięcie problemu.

### AI a analiza kodu statycznego

Nowoczesne narzędzia bezpieczeństwa coraz częściej łączą klasyczną analizę statyczną (Static Application Security Testing, SAST) z modelami sztucznej inteligencji. Pozwala to wykrywać nie tylko znane wzorce podatności, ale również bardziej złożone problemy logiczne trudne do identyfikacji za pomocą tradycyjnych reguł.

AI może analizować zależności między modułami aplikacji, wskazywać potencjalne miejsca występowania podatności typu SQL Injection, Cross-Site Scripting (XSS) czy błędów autoryzacji oraz proponować bezpieczniejsze implementacje.

Dodatkowo rozwiązania wykorzystujące AI potrafią priorytetyzować wykryte podatności. Zamiast prezentować programistom setki potencjalnych problemów, system może wskazać te, które mają największy wpływ na bezpieczeństwo aplikacji i powinny zostać naprawione w pierwszej kolejności.

Takie podejście pozwala zespołom szybciej reagować na zagrożenia oraz efektywniej zarządzać procesem usuwania błędów bezpieczeństwa.

---

## 5. Kontrowersje prawne i kwestie własności intelektualnej

Rozwój generatywnej sztucznej inteligencji wywołuje wiele dyskusji związanych z prawami autorskimi.

Najczęściej wskazywane problemy:

- trenowanie modeli na publicznych repozytoriach,
- możliwość generowania kodu podobnego do istniejących projektów,
- brak informacji o źródle wygenerowanych fragmentów,
- potencjalne naruszenia licencji Open Source.

Duże zainteresowanie wzbudziły pozwy dotyczące GitHub Copilot, w których podnoszono kwestie wykorzystania publicznie dostępnego kodu podczas trenowania modeli AI.

Obecnie przepisy nie nadążają za tempem rozwoju technologii, dlatego kwestie prawne pozostają przedmiotem licznych debat.

---

## 6. Przyszłość systemów kontroli wersji

System Git pozostaje podstawowym narzędziem kontroli wersji wykorzystywanym przez większość zespołów programistycznych.

W przyszłości AI może wspierać:

- automatyczne rozwiązywanie konfliktów merge,
- generowanie opisów commitów,
- analizę historii zmian,
- przewidywanie problemów integracyjnych,
- tworzenie dokumentacji technicznej.

Pomimo rosnącej roli AI trudno oczekiwać całkowitego zastąpienia programistów. Bardziej prawdopodobny jest model współpracy człowieka i sztucznej inteligencji, w którym AI przejmuje zadania rutynowe, a człowiek odpowiada za decyzje architektoniczne i biznesowe.

---

## Podsumowanie

Sztuczna inteligencja zmienia sposób tworzenia i utrzymywania oprogramowania. Narzędzia takie jak GitHub Copilot, GitHub Spark oraz rozwiązania Agentic AI zwiększają produktywność zespołów i wspierają procesy związane z bezpieczeństwem aplikacji.

Jednocześnie rozwój tych technologii rodzi nowe wyzwania prawne i etyczne dotyczące własności intelektualnej oraz odpowiedzialności za generowany kod.

Najbardziej prawdopodobnym scenariuszem jest dalsza współpraca człowieka z AI. Programiści nie zostaną zastąpieni, jednak ich codzienna praca będzie coraz silniej wspierana przez inteligentne narzędzia automatyzujące proces wytwarzania oprogramowania.

---

# Bibliografia

1. GitLab, *Finally, AI for the entire software lifecycle*.
2. GitLab Duo Documentation.
3. GitHub, *About GitHub AI Features*.
4. GitHub Copilot Documentation.
5. GitHub Spark Documentation.
6. GitHub Models Documentation.
7. GitHub Copilot Litigation Documentation.
8. Open Source Initiative.
9. Software Freedom Conservancy.
10. Git Project Documentation.
11. ThoughtWorks Technology Radar.
12. ACM Communications.
13. IEEE Software Magazine.
