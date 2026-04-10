# e-Opieka - System Zarządzania Placówką Medyczną

Projekt aplikacji Full-Stack przygotowany jako praktyczna część pracy licencjackiej. 

## 🎯 Cel i zakres pracy

Głównym celem projektu jest zaprojektowanie oraz implementacja aplikacji webowej optymalizującej przepływ informacji medycznej pomiędzy placówką ochrony zdrowia a pacjentem. System ułatwia korzystanie z nowoczesnych narzędzi informatycznych szerokiej grupie odbiorców – zarówno personelowi medycznemu, jak i pacjentom.

**Kluczowe założenia:**
* **Dostępność cyfrowa (Accessibility):** Szczególny nacisk położono na osoby starsze (seniorów). Dedykowany tryb wyświetlania danych "+60" niweluje bariery wynikające ze złożoności tradycyjnych interfejsów.
* **Centralizacja informacji:** Udostępnienie cyfrowego harmonogramu leków, kalendarza wizyt oraz bazy danych personelu w jednym miejscu.
* **Optymalizacja procesów:** Zminimalizowanie konieczności osobistych wizyt w celach wyłącznie informacyjnych, co przekłada się na skrócenie kolejek i zwiększenie bezpieczeństwa.

## 🚀 Kluczowe funkcje systemu

* **Trzy poziomy uprawnień:**
    * **Administrator:** Zarządzanie kadrą, kontami użytkowników oraz globalnymi ustawieniami placówki.
    * **Lekarz:** Podgląd kart pacjentów, edycja zaleceń, zarządzanie grafikiem pracy oraz wystawianie e-recept.
    * **Pacjent:** Dostęp do własnej dokumentacji, harmonogramu leczenia i modułu pomocy SOS.
* **Tryb Dostępności 60+:** Powiększony interfejs o wysokim kontraście wspierany przez syntezator mowy (Web Speech API) pełniący rolę lektora.
* **Moduł E-Recept:** System generujący unikalne kody dostępu z automatycznym powiadomieniem e-mail (Nodemailer).
* **Interaktywny Kalendarz:** Zarządzanie wizytami i zabiegami w czasie rzeczywistym.

## 🛠️ Stack Technologiczny

**Frontend:**
* React.js (Vite)
* Lucide React (ikony)
* Web Speech API (obsługa głosowa)

**Backend:**
* Node.js & Express.js
* Nodemailer (automatyzacja wysyłki maili)

**Baza danych:**
* MongoDB Atlas (NoSQL)


*Projekt przygotowany na potrzeby obrony tytułu licencjata.*