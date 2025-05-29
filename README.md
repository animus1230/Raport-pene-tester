# 💻 Raport praktyczny – cyberbezpieczeństwo

**Autor**: Kevin  
**Wiek**: 17 lat  
**Kierunek**: Pentesting / Cyberbezpieczeństwo  
**Kontakt**: bibip0662@gmail.com

---

## 🎯 Cel:
Rozpoczynam budowę mojego portfolio w dziedzinie **cyberbezpieczeństwa**, z naciskiem na **testy penetracyjne** oraz praktyczną naukę z wykorzystaniem maszyn wirtualnych (Hack The Box, Kali Linux, terminal). 

Nie jestem jeszcze ekspertem, ale uczę się **każdego dnia z pasją i zaangażowaniem**. Szukam praktyk, nawet **bezpłatnych**, gdzie mógłbym rozwijać swoje umiejętności i uczyć się od osób z branży.

---

## ✅ Co zrobiłem:

### 🧪 Skanowanie sieci i analiza usług:
- Użyłem poleceń `ping` i `nmap` do identyfikacji aktywnych hostów i otwartych portów.
- Zrozumiałem działanie portów TCP, m.in.:
  - **FTP (port 21)** – niezabezpieczony transfer plików (brak szyfrowania)
  - **SFTP (port 22)** – bezpieczna wersja FTP działająca przez SSH
  - **Telnet (port 23)** – przestarzała i niezalecana metoda komunikacji

### 📂 Połączenie z serwerem FTP:
- Połączyłem się z serwerem za pomocą `ftp IP`.
- Zalogowałem się jako `anonymous` i pobrałem plik `flag.txt`.
- Użyłem komend takich jak `ls`, `get`, `bye` oraz `cat` do sprawdzenia plików.
- Zrozumiałem, jak wygląda przesyłanie danych bez szyfrowania i jakie są zagrożenia (np. sniffing).
- Przećwiczyłem interpretację odpowiedzi serwera FTP (np. 220, 331, 230, 421).

---

## 📚 Czego się nauczyłem:

- Rozpoznawać otwarte porty i identyfikować usługi (FTP, SSH, Telnet, HTTP).
- Używać `nmap -sV` do wykrywania wersji usług i systemu operacyjnego.
- Ręcznie łączyć się z usługami (np. `ftp`, `telnet`) i interpretować ich komunikaty.
- Różnic między FTP a SFTP i dlaczego nie należy używać FTP do przesyłania wrażliwych danych.
- Tworzyć bezpieczne środowisko testowe na maszynach wirtualnych (VirtualBox, HTB).
- Podstaw obsługi klientów FTP z poziomu terminala oraz komend takich jak:
  - `ls`, `cd`, `get`, `put`, `bye`, `open`, `close`
- Znaczenia komunikatów odpowiedzi FTP (np. "230 Login successful", "421 Timeout").
- Podstaw obsługi plików i katalogów w terminalu (np. `ls -la`, `cat`, `pwd`).
- Lepszego zrozumienia, jak działa warstwa aplikacji w modelu OSI (FTP, SSH itp.).
- Samodzielnego myślenia i rozwiązywania błędów (np. "Invalid command", "Already connected").
- Cierpliwości i dokładności w pracy z konsolą – każdy znak ma znaczenie.
- Jak ważne są **podstawy** – to one budują prawdziwą wiedzę.

---

## 🧠 Moje podejście:
- Uczę się **praktycznie**, samodzielnie rozwiązuję problemy.
- Wiem, że **nie znam jeszcze wszystkiego**, ale jestem zdeterminowany.
- Nie boję się popełniać błędów – to dzięki nim uczę się najwięcej.
- Szukam mentora lub zespołu, który da mi szansę rozwoju w prawdziwym środowisku.

---

## 🙏 Prośba:
Jeśli jesteś profesjonalistą w branży cyberbezpieczeństwa i szukasz młodego, ambitnego i uczciwego praktykanta, **będę zaszczycony możliwością nauki od Ciebie**. Nawet proste zadania czy wskazówki pomogą mi się rozwinąć. Nie zawiodę!

📬 **Kontakt**: bibip0662@gmail.com

---

> "Z pasji rodzi się siła. Z wiedzy – odpowiedzialność. A z połączenia obu – przyszłość."
