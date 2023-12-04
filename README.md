# Zadání

Naprogramujte (pouze) kontrakt pokladny, která umí (co use-case to metoda):
- přidávat položku, co položka to: název, cena, množství
- vrátit mezisoučet
- vrátit výslednou účtenku: seznam položek, suma celkem
- na danou zaplacenou částku v hotovosti říct, kolik se má vrátit

Můžete použít pomocné datové struktury (`@dataclass`). Nezapomeňte dědit od `ABC` a anotovat metody `@abstractmethod`. Pište pouze kontrakt, nepište těla metod.
