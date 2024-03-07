# Przerwania mikrokontrolera
**Czym jest przerwanie?**
Zdarzenie przerywające wykonywanie kodu głównego i uruchamiające obsługę przerwania, czyli funkcji przypisanej do wykonania w trakcie przerwania. Po wykonaniu obsługi przerwania program wznawia wykonywanie głownego kodu od miejsca wystąpienia zdarzenia. 

![[Schemat przerwania systemowego|1000]]
**Rodzaje przerwań**
1. Wewnętrzne - pochądzące od wewnętrznych układów mikrokontrolera
2. Zewnętrzne - pochodzące od sensorów lub urząrzeń sterowanych przez mikrokontroler

**Przerwania wewnętrzne**
- Przerwanie od wewnętrznego licznika
- Przerwanie od gotowości pamięci EEPROM
- Przerwanie od układu watchdog
- Przerwanie od przetwornika analogowo cyfrowego
- Przerwanie od komparatora analogowego

**Przerwania zewnętrzne:**
- RESET
- Reakcja na zbocze sygnału narastające lub opadające
- Reakcja na zmianę stanu
- Reakcja na stan cyfrowy (1 lub 0)
- Reakcja na różnicę napięć wejść analogowych

