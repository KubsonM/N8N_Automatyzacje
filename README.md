# N8N_Automatyzacje

Projekt workflowy w N8N automatyzujące dwa kluczowe zadania:
  
Automatyczne powiadomienia o nowych mailach:
  -  System sprawdza skrzynkę e-mail pod kątem nowych wiadomości (np. faktury za internet)
  -  W przypadku wykrycia nowej wiadomości automatycznie wysyła powiadomienie na Telegram

Monitoring dostępności produktu online:
  -  Bot regularnie sprawdza wybrany sklep internetowy pod kątem dostępności określonego produktu lub rozmiaru
  -  W przypadku pojawienia się dostępności automatycznie wysyła alert na Telegram

Automatyczna aktualizacja budżetu domowego:
  - w pełni zautomatyzowany, oparty na self-hostingu system do śledzenia wydatków domowych w czasie rzeczywistym. Rozwiązanie wykorzystuje natywne automatyzacje smartfona (Skróty), które w tle przechwytują informacje o dokonanych płatnościach kartą
  - dane są natychmiast wysyłane poprzez Webhook do platformy n8n, gdzie następuje ich przetworzenie i kategoryzacja. Docelowo transakcje zapisywane są przez API w aplikacji Firefly III, która jest hostowana na prywatnym serwerze


Technologie:
  - N8N (automatyzacja)
  - Telegram Bot (powiadomienia)
  - Web scraping (sprawdzanie dostępności produktów)

Efekt:
Całkowicie zautomatyzowany system powiadomień oszczędzający czas i eliminujący ryzyko przegapienia ważnych informacji lub okazji zakupowych.


Automatyczne powiadomienia o nowych mailach
![image](https://github.com/user-attachments/assets/d7dacd7b-e43a-4220-b16f-e2fab53a3ce1)
![mailn8n](https://github.com/user-attachments/assets/66f4347d-92b8-442c-b4b2-1ecb6b34b2ce)


Monitoring dostępności produktu online
![image](https://github.com/user-attachments/assets/176bc067-e16d-497d-8f09-0ffdd939b7cf)
![stronan8n](https://github.com/user-attachments/assets/ae420bd6-f27f-4117-844a-819411cac72f)

Automatyczna aktualizacja budżetu domowego

