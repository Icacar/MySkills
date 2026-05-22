# SKILL: RFQ & CT Kalkulacija (4-4-4 AI Rešenje)
**Uloga:** Process and Maintenance Manager PCBA
**Kontekst:** Godišnji cilj FY25/26 – implementacija AI alata za brži izračun CT, investicija i troškova

---

## Svrha ovog skilla
Ovaj skill direktno podržava moj godišnji biznis cilj:
> *"Find a solution and implement a 4-4-4 solution through AI tools for faster calculation of CT, investment, cost of production – to calculate accurate CT and investment based on which RFQ can be calculated."*

---

## Kada koristiti ovaj skill
- Kalkulacija Cycle Time (CT) za nove NPI projekte
- Procena investicija u novu opremu ili procese
- Izrada kalkulacije troškova proizvodnje
- Priprema podloga za RFQ (Request for Quotation)
- Komparacija opreme različitih dobavljača
- Analiza isplativosti automatizacije

---

## 4-4-4 Framework
Cilj je da svaka kalkulacija bude gotova u 4 koraka, za 4 minuta, sa 4 ključna outputa:

**4 koraka:**
1. Unos parametara (broj komponenti, tip ploče, zahtevani output)
2. Izračun CT po operaciji (stencil print, P&P, reflow, AOI...)
3. Izračun investicije i troškova
4. Output za RFQ

**4 ključna outputa:**
1. CT po ploči (sekunde)
2. Kapacitet linije (kom/sat, kom/smena)
3. Trošak po ploči (€)
4. Potrebna investicija (€)

---

## Ulazni parametri za CT kalkulaciju
- Broj SMD komponenti (ukupno, po strani)
- Broj through-hole komponenti
- Dimenzije ploče (mm x mm)
- Broj ploča po panelu
- Zahtevani godišnji volumen
- Dostupni broj smena i radnih dana

---

## Kako Claude treba da mi pomaže

### Format odgovora
- Uvek napravi tabelu sa svim parametrima i rezultatima
- Prikaži formule koje su korišćene
- Daj preporuku za konfiguraciju linije
- Ukaži na bottleneck operaciju

### Primeri zadataka
- "Izračunaj CT za ploču sa 450 SMD komponenti, dimenzije 150x100mm, 2 ploče po panelu"
- "Koliki kapacitet nam treba za 500.000 kom godišnje?"
- "Napravi Excel template za RFQ kalkulaciju"
- "Uporedi investiciju u novu P&P mašinu vs. optimizacija postojeće"
- "Proceni trošak uvođenja AOI inspekcije na liniji"
