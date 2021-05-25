# AZ-900-training-01
### (I prepare myself to pass AZ-900 certificate.)

<br>
<br>
<br>

## Cloud computing <br>
(przetwarzanie w chmurze) to:
* wynajmowanie przestrzeni dyskowej,
* dostarczanie zasobów od dostawcy usług w chmurze,
<br>
za pośrednictwem internetu.<br>

> Dzięki temu nie trzeba się martwić o fizyczną infrastrukturę, serwery czy ich utrzymywanie.

<br>
<br>

---
<br>
<br>

## Trzy modele wdrożenia chmury

<br>


1. Chmura publiczna<br>

Najbardziej popularny model wdrażania. Za infrastrukturę odpowiedzialny jest dostawca usługi (np. Azure). Dostęp via internet.<br>

>Do zarządzania nie jest potrzebna wiedza detaliczna bo zarządzanie odbywa się po stronie dostawcy usług.<br>

<br>


2. Chmura lokalna (prywatna)<br>

Tutaj to klient jest odpowiedzialny za infrastukturę, wdrożenie, zarządzanie czy aktualizację. Z punktu widzenia bezpieczeństwa, tylko klient i tylko jego organizacja, mają dostęp do zasobów.<br>

>Klient ma pełną kontrolę ale ten model wymaga wiedzy specjalistycznej.<br>

<br>


3. Chmura hybrydowa<br>

Połączenie elementów chmury publicznej z chmurą prywatną. Chmura hybrydowa jest elastyczna, co pozwala na zbudowanie modelu pod potrzeby klienta (np. klient potrzebuje część danych pozostawić tylko i wyłącznie do własnej dyspozycji, nie publikując ich "na zewnątrz").<br>

