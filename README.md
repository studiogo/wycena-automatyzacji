# Wycena automatyzacji

[![licencja MIT](https://img.shields.io/github/license/studiogo/wycena-automatyzacji?style=flat-square)](LICENSE)
[![ostatnia zmiana](https://img.shields.io/github/last-commit/studiogo/wycena-automatyzacji?style=flat-square)](https://github.com/studiogo/wycena-automatyzacji/commits/main)
![Claude Code](https://img.shields.io/badge/Claude%20Code-wtyczka-D97757?style=flat-square)

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

## Wycena wyszła nie tak albo masz świeższe dane

[Załóż zgłoszenie](https://github.com/studiogo/wycena-automatyzacji/issues/new/choose) — są dwa szablony: na nietrafioną wycenę i na nowe dane cenowe. Przy nietrafionej podaj opis zlecenia, kwotę agenta i kwotę właściwą.

Zasady przysyłania widełek: [CONTRIBUTING.md](CONTRIBUTING.md).

## Licencja

MIT — [LICENSE](LICENSE).

---

Widełki: polski rynek, sierpień 2026 (publiczne cenniki wykonawców). Punkt odniesienia,
nie sztywna taryfa — wartość zależy od tego, ile klient odzyska.
