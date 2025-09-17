# 🔑 Řešení úkolů - Datové struktury v Pythonu

## 📖 O tomto souboru

Tento README popisuje notebook `reseni.ipynb`, který obsahuje **kompletní řešení všech úkolů** z Lekce 1 o datových strukturách v Pythonu.

## 🎯 Účel notebooku

### Pro lektory:
- ✅ Kontrola správnosti řešení studentů
- 📝 Referenční materiál pro výuku
- 💡 Alternativní způsoby řešení úkolů
- ⚡ Rychlé ověření funkčnosti kódu

### Pro studenty:
- 🔍 Porovnání vlastního řešení
- 📚 Učení se z příkladů
- 🚀 Inspirace pro pokročilejší techniky

## 📋 Obsah řešení

### 1. Seznamy (Lists)
**Úkoly:**
- Vytvoření seznamu oblíbených filmů
- Přidávání a odebírání prvků
- Řazení podle abecedy
- Přístup k prvnímu a poslednímu prvku

**Řešené koncepty:**
- `append()`, `remove()`, `sort()`
- Indexování `[0]`, `[-1]`
- Základní operace se seznamy

### 2. N-tice (Tuples)
**Úkoly:**
- Vytváření n-tic se souřadnicemi
- Demonstrace neměnitelnosti
- Práce s informacemi o městě

**Řešené koncepty:**
- Neměnitelnost n-tic
- Rozbalování (unpacking)
- Praktické použití pro strukturovaná data

### 3. Množiny (Sets)
**Úkoly:**
- Automatické odstranění duplicit
- Sjednocení a průnik množin
- Bezpečné odebírání prvků

**Řešené koncepty:**
- Operace s množinami (`|`, `&`, `-`)
- `discard()` vs `remove()`
- Unikátnost prvků

### 4. Slovníky (Dictionaries)
**Úkoly:**
- Vytváření slovníku o studentovi
- Přidávání nových klíčů
- Procházení klíčů a hodnot
- Úprava existujících hodnot

**Řešené koncepty:**
- `keys()`, `values()`, `items()`
- Bezpečný přístup s `get()`
- Iterování přes slovník

### 5. Mini projekt - Knihy
**Úkoly:**
- Práce se seznamem slovníků
- Filtrování podle podmínek
- Řazení podle kritérií

**Řešené koncepty:**
- Vnořené datové struktury
- `sorted()` s `key` parametrem
- List comprehensions (bonus)

## 🛠️ Technické požadavky

- **Python 3.8+**
- **Jupyter Notebook** nebo **VS Code** s rozšířením pro notebooky
- Žádné externí knihovny nejsou potřeba

## 🚀 Jak používat

### Pro lektory:
1. Otevřete `reseni.ipynb` v Jupyter/VS Code
2. Spusťte všechny buňky (`Ctrl+Shift+P` → "Run All")
3. Používejte jako referenci při kontrole studentských prací
4. Můžete kopírovat části kódu pro demonstrace

### Pro studenty:
1. **NEJDŘÍVE** se pokuste vyřešit úkoly v `lekce1.ipynb`
2. Teprve pak se podívejte na řešení v `reseni.ipynb`
3. Porovnejte své řešení s naším
4. Studujte alternativní přístupy

## 📚 Pokročilé techniky v řešeních

### List Comprehensions
```python
# Místo cyklu:
nazvy = [kniha["nazev"] for kniha in knihy]

# Místo filtru:
knihy_po_1950 = [kniha for kniha in knihy if kniha["rok"] > 1950]
```

### Bezpečná práce s daty
```python
# Bezpečné odebírání ze setu
mnozina.discard("prvek")  # nevyvolá chybu

# Bezpečný přístup ke slovníku
hodnota = slovnik.get("klic", "vychozi_hodnota")
```

### Práce s vnořenými strukturami
```python
# Řazení seznamu slovníků
serazene = sorted(seznam, key=lambda item: item["klic"])
```

## ⚠️ Doporučení

### Pro studenty:
- Neopisujte řešení mechanicky
- Snažte se pochopit logiku každého kroku
- Experimentujte s vlastními variacemi
- Pokud něčemu nerozumíte, zeptejte se lektora

### Pro lektory:
- Ukažte různé způsoby řešení stejného problému
- Zdůrazněte kdy použít kterou datovou strukturu
- Diskutujte výhody a nevýhody různých přístupů

## 📞 Kontakt

Máte-li dotazy k řešením nebo návrhy na vylepšení, kontaktujte lektora nebo vytvořte issue v repozitáři.

---

*Tento notebook je součástí kurzu "Learning Python" - praktického kurzu programování v Pythonu.*