[Tutaj link](https://github.com/git-atoms/AZ-900-training-01/blob/main/Screeny/01%20Rodzaje%20chmur.jpg) z podsumowaniem chmur.<br>

<br>
<br>

---
<br>
<br>

## Zalety chmury

<br>

* High availability (wysoka dostępność) - ciągła dostępność usług, z jak najmniejszymi przerwami w ich świadczeniu.<br>
>SLA - Service Level Agreement (umowa określająca poziom dostępności usług)<br>

<br>
<br>

* Fault tolerance (odporność na uszkodzenia) - dzięki temu dostawca może wciąż zapewnić ciągłość usług, nawet jeśli jakiś z elementów jego infrastruktury przez chwilę nie funkcjonuje.<br>
>Resiliency - odporność<br>
>Redundancy - nadmiarowość<br>

<br>
<br>

* Scalability (skalowalność) - możliwość zwiększania lub zmniejszania zasobów.<br>
* Elasticity (elastyczność) - automatyczne skalowanie<br>.

>Dzięki skalowalności i elastyczności mamy możliwość dodawania lub odejmowania zasobów, wtedy kiedy są nam potrzebne.<br>

<br>

**Skalowanie w pionie** (skalowanie w górę) - dodawanie zasobów w celu zwiększenia możliwości istniejącego serwera<br>
>np. dodanie procesorów lub dodanie ilości pamięci

<br>

**Skalowanie w poziomie** (skalowanie na zewnątrz) - dodanie większej liczby serwerów<br>

<br>
<br>

Przykład elastyczności chmury:
Kiedy uruchamiamy jakąś kampanię marketingową czy poszukiwanie nowych pracowników (mailing, baza danych, itp) chmura przydziela automatycznie zasoby aby to obsłużyć.<br>
A kiedy kampania się skończy, chmura automatycznie cofnie przydział dodatkowych zasobów.<br>

<br>
<br>

* Globa reach (zasięg globalny) - mapa Azure, mapa dostepności usługi. Oznacza to, że można swoje zasoby umieścić w regionie bliżej klienta. Obniża to również koszty.<br>

<br>
<br>

* Customer latency capabilities (opóźnienie w dostawie usług) - korzystanie z zasobów chmury powinno być dostępne przy jak najmniejszym opóźnieniu (natychmiast, bez oczekiwania czy opóźnienia).<br>

<br>
<br>

* Agility (zręczność) - zdolność do szybkiego działania, tworzenia nawet setek maszyn wirtualnych, gotowych do działania w minutę, w tym samym czasie.<br>

<br>
<br>

* Predictive cost considerations (przewidywanie kosztów) - kiedy działamy na urządzeniach fizycznych, możemy próbować szacować koszta ale nie da się ich dokładnie przewidzieć<br>


>Na masynach wirtualnych, w chmurze możliwe jest przewidzenie wszystkich kosztów, sprawdzenie ile będzie kosztowało włączenie tej czy innej usługi.

<br>
<br>

---

<br>
<br>

## CapEx vs OpEx

<br>

**CapEx** (wydatki kapitałowe) - mówimy o tym jak budowane i finansowane były centra danych przed chmurą (onPremises lub jako chmura prywatna).<br>
>Planujemy i kupujemy z pewną nadwyżką.

<br>

**OpEx** (wydatki operacyjne) - ponosimy tylko koszta operacyjne, które są uzależnione tylko od naszych aktualnych potrzeb.<br>

<br>

Za korzystanie z usłuch chmurowych, rozliczamy się miesięcznie lub kwartalnie (w zależności od typu umowy).<br>

<br>

**Consumption-based model** płacimy za to, z czego faktycznie korzystaliśmy.<br>
>Model oparty na faktycznym zużyciu zasobów.<br>

<br>
<br>

---
<br>
<br>

## Rodzaje usług w chmurze

<br>

* **IaaS** (Infrastucture as a Service) - najbardziej podstawowy model, bardzo zbliżony do środowiska on-Premise. Elastyczny (najczęściej wybierany na początku).<br>

Dostawca jest odpowiedzialny za infrastrukturę ale za wszystko inne user: usługa musi być odpowiednio skonfigurowana, zaktualizowana i udostępniona klientom.<br>
>Lift-And-Shift (migrowanie środowiska lokalnego do chmury)<br>

<br>
<br>

* **PaaS** (Platform as a Service) - dostawca usług ma tu większą odpowiedzialność (nie tylko infrastuktura ale również system operacyjny).<br>
>Po stronie użytkownika pozostaje tylko tworzenie aplikacji na gotowej infrastrukturze i systemie operacyjnym.

<br>
<br>

* **SaaS** (Software as a Service) - korzystanie z aplikacji w chmurze za pomocą internetu. Użytkownika nic nie interesuje i jedyne co musi robić to mieć dostęp do internetu i płacić za subskrybcję.<br>

<br>

[Tutaj podsumowanie](https://github.com/git-atoms/AZ-900-training-01/blob/main/Screeny/02%20Por%C3%B3wnanie%20us%C5%82ug%20w%20chmurze.jpg) porównania tych usług.

<br>

Chmura cechuje się modelem dzielonej współodpowiedzialności.
>Użytkownik zawsze jest odpowiedzialny za dostęp oraz za dane.

<br>

[Tutaj przykład](https://github.com/git-atoms/AZ-900-training-01/blob/main/Screeny/03%20Dzielenie%20wsp%C3%B3%C5%82odpowiedzialno%C5%9Bci.jpg) modelu dzielonej współodpowiedzialności.

<br>
<br>

* Serverless computing (przetwarzanie bezserwerowe) - umożliwia uruchamianie kodu aplikacji bez tworzenia, konfigurowania i utrzymywania serwera.

>Azure Functions - umożliwia uruchamianie fragmentów kodu, bez martwienia się o infrastrukturę.

<br>

>Azure Logic Apps - usługa pozwala zaplanować oraz zautomatyzować zadania. Korzystamy tu z galerii gotowych triggerów (wyzwalaczy akcji) oraz samych akcji.

<br>
<br>

---

<br>
<br>

## Infrastruktura Azure

<br>

**Region** - jest obszar na Ziemi, który zawiera co najmniej jedno centrum danych (datacenter) ale jeśli wiele, to znajdują się blisko siebie i są ze sobą połączone siecią o małych opóźnieniach.

<br>

**Pary regionów** (Region Pairs) - każdy region Azure jest połączony z innym regionem w obrębie tego samego obszaru geograficznego (USA, Europe, Asia) w odległości co najmniej 300mil czyli ok 500km.
> Region Pair przejmuje na siebie usługi, kiedy cały region przestaje funkcjonować.

<br>

**SLA** - Service Level Agreement(dostępność usługi)

<br>

**Strefy dostępności** (Availability Zones) - fizycznie oddzielone centra danych w regionie świadczenia usługi Azure.<br>
Każda Availability Zone składa się co najmniej z jednego DataCenter, wyposażonego w niezależne zasilanie, chłodzenie i sieć.
>Availability Zone przejmuje na siebie usługi, kiedy jedno z DataCenter przestaje działać z danego regionu.

<br>
<br>

---

<br>
<br>

## Zasoby Azure (Azure Resources)

<br>

**Resource Group** (grupa zasobów) - to podstawowy element platformy Azure. Zasobnik wszystkich elementów, wdrożony na platformie Azure.
>Zasób może należeć tylko do jednej grupy ale zasoby mogą być przenoszone pomiędzy tymi grupami.

<br>

**Azure Resource Manager** (ARM) - usługa wdrażania i zarządzania dla platformy Azure.
>Przez ARM przechodzi wszystko co robimy na Azure.

<br>

**Azure Subsriptions** - też jest zarządzane przez ARM i pozwala dobrać subskrybcję, a co za tym idzie kosztorys i dostępy dla poszczególnych części organizacji.

<br>

**Management Group** - sposób wykorzystania ARM (Azure Resource Manager) aby kontrolował wszystkie subskrybcje, grupy zasobów i same zasoby.

<br>
<br>

---

<br>
<br>

## Core Azure Workloads

<br>

**Azure Compute** - to usługa obliczeniowa on-demand (na żądanie) dla aplikacji w chmurze. Zapewnia zasoby obliczeniowe w ramach maszyn wirtualnych i kontenerów.
<br>

[Tutaj screen](https://github.com/git-atoms/AZ-900-training-01/blob/main/Screeny/05%20Azure%20Compute.jpg) Azure Compute.

<br>

**Virtual Machines** (VM) 