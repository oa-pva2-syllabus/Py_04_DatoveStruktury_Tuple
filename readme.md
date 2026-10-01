# PVA2 - Programování a vývoj aplikací
## Cvičení 04: Datové struktury: N-tice (tuple)

### Jak řešit
- Všechny úkoly řešte v souboru `reseni.py`, kde jsou připravená data a proměnné ve tvaru `vysledek = ...`.
- Místo `...` doplňte své řešení. Názvy proměnných neměňte, podle nich se řešení automaticky vyhodnocuje.
- Výsledek počítejte z dat v programu (indexem, řezem, funkcí), ne opsáním hodnoty.
- Po každém `git push` se řešení vyhodnotí a výsledek najdete v pull requestu **Feedback**.
  Čísla požadavků odpovídají číslům úkolů níže.

```python
alphabet = ('a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o',
            'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z')
```

### 1
Délku ntice `alphabet` uložte do `delka`.

### 2
1. Deklarujte jednoprvkovou ntici `onlyOne` s hodnotou `'Python'`.
2. Vytiskněte uživateli její hodnotu a datový typ.

### 3
Do `profese` uložte ntici prvků: `Strojvedoucí`, `Vlakvedoucí`, `Vozmistr`.

### 4
`souradnice = (11, 22)`

1. Přidejte do ntice `souradnice` hodnotu `33`.
2. Odeberte první prvek.

Ntici nelze změnit – vytvořte novou a uložte ji zpět do `souradnice`. Ve formě komentáře vysvětlete, proč to jinak nejde.

### 5
Z ntice `alphabet` uložte první prvek do `prvni` a druhý prvek do `druhy`.

### 6
Z ntice `alphabet` uložte pomocí záporných indexů poslední prvek do `posledni` a předposlední prvek do `predposledni`.

### 7
Z ntice `alphabet` uložte každý třetí prvek (začínaje prvním) do `kazdyTreti`.

### 8
Z ntice `alphabet` uložte prvních pět prvků do `prvnichPet`.

### 9
Z ntice `alphabet` uložte posledních pět prvků do `poslednichPet`.

### 10
Z ntice `alphabet` uložte první polovinu prvků do `prvniPulka`. Polovinu spočítejte z délky ntice.

### 11
`datum = (2026, 10, 1)`

Rozbalte ntici `datum` do proměnných `rok`, `mesic` a `den` jedním přiřazením.

### 12
`designPatterns = ('Adapter', 'Repository', 'Facade', 'Factory')`

1. Index hodnoty `Repository` uložte do `indexRepository` a index hodnoty `Factory` do `indexFactory`.
2. Ve formě komentáře napište, co se stane, když budete hledat index hodnoty `repository` (malým písmenem), a proč.

### 13
1. Hodnoty proměnných `x`, `y`, `z` bude zadávat uživatel (`input()`).
2. Deklarujte ntici `hodnoty` s prvky `x`, `y`, `z` a vytiskněte ji.
3. Spočítejte, kolikrát se v ntici `hodnoty` opakuje hodnota `x`, `y` a `z`, a vytiskněte:

   `Počet výskytů – x: 2, y: 1, z: 2`

### 14
Zobrazte uživateli text:

`Byly zadány hodnoty x: 1, y: 2, z: 1 a jejich součet je: 4`

(Čísla ve vzorových výstupech platí pro vstup `1`, `2`, `1`.)
