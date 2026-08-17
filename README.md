# Wycena automatyzacji

Wtyczka do Claude Code z kursu **„Twój pierwszy agent AI"** (Studio GO).

Agent do wyceny automatyzacji, agentów AI i chatbotów. Zamiast rzucać kwotą z sufitu,
przepytuje o proces i o to, ile problem kosztuje klienta dziś, dobiera kategorię, podaje
widełki cenowe zakotwiczone w polskim rynku 2026, model rozliczenia (budowa + abonament)
i szkic oferty w strukturze „faza jako produkt".

## Instalacja

```
/plugin marketplace add studiogo/wycena-automatyzacji
/plugin install wycena-automatyzacji
```

## Użycie

Powiedz agentowi zwykłym zdaniem:

```
Wyceń mi tę automatyzację: [opis zlecenia]. Ile mam policzyć?
```

Albo wywołaj wprost: `/wycena-automatyzacji`.

Agent nie poda ceny, dopóki nie przejdzie wywiadu — to celowe. Cena rzucona przed
obejrzeniem zakresu wiąże wykonawcę na całą robotę i zwykle jest zaniżona.

## Zasada działania

- **Podłoga** = Twoje godziny × Twoja stawka (nigdy nie schodzisz niżej).
- **Sufit** = miesięczna oszczędność klienta × 3 do 6 (zwrot w 3–6 miesięcy).
- **Reguła rozstrzygnięcia:** z dwóch liczb bierzesz wyższą, nie środek.
- Dokłada trzy warstwy, o których początkujący zapomina: płatny audyt przed budową,
  abonament za utrzymanie, koszty bieżące po stronie klienta.

---

Widełki: polski rynek, sierpień 2026 (publiczne cenniki wykonawców). Punkt odniesienia,
nie sztywna taryfa — wartość zależy od tego, ile klient odzyska.
