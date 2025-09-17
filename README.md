# 📊 Prototypes Dashboard (Power BI)

Tento Power BI dashboard bol vytvorený pre tím projektových manažérov v spoločnosti **Mubea**.  
Jeho hlavným cieľom je poskytovať rýchly prehľad o stave prototypových projektov – od prijatia požiadavky až po jej dokončenie.

---

## 🎯 Ciele dashboardu
- Zobraziť **celkový počet prototypov** a ich aktuálny stav (dokončené, prebiehajúce, oneskorené).
- Umožniť **sledovanie výkonu jednotlivých projektových manažérov** (počet dokončených a prebiehajúcich projektov).
- Poskytnúť **prehľad o oneskorených projektoch** a dôvodoch oneskorenia.
- Analyzovať počet projektov podľa **mesiaca a roku** pre identifikáciu trendov.

---

## 🗂 Zdroj dát
Dashboard čerpá dáta z **Excel súboru**, ktorý obsahuje nasledujúce informácie:
- 🔹 ID projektu a interné číslo objednávky  
- 🔹 Zadávateľ požiadavky  
- 🔹 Zákazník a produkt  
- 🔹 Počet kusov  
- 🔹 Dátum vytvorenia požiadavky a odoslania  
- 🔹 Stav projektu (dokončený, prebiehajúci, oneskorený)  
- 🔹 Projektový manažér zodpovedný za projekt  

---

## 📸 Ukážka dashboardu

<img width="1441" height="808" alt="image" src="https://github.com/user-attachments/assets/9c465187-6bc8-4e38-a4eb-a5d5bbd7889f" />

---

## 📊 Kľúčové metriky
- **Total prototypes** – celkový počet projektov  
- **Finished** – počet dokončených projektov  
- **Ongoing** – počet prebiehajúcich projektov  
- **Delayed** – počet projektov po termíne  
- **Finished vs. Ongoing** – rozdelenie podľa stavu  
- **Projects by Month** – vývoj počtu projektov v čase  
- **Projects by Manager** – porovnanie ukončených a prebiehajúcich projektov podľa manažéra  

---

## 🌍 Interaktivita
Dashboard umožňuje:
- filtrovanie podľa **projektového manažéra**,  
- drill-down do detailu oneskorených projektov,  
- prehľad ďalších krokov pri jednotlivých projektoch.  

---

## 📂 Obsah repozitára
- `prototypes_dashboard.pbix` – Power BI dashboard  
- `dataset.xlsx` – vzorka dát (anonymizovaná)  
- `docs/dashboard.png` – screenshot dashboardu  
- `README.md` – popis projektu  

---

## 🚀 Použitie
1. Otvor súbor `prototypes_dashboard.pbix` v **Power BI Desktop**.  
2. Pripoj sa k zdrojovému súboru `dataset.xlsx`.  
3. Uprav filtre alebo pridaj vlastné dáta pre testovanie.  

---

## 📌 Autor
Vytvorené ako interný projekt pre tím projektových manažérov s cieľom zefektívniť sledovanie prototypov.  
Autor: **Tomas Mesáros**
