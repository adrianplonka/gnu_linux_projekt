# Gra – Escape Room: GNU/Linux 

Ten projekt to interaktywna gra edukacyjna w stylu escape roomu, która łączy mechanikę rozgrywki z nauką podstaw systemu GNU/Linux, poleceń terminala oraz popularnych narzędzi open-source. Gracz, aby przejść dalej, musi poprawnie odpowiadać na pytania związane z obsługą systemu i oprogramowaniem edukacyjnym.

## Koncepcja i rozgrywka

Gra została stworzona w języku Python z wykorzystaniem biblioteki **Pygame**. Gracz przemierza kolejne pokoje, w których musi rozwiązać zagadki i unikać pułapek. W interaktywnych punktach pojawiają się pytania wymagające znajomości terminala, programów graficznych (np. GIMP, Inkscape), LaTeX-a oraz języka R.

Poprawne odpowiedzi odblokowują dalszy postęp i odsłaniają kolejne litery tajnych haseł. Interfejs gry umożliwia także otwarcie terminala w celu wykonania rzeczywistych poleceń systemowych (np. `ls`, `cat`, `who`, `man`).

## Tematyka edukacyjna

- Nawigacja i praca z plikami w terminalu bash
- Polecenia systemowe (chmod, echo, man, who itp.)
- Praca z plikami tekstowymi (FASTA, katalogi, prawa dostępu)
- Edytory graficzne: GIMP, Inkscape
- Tworzenie dokumentów w LaTeX-u
- Obsługa funkcji w języku R (np. `getwd()`)

## Mechanika i pytania

Przykładowe pytania:
- Ile plików znajduje się w katalogu `images/`?
- Jaką funkcję w R używa się do sprawdzenia katalogu roboczego?
- Jakie polecenie wypisze dokumentację programu w systemie Linux?
- Jak nazywa się darmowy edytor grafiki rastrowej?
- Co wypisze `echo $((A++))`, gdy A=0?

## Struktura projektu

├── skrypt/ # Finalne wersje gry (Linux/Windows)
│ ├── skrypt_linux.py
│ └── skrypt_windows.py
├── images/ # Grafiki i ilustracje do gry
├── other_files/ # Pliki pomocnicze (np. seq.fasta, pass/word)
├── gnu_linux_projekt.tar # Spakowany katalog projektu
├── README.md # Opis projektu

## Autorzy projektu
- Adrian Płonka
- Aleksandra Pacułt
- Julia Skiba

## Źródła i inspiracje
- system GNU
- język R
- edtor grafiki GIMP
- grafika wektorowa inkscape
- system LaTeX
- chatGPT - pomoc w pisaniu kodu 



