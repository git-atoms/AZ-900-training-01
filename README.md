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

**Skalowanie w poziomie**